# Práctica-08

1.¿Cómo se inicializa un repositorio en Git?

```bash
  git init
```
2.¿Cómo creas un repositorio en GitHub?


Para crear un repositorio en línea solo tenemos que ir a _github_ y en nuestra esquina superior derecha  en el simbolo de **+**, seleccionamos nuevo repositorio. 

3.¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

Se vinculan con la liga que te proporciona _Github_ al crear el repositorio y con el siguiente comando. 

```bash
 git branch -M main
 git remote add origin [URL]
 git push -u origin main
```
4.¿Cuál es el flujo básico de trabajo en Git y GitHub?

 Working Directory 
 ```bash
  git add 
```

Staging 
```bash
  git commit 
```
HEAD 
```bash
  git push 
```
Remote

5.¿Para qué sirve el archivo .gitignore?

Sirve para evitar llevarse a la etapa de _staging_ archivos en especificos por su extensión.

6.¿Cuál es el propósito de una rama?

Poder hacer cambios al código principal (_main_) sin afectar a este pudiendo hacer mejoras e implementaciones de una manera más segura y sin afectar al usuario. 

7.¿Qué es una fusión?

Es el proceso en donde plasmamos los cambios de una rama diferente de la _main_ a la rama _main_.

8.Explica los diferentes tipos de fusión que existen.

Existen dos tipos de fusión la automática y la manual, siempre aspiraremos a la primera pero la segunda se ocasionará cuando la información se superponga en el mismo lugar donde tendremos las opciones de **Mantener cambios propios**, **Mantener cambios entrantes**, **Mantener ambos cambios**, **Elegir manualmente los cambios**.

9.¿Cómo puedes ver el historial de tu repositorio?

Con el comando:
```bash
  git log 
```
Pero este cuenta con muchas banderas para poder definir como queremos ver el historial o incluso gaurdarlo en algun archivo txt, EJEMPLO:

```bash
  git log --oneline
```

```bash
  git log --oneline
```
```bash
  git log  --oneline --graph --all
```
```bash
  git reflog  
```

10.¿Cuál es el propósito de una etiqueta?

El propósito es mantener un versionado de tipo _v1.0.0_ para que se lleve un control en las diferentes versiones que saquemos a lo largo del tiempo, y se pueda descargar las versiones anteriores. 