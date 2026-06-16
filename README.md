# WebGIS - Les coses de Marina

## Descripció del Projecte
Aquest repositori conté el codi font del projecte de desenvolupament web i cartografia digital interactiva (WebGIS) per a l'establiment comercial "Les coses de Marina", ubicat al municipi de Valls (Alt Camp). El desenvolupament s'emmarca en l'aplicació pràctica d'eines d'anàlisi territorial, accessibilitat i sostenibilitat aplicades al comerç de proximitat.

## Estructura de l'Aplicació Cartogràfica
El lloc web integra diferents solucions de cartografia interactiva interactuant amb el disseny front-end:

* **Cartografia de Proveïdors (`nosotros.html`):** Visualització espacial de la xarxa de distribució i producció ètica. Implementació de funcions de control i renderització de marcadors ràster dinàmics a partir de bases de dades GeoJSON.
* **Cartografia d'Accessibilitat Local (`ubicacion.html`):** Anàlisi geoespacial de l'entorn urbà de l'establiment. Integra la localització dels punts d'aparcament i PDI mitjançant iconografia vectorial gestionada a través de Leaflet DOM (`L.divIcon`) sobre cartografia base de Carto Voyager.

## Stack Tecnològic
* **Sistemes d'Informació Geogràfica (SIG):** QGIS 3.x i connector `qgis2web`.
* **Desenvolupament Front-end:** HTML5, CSS3 (propietats avançades d'ajust d'aspect-ratio) i framework Bootstrap 5.
* **Llibreries de Web Mapping:** Leaflet.js i FontAwesome per a iconografia de nodes.

## Desplegament
L'aplicació es troba completament operativa i desplegada en servidor públic mitjançant el servei de GitHub Pages.
