# Veille IA brute — semaine du 2026-10-26

Période couverte : 19/10/2026 → 26/10/2026 (7 derniers jours avant la date du run).
Règle appliquée : seules les informations dont la date de publication a pu être identifiée dans cette fenêtre sont retenues. Plusieurs pistes trouvées lors de la recherche (ex. "Nanbeige4.3-33B", "Qwen3.6 27B" daté d'octobre, "Kimi K3.1 Pro Highspeed", un "laboratoire de biosécurité IA au Royaume-Uni financé par Google DeepMind/OpenAI/Anthropic") n'ont pas pu être confirmées par des sources cohérentes ou ont été explicitement contredites par une recherche complémentaire — elles ont donc été exclues plutôt qu'incluses par défaut.

---

## Tendances : agents autonomes

### Anthropic lance "Claude Duet", un agent proactif en preview de recherche
- **Date de publication trouvée** : 21/10/2026
- **Résumé** : Anthropic ouvre une preview de recherche de Claude Duet, une application où Claude agit comme agent proactif : il envoie chaque matin un résumé des éléments nécessitant une attention, peut accomplir des tâches en arrière-plan sur sa propre machine virtuelle (même ordinateur éteint), et demande confirmation avant les actions importantes. Accès par liste d'attente, réservé aux abonnés Pro et Max aux États-Unis ; le modèle sous-jacent est Opus 5.5, et l'usage partage les mêmes limites que les autres outils Claude.
- **Lien source** : https://www.engadget.com/2293646/claude-duet-is-anthropics-answer-to-meta-muse-and-openai-dots/ ; annonce officielle https://x.com/claudeai/status/2112984664256241837

---

## Sorties majeures de modèles + multimodal

### Mistral AI dévoile Voxtral 3, une famille de modèles vocaux multilingues
- **Date de publication trouvée** : 20/10/2026
- **Résumé** : Mistral publie Voxtral 3 : modèles de transcription (Small/Mini Transcribe 3, 50+ langues), un modèle temps réel, et Voxtral Mini TTS 3 (35+ langues, 50+ dialectes), accompagnés d'un SDK d'agents vocaux basé sur LiveKit (latence sub-seconde, diarisation, clonage de voix, appel de fonctions, intégration SIP). Disponible via l'API hébergée en UE de Mistral ou en déploiement privé.
- **Lien source** : https://aiweekly.co/fr/alerts/mistral-publie-voxtral-3-modles-vocaux-multilingues-et-sdk-agents-partir-de

---

## Tendances : distribution / partenariats

### Les modèles d'OpenAI arrivent sur Google Cloud Model Garden
- **Date de publication trouvée** : 21/10/2026
- **Résumé** : OpenAI et Google Cloud annoncent que les modèles frontières d'OpenAI et les workflows Codex seront proposés via Model Garden et facturables sur Google Cloud Marketplace. L'accès démarre en private preview pour des clients entreprise sélectionnés, la disponibilité générale étant annoncée pour "les prochaines semaines".
- **Lien source** : https://www.techzine.eu/news/applications/145174/openais-models-are-finally-fully-supported-on-google-cloud/

---

## Hardware IA (NPU / edge)

### Synaptics annonce les puces Astra SR200, basées sur le NPU Coral open-source de Google
- **Date de publication trouvée** : 20/10/2026
- **Résumé** : Synaptics présente trois puces (SR210/SR230/SR250, de 200 à 400 GOPS) combinant cœurs Arm Cortex-M85/M52 et le NPU Coral de Google, ciblant wearables, capteurs sur batterie et vision/voix industrielle. Le même jour, Google publie la dernière brique (design 32-bit + compilateur) de l'architecture Coral NPU, en open-source. Seule la carte de développement Coralboard SL est disponible à l'achat (DigiKey) ; les puces SR200 sont encore en phase d'échantillonnage.
- **Lien source** : https://www.techrepublic.com/article/news-synaptics-astra-sr200-google-coral-npu/

---

## Nouveaux modèles / baisse de prix

### MiniMax lance M3.1 Flash, moins chère et plus rapide, poids ouverts à venir
- **Date de publication trouvée** : 19/10/2026
- **Résumé** : MiniMax publie M3.1 Flash avec une fenêtre de contexte de 1M tokens et une profondeur de raisonnement ajustable, au tarif API de 0,15 $ / 0,60 $ par million de tokens (entrée/sortie). MiniMax annonce ce modèle ~3x plus rapide que M3 avec un coût d'usage agentique réduit (chiffres du fournisseur ; des mesures indépendantes citées par VentureBeat évoquent une réduction plus modeste, environ -57 %). Les poids ouverts du modèle sont promis pour le 23/10/2026.
- **Lien source** : https://letsdatascience.com/news/minimax-cuts-m31-flash-token-prices-dbc14153

---

## Catégories sans actualité fraîche confirmée cette semaine
- Miniaturisation / quantisation (GGUF, GPTQ, AWQ) : aucune sortie ou mise à jour clairement datée des 7 derniers jours n'a été trouvée.
- Nouveaux modèles locaux/open-source (hors MiniMax ci-dessus) : plusieurs pistes (Qwen, Kimi, Nanbeige) sont apparues dans les résultats de recherche mais n'ont pas pu être confirmées avec une date dans la fenêtre — elles sont donc omises.
