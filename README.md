# Définitions de structure FHIR des données d'identification des acteurs de santé
## Contexte de publication des définitions de structure

L’interopérabilité est la capacité d’un système d’information à communiquer avec d’autres systèmes d’information sans multiplier les efforts de développements. C'est un enjeu important pour la e-santé : pour que cette communication dématérialisée soit possible, il faut que tous les acteurs et surtout, tous leurs systèmes d’informations parlent le même langage. C’est dans ce cadre d’interopérabilité que l’Agence du Numérique en Santé propose une nouvelle offre de services, en mettant à disposition des utilisateurs de nouvelles extractions au format JSON, structurés selon la norme l’interopérabilité Fast Healthcare Interoperable Ressources (FHIR).

Une définition de structure définit les contraintes pour un champ dans une ressource FHIR. Les définitions de structure font également référence à des ensembles de valeurs qui associent des systèmes de code et des ressources FHIR.

L'agence du numérique en Santé propose ici les définitions de structure FHIR des données d'identification des acteurs de santé pour concertation.

## CONCERNANT L’API
Une API d'interrogation des données FHIR d'identification des acteurs de santé conforme au définitions de structure est en cours de développement par l’Agence du Numérique en Santé. Un premier service est disponible pour répondre à des besoins institutionnels. Un dossier de spécifications techniques et fonctionnelles, mises en concertation mi-2020, est consultable sur le site de l'ANS https://esante.gouv.fr/actualites/mise-en-concertation-du-nouveau-dsft-de-lannuaire-sante. Un service ouvert à tous exposant les données en libre accès doit ouvrir dans les prochains mois. 

Cette nouvelle offre met à disposition des web-services en mode :
-    « FULL », pour récupérer l’ensemble des données disponibles ; 
-    « DELTA », pour récupérer uniquement les fiches modifiées depuis une date donnée : ce mode correspond aux fichiers d’extractions différentielles sollicités par les acteurs de santé.
-    « UNITAIRE », pour récupérer les informations d’une seule personne ou une structure.
Les fichiers sont au format JSON, structurées selon la norme d’interopérabilité FHIR. 
 
Enfin, ce nouveau service offre la possibilité de récupérer les données de l'Annuaire santé via plusieurs critères de recherche : par profession, par géographie, par identifiant national, ou encore par type de personne physique ou morale.

Vous trouverez les dernières informations à ce propos sur le site de l'ANS : https://esante.gouv.fr/securite/annuaire-sante.


A noter que ces structures définitions sont également disponibles sur simplifier.net : https://simplifier.net/Modelisationdesstructuresetdesprofessionnels/~introduction



© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
