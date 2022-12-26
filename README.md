# MeetingPlannerProject
## Description
Ce projet est une API en SpringBoot qui permet la gestion des salles de réunion d'une PME durant le COVID.
## Technologies utilisées
SpringBoot, Swagger, JUnit.
## Fonctionnalitées
1- Ajouter un matériel(pieuvre,tableau,camera,écran) à une salle.<br>
2- Ajouter une salle.<br>
3- Lister toute les salles.<br>
4- Ajouter une matériel.<br>
5- Ajouter un matériel à une réunion.<br>
6- Lister toute les types de réunions possibles.<br>
7- Ajouter une demande de réservation d'une salle.<br>
8- Lister toute les demandes.<br>
9- Proposer une meilleur salle selon le type de la réunion et le nombre de places. <br>

## Endpoints
##### L'ajout d'une sallle 
`http://localhost:8080/addsalle`
##### L'ajout d'un matériel à une salle 
`http://localhost:8080/add_materiel_au_salle`
##### L'ajout d'une demande 
`http://localhost:8080/ajouterdemande`
##### L'ajout d'une reunion 
`http://localhost:8080/add_reunion_type`
##### Avoir une propositon sur une salle 
`http://localhost:8080/proposersalle`
##### Voir toute les demandes
`http://localhost:8080/allDemandes`
##### Voir toute les salles
`http://localhost:8080/allsalles`
##### Voir toute les réunions 
`http://localhost:8080/add_materiel_au_salle`


