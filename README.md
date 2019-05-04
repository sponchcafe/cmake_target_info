# Target info dump for cmake


## Usage

```cmake
cmake_minimum_required(VERSION 3.10 FATAL_ERROR)
project(<your project>)

# include script
include("target_info.cmake")

# enable target collection
enable_register_targets()

<all target definitions, subdirectories, ...>

# Write collected targets to file (yaml formatted)
dump_target_info("targets.yml")
```
