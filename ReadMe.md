**nombre del estudiante:** Román Eloy Solís Reyes

**matricula:** 2630402

**objetivo de la practica:** realizar un repositorio de git y vincularlo a GitHub

**descripción del proceso realizado:**

## 1- inicio de carpeta y rama

* inicie creando un nuevo folder con el comando

```javascript
"$MKdir"
``` 

* después introduje git al folder con

```javascript
"$git init"
```

* le di un nombre a la rama principal (con el nombre "main")

```javascript
"$git branch -M main"
```

* y cree los primeros archivos

## 2- primeros commits

* verifique el estado del folder

```javascript
"$git status"
``` 

* añadí los primeros archivo que tenia

```JavaScript
"$git add -A"
```

* confirme su estado una vez mas y cree el primer commit

```javascript
"$git commit -m"
```

## 3- creación de repositorio en GitHub

* cree un repositorio con el mismo nombre del folder desde GitHub
* vincule el repositorio de GitHub con el folder que ya tenia de git

```javascript
"$git remote add original URL\_DE\_GITHUB"
```

* verifique que estuviera que se guardase la URL

```javascript
"$git remote -v"
``` 

\-y envié mi primer commit a GitHub (obviamente después de recuperar mi contraseña) :^

```JavaScript
"$git push -u origin main"
```

## 4- commit desde GitHub

* desde GitHub verifique que se subieran todos los archivo que tenia en mi folder y edite el archivo "Datos.txt" y desde la esquina superior derecha un commit
* ya con el commit listo desde GitHub lo descargue en mi folder

```javascript
"$git pull origin main"
```

## 5- commit desde el folder a GitHub

* desde el folder mofifique el archivos de "Datos.txt" corrigiendo errores de ortografía
* luego agrege las modificaciones y cree un nuevo commit y emvie los cambios a GitHub

```javascript
"$git push"
```
## 6- modificación del archivo "ReadMe"
-modificó el archivo "ReadMe.md" con las especificaciones solicitada y procederé a crear un commit ya con este modificado 

**conclusión:**
En esta practica repase una vez mas el como utilizar de manera efectiva tanto git como GitHub conociendo de una mejor manera los comando que constituyen a estos dos programas y recuperando mi contraseña de GitHub en el proceso

