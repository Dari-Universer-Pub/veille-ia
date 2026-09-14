# Veille IA brute — semaine du 2026-09-14

Période couverte : 07/09/2026 → 14/09/2026 (recherche effectuée le 14/09/2026).
Seules les actualités dont la date de publication a pu être confirmée dans cette fenêtre sont listées ci-dessous. Les catégories sans actualité fraîche confirmée sont laissées vides plutôt que remplies avec du contenu daté.

## Sorties majeures de modèles + benchmarks

### Meta lance Muse, son agent IA personnel (modèle Muse Spark)
- **Date de publication** : 08/09/2026
- **Résumé** : Meta a lancé Muse, un agent IA personnel destiné aux adultes (18+, disponible d'abord aux États-Unis), propulsé par le modèle Muse Spark. L'agent exécute des tâches concrètes (achats, réservations, gestion de projets) via des VM cloud dédiées ("Muse Secure VM") et communique notamment via WhatsApp, avec un superviseur de sécurité "Sentinel". Accès gratuit pour un usage basique, formules payantes pour plus de puissance de calcul.
- **Lien source** : https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/ ; https://techcrunch.com/2026/09/08/meta-debuts-its-muse-ai-agent-will-consumers-trust-it/

### OpenAI lance GPT Image 2.5 (Flare & Sunburst)
- **Date de publication** : 08/09/2026
- **Résumé** : OpenAI a annoncé deux nouveaux modèles de génération d'image dans l'API, `gpt-image-2.5-flare` (plus rapide/léger, -50% de latence vs GPT-Image-2) et `gpt-image-2.5-sunburst` (plus lourd, pour workflows créatifs exigeants). Amélioration du détail, de la fidélité au style et du contrôle sur les éditions multi-tours, jusqu'à 4K.
- **Lien source** : https://openai.com/index/introducing-chatgpt-images-2-5/ ; https://9to5mac.com/2026/09/08/openai-releases-chatgpt-images-2-5-with-sharper-details-and-more-precise-editing/

## Nouveaux modèles locaux et open-source

### DeepSeek-V4.1-Flash (licence MIT, poids ouverts)
- **Date de publication** : 10/09/2026
- **Résumé** : DeepSeek a officiellement lancé V4.1-Flash, un modèle multimodal Mixture-of-Experts (552B de paramètres, ~8B actifs en entrée / 16B en sortie, architecture Causal Encoder-Decoder, contexte 1M tokens) sous licence MIT, avec support natif de la compréhension d'images. DeepSeek affirme qu'il dépasse V4 Pro en performance, coût et vitesse ; à partir du 14/09, les requêtes vers V4 Pro seront automatiquement routées vers V4.1-Flash.
- **Lien source** : https://www.deepseek.com/en/news/deepseek-v4-1-flash/ ; https://technode.com/2026/09/10/deepseek-formally-launches-v4-1-flash-routes-v4-pro-requests-to-flash/

### Cohere North-Small-Translate-1.0 (poids ouverts, MoE)
- **Date de publication** : 10/09/2026
- **Résumé** : Cohere a publié North-Small-Translate-1.0, un modèle de traduction MoE à poids ouverts (218B de paramètres totaux, 25B actifs, 128 experts, plus de 50 langues), sous licence CC BY-NC 4.0 (recherche/non-commercial). Il obtient un score de 83,6 sur WMT26 toutes langues confondues, devançant des modèles propriétaires (DeepL, Google Translate) et open-weight concurrents (Gemma, GLM, Mistral Large).
- **Lien source** : https://www.marktechpost.com/2026/09/10/cohere-releases-north-small-translate-a-218b-moe-translation-model-that-scores-83-6-on-wmt26-across-50-languages/ ; https://huggingface.co/CohereLabs/North-Small-Translate-1.0

## Miniaturisation, quantisation (GGUF, GPTQ, AWQ)

### Premières quantisations GGUF communautaires de DeepSeek-V4.1-Flash
- **Date de publication** : 10-11/09/2026 (dans la foulée de la sortie officielle du 10/09/2026)
- **Résumé** : Dès la sortie de DeepSeek-V4.1-Flash le 10/09, la communauté Hugging Face a publié plusieurs conversions GGUF quantisées (Q2_K à Q4_K_M, variantes GSQ-RCO à ~3 bits/poids) pour permettre l'inférence locale du modèle malgré sa taille (763B de paramètres), avec un projecteur vision en BF16 et un brouillon de décodage spéculatif dédié.
- **Lien source** : https://huggingface.co/ngquocvinh/DeepSeek-V4.1-Flash-GGUF ; https://huggingface.co/pfeifferj/DeepSeek-V4.1-Flash-GSQ-RCO-GGUF

## Tendances : agents autonomes, multimodaux, reasoning, MoE

### Sakana AI scinde Fugu en deux modèles : Fugu Max et Fugu Ultra v2.0
- **Date de publication** : 10-11/09/2026
- **Résumé** : Sakana AI (Tokyo) a lancé Fugu Max et Fugu Ultra v2.0, des modèles "orchestrateurs" multi-agents (contexte 1M tokens) qui répartissent les tâches entre plusieurs LLM au lieu de répondre eux-mêmes, réduisant les coûts d'environ 60%. Fugu Ultra v2.0 (5$/30$ par million de tokens) exclut explicitement Claude Fable 5/5.1 et GPT-6 Astra de son pool de modèles ; il dépasse Opus 5 sur le benchmark Chartography (48,3 vs 27,3). Non disponible dans l'UE/EEE.
- **Lien source** : https://www.marktechpost.com/2026/09/10/sakana-ai-launches-fugu-max-and-fugu-ultra-v2-for-cheaper-stronger-multi-agent-orchestration/ ; https://alphasignal.ai/news/sakana-ai-splits-fugu-into-max-and-ultra-v2-to-cut-costs-60

## Baisses de prix de modèles / API

Aucune baisse de prix d'API significative et clairement datée des 7 derniers jours n'a été identifiée (les baisses trouvées chez OpenAI et Anthropic datent de juillet-août 2026, hors fenêtre). À noter toutefois la baisse de coût d'environ 60% permise par l'architecture Fugu Max/Ultra v2 de Sakana AI (voir section "Tendances" ci-dessus, 10-11/09/2026).

## Hardware IA (NPU, puces, edge AI, Nvidia, Apple, Qualcomm)

Aucune annonce matérielle majeure et clairement datée dans les 7 derniers jours n'a été identifiée. Le prochain AI Infra Summit de NVIDIA (où de nouvelles annonces hardware sont attendues) est prévu pour le 15-17/09/2026, donc après la fenêtre de cette veille — à surveiller la semaine prochaine.
