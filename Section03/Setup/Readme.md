## Instalación y configuración de Visual Studio Code
Keywords: `VS-Code` `Setup` `Python` `Jupyter` `Markdown` `Powershell` `Material-Icon-Theme` `MagicPython` `HTML-CSS` `GitHub-Repositories` `GitHub-Pull-Requests-and-Issues`

Para la gestión de repositorios GitHub a través de Visual Studio Code, es necesario instalar el entorno de desarrollo integrado (IDE) y diferentes extensiones.

<div align="center">
<br><img alt="R.TeachingResearchGuide" src="Graph/VSCode.png" width="30%"><br><br>
</div>


### Objetivos

* Instalar y configurar la interfaz VS Code.
* Instalar y configurar complementos documentación Markdown, Python, HTML, CSS y los complementos para gestión de repositorios de GitHub.


### Requerimientos

* Cuenta GitHub. [:mortar_board:Aprender.](../../Section01/GitHubRepository)


### Descarga e instalación de VS Code

1. Ingrese a https://code.visualstudio.com/, seleccione su sistema operativo y de clic en el botón `Download`.

![R.TeachingResearchGuide](Screenshot/VSCodeDownload.png)

2. Desde la carpeta de descargas, ejecute el instalador, acepte los términos de licencia y de clic en el botón `Next >`

![R.TeachingResearchGuide](Screenshot/VSCodeInstallLicense.png)

Utilice la ruta por defecto direccionada a la carpeta de su usuario local y de clic en el botón `Next >`, utilice el nombre por defecto para la creación de la carpeta de Inicio.

![R.TeachingResearchGuide](Screenshot/VSCodeInstallPath.png)

En las opciones adicionales, marque las casillas _Register Code as an editor supported file types_ y _Add to PATH_, de clic en `Next >` e `Install`

![R.TeachingResearchGuide](Screenshot/VSCodeInstallAdditionalTasks.png)

Al finalizar la ejecución, de clic en el botón `Finish`. Automáticamente, se abrirá la aplicación.

![R.TeachingResearchGuide](Screenshot/VSCodeInstallFinish.png)


### Configuración general de VS Code

1. En la ventana principal encontrará la pestaña _Get Started_ que le permitirá realizar las configuraciones preliminares, para iniciar, seleccione el tema de su preferencia, p. ej., _Light_

![R.TeachingResearchGuide](Screenshot/VSCodeTheme.png)

2. Active las opciones de sincronización de configuración entre múltiples dispositivos dando clic en el botón `Enable Settings Sync`. En la parte superior de la ventana podrá observar que se muestran diferentes opciones de búsqueda y un botón para ingresar a su cuenta, de clic en `Sign in & Turn on`

![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSync.png)

De clic en el botón _Sing in with Microsoft_ para ingresar utilizando su cuenta de correo de Microsoft Outlook, o en _Sign in with GitHub_. Para este ejemplo, realizaremos el ingreso a través de una cuenta en GitHub.

![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSyncLogin.png)

De clic en el botón `Authorize Visual-Studio-Code` y luego en el botón `Open Visual Studio Code`

![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSyncLogin1.png)
![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSyncLogin2.png)
![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSyncLogin3.png)

Luego de realizar el ingreso y la autorización, podrá observar en la parte inferior derecha de la ventana de VS Code, un mensaje indicando que las opciones de sincronización de configuración se encuentran activas.

![R.TeachingResearchGuide](Screenshot/VSCodeEnableSettingsSync1.png)

3. Visualice las instrucciones de _One shortcut to access everything_, correspondientes a la combinación de teclas <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> que permiten realizar desde la parte superior de la ventana, búsquedas de elementos dentro de todo el entorno de VS Code.

![R.TeachingResearchGuide](Screenshot/VSCodeOneShortcut.png)

4. En _Rich support for all your languages_, de clic en el botón `Browse Language Extensions` 

![R.TeachingResearchGuide](Screenshot/VSCodeBrowseLanguageExtensions.png)

Automáticamente ha sido redireccionado al administrador de extensiones o Extensions Marketplace, cuyo atajo por teclado es <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>X</kbd>

