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
