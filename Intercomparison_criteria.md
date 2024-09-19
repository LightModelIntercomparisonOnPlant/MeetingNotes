# Echelles:
  - temporelle: snapshot ou intégration sur la journée (ou autre)
  - spatiale: capteur, organe, plante, branche / rameau (dans le cas d'un arbre) ?, scène entière / couvert.

# Variables:
  - capteurs -> éclairement / irradiance
  - pas de capteurs -> absorbtion et irradiance
  - par unité de surface
  - Rediffusion: pour comparer les modèles entre eux, séparer le 1er ordre et la rediffusion.
  - Définition de bandes de longueur d'onde, e.g. dans les bandes extrèmes ou il peut y avoir bcp de rediffusion ou infrarouge..
  - Application photomorphogénèse: rayonnement directionnel. Est ce que les modèles peuvent le sortir ? Est ce qu'il y a des données ?

# Critères:
## Calcul:
  - Ref: 1 CPU, sur une seule machine
  - Parallélisation: scale jusqu'à combien de procs ?
  - GPU ? Est-ce que ça marche ?
  - Jusuqu'à quelle complexité on peut aller avec quel modèle
  - Permet de justifier le choix d'un modèle en fonction des ressources disponibles
  - Evaluation sur des scènes intégrées dans le temps ou snapshot
## Evaluation capteurs:
  - RMSEp et biais, model efficiency
  - autre ?
## Génériques
  - critères de dispertion: "relative distance RDP" (?) -> permet de voir si un modèle est vraiment différent des autres
  - dispertion
  - A l'échelle de l'organe:
    - préciser la situation dans la scène: + / - haut ou bas dans le couvert,
    - selon l'orientation de l'organe
  - Sensibilité des modèles à certain paramètres
    - ciel
    - propriétés optiques
    - structure
## Resolution
  - Faire une étude de sensibilité sur la résolution, et lien avec le temps de calcul.
