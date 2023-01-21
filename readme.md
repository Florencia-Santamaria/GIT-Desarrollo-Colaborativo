# Curso GIT: Desarrollo Colaborativo. *Educación IT*

## Configuración Inicial
``` js
1. Configurar nombre de usuario
> git config --global user.name "Mi Nombre de Usuario"

2.Configurar correo electrónico
> git config --global user.email "mail@ejemplo.com"

3. Verificar todas las configuraciones con
> git config --list

o también podemos consultar el valor de una variable en particular con

> git config user.name
> git config user.email
```
---

## Primeros pasos
``` js
1. En la carpeta que queramos que sea el repositorio local

> git init
> git remote add origin "Link del repositorio"
```

## Comandos útiles

```js
1. Ver el estado de los archivos
> git status

2. Agregar archivos al Stage area
> git add <nombre archivo>
> git add . (agrega todos los archivos)

3. Confirmar cambios(agregar archivos al track)
> git commit -m "Mensaje explicativo del commit"

4. Ver registro de cambios
> git log 
Muestra info detallada sobre todos los commits

> git log --oneline --graph
Muestra info más resumida

5.Guardar los archivos en el repositorio Local
> git push origin rama



```