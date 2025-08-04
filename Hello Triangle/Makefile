# Windows Build
win:
	g++.exe -fdiagnostics-color=always -I./include ./src/main.cpp ./src/glad.c -o ./build/main.exe -Llib -lglfw3dll -lopengl32 -lgdi32
	./build/main.exe

# Linux Build
linux:
	g++ -fdiagnostics-color=always -I./include ./src/main.cpp ./src/glad.c -o ./build/main -Llib -lglfw -lGL -lXrandr -lX11 -lrt -ldl
	./build/main
