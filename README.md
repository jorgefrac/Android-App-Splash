# Android Splash Screen

# Libraries
Dentro de nuestro archivo **build.gradle** tenemos que compilar nuestra librería que utilizaremos en nuestra app. La librería se llama **nineoldandroids-2.4.0** y la puedes descargar del repositorio oficial del creador en **GitHub** aquí te dejo el link para que revises la documentación también -> [com.nineoldandroids](https://github.com/JakeWharton/NineOldAndroids).

Una vez descargada tenemos que integrarla a nuestro proyecto dentro de la carpeta **libs** para ir a ella tienes que seguir la siguiente ruta **projectname/app/libs/** dentro de la carpeta **libs** agrega el archivo **.jar** que descargaste del repositorio de GitHub.

Después de agregar la librería mencionada tenemos que compilarla en nuestro proyecto, esto se hace yendo a nuestro archivo **build.gradle**  y agregando la siguiente línea de código y después sincronizar nuestro proyecto para que la reconozca.

```
dependencies {
   ...
   ...
    compile files('libs/nineoldandroids-2.4.0.jar')
}
```
