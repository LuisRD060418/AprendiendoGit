# Comandos Esenciales

## Inicializando un repositorio de Git

```bash
git init
```

Inicializar un nuevo repositorio de Git. Este comando crea un nuevo repositorio de Git en el directorio actual. Configura los archivos y directorios basicos y necesarios para empezar a rastrear los cambios.

## Clonando un repositorio

```bash
git clone [repositoryURL]
```

Clona un repositorio de Git existente. Este comando crea una copia de un repositorio existente en tu máquina local. Copia el historial entero y los archivos del repositorio especificado en tu máquina local.

## Agregando archivos al area de preparación

```bash
git add [file/directory]
```

Agrega un archivo o directorio al área de preparación. Este comando prepara los cambios para el próximo commit. Agrega el archivo o directorio especificado.

```bash
git add .
```

Esto agrega todos los archivos o carpetas modificadas al área de preparación.

## Realizando un commit con un mensaje descriptivo

```bash
git commit -m "[commit message]"
```

Crea un nuevo commit con un mensaje describiendo los cambios realizados. Este comando crea un nuevo commit con los cambios que hiciste en tu repositorio local. El mensaje del commit describe los cambios hechos.

## Extrayendo cambios

```bash
git pull
```

Actualiza el repositorio local con los cambios del repositorio remoto. Extrae los cambios del repositorio remoto y los fusiona con los cambios locales.

## Enviando Cambios

```bash
git push
```

Este comando envia los cambios locales al repositorio remoto. Actualiza el repositorio remoto con los cambios realizados localmente.

## Verificando el Estado

```bash
git status
```

Muestra el estado actual del repositorio. Este comando muestra el estado del repositorio y los cambios que están o no en el área de preparación actualmente.

## Listar ramas

```bash
git branch
```

Este comando muestra en una lista todas las ramas en el repositorio actual. Muestra la rama en la que estas situado y lo resalta con un asterisco (*).

## Cambiando de rama

```bash
git checkout [branchName]
```

Este comando cambia a una rama especifica. Actualiza el directorio de trabajo para coincidir con el contenido de la rama especificada.

## Fusionando ramas

```bash
git merge [branchname]
```

Este comando fusiona una rama especifica con la rama en la que estamos situados. Combina los cambios de ambas ramas y crea un nuevo commit.

## Listar todos los commits

```bash
git log
```

Este comando muestra una lista de todos los commits en el repositorio. Muestra el autor, la fecha, y el mensaje descriptivo de cada commit que se hizo en el repositorio.

## Mostrando repositorios remotos

```bash
git remote -v
```

Este comando lista todos los repositorios remotos asociados al repositorio local. Muestra la URL de cada repositorio remoto.

## Verificando diferencias

```bash
git diff [file]
```

Este comando muestra las diferencias entre el directorio de trabajo y el area de preparación o el repositorio. Muestra los cambios hechos en el archivo especificado.

## Obtener cambios

```bash
git fetch
```

Este comando descarga los cambios hechos en el repositorio remoto y actualiza tu repo local, pero no fusiona los cambios con tu rama local.

## Resetear cambios

```bash
git reset [file]
```

Elimina un archivo especificado del área de preparación, deshaciendo cualquier cambio hecho en el archivo desde el último commit. Esto no elimina los cambios hechos en un archivo.

## Revertir cambios

```bash
git revert [commit]
```

Crea un nuevo commit que deshace los cambios hechos en el commit especificado. Esto no elimina el commit especificado, pero crea un nuevo commit que revierte los cambios hechos en ese commit.