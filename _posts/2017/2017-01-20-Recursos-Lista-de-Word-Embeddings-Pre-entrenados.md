---
layout: post
title: Lista de Word Embeddings Pre-entrenados ENG
category: Recursos
tags: [Recursos Investigación NLP]
overview: Compilación de Word Embeddings usados en problemas de NLP para el idioma Ingles
---

## Lista de Word Embeddings Pre-entrenados para el idioma Ingles
##### Posteado por: Orlando Montenegro

### Introducción

<p style='text-align: justify;'>
Word Embeddings, es una técnica que expresa una palabra como un vector de números reales,
aproximadamente de 200 dimensiones o más. Es una característica de estos modelos que las
palabras que tienen un significado similar se pueden hacer corresponder mediante la
representación de un vector cercano y obtener resultados significativos al sumar o restar vectores,
por ejemplo, <B>el vector(rey) - vector(hombre) + vector(mujer) = vector(reina)</B>.
</p>

<p style='text-align: justify;'>
Esta técnica es utilizada en varias aplicaciones de NLP, como el etiquetado de part-of-speech,
la recuperación de información, la respuesta a preguntas, etc. Sin embargo, es un trabajo bastante
complicado preparar los Word Embeddings: Es necesario contar con una gran cantidad de datos,
hacer un pre-procesamiento de la información, entrenar los modelos durante bastante tiempo,
verificar el resultado y realizar ajustes de hiperparámetros para reentrenar nuevamente los modelos,
contando con un sistema de cómputo que por lo general tiene prestaciones técnicas más elevadas.
</p>

<p style='text-align: justify;'>
Si solo desea utilizar los Word Embeddings, es preciso usar vectores pre-entrenados.
A continuación, enumero los Word Embeddings más usados en trabajos de NLP para el idioma Ingles.
</p>

### Word2Vec

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">Vectores pre-entrenados Word2Vec.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2013</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="https://code.google.com/archive/p/word2vec/">https://code.google.com/archive/p/word2vec/</a></td>
    </tr>
  </tbody>
</table>
<p style='text-align: justify;'>
Usted puede obtener vectores pre-entrenados en otros lenguajes en el siguiente link:
</p>
<ul>
  <li>
    <a href="https://github.com/Kyubyong/wordvectors">https://github.com/Kyubyong/wordvectors</a>
  </li>
</ul>

### GloVe

<p style='text-align: justify;'>
GloVe combina descomposición gobal de Matrices y contextos locales de ventana
</p>

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">GloVe: Desarrollado por Stanford NLP Group.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2014</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="http://nlp.stanford.edu/projects/glove/">http://nlp.stanford.edu/projects/glove/</a></td>
    </tr>
  </tbody>
</table>

### fastText

<p style='text-align: justify;'>
Modelo de aprendizaje muy Veloz! considerando morfemas, cada palabra es una representacion de ngramas de caracteres y las expresiones vectoriales de estas estan aprendidas.
</p>

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">FastText de los mismo creadores de Word2Vec.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2016</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="https://github.com/icoxfog417/fastTextJapaneseTutorial">https://github.com/icoxfog417/fastTextJapaneseTutorial</a></td>
    </tr>
  </tbody>
</table>

### Dependecy-Based

<p style='text-align: justify;'>
Word Embeddings desarrollados por Omer Levy y Yoav Goldberg, con aprendizaje de dependecias basdas en contextos, los cuales son robustos en trabajos de similaridad sintáctica.
</p>

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">Dependency-Based Word Embeddings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2014</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="https://levyomer.wordpress.com/2014/04/25/dependency-based-word-embeddings/">https://levyomer.wordpress.com/2014/04/25/dependency-based-word-embeddings</a></td>
    </tr>
  </tbody>
</table>

### Meta-Embeddings

<p style='text-align: justify;'>
Al combinar diferentes conjuntos de embeddings públicos, se generan mejores vectores Meta-Embeddings.
</p>

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">Meta-Embeddings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2016</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="http://cistern.cis.lmu.de/meta-emb/">http://cistern.cis.lmu.de/meta-emb/</a></td>
    </tr>
  </tbody>
</table>

### LexVec

<p style='text-align: justify;'>
En tareas de similaridad de palabras, en algunos casos excede a Word2vec
</p>

<table>
  <thead>
    <tr>
      <th align="left" style="width: 100px;"></th>
      <th align="left" style="width: 680px;">LexVec</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" style="width: 100px;">Año</td>
      <td align="left" style="width: 680px;">2016</td>
    </tr>
    <tr>
      <td align="left" style="width: 100px;">URL</td>
      <td align="left" style="width: 680px;"><a href="http://cistern.cis.lmu.de/meta-emb/">http://cistern.cis.lmu.de/meta-emb/</a></td>
    </tr>
  </tbody>
</table>

### Conclusión

<p style='text-align: justify;'>
En este artículo, se hace referencia a los vectores pre-entrenados mas usados, adicionalemnte recomedamos el siguiente links con vectores pre-entrenados adicionales.
</p>
[https://github.com/Hironsan/awesome-embedding-models](https://github.com/Hironsan/awesome-embedding-models)

### Referencias

[The List of Pretrained Word Embeddings](http://ahogrammer.com/2017/01/20/the-list-of-pretrained-word-embeddings/)
