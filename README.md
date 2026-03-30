# Pruebas-HTML-CSS
Pasos Git Uso Diario
1. Entrar a la carpeta cd .ruta/de/tu/proyecto
   esto es como ejemplo, se pone la ruta de la carpeta para acceder bien a ella con git
   
(En caso de querer importar un proyecto, repositorio usar git clone ponerUrl )

2. Con este comando se pone como en espera los cambios antes de confirmalos del commit
   en caso de querer agregar todo git add . / en caso de querer guardar un cambio de solo un archivo, agregar el nombre del archivo git add app.py (esto es un ejemplo)

3. Para Confirmar los cambios, se utiliza lo siguiente.
   git commit -m "mensaje"
   

5. Para subir los cambios al repositorio remoto de github
   git push {remoto} {rama} sirve para aplicar los cambios en stagging al repositorio remoto (requiere autenticación) ejemplo: aplicar cambios del commit a la rama main en el repositorio de origen
   
   git push origin main


OTROS COMANDOS

1. para ver los cambios a nivel local
   git log

2. En caso de querer ver si hay cambios sin guardar o nuevos por aplicar
   git status

4. En caso de querer extraer los cambios del repositorio desde un pc que no cuenta con los cambios nuevos
    cd .ruta/de/tu/proyecto primero para poder entrar al repositorio, luego
   git pull

   
mi primer commit

prueba pull
