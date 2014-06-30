
## julia-logger

A tiny logger for julia.

### Installation

```bash
julia >Pkg.clone("queckezz/julia-logger")
```

### Example

```julia
# import
import Logger

# create a new Log type
warn = Logger.Log("warn", "red")

# use it
Logger.log("warn", "a message")
```

### Notes

Im just exploring Julia and trying to learn functional programming, as its one of the core philosophies in Julia. So expect things to change.

* Implement all bash colors

### Licence

The [MIT](http://opensource.org/licenses/MIT) License &copy; 2014, Fabian Eichenberge