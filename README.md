# SimpleOpenGLShader
My Own OpenGL Shader class

# a simple example:

## ShaderFromFile* shader = new ShaderFromFile("vertex.txt", "fragment.txt");
## shader->Use();

## int ourColor = shader->GetShaderSourceUniform("ourColor");
## glUniform4f(ourColor, 0.0f, 1.0f, 0.0f, 1.0f);

## delete shader;
