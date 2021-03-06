## Usage

1. Pre-requirements:
   * `node` version 8 or above
   * `yarn`
1. Clone the repository
1. Run `yarn` to install the dependencies
1. Run `yarn test` to run the unit tests
1. Implement your neural network solution using TinyBrain, or see examples below

The `examples` directory has an example for learning the XOR function.

To teach the network and run the test inputs, do e.g.

```
node xor.js --layers 2 --relu --value --epochs 1e5 --rate 0.01
```

```
node xor.js --layers 2 --sigmoid --classification --epochs 1e5 --rate 0.1
```

If you have `gnuplot` installed, you can run:

```
node xor.js --layers 2 --relu --value --epochs 1e5 --rate 0.01 --plot | sh plotter.sh > graph.png && open graph.png
```
