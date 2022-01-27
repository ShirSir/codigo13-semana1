# codigo13-semana1
# Comando para GIT
```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- :eye: crear una :file_folder: carpeta oculta llamada ```git```

```
git status
```

- Poder listar y ver si los archivos están listos para subir
- ojo e caso de los archivos no esten listos se veran rojos y cuando lo esten de color verde.
```
git add .
git add nombre_de_archivo
```

- Agrega los archivos a la memoria git, es decir los guarda en un STASH
```
git  commit -m "comentario"
```

- crea un punto d elinea de tiempo de nuestros cambios y a estos se le es posible adjuntar un comentario.
- Los comentarios deben estar relacionados a los cambios realizados, es una recomendacion.

```
git  push origin main
```
- Sirve para poder subir los cambios al repositorio en la nube, en este caso gitHub

```
git  pull origin main
```
- :eye: sirve para poder descargar los cambios en nuestro repositorio  en la nube , en este caso gitHub 

```
git  branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro localmente.

```
git  branch
```
- :eye: sirve para poder listar los branch que tengo localmente  y me dice en cual me encuentro localmente.


```
git checkout -b nombre_del_branch
git  check out -b develop
```

- Sirve para crear una rama principal
- :eye: sirve para crear una rama principal 

```
git checkout  nombre_del_branch

```
- Sirve para poder moverme entre ramas.
-:eye: solamente se crea el branch, si el checkout no tiene -b solo e spara moverse entre ramas.