![R.TeachingResearchGuide](Screenshot/VSCodeBrowseLanguageExtensionsMarketplace.png)

En la casilla de búsqueda, ingrese e instale las siguientes extensiones:

**GitHub Repositories**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceGitHubRepositories.png)

**GitHub Pull Requests and Issues**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceGitHubPullRequestsIssues.png)

**Python de Microsoft**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplacePython.png)

> Luego de la instalación del paquete, podrá observar que se despliega una nueva pestaña _Get Started_ para la configuración del entorno de Python dentro de VS Code.

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplacePythonGetStarted.png)

De clic en el botón `Select Python Interpreter`, ingrese la ruta de Python instalada en su equipo local, p. ej., `C:\Python310\python.exe`

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplacePythonGetStartedInterpreter.png)

**Jupyter de Microsoft** 

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceJupiter.png)

> La instalación de Jupiter se realiza automáticamente al instalar la extensión Python de Microsoft 

**Markdown de Yu Zhang**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceMarkdown.png)

**Powershell de Microsoft**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplacePowerShell.png)

**Material Icon Theme de Phillip Kief**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceMaterialIconTheme.png)

> Con esta extensión, podrá visualizar los íconos asociados a los archivos de Python y Markdown.

**MagicPython de MagicStack Inc.**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceMagicPython.png)

**HTML CSS Support de ecmel**

![R.TeachingResearchGuide](Screenshot/VSCodeMarketplaceHTMLCSS.png)

> Busque e instale las demás extensiones requeridas para su proyecto.

5. Desde la ventana principal _Get Started_, podrá observar que dispone de diferentes opciones de configuración adicionales de acuerdo a las extensiones instaladas.

![R.TeachingResearchGuide](Screenshot/VSCodeGetStarted.png)

> La ventana _Get Started_ puede ser abierta desde el menú _Help / Get Started_.


### Actividades complementarias:pencil2:

En la siguiente tabla se listan las actividades complementarias a ser desarrolladas por el estudiante.

|  #  | Alcance                                                                                        |
|:---:|:-----------------------------------------------------------------------------------------------|
|  1  | Descargue, instale y configure VS Code.                                                        |
|  2  | Descargue, instale y configure las extensiones requeridas para el desarrollo de sus proyectos. |


### Preguntas y respuestas Q&A

| Pregunta                                                       | Respuesta                                         |
|----------------------------------------------------------------|---------------------------------------------------|
| ¿VS Code permite la gestión Git de mis repositorios en GitHub? | Sí, a través de la extensión GitHub Repositories. |

> Ayúdame desde este [hilo de discusión](https://github.com/rcfdtools/R.TeachingResearchGuide/discussions/24) a crear y/o responder preguntas que otros usuarios necesiten conocer o experiencias relacionadas con esta actividad.


### Referencias

* [Referencias generales](../../References.md)
* [Abreviaturas y definiciones generales](../../Definitions.md)
* [Consejos y buenas prácticas de desarrollo colaborativo](../../BestPractice.md)
* https://code.visualstudio.com/docs/setup/setup-overview
* https://code.visualstudio.com/docs/setup/windows
* https://code.visualstudio.com/docs/getstarted/introvideos
* https://code.visualstudio.com/docs/getstarted/themes


### Control de versiones

| Versión    | Descripción                                                                           | Autor                                      | Horas |
|------------|:--------------------------------------------------------------------------------------|--------------------------------------------|:-----:|
| 2022.09.14 | Versión inicial. Descarga e instalación de VS Code. Configuración general de VS Code. | [rcfdtools](https://github.com/rcfdtools)  |   5   |


_R.TeachingResearchGuide es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](../../LICENSE.md)._

_¡Encontraste útil este repositorio!, apoya su difusión marcando este repositorio con una ⭐ o síguenos dando clic en el botón Follow de [rcfdtools](https://github.com/rcfdtools) en GitHub._

| [Anterior](../Readme.md) | [:house: Inicio](../../Readme.md) | [:beginner: Ayuda / Colabora](https://github.com/rcfdtools/R.TeachingResearchGuide/discussions/24) | [Siguiente](../SingleProject) |
|--------------------------|-----------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------|

[^1]: 