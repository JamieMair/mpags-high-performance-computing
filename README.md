# High Performance Computing in Julia

This is the main site for documentation about he High Performance Computing in Julia MPAGS module. The link to the site can be found [here](https://jamiemair.github.io/mpags-high-performance-computing/).


## Locally running the website

Make sure you have `julia` installed on your system and open up a terminal in this directory:
```bash
julia
```
Then run the following in the REPL:
```julia
using Pkg;
Pkg.activate(".");
Pkg.instantiate();
```
This only needs to be done once. After you can run the project locally with
```julia
using Franklin
serve()
```

This will open up the live server.