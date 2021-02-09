# NVM (Node Version Manager)

El objetivo de este fichero es mostrar la utilidad de nvm así como resumir los comandos que yo personalmente he utilizado.

## ¿Qué es NVM?
Nvm es un gestor de versiones de Nodejs. Te permite tener instaladas distintas versiones de node en tu equipo, además te permite  
cambiar entre ellas en cualquier momento.  

## Instalación 
**Importante**: nvm solo está disponible para linux y mac (según su repositorio oficial). Existen alternativas para windows pero no  
de los mismos creadores.  
  
Para instalar nvm puedes seguir los pasos del repositorio oficial. La última versión es la 0.37.2

El resumen en español de la instalación es el siguiente:



Lo bueno de nvm es que crea un directorio oculto en tu /home, evitandote así hacer todos los pasos del **mirar diapos** y evitamos problemas con sudo y el /usr.  
Cuando instalemos nvm se nos creará un directorio oculto `.nvm` en el cual se hayarán todas las cosas necesarias para su funcionamiento. Cuando instalemos node,  
sus distintas versiones se instalarán en `home/<username>/.nvm/versions/node/`
## Uso
Una vez instalado, podemos instalar node de la siguiente manera:  

### Última versión de node
Si queremos instalar la última versión disponible de node ejecutamos `nvm install node`  
  
**nota**: a día de hoy 09-02-2021, la última versión de node es la 15.8.0  

### Última versión LTS (Long Term Support)
Para instalar la última versión lts (explicar lts), ejecutamos el comando `nvm install --lts`

### Una versión específica de node
Si queremos instalar una versión específica de node, ejecutamos `nvm install X.X.X` donde X son los números de la versión. Por ejemplo, en clase   
teníamos que instalar la versión 14.15.5, para ello ejecutariamos `nvm i 14.15.5` (i es la versión corta de install, para no estar escribiendo tanto).  

Si ejecutamos, por ejemplo `nvm i 13` o cualquier número de versión, instalará la última versión disponible de dicha versión, no la versión .0 (osea 13.0.0).  

**Nota**: por lo general cuando instalamos una versión de node, esta se pone como la versión a utilizar pero no preocuparse que podemos cambiar eso. 
 
### Desinstalar una versión
Para desinstalar una versión de node ejecutamos el comando `nvm uninstall <version de node>`. Por ejemplo, para desinstalar la versión 14.15.5 sería `nvm unistall 14.5.5`.

### Listar versiones instaladas

### Listar todas las versiones disponibles

### Seleccionar la versión a utilizar

### Establecer una versión por defecto

### Establecer un alias

Para una versión detallada de estos comandos y del resto puesto
