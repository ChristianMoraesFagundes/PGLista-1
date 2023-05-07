# PGLista-1
 Lista 1 exercicios 

Chamadas de alguns exercicios estão comentadas seguindo o padrão "Exercicio X(y)" sendo X o numero da questão e y a letra

1. O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável
da versão atual que trabalhamos em aula e o que eles processam?
 GLSL é uma liguagem de programação usada para o desenvolvimento de shaders dentro do pipeline do openGL. Os shaders que são obrigatorios serem configurados é o vertex shader e o fragment shader, o fragment shader processa cada fragmento individualmente após a rasterização e o vertex shader processa cada vertex individualmente.

2. O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?
Uma primitiva grafica é fundamentalmente uma geometria, como pontos, linhas , etc, e o armazenamento é feito em arrays dentro do openGl. 

3. Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer
um gráfico representando a relação entre eles). 
O Vertex buffer object(VBO) permite que arrays de vertices sejam renderizado na placa grafica ja que os dados são armazenados diretamente na GPU. O vertex array buffer(VAO) faz a ligação dos atributos de um vertice, alem de definir qual VBO usar, a localização dos dados do VBO e o formato dos dados. O EBO e um buffer que armazena indices que o openGL usa pra decidir quais vertices desenhar.
