<h1 align="center">GitFlow</h1>

<div align="center">
<img width="40%" src="https://cdn-images-1.medium.com/v2/resize:fit:1600/1*9yJY7fyscWFUVRqnx0BM6A.png">
</div>
<hr>
<p align="center"><strong>Gitflow</strong> es el modelo de flujo de trabajo que utiliza Git. Consiste en dividir el desarrollo de un proyecto en <strong>varias ramas que permitan una organización eficiente del mismo.</strong></p>

<h2>Ramas Principales</h2>

<li><strong>Master</strong></li>
<p>En esta rama se encuentra la <strong>versión estable del proyecto</strong> y que está </strong>lista para entrar en producción.</strong> </p>

<li><strong>Develop</strong></li>
<p>En esta rama <strong>se agregan nuevas características</strong> a nuestro proyecto , incluyendo la <strong>implementación de nuevo código.</strong></p>

<h2>Ramas de Soporte</h2>

<li><strong>Feature</strong></li>
<p>En esta rama <strong>se agregan nuevas características partiendo de la rama Develop</strong> y son introducidas en esta última una vez que la funcionalidad se haya completado.</strong></p>

<li><strong>Release</strong></li>
<p>Rama que <strong>prepara una nueva versión del proyecto</strong>, incluyendo correcciones de errores y preparativos antes de pasar a una nueva rama (Master o Develop).</p>

<li><strong>Hotfix</strong></li>
<p>Rama <strong>dedicada a la corrección de errores críticos que hayan surgido en producción</strong>. Surgen de la rama Master y al corregir el problema se integran tanto con esta última rama como con Develop.</p>
