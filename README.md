# Guía rápida herramientas fundamentales para el desarrollo del arte digital

Realizada por Raúl Federico Lacabanne (aka: knnv-ar) en estrecha relación a los documentos de la referencia. Fecha: 2022/09/12

## Herramientas fundamentales

* Editor VS Code (editor de texto)
* Terminal (gestión y administración de archivos)
* Markdown (lenguaje de marcado ligero: lenguaje de documentación)
* Git (control de versiones de archivos: mantenimiento de archivos)
* Github (repositorio de archivos: conservación de archivos)
* Javascript (lenguaje de programación: lenguaje de escritura)

## VS Code

### Definir VS code como editor de Git

https://code.visualstudio.com/docs/editor/versioncontrol#_vs-code-as-git-editor

Here are the steps to do so:

Make sure you can run `code --help` from the command line and you get help.

if you do not see help, please follow these steps:

* macOS: Select **Shell Command: Install 'Code' command in path** from the **Command Palette**.
* Windows: Make sure you selected **Add to PATH** during the installation.
* Linux: Make sure you installed Code via our new .deb or .rpm packages.

From the command line, run `git config --global core.editor "code --wait"`

Now you can run `git config --global -e` and use VS Code as editor for configuring Git

# Control de versiones en Vs Code

https://code.visualstudio.com/docs/introvideos/versioncontrol



## Git

### ¿Qué es git?

Git es un **software de control de versiones** diseñado por Linus Torvalds y lanzado el 7 de abril de 2005. Es un software gratuito y de código abierto para el **control de versiones distribuidas**: es decir, **seguimiento de cambios en cualquier conjunto de archivos**, generalmente utilizado para **coordinar el trabajo entre programadores que desarrollan código fuente de forma colaborativa** durante el desarrollo del software. Sus objetivos incluyen la velocidad, la integridad de los datos y la compatibilidad con flujos de trabajo no lineales distribuidos (miles de sucursales paralelas que se ejecutan en diferentes sistemas).

Los **sistemas de control de versiones distribuidos** son una forma de control de versiones en la que el código base completo, incluido su historial completo, es copiado en la computadora de cada desarrollador. En comparación con el control de versiones centralizado, esto permite la administración automática de bifurcación (branching) y fusión (merging), acelera la mayoría de las operaciones (excepto empujar (push) y tirar (pull)), mejora la capacidad de trabajar sin conexión (offline) y no depende de una sola ubicación para las copias de seguridad.

### Instalación de git v2.37.3

1. Descargar git desde: https://git-scm.com/

2. Instalar git en Windows 10. Recomendaciones de intalación. Tildar las siguiente opciones:

**Select components**

* Windows Explorer integration && Git Bash Here && Git GUI Here
* Git LFS
* Associate .git* configuration files with the default text editor
* Associate .sh files to be run with Bash
* (NEW!) Add a Git Bash  Profile to Wiondows Terminal

**Choosing the default editor used by Git**

* Use Visual Studio Code as Git´s default editor

**Adjunsting the name of the initial branch in new repositories**

* Let Git decide (master)

> La otra opción habilita la elección de otros nombres como por ejemplo: main, trunk, development, o cualquier otro que desees.

**Adjusting your PATH environment**

* Git from the command line and also from 3rd-party software

**Choosing the SSH executable**

* Use bundled OpenSSH

**Choosing HTTPS transport backend**

* Use the OpenSSL library

**Configuring the line ending conversions**

* Checkout Windows-style, commit Unix-style line endings

**Configuring the terminal emulator to use with Git Bash**

* USe WinTTY...

**Choose the default behavior of 'git pull'**

* Default

**Choose a credential helper**

* Git Credential Manager

**Configuring extra options**

* Enable file system caching

