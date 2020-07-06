# Bootcamp 2020 prácticos
Repositorio de prácticos del Bootcamp generación 2020 👩‍💻👨‍💻.

El objetivo de este repositorio es poder organizar y subir todos los prácticos de los participantes del Bootcamp. Esto será de gran utilidad para el resto del grupo, de esta manera podrán visualizar como resolvieron los ejercicios el resto de los compañeras y compañeros, **la mejor manera de aprender es mirar código de otros** 🔍.

## ¿Cómo subir las soluciones de los prácticos?
1. Clonar el repositorio
2. Crear un branch con la siguiente sintaxis `[nombre]-[semana]-[practico]`
3. Pararse dentro de la carpeta del sprint
4. Crear una carpeta con la siguiente sintaxis `[nombre]-[semana]-[practico]`
5. Desarrollar la solución del práctico
6. Commitear y pushear los cambios al branch
7. Hacer un PR contra el branch `master` y pasarlo para recibir el `code review`

### 1. Clonar el repositorio
```bash
git clone https://github.com/Matea-Social/bootcamp-js-2020-practicos.git
```
### 2. Crear un branch con la siguiente sintaxis `[nombre]-[semana]-[practico]`
Antes que nada, ⚠️ asegurate de estar en el branch `master` y tenerlo actualizado con los últimos cambios.

```bash
git checkout master
git pull origin master
git checkout -B martinvarela-examplesprint-suma
```

### 3. Pararse dentro de la carpeta del sprint
Cada sprint debe tener una carpeta dónde todos podamos subir los ejercicios, esto con el objetivo de organizarnos mejor. Por ejemplo, el nombre de la carpeta del primer sprint puede ser `examplesprint`.

### 4. Crear una carpeta con la siguiente sintaxis `[nombre]-[semana]-[practico]`
Luego de estar dentro de la carpeta perteneciente al sprint en el que estemos, deberas crear otra carpeta con el mismo nombre que le pusiste al branch, por ejemplo: `martinvarela-examplesprint-suma`.
```bash
mkdir martinvarela-examplesprint-suma
cd martinvarela-examplesprint-suma
```
### 5. Desarrollar la solución del práctico
Aquí es dónde ocurre la magia 🔮, desarrolla la solución. Puedes ver un ejemplo en la carpeta `examplesprint`.

### 6. Commitear y pushear los cambios al branch
Una vez que termines de desarrollar la solución, debes subirla para que podamos aprender de tí y darte nuestro feedback sobre el trabajo.

```bash
git add .
git commit -am 'solucion de practico sobre buenas practicas de bem'
git push origin martinvarela-examplesprint-suma
```

### 7. Hacer un PR contra el branch `master` y pasarlo para recibir el `code review`
Una vez que subas el branch a los servidores de Github, debes crear un PR apuntando al branch `master` y pasarlo por slack al resto pidiendo que te hagan code review.

## Ejemplo
Dentro de la carpeta `examplesprint` podrán encontrar un ejemplo de solución a un práctico de prueba.
