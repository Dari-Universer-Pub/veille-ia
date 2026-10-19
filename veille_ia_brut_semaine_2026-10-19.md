# Veille IA brute — semaine du 2026-10-19

Période couverte : 12/10/2026 → 19/10/2026 (7 derniers jours). Seules les informations dont la date de publication a pu être confirmée dans cette fenêtre sont retenues.

## Nouveaux modèles locaux et open-source

### Liquid AI lance LFM2.5-24B-A2B
- **Date de publication** : 13/10/2026
- **Résumé** : Liquid AI a publié LFM2.5-24B-A2B, son plus grand modèle de la famille LFM2.5 : un modèle de raisonnement en mixture-of-experts avec 24 Md de paramètres totaux mais seulement ~2,0–2,45 Md de paramètres actifs par token (64 experts, top-4 routing), conçu pour des agents embarqués rapides. Poids ouverts (licence LFM Open License v1.0) disponibles sur Hugging Face et le Liquid Playground, avec un contexte de 131 072 tokens. Le fabricant revendique des performances comparables à Qwen3.6-35B-A3B sur plusieurs benchmarks agentiques (chiffres non vérifiés de façon indépendante).
- **Lien source** : https://www.llmreference.com/model/lfm-2.5-24b-a2b

### NVIDIA étend la famille Nemotron 3.5 (Super VL + Bolt)
- **Date de publication** : 15/10/2026
- **Résumé** : NVIDIA a ajouté deux modèles ouverts à sa famille Nemotron 3.5 : Super VL (120 Md de paramètres, vision+texte, agents) et Bolt 74B-A9B, pensé pour des déploiements locaux. Ces modèles s'inscrivent dans la stratégie de NVIDIA de modèles ouverts optimisés pour ses propres puces.
- **Lien source** : https://letsdatascience.com/news/nvidia-expands-nemotron-35-with-super-vl-and-bolt-ff81d36b

### MBZUAI et Inception42 présentent Jais 3
- **Date de publication** : 15-16/10/2026
- **Résumé** : MBZUAI et Inception42 ont lancé la famille de modèles ouverts Jais 3 (licence Apache 2.0), bilingues arabe/anglais, adaptés depuis le modèle K2 Horizon d'IFM (375B, 23B actifs). La gamme va de 0,9 Md de paramètres (exécutable sur smartphone) jusqu'à 375 Md, avec un modèle associé de reconnaissance vocale arabe. Poids disponibles sur Hugging Face.
- **Lien source** : https://www.hpcwire.com/aiwire/2026/10/16/mbzuai-and-inception42-introduce-jais-3-and-arabic-speech-recognition-model/

## Miniaturisation, quantisation

### Multiverse Computing compresse Nemotron 3.5 Super VL en Comet 60B
- **Date de publication** : 15/10/2026
- **Résumé** : Multiverse Computing a lancé Comet 60B, une version compressée du Nemotron 3.5 Super VL de NVIDIA (120 Md → 60 Md de paramètres totaux, mêmes ~12 Md de paramètres actifs), en gardant les trois modalités (texte, image, vidéo). La compression utilise CompactifAI, une méthode à base de réseaux tensoriels inspirée de l'informatique quantique, plutôt qu'un simple élagage. L'entreprise revendique une précision à moins de 5% du modèle original et un besoin mémoire réduit de moitié (le checkpoint BF16 tournerait sur 2x H200 au lieu de 4). Poids disponibles sur Hugging Face en BF16, FP8 et NVFP4 sous licence NVIDIA Nemotron Open Model License. Chiffres de performance non vérifiés de façon indépendante.
- **Lien source** : https://www.hpcwire.com/aiwire/2026/10/15/multiverse-computing-launches-comet-60b-in-collaboration-with-nvidia/

## Sorties majeures de modèles + benchmarks

### xAI lance Grok Voice 3.0
- **Date de publication** : 14/10/2026
- **Résumé** : xAI a publié Grok Voice 3.0, un modèle speech-to-speech pour agents vocaux temps réel (centres d'appels, assistants in-app), disponible via la Voice Agent API (`grok-voice-3.0`, alias `grok-voice-latest`). Il remplace Grok Voice 2.0 au même tarif (0,08 $/minute) et xAI revendique une latence sous la seconde ainsi qu'une bonne gestion des pauses/interruptions. Les scores de benchmark (ex. Speech-to-Speech Index) sont des chiffres fournis par xAI, non confirmés par une évaluation indépendante.
- **Lien source** : https://www.devx.com/artificial-intelligence-ai/what-is-grok-voice-3-0-xai-speech-to-speech-model/

## Tendances : agents autonomes

### Anchor lance Action Index pour réduire le coût des agents "computer-use"
- **Date de publication** : 15/10/2026
- **Résumé** : Anchor a lancé Action Index, une mémoire partagée des parcours web déjà résolus par des agents, permettant de rejouer des chemins connus plutôt que de les redécouvrir à chaque fois. Sur un benchmark de 300 tâches (Online-Mind2Web), Anchor rapporte une baisse du coût par tâche d'environ 97x (4,87 $ contre 472 $ pour l'ensemble des tâches) et un taux de succès en hausse pour un petit modèle (62,7% → 93,3%). Disponible via l'API REST et le serveur MCP d'Anchor, y compris sur l'offre gratuite. Chiffres communiqués par Anchor, non vérifiés de façon indépendante.
- **Lien source** : https://thenextweb.com/news/anchor-action-index-computer-use-agents-cost

## Catégories sans actualité fraîche confirmée cette semaine

- **Baisses de prix de modèles / API** : aucune baisse de prix datée avec certitude dans la fenêtre du 12-19/10/2026 n'a été trouvée (les dernières baisses confirmées — OpenAI, Google — datent de juillet-septembre 2026).
- **Hardware IA (NPU, puces, edge AI)** : rien de confirmé cette semaine ; NVIDIA GTC Berlin se tient du 20 au 22/10/2026 (keynote de Jensen Huang le 21/10), donc après la fenêtre couverte — à suivre la semaine prochaine.

---
*Note méthodologique : plusieurs résultats de recherche renvoyaient du contenu d'agrégateurs non datés ou des rumeurs non confirmées (ex. GPT-6.1 Astra, Gemini 4, Mistral Large 4 dont l'annonce du 06/10/2026 est hors fenêtre) ; ces éléments ont été écartés conformément à la règle de fraîcheur stricte.*
