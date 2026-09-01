<!-- ![estado de compilación](https://github.com/schoeberl/chisel-book/actions/workflows/test.yml/badge.svg) -->

# Nota del traductor

Esta traducción al castellano se ha realizado de forma manual, sin recurrir a
traducción automática. Para la revisión del texto se ha empleado el modelo
Opus 5 de Anthropic.

# Diseño Digital con Chisel

[![Portada del libro](cover-small-es.jpg)](http://www.imm.dtu.dk/~masca/chisel-book.html)

Este libro es una introducción al diseño de sistemas digitales utilizando un
lenguaje moderno de construcción de hardware, [Chisel](https://www.chisel-lang.org/).
En este libro nos centramos en un nivel de abstracción ligeramente superior al habitual,
para que puedas ponerte al día y construir sistemas digitales más complejos que interactúan entre sí.

Hay disponible una versión PDF compilada del libro en inglés en
[Digital Design with Chisel PDF](http://www.imm.dtu.dk/~masca/chisel-book.pdf).
También hay traducciones al chino, al japonés, al vietnamita y al castellano disponibles
[aquí](http://www.imm.dtu.dk/~masca/chisel-book.html).

El libro en inglés está disponible [en Amazon](https://www.amazon.com/dp/168933603X/).

Por si quieres citar el libro:

```
@book{chisel:book,
  title = {Digital Design with Chisel},
  publisher = {Kindle Direct Publishing},
  year = {2019},
  author = {Martin Schoeberl},
  url = {https://github.com/schoeberl/chisel-book}
}
```

Este proyecto de libro cuenta con un repositorio complementario que contiene
[ejemplos de Chisel](https://github.com/schoeberl/chisel-examples).

Para compilar el libro de Chisel a partir del código fuente necesitas tener
instalados make, latex, sbt y un JDK de Java (1.8 o posterior). Para algunas
pruebas también necesitas Verilator y z3 instalados. Después, simplemente
compila el libro con:

```
make
```

El libro también incluye diapositivas para un curso semestral de electrónica
digital con Chisel. Las diapositivas están [aquí](slides). Puedes consultar el
[plan de la asignatura](http://www2.imm.dtu.dk/courses/02139/) de un curso impartido
en la DTU que incluye los PDF de las diapositivas y el correspondiente
[material de laboratorio](https://github.com/schoeberl/chisel-lab).

