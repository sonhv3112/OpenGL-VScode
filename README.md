# OpenGL-VScode

## Build

- Use task.json then Run Build Task (Ctrl + Shift + B) to build 
- Command: 

``` bash 
g++ -g --std=c++17 -I./include -L./lib ./src/glad.c ./src/*.cpp -lglfw3dll -o ./bin/main
```

Excutable file is generated to bin folder

## Run 

Run file main.exe in bin folder 

``` bash
./bin/main
```
