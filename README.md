
![Redes neuronales](http://cosmonio.com/Research/Deep-Learning/files/small_1420.png)

**Bienvenido al curso de Redes Neuronales de la Licenciatura en Ciencias de la computación de la Universidad de Sonora**


# Información general del curso

- *Profesor:* [Julio Waissman Vilanova](http://mat.uson.mx/~juliowaissman/)

- *Horario*: lunes a viernes de 12:00 a 13:00 horas

- *Lugar:* Aula 102, edificio 3K-4

- *Fecha de inicio:* 14 de agosto de 2017

- *Fecha de término:* 8 de diciembre de 2017

- [Material para el curso (sin incluir los proyectos)](https://curso-redes-neuronales-unison.github.io/Material/ "Material para el curso")


# Objetivo del curso

Los **objetivos** de este curso son:

1. Conocer los aspectos teóricos básicos de las redes neuronales.

2. Comprender los mecanismos de aprendizaje en redes neuronales.

3. Conocer los aspectos generales de aprendizaje profundo y las
   diferentes arquitecturas existentes.

4. Saber aplicar una librería de desarrollo de aprendizaje profundo
   para realizar al menos 3 tareas no triviales diferentes.

5. Tener la capacidad de entender y aplicar tecnologías de aprendizaje
   profundo a otros problemas.

Las **competencias** que espero ayudar a desarrollar en los estudiantes a
lo largo del semestre 2017b son las siguientes:

1. Saber programar una red neuronal sencilla hacia adelante con el
   algoritmo de *b-prop* y de *r-prop* en Python

2. Utilizar *Tensorflow* y/o *Theano* para desarrollar una red
   convolucional para clasificación de imágenes.

3. Utilizar *Tensorflow* o *Theano* para desarrollar una red neuronal
   recurrente y su aplicación a un problema de procesamiento de
   lenjuage natural (como la generación de *word2vec*) o un problema
   de predicción en series de tiempo.

4. Saber ajustar, analizar y modificar los parámetros de una red
   neuronal profunda, utilizando diferentes técnicas. Muy en
   particular, saber cuando es posible y cuando no es posible aplicar
   una red neuronal profunda.
   
5. Implementar una arquitectura avanzada de aprendizaje profundo,
   entendiendo en términos generales su funcionamiento, entre estas
   pueden ser:
   
   1. Un algoritmo de aprendizaje con refuerzo tipo *DeepQL* para su
      aplicación en juegos.
   2. Un modelo generativo para modificación automática de imágenes.
   3. Una red profunda tipo *Densenet* para su uso con bases de datos reducidas.

# Temario del curso

1. Redes neuronales

2. Arquitecturas profundas: ideas generales

3. Redes convolucionales

4. Herramientas y métodos de análisis y ajuste de hiperparámetros

5. Redes recurrentes

6. Tema selecto (a decidir en conjunto con los estudiantes) 

# Método de evaluación

Se contemplan 3 tipos diferentes de evaluación:

1. *Evaluación continua:* Esta se realiza a lo largo del curso y se
   basará exclusivamente en el avance y solución de las libretas en
   *Jupyter* que se deberá de resolver a lo largo del curso. 

2. *Evaluación teórica:* Esta se realiza a partir de dos exámenes
   teóricos, uno al final del tema 1, y otro al final del semestre.
   
3. *Evaluación de competencias:* Esta se realizará a través de 3
   proyectos pequeños que deberán desarrollar los estudiantes en forma
   individual, los cuales son:
   1. Una red convolucional.
   2. Una red recurrente.
   3. Una red con la arquitectura sobre el tema selecto elegido (u
      otra arquitectura diferente).

La evaluación tendrá el siguiente peso:

- Evaluación continua: 30% de la calificación

- Evaluación teórica: 30% de la calificación (promedio de ambos
  exámenes)

- Evaluación de competencias: 40% de la calificación (promedio de
  calificación de los 3 proyectos)

# Proyecto 1: Reconocimiento y localización de objetos en imágenes con RCNN

En este proyecto se desarrolla una aplicación de reconocimiento y localización de objetos en imágenes utilizando una variante de las redes convolucionales llamada *Regional Convolutional Neural Netkorks* (RCNN). La expicación de que es una RCNN, como entrenarla, como utilizar un modelo preentrenado y como realizar todo esto en la nube a través de los servicios de *Google Cloud* se encuentran bien expicados en cada uno de los proyectos realizados. Para muestra de lo que son capaces de realizar los estudiantes de la LCC, se listan los proyectos realizados.

- [**Pokedex** Reconocimiento de *pokemones*](https://ErickLF.github.io/Pokedex-R-CNN), por [**Erick Fernando López Fimbres**](https://ericklf.github.io).
- [Reconocimiento de víboras](https://alexis96.github.io/proyecto-CNN/), por **Fernando Alexis Martínez Valenzuela**.
- [Reconocimiento de *pokemones*](https://nanmon.github.io/redes-neuronales/) por **Luís Roberto Montaño Valdez**.
- [Reconocimento de botellas de cerveza](https://abmorenoc.github.io/Deteccion-de-objetos-en-imagenes/) por **Jesús Abraham Moreno Ceballos**.
- [Reconocimiento de *pokemones*](https://nanmon.github.io/redes-neuronales/) por **Luís Roberto Montaño Valdez**.

# Proyecto 2: Generación de texto en español (caracter por caracter) utilizando Redes Neuronales Recurrentes (RNN)

En este proyecto, los estudiantes demuestran su habilidad y conocimiento para desarrollar una RN que genere texto en español. En principio el proyecto consta de dos tareas:

1. Hacer un generador de nombre falsos de municipios de México, aprendiendo de la [lista de municipios de la República Mexicana](municipios.txt). Para esto, poner en una libreta de *Jupyter* bien comentado y parametrizado correctamente el método de RNN simple que se presenta en [este gist](https://gist.github.com/karpathy/d4dee566867f8291f086), o si quieres algo más sofisticado, está [este otro gist](https://gist.github.com/karpathy/587454dc0146a6ae21fc) que hace una implementación sencilla de las LSTM.

2. Hacer un generador de textos, los cuales pueden ser (aunque no se restringen) a:
   1. Generador de discursos políticos (los texots se pueden obtener del senado de la república o la camara de diputados).
   2. Generador de parrafos de teatro de la época de oro (a partir de las obras en el [proyecto Gutemberg](https://www.gutenberg.org/browse/languages/es)).
   3. Generador de tareas autom´icas (a partir de las infames tareas que se encuentran en [monografias.com](http://www.monografias.com).
   
Los proyectos realizados son los siguientes:

- [**G-Texts**: Generación de textos en español](https://ericklf.github.io/Generador-Textos-RNN/), por [**Erick Fernando López Fimbres**](https://ericklf.github.io).
- [Generación de textos políticos](https://alexis96.github.io/proyecto-RNN/), por **Fernando Alexis Martínez Valenzuela**.
- *En desarrollo* por **Luís Roberto Montaño Valdez**.
- *En desarrollo* por **Jesús Abraham Moreno Ceballos**.
- *En desarrollo* por **Luís Roberto Montaño Valdez**.

