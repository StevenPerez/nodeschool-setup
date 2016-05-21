# NodeSchool Setup

NodeSchool es un excelente recurso que te permitirá aprender los conceptos básicos de node.js, el cual está compuesto
por módulos de código abierto proporcionados de forma gratuita.



Los siguientes pasos te ayudarán a configurar tu entorno (Mac OS X, Ubuntu/Linux o Windows) de forma que tengas lo
necesario para realizar los Workshop de NodeSchool.



<h2>OS X</h2>

<h2>Ubuntu</h2>

<ul>
	<li>Lo primero que debemos hacer es escoger una terminal, podríamos usar Gnome Terminal que viene por defecto en
		Ubuntu; sin embargo, te recomendamos <a href="http://guake.org/">Guake</a>, la cual se puede obtener desde el Centro
		de Software de Ubuntu.
	</li>
	<br>
	<li>Una vez que tienes configurada la terminal, debes abrirla y proceder a instalar <a
		href="https://github.com/creationix/nvm">nvm</a> (“Node Version Manager” o “Gestor de Versiones de Node”), Nvm
		permite instalar múltiples versiones de Node.js y npm en un mismo ambiente, dejando cada una completamente aislada
		de las otras.
	</li>
</ul>
Para instalar nvm puedes utilizar el script de instalación:
### CURL
```javascript
~ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.25.2/install.sh | bash
```
O bien

###WGET
```sh
~ wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.25.2/install.sh | bash
```
Nota: Una vez que instalas nvm, debes cerrar y volver a abrir la terminal para empezar a utilizarlo.
<p>Ahora podemos instalar la versión de node. El siguiente comando te permitirá ver la lista de versiones
disponibles; te recomendamos instalar las versiones más recientes.</p>
```sh
~ nvm ls-remote latest
```
<br>
Por ejemplo: Al momento de escribir este post yo instalé la versión 4:
```sh
~ nvm install 4.2.1
```

Posterior a la instalación de nvm, podemos ver que ya tenemos el paquete de node instalado utilizando el siguiente
comando:

```sh
~ node -v
```
* Para realizar los talleres también se debe tomar en cuenta que necesitaremos un editor de texto. Yo he decidido
instalar <a href="https://atom.io/">Atom</a> por su flexibilidad y además cuenta con una interfaz moderna y fácil de
utilizar (puedes descargar el paquete de atom desde el sitio oficial).

Posteriormente procedemos a instalar el <a href="http://nodeschool.io/">Workshop</a> a trabajar; utilizando npm, a
traves de Guake Terminal.
<p>Por ejemplo:</p>
```sh
~ npm install -g javascripting
```
Nota: Si tienes algún problema a la hora de instalar, intenta añadiendo el prefijo “sudo”:
```sh
~ sudo npm install --global javascripting
```
Y finalmente ejecutamos el comando del taller respectivo para comenzar:
```sh
~ javascripting
```
</ul>

<h2>Windows</h2>
<ul>
	<li>Lo primero que debemos hacer es escoger una terminal; sin embargo, para realizar los talleres de nodeschool se
		puede utilizar perfectamente el cmd de Windows (Símbolo del Sistema).
	</li>
	<br>
	<li>Vamos a descargar y ejecutar el instalador de <a href="https://github.com/coreybutler/nvm-windows">nvm para
		Windows</a> (“Node Version Manager” o “Gestor de Versiones de Node”).
		Nvm permite instalar múltiples versiones de node.js y npm en un mismo ambiente, dejando cada una completamente
		aislada de las otras.
	</li>
</ul>
Para empezar a utilizar nvm debemos reiniciar el cmd de Windows.
Una vez iniciada la consola, ejecutamos el siguiente comando para ver las versiones de nvm disponibles:
```sh
c:\Users\user1> nvm list available
```

Por ejemplo: Al momento de escribir este post yo instalé la versión 4:
```sh
c:\Users\user1> nvm install 4.2.1
```
```sh
c:\Users\user1> nvm use 4.2.1
```
Posterior a la instalación de nvm, podemos ver que ya tenemos el paquete de node instalado, a través del siguiente
comando:

```sh
c:\Users\user1> node -v
```
* Para realizar los talleres también se debe tomar en cuenta que necesitaremos un editor de texto. Yo he decidido
instalar <a href="https://atom.io/">Atom</a> por su flexibilidad y además cuenta con una interfaz moderna y fácil de
utilizar. Atom tiene soporte para versiones posteriores a Windows 7.

* Posteriormente procedemos a instalar el <a href="http://nodeschool.io/">Workshop</a> a trabajar; utilizando npm, a
través del cmd de Windows.
Por ejemplo:

```sh
c:\Users\user1> npm install -g javascripting
```
Nota: Si tienes algún problema a la hora de instalar, intenta añadiendo el prefijo “sudo”:

```sh
c:\Users\user1> sudo npm install --global javascripting
```
Y finalmente ejecutamos el comando del taller respectivo para comenzar:

```sh
c:\Users\user1> javascripting
```
</ul>
<br/>

<p><strong>Listo, ahora tienes lo necesario para desarrollar cada Workshop!</strong></p>
