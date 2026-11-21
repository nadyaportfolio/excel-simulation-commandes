# Outil de simulation des commandes (DRP) – Excel

**Outil** : Excel · **Projet 7**

**Objectif** : rendre la passation de commande plus fiable, pour limiter les ruptures et les surstocks.

**Démarche**
- Contrôle des données : 3 anomalies (dates hors périmètre, prévisions négatives, clé orpheline)
- DRP V1 : projection du stock sur 8 semaines et détection des ruptures
- DRP V2 : stock de sécurité, MOQ et transport
- Analyse ABC-XYZ et gestion par exception (5 profils)

**Résultats** (boutique 1201)
- Taux de rupture : 80 % en V1, 24 % en V2, mais un stock moyen multiplié par 18
- 90 % des références ont une demande volatile
- V3 avec un stock de sécurité lissé : rupture 20 % et stock -12 % par rapport à la V2

**Recommandations**
- Utiliser le DRP V2 au quotidien pour anticiper les commandes
- Ajouter une gestion par exception pour traiter d'abord les urgences
- Étendre l'analyse ABC-XYZ à toutes les boutiques avant de généraliser la V3

**Compétences** : analyse des approvisionnements, optimisation de la supply chain

**Fichiers** : `P7_DRP_V1_V2_092026.xlsx`, `P7_presentation_092026.pptx`
