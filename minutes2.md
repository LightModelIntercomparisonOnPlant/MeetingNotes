# Virtual Meeting 15/11/2024

## Agenda
Writers : Aurelien and Christophe

1. The benchmark : state of the art and RAMI comparison

* [LESS-RT](http://lessrt.org)
* [DART for 3D vegetation](https://dart.omp.eu)

2. Development : What's new? 

* [Reading and writing PlantGL scene](https://github.com/LightModelIntercomparisonOnPlant/SceneManagement/blob/main/tutorials/scene_tuto.ipynb) (Aurelien) (5mn)
* [Definition of a radiative scene](https://github.com/LightModelIntercomparisonOnPlant/TemplateScene) (Christian) (5mn)
* [Tutorial](https://github.com/LightModelIntercomparisonOnPlant/SceneManagement/blob/main/tutorials/caribu_tuto.ipynb) : Runing Caribu on the radiave scene (Aurelien)

3. Next steps : Your contributions

* **Use Cases** : 3D/3D+t plus optical properties & description (see RAMI IV)
* **Light Models** Publication (doi) + check inputs + tuto
* **Benchmark the models** : compare the result and build a table for needed outputs / plot the results
* **Web site** : strategy to detailled the benchmark / data paper

## Participants
* Aurelien Besnier
* Christian Fournier
* Christophe Pradal
* Gaetan Heidsieck
* Tim Oberlaender
* Romain Barillot
* Remi Vezy
* Thomas Arsouze

## Excused
* Raphael Perez
* Arman Grumel

## Meeting
- Add opf format in scene management (remi)
- Add global frame in scene management (christophe)
- complete a tutorial scene (Christian)
- add a wrapper to archimed (remi/christian)
- romain : make a tutorial to provide a scene with MTG, optical properties and the results with Caribu.
- tim : import the scene to GROIMP
- tim :  run the scene management code and the run of the models in Docker. Not only in Python.
- Thomas: archimed (remi/thomas). Design an architecture to work on Docker.
- Gaetan : provide a dummy scene
- Remi : Documentation of the scene.
- Remi : how to manage a sky rather than ponctual lights
- Remi : export the scene to ops
- Remi : use case with palm tree, coffee and cocoa
- Romain : RATP / RER

