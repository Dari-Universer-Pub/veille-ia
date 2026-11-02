# Veille IA brute — semaine du 2026-11-02

Période couverte : 26/10/2026 → 02/11/2026 (run exécuté le 02/11/2026). Seules les actus dont la date de publication a pu être identifiée avec certitude dans cette fenêtre sont retenues.

## Nouveaux modèles locaux et open-source

### Mistral publie les poids ouverts de Mistral Large 4 ("Le Chonk")
- **Catégorie** : Nouveaux modèles open-source
- **Date de publication** : 29/10/2026
- **Résumé** : Mistral AI a publié sur Hugging Face les poids ouverts de Mistral Large 4, un modèle MoE d'environ 1 000 milliards de paramètres (~49-52B actifs par token), sous licence "Mistral Ecosystem Open-Weight" (dérivée de MIT, avec clause spécifique pour les revendeurs MaaS). Le modèle, présenté comme orienté codage agentique et cybersécurité, revendique la première place parmi les modèles ouverts sur FrontierCode 2.0 et Terminal-Bench 4.0 (chiffres non vérifiés de manière indépendante) ; la sortie intervient trois semaines après une preview API lancée le 06/10/2026.
- **Source** : https://mistral.ai/news ; https://huggingface.co/blog (« Welcome Le Chonk: Mistral Large 4 on Hugging Face »)

### IBM publie Granite Switch 4.1.1
- **Catégorie** : Nouveaux modèles open-source
- **Date de publication** : 29/10/2026
- **Résumé** : IBM a mis en ligne un correctif de sa famille Granite Switch 4.1 (sortie quelques jours plus tôt), ajoutant notamment un support multilingue et une ponctuation native. Les détails techniques précis (variantes de paramètres, benchmarks) restent peu documentés par des sources primaires à ce stade.
- **Source** : https://huggingface.co/blog ; https://ecosistemastartup.com/?p=125906

## Miniaturisation, edge AI et modèles on-device

### Hugging Face publie AnySpeechRecognizer et AnyDecisionModel pour les plateformes Apple
- **Catégorie** : Miniaturisation / edge AI
- **Date de publication** : 29/10/2026
- **Résumé** : Hugging Face a publié deux packages open source permettant de faire tourner des modèles de reconnaissance vocale et de prise de décision structurée directement sur les appareils Apple, en conservant l'API native "SpeechAnalyzer" d'Apple. Les développeurs peuvent remplacer le moteur par défaut par des modèles ouverts comme NVIDIA Parakeet ou Qwen3-ASR, exécutés on-device via Core ML, MLX ou llama.cpp.
- **Source** : https://huggingface.co/blog (« Introducing AnySpeechRecognizer and AnyDecisionModel »)

### Liquid AI publie la famille LFM3 (modèles multimodaux 2B pour l'edge)
- **Catégorie** : Miniaturisation / edge AI
- **Date de publication** : 27/10/2026
- **Résumé** : Liquid AI a dévoilé LFM3, une famille de six modèles ouverts (~2B paramètres, licence LFM Open License v1.0) partageant un même socle entraîné sur 22 000 milliards de tokens : texte (contexte 256K), vision-langage, audio, omni-modal, et deux modèles de décision. Le modèle texte tiendrait en ~1 Go en quantisation 4-bit, ciblant téléphones et laptops ; Liquid AI revendique de meilleures performances que LFM2.5-2.6B avec 35 % de paramètres en moins (chiffres du constructeur, non vérifiés indépendamment).
- **Source** : https://huggingface.co/blog (« Build specialized multimodal models with LFM3 ») ; https://hyper.ai

## Sorties majeures de modèles et tendances (multimodal, agents, MoE)

### Google DeepMind dévoile Genie 4, un modèle de monde en temps réel avec audio natif
- **Catégorie** : Sortie majeure / tendance multimodale
- **Date de publication** : 27/10/2026
- **Résumé** : Google DeepMind a ouvert un accès restreint (testeurs de confiance) à Genie 4, présenté comme son premier modèle de monde temps réel capable de générer musique, ambiances sonores et dialogues interactifs, avec modification de la scène via prompts texte en direct (météo, angle de caméra). La cohérence visuelle tiendrait désormais environ deux minutes (contre une minute pour la version précédente) ; une expérimentation associe Genie 4 à un modèle Gemini 4 Argon pour simuler des tâches robotiques avant déploiement réel.
- **Source** : https://www.freepressjournal.in/tech/google-deepmind-unveils-genie-4-for-real-time-ai-worlds-with-built-in-audio ; https://northeasttimes.com/2026/10/27/google-deepmind-opens-genie-4-preview-to-testers-with-audio-and-two-minute/

### Anthropic : premiers résultats d'agents Claude pour accélérer la découverte de médicaments
- **Catégorie** : Tendance agents autonomes appliqués à la science
- **Date de publication** : 27/10/2026
- **Résumé** : Anthropic a publié un billet détaillant des progrès précoces sur l'utilisation d'agents Claude pour accélérer des étapes du développement de médicaments, dans la continuité de son programme « AI for Science ».
- **Source** : https://www.anthropic.com/news

## Autres actualités notables du secteur

### Anthropic dépose son dossier S-1 auprès de la SEC en vue d'une IPO
- **Catégorie** : Actualité industrielle (hors catégories techniques ci-dessus, mais jugée notable)
- **Date de publication** : 26/10/2026
- **Résumé** : Anthropic a annoncé le dépôt d'un formulaire S-1 auprès de la SEC américaine, première étape formelle vers une introduction en bourse envisagée.
- **Source** : https://www.anthropic.com/news

---

**Catégories sans actualité fraîche confirmée cette semaine** (exclues pour éviter du contenu daté ou non vérifiable) : baisses de prix de modèles/API, hardware IA (puces, NPU) grand public, avancées spécifiques en quantisation GGUF/GPTQ/AWQ.

**Note méthodologique** : plusieurs informations trouvées lors de la recherche (Gemini 4 Argon — lancement général le 13/10/2026, EmbeddingGemma 2 — 06/10/2026, DeepSeek-V4.1-Flash-1017 — 17/10/2026, etc.) ont été volontairement exclues car leur date de publication est antérieure à la fenêtre des 7 derniers jours.
