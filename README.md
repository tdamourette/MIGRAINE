MIGRAINE
========

Mécanisme Installé pour Gérer et Rechercher l'Abscence d'INE

Suite à une rencontre avec JMD, on s'est rendu compte que le Kwartz dans sa version 5 avait intégré une moulinette pour les nouveaux utilisateurs (nous qui avions prévu de la recoder ... Ouf on s'en est rendu compte à temps ... Merci JMD !  )

Nous nous sommes rendu compte que la moulinette se base sur les INE et non plus sur les login (ouf  ), mais le soucis est qu'il peut arriver durant l'année scolaire de nouveaux élèves, et afin de gagner du temps on remplie sa fiche rapidement sans se soucier du numéro INE.
Et là ça aurait été problématique pour ces comptes qui auraient été recréés, etc.

Donc pour pouvoir retrouver plus rapidement les élèves qui n'ont pas d'INE, plutôt que de les parcourir 1 par 1 (avec 960 ça peut prendre un temps certain, voir un certain temps !) on a développé un petit script qui nous affiche les élèves n'ayant pas ce numéro.

Il est facilement exportable et utilisable si on change les 3 premières variables, donc on vous le file 

Si il y a des questions, ne pas hésiter.

T.DAMOURETTE

/* Détail des MAJ
 * 
 * Version "2.1"
 * 
 * FIX suppresion d'un onload dans le body qui ne servait a rien pour ce script (Merci romainh)
 * FIX des opérateurs logique (Merci ABDev)
 * 
 * 
 * Version "2.0"
 * 
 * FIX les login commencant par z n'étaient pas pris en compte
 * FIX agrandissement de l'espace en cas de nom de groupe long dans la liste
 * ADD fonction qui permet de trouver les gidnumber de manière dynamique (Merci romainh)
 * ADD fonction qui met en forme le nom de domaine LDAP en fonction du nom de domaine (plus simple pour certains utilisateurs)
 * ADD une interface pour changer directement les 3 variables qui nous intéressent sans toucher au code
 */
