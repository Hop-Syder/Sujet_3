# Projet de Transcription Automatique en Langue Fon

## Description scientifique
L'objectif de ce projet est d'utiliser des **APIs de reconnaissance vocale automatique (ASR)** existantes pour transcrire des vidéos en **langue Fon**.  
La transcription automatique de la parole en texte est un domaine clé du **traitement automatique des langues**. Cependant, les langues africaines à faibles ressources, comme le Fon, manquent souvent de données linguistiques centralisées.

Des initiatives telles que le **laboratoire des langues africaines** ont permis de collecter des données vocales et textuelles pour ces langues, contribuant à leur documentation et à leur disponibilité numérique. Malgré ces progrès, plusieurs défis subsistent :
- **Variabilité dialectale** ;
- **Manque de standardisation orthographique** ;
- **Rareté des ressources annotées**.

Ce projet se concentrera sur la **collecte de données audio** en langue Fon, l'**adaptation et l'optimisation des APIs ASR**, et l'**évaluation de la précision des transcriptions** obtenues.

## Objectifs du projet
1. **Utilisation des APIs ASR** pour transcrire des vidéos YouTube en langue Fon.
2. **Collecte de données audio** en langue Fon à partir de vidéos YouTube pour tester et améliorer les performances des APIs.
3. **Adaptation et optimisation** des APIs ASR aux spécificités de la langue Fon, en tenant compte des particularités dialectales et phonétiques.
4. **Évaluation des transcriptions** pour identifier les axes d'amélioration et proposer des solutions aux limitations.

## Structure du projet
- `dataset/` : Répertoire contenant les données du projet.
  - `videos/` : Fichiers vidéo utilisés pour la transcription.
  - `audio/` : Données audio extraites des vidéos.
  - `transcripts/` : Transcriptions générées et annotées.

## Enjeux et défis
- La **variabilité dialectale** et l'absence de standardisation orthographique compliquent l'entraînement et l'utilisation d'APIs ASR existantes.
- Le **manque de données annotées** pose des limitations à la précision des transcriptions automatiques.
- La nécessité d'**optimiser les APIs ASR** pour les adapter aux caractéristiques spécifiques de la langue Fon.

## Résultats attendus
- Une **évaluation détaillée** des performances des APIs ASR sur la langue Fon.
- Des propositions de solutions pour surmonter les **limites actuelles** des outils de transcription vocale automatique.
- Une contribution à la **documentation numérique** de la langue Fon, facilitant son utilisation dans des applications modernes.

## Technologies utilisées
- **APIs de reconnaissance vocale automatique** (telles que Google Speech-to-Text, Whisper d'OpenAI, etc.).
- Outils de traitement audio et vidéo.
- Méthodes d'annotation et d'évaluation linguistique.


