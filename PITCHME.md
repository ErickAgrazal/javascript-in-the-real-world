## Javascript en el mundo <span style="color: #e49436">profesional</span>
#### <span style="color: #e49436">¿Quién soy yo?</span>
##### Erick Agrazal
#### <span style="color: #e49436">¿A qué me dedico?</span>
##### A muchas cosas...

---

¿A qué me dedico?
-----------------
###### - All Safe Solutions <span style="color: #e49436">(55%)</span>
###### - Smart Motion <span style="color: #e49436">(20%)</span>
###### - Profesor <span style="color: #e49436">(20%)</span>
###### - Entre otras cosas <span style="color: #e49436">(5%)</span>

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
- Un *framework* para crear interfaces 
  gráficas multiplataformas (*Adobe Flex*) 

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

![Javascript Logo](assets/javascript_logo.png "Javascript Logo")
- European Computer Manufacturers Association <span style="color: #e49436">(ECMA)</span>

---

Javacript en el día de hoy
--------------------------

![You're wrong kiddo](assets/javascript_you_are_wrong.png "You're wrong kiddo")

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

![Vue Logo](assets/vue_logo.png)
- Jquery... <span style="color: #e49436">Fue genial.</span>
- Angular 1.0 JS
- Angular 2.0 JS
- React JS
- Vue JS

---

Backend
-------

Llegó Node.JS en 2009... <span style="color: #e49436">¡Gracias Ryan Dahl's!</span>
![NodeJS](assets/nodejs_logo.png "Node JS Logo")
![Chrome V8](assets/chrome_v8_logo.png "Chrome v8 logo")

---

Backend
-------

![Express](assets/express_logo.png "Express Logo")
- Express JS
- Sails JS
- Meteor JS

---

Aplicaciones Móviles
--------------------

![React](assets/react_logo.png "React Logo")
- React Native
- Titanium

---

Aplicaciones Locales
--------------------

![Electron](assets/electron_logo.png "Electron logo")
- Electron JS

---

¡Hasta IoT y Robótica!
----------------------

![Jhonny Five](assets/jhonny_five_robot_2.png "Jhonny Five Logo")
- Jhonny Five JS
- NodeMCU
- Arduino

---

¡Incluso Bases de Datos!
------------------------

![Mongo DB](assets/mongodb_logo.png "Mongo logo")
- Mongo DB <span style="color: #e49436">(Para las consultas)</span>

---

¿Quién utiliza Javascript?
--------------------------

![Production Images](assets/production_js_logo.png "Production Images")

---

Seguridad en Javascript
-----------------------
![Mr. Robot](assets/mr_robot_logo.jpg "Mr. Robot Logo")
- Ataques:
  - XSS <span style="color: #e49436">(Cross-Site Scripting)</span>
  - CSRF <span style="color: #e49436">(Cross-Site Request Forgery)</span>
  - *Básicamente los mismos que los demás lenguajes (Backend)*

---

Seguridad en Javascript (Express)
-----------------------
![Mr. Robot](assets/mr_robot_logo.jpg "Mr. Robot Logo")
- HTTPS
- CSURF, <span style="color: #e49436">protección contra CSRF</span>
- XSS

---

Seguridad en Javascript (Express)
-----------------------

- Parametrización de consultas
- SQLMap, <span style="color: #e49436">herramienta para detectar 
  ataques de inyección de SQL</span>
- NMAP y SSLYZE, <span style="color: #e49436">probar
  configuraciones</span> de SSL, métodos de cifrado, llaves
  además de la revisión de la validez de los certificados digitales.

---

No todo es bonito...
-------------------------
![Javascript Fatigue](assets/javascript_fatigue.jpg "Javascript Fatigue")
- No funciona (tan) bien para cálculos complejos.
  - 2^53-1
- La *fatiga* de JS.

---

¿Dónde aprender Javascript?
---------------------------

- [Freecodecamp](https://www.freecodecamp.org/)
- [Addy Osmany](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)

---

## Para volver a ver la presentación
#### [https://github.com/ErickAgrazal/javascript-in-the-real-world/blob/master/PITCHME.md](https://github.com/ErickAgrazal/javascript-in-the-real-world/blob/master/PITCHME.md)

---

## Conclusión