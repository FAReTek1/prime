# prime.gs

> simple prime number utilities

This is a prime number library which is built for [goboscript](https://github.com/aspizu/goboscript).
It is designed to be used with [inflator](https://github.com/faretek1/inflator).

## Credits

...

## Installation

Make sure you have inflator installed

`inflate install https://github.com/FAReTek1/prime`

add prime to your `inflator.toml` config:
```toml
[dependencies]
# ...
prime = "https://github.com/FAReTek1/prime"
```

## Development

use `inflate install -e .`:

1. clone the respository: `git clone https://github.com/FAReTek1/prime`
2. `cd prime`
3. `inflate install -e .`
4. `cd test`
5. `inflate`
6. `goboscript build`
7. open `test.sb3`
