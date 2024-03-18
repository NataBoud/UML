# EXO1 — Diagramme de cas d’utilisation UML :Identification des acteurs et de cas d’utilisation simple

### On considère une borne de chargement de titre de transport Navigo. Les utilisateurspeuvent charger leur Navigo et les techniciens peuvent intervenir en cas de panne.

- `Question 1:` Pour charger son titre, le client dépose son titre et suit les instructions indiquées. Quel est l’acteur et l’action dans ce cas d’utilisation.

L’acteur - Client 
L'action - chargement de titre ;

- `Question 2 :` Jojo, dont le métier est technicien au sein de la RATP, veut charger le navigode son fils. Pour modéliser cette activité de Jojo, doit-on définir un nouvel acteur ? Comment modélise-t-on ça ?

Acteur : Client (cela reste toujours client)
Action : Charger le Navigo de son fils

- `Question 3 :` Lorsque Jojo vient avec ses outils pour réparer la borne en cas de panne, est-il considéré comme un nouvel acteur ? Comment modélise-t-on cela ?

Acteur : Technicien 
Action : Réparer la borne en cas de panne

- `Question 4 :` Certains agent de la RATP qui ne sont pas des techniciens sont aussi qualifiés pour opérer des opérations de maintenance en plus des opérations habituelles des techniciens telles que le remplacement de certains pièces et produits. Ils sont donc techniciens en plus d'être agents. Comment modéliser cela ?

Acteur : Agent  -----> et souclasse Technicien 
Action : Opérer des opérations de maintenance en plus des opérations habituelles

`Généralisation : le cas A est une généralisation du cas B (B est une sortede A ou le cas d’utilisation enfant B est une spécialisation du casd’utilisation parent)
Utopios® Tous droits réservés 33`
