# Monad Mersenne Random

An efficient random generator monad, based on the Mersenne Twister

## Description
Often we need an efficient way to generate high quality pseudo-random numbers in Haskell. We have good generators
themselves (for example, the mersenne-random-pure64 package), however, users are often tempted to store the generator in a lazy state monad. This causes performance problems.
This package provides an optimized 'Rand' monad for monadic generation of random numbers from a state, with close attention to performance. You may have results an order of magnitude or more better than using Control.Monad.State to store your generator.

## Homepage
http://code.haskell.org/~dons/code/monad-mersenne-random

## Author
Don Stewart

## License

See [License](LICENSE)
