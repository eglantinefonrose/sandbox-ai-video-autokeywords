# Sandbox AI Video Autokeywords

Ce projet a pour but de générer des mots clés à partir de vidéos ou d'audios.
Pour ce faire,
- On génère la **transcription écrite** de la vidéo ou de l'audio.
- On utilise un **modèle d'IA** pour générer les mots clés de la vidéo.

On utilise dans un premier temps un modèle d'IA spécifique à la génération de mots-clés (**kbir** de **ml6team**), puis ensuite un LLM (**MistralAI**) à qui on passe un prompt pour générer des mots clés spécifiques au **type de vidéo** (reportage, émission...) puis au **contenu de la video** (par exemple 'Guerre froide', 'Téléphone rouge'...).
