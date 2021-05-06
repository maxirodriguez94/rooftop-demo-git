# Rooftop Academy

Esto es un _proyecto_ de ejemplo para el curso de **Rooftop Academy**.

## Instalacion

Lo primero que debes hacer es clonar el proyecto

```
git clone https://github.com/maxirodriguez94/rooftop-demo-git
```

## Recomendaciones

```js
var ejemplo = false
```
     
###### Agradecimientos

- Gracias Rooftop Academy



###Manejo de directorios y archivos

Para ingresar a una carpeta:

```
cd C:/carpeta
```

Para volver a la carpeta anterior: 
```
cd ..
```

Para listar archivos y carpetas :

###### Windows

```
dir
```

###### Linux y mac

```
ls
```
---

### Para trabajar con git

Si es la primera vez que usamos git, sera necesario configurar las credenciales para comenzar a comitear pushear.

```
git config --global user.email "email@..@"
git config --global user.name "nombre-de-usuario"
```

Clonar un proyecto

```
git clone https://github.com/maxirodriguez94/repositorio
```

Agregar cambios

```git add nombre-del-archivo.ext```

Verificar el estado actual del espacio de trabajo

```git status```

Crear una rama

```git branch nombre-de-la-rama```

Para empaquetar cambios

```git commit -m "explicamos los cambios realizados"```

resetear url : 
```git remote set -url origin "url"```

Para saber URL del origin

```git remote -v```