## First steps in Julia

I installed Julia and some VSCode Julia extensions. Execute `Julia` in the terminal to get the Julia REPL:
``` shell
> Julia
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.11.5 (2025-04-14)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia> 
```

Just like a Python script a Julia script `script.jl` is executed as 

``` shell
> echo 'println("Hello world")' > script.jl
> julia script.jl
Hello world
```

Note that `.jl` is the standard file extension for a Julia script.
