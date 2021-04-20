# OpenGL-Simple-Shader-Class
Simple class for OpenGL Shaders based on LearnOpengl.com course.

## Usage
```cpp
Shader shader("path/to/vertexShader.glsl", "path/to/fragmentShader.glsl");
shader.setInt("uniformName", 1); // sets an int uniform named uniformName

shader.use(); // binds the OpenGL program
```