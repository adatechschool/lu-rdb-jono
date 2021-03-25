# Appliquer

# Donner les requêtes SQL pour extraire :

- la liste des livres dont le titre comprend “renard”

SELECT *  FROM Livre WHERE titre LIKE ‘%renard%’

- la liste de livres de la catégorie roman

SELECT * FROM Livres WHERE nature = "roman"

- la liste des livres en cours d’emprunt. (à trouver)

Livres / Emprunt date d'emprunt > aujourd'hui

INNER JOIN

- La liste des usagers en retard pour leur retour. (à trouver)

Usager / Emprunt / date de retour ≤ aujourd'hui 

INNER JOIN
