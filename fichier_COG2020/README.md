# Objectif

Les variables géographiques des communes de naissance (*code_lieu_naissance*) et de décés (*code_lieu_deces*) nécessitent une étape préalable d'harmonisation avant d'être utilisées. 

Le référentiel des codes communes (COG) utilisé dans le fichier n'est pas le même selon la date d'enregistrement du décès. La conversion des codes communes utilisés dans le référentiel 2020 permet d'harmoniser les localisations.

Des erreurs d'encodage des codes communes existent et peuvent être corrigées.

# Procédure

Comparaison des codes communes du fichier original avec le COG 2020.

Actualisation des codes communes périmés avec l'historique des mouvements communaux.

Corrections au cas par cas des codes communes inconnus. 

# Résultat

Fichier agrégé avec référentiel géoographique cohérent et actualisé.
Les variables **code_nai20** et **code_dec20** sont ajoutées au fichier original. 

**Les enregistrements doublons des décés sont supprimés**
