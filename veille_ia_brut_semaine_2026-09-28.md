# Veille IA brute — semaine du 2026-09-28

Période couverte : 21/09/2026 → 28/09/2026.

## Sorties majeures de modèles + benchmarks

### Anthropic lance Claude Opus 5.5
- **Date de publication** : 22/09/2026
- **Résumé** : Anthropic a sorti Claude Opus 5.5, premier modèle de la nouvelle famille 5.5, taillé pour le codage agentique de longue durée et le travail de connaissance. Le modèle réduit les coûts typiques de 40 % par rapport à Opus 5, augmente la vitesse de sortie de plus de 30 %, et dépasserait le plus gros modèle Fable sur plusieurs benchmarks. Il conserve les garde-fous "preserved thinking" et biosécurité introduits avec Fable 5.1, et lance un programme de vérification pour les organisations de sciences de la vie.
- **Lien** : https://techcrunch.com/2026/09/22/anthropic-releases-opus-5-5-with-lower-prices-and-fable-level-performance/ ; https://www.anthropic.com/claude-opus-5-5

### OpenAI sort GPT-6 Sol et GPT-6 Luna
- **Date de publication** : 22/09/2026
- **Résumé** : OpenAI a publié GPT-6 Sol et GPT-6 Luna, avec des tarifs API réduits de moitié ou plus par rapport à la série 5.6 (Sol : 2$/10$ par million de tokens entrée/sortie contre 4$/20$ ; Luna : 0,10$/0,50$ contre 0,20$/1,20$). OpenAI affirme que ces baisses sont permanentes et attribue les gains à des améliorations de mise en cache et d'inférence (jusqu'à 90 % de réduction sur les lectures de tokens en cache).
- **Lien** : https://qz.com/openai-gpt-6-sol-luna-api-price-cut-092326 ; https://technori.com/2026/09/26896-llm-api-pricing-gpt-6-sol-luna/kate/

## Nouveaux modèles locaux et open-source

### Xiaomi ouvre les poids de MiMo-V2.6 (Pro, Flash, Distill-Qwen-9B)
- **Date de publication** : 21-22/09/2026
- **Résumé** : Xiaomi a open-sourcé la famille MiMo-V2.6 (Pro-RL, Flash-RL, Distill-Qwen-9B) sous licence MIT. Le modèle Pro (1T paramètres, MoE A42B actifs) est multimodal (texte, image, vidéo, audio), avec un contexte jusqu'à 1M tokens, et se positionne comme le meilleur modèle en poids ouverts au monde sur l'Intelligence Index d'Artificial Analysis (score 46, ex-aequo avec Grok 4.7 sorti le même jour). Xiaomi publie aussi plus de 7 000 environnements de RL et un framework complet d'entraînement agentique.
- **Lien** : https://venturebeat.com/technology/better-than-deepseek-xiaomis-mimo-v2-6-pro-debuts-as-the-top-open-weights-model-in-the-world-alongside-cheaper-v2-6-flash ; https://technode.com/2026/09/22/xiaomi-open-sources-mimo-v2-6-models-after-scaling-reinforcement-learning/

## Hardware IA (NPU, puces, edge AI, Nvidia, Apple, Qualcomm)

### Qualcomm met en avant Snapdragon pour l'IA agentique mobile
- **Date de publication** : 22-23/09/2026
- **Résumé** : Qualcomm a communiqué sur deux nouveaux SoC Snapdragon présentés comme parmi les plus rapides au monde pour l'IA agentique embarquée, destinés à la prochaine génération de smartphones. L'annonce s'accompagne d'un renouvellement de l'accord de licence de brevets mondial avec Apple (24/09/2026).
- **Lien** : https://www.qualcomm.com/news/releases

## Tendances : agents autonomes, multimodaux, reasoning, MoE / gouvernance IA

### Google, OpenAI et Anthropic projettent une agence commune de standards IA
- **Date de publication** : 24/09/2026 (révélé par The Information)
- **Résumé** : Les trois laboratoires auraient convenu de créer un auto-régulateur de type FINRA, provisoirement nommé "Frontier AI Standards Agency", sans supervision gouvernementale directe, avec un lancement visé fin 2026 ou début 2027. Ils auraient approché Sriram Krishnan (ex-conseiller IA de la Maison-Blanche) pour le diriger. L'initiative prévoit des évaluations techniques partagées, des audits pré-lancement et des protocoles de sécurité standardisés.
- **Lien** : https://www.govinfosecurity.com/google-openai-anthropic-plan-frontier-ai-standards-body-a-32926

### Meta renforce l'avertissement de sécurité de son agent Muse après une faille
- **Date de publication** : 25-26/09/2026
- **Résumé** : Un chercheur en sécurité a signalé via le bug bounty de Meta une faille dans l'agent IA personnel Muse (lancé en septembre 2026), qui aurait pu permettre à un attaquant d'accéder à la machine virtuelle dédiée d'un utilisateur (emails, fichiers). Classée SEV-2 par Meta, la faille a poussé l'entreprise à ajouter un avertissement de sécurité plus clair dans l'application, sans preuve d'exploitation en conditions réelles.
- **Lien** : https://www.thestar.com.my/tech/tech-news/2026/09/26/meta-bolsters-muse-safety-warning-after-security-vulnerability-found-the-information-reports

## Baisses de prix de modèles / API

Voir la sortie de GPT-6 Sol/Luna ci-dessus (section "Sorties majeures"), qui inclut une baisse tarifaire permanente de 50 % ou plus sur l'API OpenAI (22/09/2026).

## Miniaturisation, quantisation (GGUF, GPTQ, AWQ)

Aucune actualité IA significative des 7 derniers jours dans cette catégorie (pas de nouvelle technique ou sortie clairement datée cette semaine ; llama.cpp a publié une version stable mais sans changement notable en quantisation).
