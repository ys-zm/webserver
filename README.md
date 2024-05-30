A simple HTTP webserver that mimicks nginx.

---

## Compiling:  
1. `make` creates the executable named "exe"
 
2. `make clean` removes object files

3. `make fclean` removes object files and the executable

4. `make re` calls `make fclean` followed by `make`  

---
## Usage:
```
./exe [config_file]
```
### Parameters:
config_file: configuration file with a ".conf" extension similar to nginx configuration files, outlining server contents and parameters. See template.conf as an example.
