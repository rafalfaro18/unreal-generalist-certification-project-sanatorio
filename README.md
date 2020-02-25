# unreal-generalist-certification-project-sanatorio

### Description

This game's level is based on El Sanatorio Duran (real location).

#### Notes:

- Requires Environment Set from marketplace to display the trees.
- Re-add the Starter Content asset pack after opening for the first time.
- Map is located in 0,0 so move landscape to (X=-94600.000000,Y=-54000.000000,Z=-6100.000000). But to fix the orientation without moving the map locate landscape at (X=54000.000000,Y=-94600.000000,Z=-6100.000000) and rotate to (Pitch=0.000000,Yaw=90.000000,Roll=0.000000).

#### Game Design - To Do:

* Usar BSP en lugar de static mesh no es problema ✔.
* No es problema que haya areas no accesibles sin pintar ✔.
* Faltan detalles (en los sotanos añadir tuberias), espacios(cuartos) muy vacios. Historia (contexto). Ambientar la escena ✔.
* Vancas desordenadas ✔. Madera demasiado brillante.
* Conectar los sotanos ✔.
* Comedor: mesas ✔.
* Orden de navegacion, no sabemos como debe proceder el jugador, debe estar mas claro.
* Terminar las ventanas ✔.
* Arreglar los agujeros entre BSPs. Visibilty Collision ✔.
* 25% vacio deberia llenarlo piedras objetos o no hacerlo navegable ✔.
* Edificio vacio de atras puede quedar ahi, no navegable. No parte del juego ✔.
* Solucionar oscuridad con algun tipo de indirect light ✔.
* Twiquear el color para que no se vea azul ✔.
* Quitar el direct light (el sol) y sustituir con otra cosa ✔. Para que no haya luz desde el suelo ✔.

#### Blueprints - To Do:


* Trabajr feedback en unlit para enfocarse en funcionalidad:
* Prints si me da tiempo pasarlos a widgets de ui.
* Revisar logica de la bateria, si linterna esta apagada no deberia consumir bateria ✔. 
* Interfaz "Interaction" para los que repiten funcionalidad, NPCs overlaps para no repetir logica.

#### Asset Creator - To Do

* Actualmente tengo poco scattering de iluminacion indirecta, solucionarlo.
* Revisar material del piso, esta muy plano en especial el zacate.
* Meterle volumetric a la niebla.
* Para arreglar el azul podria usar un emissive tambien ✔.
* A las luces del gate aumentarles el atenuation radius un poco pero arreglar primero el suelo para que no brille ✔.
* Arreglar el material que brilla de las paredes (el anaranjado, plaster). Brillo espantoso. Roughness y luz indirecta del nivel ✔.
* Settings de iluminacion en general.
* Material de las mesas.

