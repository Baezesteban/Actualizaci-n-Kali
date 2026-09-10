<h1>Actualización Kali Linux</h1>

<p>
  <a href="https://youtu.be/7eJexJVCqJo">YouTube Demonstration</a>
</p>

<section>
  <h2>Bienvenido a este proyecto</h2>

  <p>
    Este proyecto está pensado para <strong>DUMMIES o personas que están comenzando desde cero</strong>,
    por lo que inicialmente las explicaciones serán detalladas y paso a paso.|
  </p>

  <p>
    A medida que avances de proyecto en proyecto,
    <strong>el nivel de dificultad irá aumentando progresivamente</strong>.
    La idea es que cada ejercicio te prepare para el siguiente.
  </p>

  <p>
    No te preocupes si al principio todo parece muy explicado;
    <strong>poco a poco iremos subiendo el nivel</strong>.
  </p>

  <p><strong>Inicialmente, comenzaremos con lo más básico. ¡Vamos a ello!</strong></p>
</section>

<section>
  <h2>Requisitos</h2>

  <ul>
    <li><strong>Kali Linux </strong></li>
    <li><strong>Terminal de Kali Linux</strong></li>
  </ul>
</section>

<section>
  <p>
    Antes de comenzar con los siguientes proyectos, prepararemos nuestro entorno
    actualizando Kali Linux y sus paquetes.
  </p>

  <h3>1. Actualizar los repositorios</h3>

  <p>
    Este comando consulta los repositorios configurados y actualiza la información
    disponible sobre los paquetes.
  </p>

  <pre><code>sudo apt update</code></pre>

  <h3>2. Actualizar los paquetes</h3>

  <p>
    Una vez actualizada la información de los repositorios, instalamos las
    actualizaciones disponibles.
  </p>

  <pre><code>sudo apt upgrade</code></pre>

  <h3>3. Configurar paquetes pendientes</h3>

  <p>
    Si existen paquetes que quedaron pendientes de configuración, podemos ejecutar:
  </p>

  <pre><code>sudo dpkg --configure -a</code></pre>

  <p>
    Con esto tendremos nuestro entorno preparado para continuar con los siguientes
    proyectos.
  </p>

  <p align="center">
Imagende referencia: <br/>
<img src="https://i.imgur.com/sbhgpBk.png"/>
<img src=""/>
<br />
</section>



<h2>Program walk-through:</h2>


<br />
Select the disk:  <br/>
<img src="https://imgur.com/a/szyZ3UP" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
