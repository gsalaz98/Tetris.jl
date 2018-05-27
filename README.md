# Tetris

![Gameplay Shots](https://raw.githubusercontent.com/djsegal/Tetris.jl/master/tetris.png)

music by: [Ghost & Kozmos](https://soundcloud.com/the-ghost-that-haunts-your-house/ghost-kozmos-tetris-theme-electro-swing-remix)

[![Build Status](https://travis-ci.org/djsegal/Tetris.jl.svg?branch=master)](https://travis-ci.org/djsegal/Tetris.jl)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/djsegal/tetris-binder/master?urlpath=apps%2FJulia%20Tetris.ipynb)

-----

### Installation

```julia
Pkg.add("Tetris")
```

### Usage

Standard usage is:

```
using Tetris
Tetris.setup()
```

However, if you have a long running function, this might be more your speed:

```
using Tetris
@tetris slow_func()
```

*// for the most part, controls match [tetris friends](http://www.tetrisfriends.com/help/tips_appendix.php#controls)*
