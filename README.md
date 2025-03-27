# Comparaison des Modèles de Reconnaissance Vocale

Ce dépôt contient un fichier de comparaison détaillée entre les modèles de reconnaissance vocale suivants :

- **Whisper Small**
- **Whisper Medium**
- **Mozilla DeepSpeech**

## Objectif du Projet

Le but de cette comparaison est de déterminer le modèle le plus adapté pour transcription audio-texte, où nous avons décidé d'utiliser **Whisper Medium** pour sa performance équilibrée entre précision et vitesse. Ce modèle est intégré à notre projet, **Mokhtassar AI**, pour la transcription des cours.

## Critères de Comparaison

Les modèles ont été comparés selon plusieurs critères, notamment :
- **Précision** : Taux d’erreurs dans la transcription. 
- **Vitesse** : Temps d’exécution sur un même fichier audio. 
- **Compatibilité** : Facilité d’intégration avec notre projet. 
- **Ressources requises** : GPU, CPU, RAM nécessaires. 
- **Support de la langue française** : Optimisation pour le français (accents, vocabulaire 
technique). 
## Résultats de la Comparaison

| Modèle             | Précision | Vitesse d'exécution | Robustesse | Consommation de ressources |
|--------------------|-----------|---------------------|------------|----------------------------|
| **Whisper Small**   | Moyenne   | Rapide              | Bon        | Faible                     |
| **Whisper Medium**  | Élevée    | Moyenne             | Très Bon   | Moyenne                    |
| **Mozilla DeepSpeech** | Faible  | Lente               | Moyenne    | Haute                      |

## Choix du Modèle

Après avoir comparé les résultats des trois modèles, nous avons choisi **Whisper Medium** pour son équilibre entre précision et performance, tout en maintenant une consommation de ressources raisonnable. Ce modèle permet de fournir des transcriptions de qualité tout en respectant les contraintes de temps d'exécution.

## Conclusion

Le modèle **Whisper Medium** a été retenu pour sa robustesse face aux divers défis du projet de transcription, tout en étant suffisamment performant pour les besoins de notre application. 

