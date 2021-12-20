# Advent of Code - Haskell Implementation

## Haskell

Install the `haskell-platform` via ghcup and make sure to install `stack`:

```bash
curl -sSL https://get.haskellstack.org/ | sh
```

VSCode seems to have the easiest and most accessible [plugin for Haskell including the Haskell-Language-Server](https://marketplace.visualstudio.com/items?itemName=haskell.haskell).

[Haskelly](https://marketplace.visualstudio.com/items?itemName=UCL.haskelly) allows to easily run and haskell files in interpreter mode and may be installed additionally.

## Usage

Make sure that `stack` is in your `$PATH`. Then from the this directory build the project and run it:

```bash
stack build
stack exec adventofcode-exe  # prints usage info
stack exec adventofcode-exe -- 2021 4a  # solves Problem 4a of AoC 2021
```

## Caveats

I am using `System.TimeIt` to time the program execution. The results seem highly unstable. Run each problem a few times to get a better idea.
I might try `Criterion` in the future.
