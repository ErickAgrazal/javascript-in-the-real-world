## Javascript en el mundo <span style="color: #e49436">profesional</span>
#### ¿Quién soy yo?
##### Erick Agrazal
#### ¿A qué me dedico?
##### A muchas cosas...

---

¿A qué me dedico?
-----------------
###### - All Safe Solutions (55%)
###### - Smart Motion (20%)
###### - Profesor (20%)
###### - Entre otras cosas (5%)

---

Javascript != Java
------------------

![Javascript_Hamster](assets/java_vs_javascript.png)

---

## Vivímos el futuro de la web, y es hermoso.
![Spotify](https://cdn-images-1.medium.com/max/800/1*7L09qgc4Xnz_vRVAKW-hhg.png)

---

## ¿Cómo llegamos hasta aquí?

---

El inicio fue Flash ...
------------------

![Adobe Flash](https://addons.cdn.mozilla.net/user-media/previews/full/144/144974.png?modified=1413224838 "Logo de Adobe Flash")

---

Flash
-----

- Reproducción de audio y video
- Comunicación en tiempo real
- Animaciones aceleradas por _hardware_
- Una sintaxis similar a **Javascript**
- Un *framework* para crear interfaces gráficas multiplataformas (*Adobe Flex*) 

---

La ilusión no demoró mucho
--------------------------

![Steve Jobs](https://qph.ec.quoracdn.net/main-qimg-2fd2f7529b33f1ccd1f95d62ad0a66e2-c "Imagen de Steve Jobs")

---

Apple nos hizo retroceder un poco
---------------------------------

>Flash es una tecnología *cerrada*, perteneciente a Adobe, y si las personas continúan usando Flash, pronto Adobe también será dueño de internet. Apple no quiere eso.
- Un "pobre" resúmen de la carta de Steve Jobs


---

Pero nos ofrecieron una solución... ¿Cierto?
--------------------------------------------

```
// ~/Desktop/interface.m

// In @interface
@property (nonatomic, assign) CGFloat lastContentOffset;

//Scroll view delegate methods
- (void)scrollViewDidEndDragging:(UIScrollView *)scrollView willDecelerate:(BOOL)decelerate
{
    if (self.tableView == scrollView) {
        if (scrollView.contentOffset.y - self.lastContentOffset < -90) {
            [self.activeField resignFirstResponder];
        }
    }
}

- (void)scrollViewWillBeginDragging:(UIScrollView *)scrollView {
    if (scrollView != self.tableView) {
        return;
    }

    self.lastContentOffset = scrollView.contentOffset.y;
}
```

---

Nacimiento de HTML5
-------------------

![HTML5](https://cdn-images-1.medium.com/max/800/1*Lk7YWiSeDYGd-ITVUXbBbA.png "HTML5 Logo")


---

Llegó Javascript, cambió el juego
---------------------------------

![Javascript Logo](assets/javascript_log.png "Javascript Logo")

---

Javacript en el día de hoy
--------------------------

![You're wrong kiddo](assets/javascript_you_are_wrong.png)

---

Javacript en el día de hoy
--------------------------

- Frontend
- Backend
- Aplicaciones Móviles
- Apicaciones Locales
- ¡Hasta IoT y Robótica!

---

Frontend
--------

- Jquery... Fue genial.
- Angular 1.0 JS
- Angular 2.0 JS
- React JS
- Vue JS

---

Backend
-------

Llegó Node.JS en 2009... ¡Gracias Ryan Dahl's!
![NodeJS](assets/nodejs_logo.svg "Node JS Logo")

---

Backend
-------

- Express JS
- Sails JS
- Meteor JS

---

Aplicaciones Móviles
--------------------

- React Native
- Titanium

---

Aplicaciones Locales
--------------------

- Electron JS

---

¡Hasta IoT y Robótica!
----------------------
- Jhonny Five JS

---

¡Incluso Bases de Datos!
------------------------

![Mongo DB](assets/mongodb_logo.png "Mongo logo")

---

¿Quién utiliza Javascript?
--------------------------

![Production Images](assets/production_js_logo.png "Production Images")

---

Seguridad en Javascript
-----------------------

---

No todo es bonito...
-------------------------

- No funciona (tan) bien para alto rendimiento.
- La *fatiga* de JS.

---

¿Dónde aprender Javascript?
---------------------------

- [Freecodecamp](https://www.freecodecamp.org/)
- [Addy Osmany](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)

---

## Para volver a ver la presentación
#### [Slides](https://github.com/ErickAgrazal/javascript-in-the-real-world/blob/master/PITCHME.md)

---

## Conclusión