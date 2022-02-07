# Comienza a programar en Python🐍 con IDLE 
Si, leíste bien... IDLE 😎 


## Contenido 

  * [¿A quién está dirigida esta publicación?](#chapter-0) 
  * [Instalación y primeros pasos](#chapter-1) 
    * [Git](#chapter-1.1)
    * [Bash for Windows](#chapter-1.2)
  * [Virtual Environment](#chapter-2) 
  * [Idle](#chapter-3) 


## ¿A quién está dirigida esta publicación? <a name="chapter-0"></a> 

Personas con poco conocimiento en python, programación o IT que nunca hayan creado su entorno virtual. Orientado principalmente a Windows. Usamos bash, así que se puede usar en linux o Mac OS sin muchas diferencias. Vamos a suponer qué:

* No tienes python instalado
* Tus conocimientos son de begginer a intermediate<br><br>

## Instalación y primeros pasos <a name="chapter-1"></a> 
Antes de empezar, lee lo siguiente en voz alta:  <br><br>
**"Todo en Python es un objeto"**  <br><br>
Muy bien, recuérdalo y repitelo constantemente cuando escribas Python. Es mas importante de lo que parece. 
&nbsp; 

❗ Si quieres comenzar YA, solo sigue las instrucciones abajo y descarga. 

🧠 Si quieres saber por que estas descargando estos dos programas. Te dejo secciones colapsables que puedes expandir con la explicación larga, pero útil.

<details>
  <summary>1. Descarga <a href="https://gitforwindows.org/" rel="noopener noreferrer" target="_blank">Git for Windows</a> </summary> 
  
## Bienvenido al mundo del collaborative coding 


### Git <a name="chapter-1.1"></a>
Wait, what? *¿Porque?* Git es un Versión Control System - VCS y es un standard para controlar las versiones de tu programa. Como referencia, GitHub, Gitlab y Bitbucket estan basadas en GIT. Cuando seas un programador profesional o crees una aplicacion, te daras cuenta que el codigo se escribe entre varios. Como funcion mas o menos, es que varias personas trabajan en una aplicacion, toman turnos para modificarla y al final se reconcilia el producto final. Sé que esto no tiene mucho sentido si apenas te estas acercando a la industria IT pero, ¿Recuerdas aquel dia cuando por fin terminaste un trabajo o tarea y guardas el archivo como "versionFinal.docx"?. Todo fino verdad?
 
Espera, 15 minutos después te has acordado que no revisaste la ortografía en los últimos párrafos y que querias cambiar una imagen. Abres el archivo y lo haces. Esta vez, lo guardas como "versionFinalFinal.docx". Uff, que alivio terminar por fin.
 
Al día siguiente abres el archivo por que necesitas agregar una nueva sección que te han pedido y lo guardas como "versionFinalLaBuena.docx". 
 
Todos hemos estado ahi, y no nos engañemos, sabemos que esa no sera la ultima vez que guardes el archivo y que en tu directorio vas a tener algo como:
 
![image](https://user-images.githubusercontent.com/71740335/149613632-ee3088c1-d6a7-4f59-a48a-d1354e1d39a6.png)

Cual fue primero y cual funciona? En ese momento lo sabes, en 6 meses; quien sabe. Y por eso usamos GIT, cada modificacion lleva un comentario y un usuario, solo se tiene una rama o branch principal, comunmente llamada Main. Cada modificacion es (usualmente) rastreable. Como Bonus, usaremos algunos comandos de Git, los mas basicos.
 
Git viene con un GUI y un CLI - Command Line Interface. Lo que nos interesa de Git for Windows en este momento es lo que sigue: BASH.

### Bash for windows <a name="chapter-1.2"></a>

Bash es Unix Shell. Siempre que escuches Shell piensa en: Interprete de comandos que corre programas, típicamente en una consola como [cmd](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmd) o [putty](https://www.putty.org/). Bash es el lenguaje con el que ejecutas comandos. 

![image](https://user-images.githubusercontent.com/71740335/149614223-d18d4ac9-9841-463e-9f53-530141d1093a.png)
 
Voy a utilizar algunos comandos básicos en bash, estos te serán útiles ya que la mayoría de los servidores corren en alguna versión de unix/linux lo que los convierte en un stardard de facto. Para la gente usando zsh, los comandos de bash funcionan -en teoria- igual en mac. 
 
</details>
<details>
<summary>2. Descarga <a href="https://www.python.org/downloads/" rel="noopener noreferrer" target="_blank">Python3 para Windows</a> </summary><br>
 
Ve a https://www.python.org/ y descarga e instala Python.<br><br>

![image](https://user-images.githubusercontent.com/71740335/152736743-11edf72b-9fc2-4674-adb4-f4bbd4eca94a.png)
</details><br>

## Virtual Environment <a name="chapter-2"></a> 

### IDLE <a name="chapter-3"></a> 

Cuando empezamos a utilizar Python, es muy fácil pasar por alto la joya que es idle. Ademas de IDLE, tenemos [Pycharm](https://www.jetbrains.com/pycharm/) de Jetbrains. Es una bestia de IDE y una delicia de usar. Ironicamente, [VSCode](https://code.visualstudio.com/) se ha convertido practicamente en el standard de la industria

Para lanzar IDLE, presiona win key + r o en el menú, busca la opcion de run. Escribe wt y presiona enter.<br>

![image](https://user-images.githubusercontent.com/71740335/152742960-61bed06f-767a-4f5e-85bc-02e966f5304c.png)

Esto es lo que verias. Por default windows abre un command prompt clásico, lo que tienes que hacer es dejar git bash como default. Esto lo haces seleccionando la flecha para abrir un menú.

![image](https://user-images.githubusercontent.com/71740335/152751645-0b6ca6c4-9916-4d26-98ac-cdec29138da9.png)


![image](https://user-images.githubusercontent.com/71740335/152751558-adf02748-d7b2-491f-b7d1-270121cce79a.png)

Una vez que abres el menú, selecciona Git Bash como determinado. Guarda el perfil y renicia.

![image](https://user-images.githubusercontent.com/71740335/152752001-17835be1-760a-4db7-8118-7de030116cac.png)

Así se ve Git bash for windows como perfil determinado.

![image](https://user-images.githubusercontent.com/71740335/152752158-00ece3d3-945e-48c2-8cbc-094d38ff4b98.png)

Para lanzar IDLE ejecuta el siguiente comando.

```python
python -m idlelib.idle 

``` 
