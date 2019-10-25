# Diálogos entre Ciencias Básicas y Especialidades (dcbye2019)
Matemática aplicada a los Videojuegos - Diálogos entre Ciencias Básicas y Especialidades

[Link a la presentation](https://docs.google.com/presentation/d/10RDvWqXDt5-xpRJ99lrus4uNXreyxbpjxtuIFhkYhBA/edit?usp=sharing)

## Referencia a materia de Técnicas Gráficas por Computador

[Link a la materia TGC](http://tgcutn.com.ar)

[Ejemplos en JavaScript](https://mbanquiero.github.io)


### Oradores:

[Ing. Rodrigo Nicolas Garcia](https://github.com/mysery) <rgarcia@frba.utn.edu.ar>

[Ing. Mariano Gonzalez]() <mago.utn@gmail.com>


## Modo de uso del mini motor de fisica para ejemplos.
El motor esta realizado con Java Script y puede ser ejecutado en Chrome para ver sus resultados.

#### Definir la gravedad:

    gravity = new Vector2(0, 10);

#### Agregar una caja:

    world.AddBox(X, Y, DX, DY);

#### Agregar un circulo:

    world.AddCircle(X, Y, radio);

#### Agregar un triangulo:

    world.AddTri(ax, ay, bx, by, cx, cy);

#### Definir un cuerpo estatico:

    piso.SetStatic();

#### Definir la orientacion de un cuerpo.

    canion.SetOrient(radianes);
