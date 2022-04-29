
 <!-- encabezados -->
# mi titulo
## mi titulo 2
### mi titulo h3
 <!-- esto es un texto negrito -->
this is an **italic** text
 <!-- esto es un texto tachado -->
esto es un ~~texto~~ tachado 

 <!-- UL -->
 * manzana
    * apple 2
 * naranja

 1. apple
    1. apple 2
 2. orange

 <!-- general url -->
 [youtube.com](https://www.youtube.com/c/PowerBITrujillo)

  [youtube.com](https://www.youtube.com/c/PowerBITrujillo "power bi trujillo")

 <!-- general citas -->
  > this is a quote

 <!-- general lineas separadoras -->
  ___

  _ _ _

   <!-- escribir codigo dentro de ``-->para escribir codigo usar  ``

`console.log('hello word')`

```
Margem Contribuição = 

VAR vTotalFixo = 
    CALCULATE(
            [Faturamento],
            ALLSELECTED(fVendas)
        )

RETURN 

    DIVIDE(
        [Faturamento],
        vTotalFixo
    )
```
<!--  para general tablas-->

| nombre    | apellido  | edad  |
|-----------|:---------:|------:|
|pedro      | castillo  |18     |
|stefanoia  | caro      |19     |

![logo](messi.png "messi logo")

<!--  GIT HUB MARKDOWNs-->

* [X] task 1
* [ ] task 3
* [X] task 4 

:smiley:

:+1:

**Trucos markdown**
[markdown]( https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

```
 ** para subir por primera vez al repositorio
git init   //iniciar git
git status   // para revisar si se ah hecho algun commit
git add .
git commit -m "mi prmer ejm con markdown"
git remote add origin https://github.com/pcastillog/test.git  // para subir al repositorio de git
git push origin -u origin master



***
para subir cambios cuando ya subiste un proyecto

git push origin master
git commit -m "mi cambio"
git add .
git push origin master
```



