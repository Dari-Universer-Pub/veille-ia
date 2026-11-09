# Veille IA brute — semaine du 2026-11-09

Période couverte : 02/11/2026 → 09/11/2026 (run exécuté le 09/11/2026). Seules les actus dont la date de publication a pu être identifiée avec certitude dans cette fenêtre sont retenues.

## Nouveaux modèles locaux et open-source

### Moonshot AI publie les poids ouverts de Kimi K3.1 Pro
- **Catégorie** : Nouveaux modèles open-source
- **Date de publication** : 04/11/2026
- **Résumé** : Après une sortie API le 23/10/2026, Moonshot AI a publié sur Hugging Face les poids ouverts de Kimi K3.1 Pro, un modèle MoE de 2,8 billions de paramètres (104 Md actifs par token) avec un contexte de 1M de tokens et une entrée image native. Pour la version en poids ouverts, Moonshot indique avoir retiré les données liées à la cybersécurité offensive des deux phases d'entraînement tout en conservant les capacités de codage général ; la licence est spécifique à Kimi (pas une licence open-source standard) et impose l'affichage du nom "Kimi" pour les produits à large audience.
- **Source** : https://letsdatascience.com/news/moonshot-releases-kimi-k31-pro-api-open-weights-due-nov-4-786e160c ; https://runtimewire.com/article/moonshot-ai-kimi-k3-1-pro-weights

### Ricursive Intelligence publie Ripple-65B Preview, un modèle dense sous Apache 2.0
- **Catégorie** : Nouveaux modèles open-source
- **Date de publication** : 04/11/2026
- **Résumé** : Ricursive Intelligence a publié Ripple-65B Preview, un modèle dense (tous les paramètres actifs, à la différence des architectures MoE dominantes actuellement) de 65 milliards de paramètres entraîné sur 12 000 milliards de tokens, avec un contexte allant jusqu'à 1M de tokens. La publication inclut un modèle instruct en BF16, un checkpoint quantisé en NVFP4 4-bit, un checkpoint de base pré-entraîné uniquement, et un petit modèle de "speculative decoding" de 4,04 Md de paramètres ; des conversions GGUF communautaires sont également mentionnées. Le score revendiqué de 80,5 sur TerminalBench 2.1 est auto-déclaré par l'entreprise et n'a pas été vérifié de manière indépendante.
- **Source** : https://www.eesel.ai/blog/ripple-65b ; https://mer.vin/news/ripple-65b-preview-open-weight-coding-model-specs-benchmarks/

## Sorties majeures de modèles et tendances (multimodal, agents, MoE)

### Tencent lance Hy4, un modèle avec vision et usage d'ordinateur (computer use)
- **Catégorie** : Sortie majeure / tendance multimodale et agents
- **Date de publication** : 04/11/2026
- **Résumé** : Tencent a lancé la version complète de Hy4, ajoutant vision native et capacités de "computer use" à une précédente préversion texte seul. Le mode computer use fonctionnerait aussi bien en ligne de commande que sur interface graphique, avec un entraînement incluant des logiciels professionnels comme Blender ou des outils CAO. Le modèle est disponible via Tencent Cloud et OpenRouter (identifiant `tencent/hy4`) ; les poids ouverts ne sont pas encore publiés, Tencent annonçant leur sortie ultérieure avec une variante plus rapide "Hy4 Flash". Les chiffres de réduction du taux d'hallucination avancés par Tencent ne sont pas vérifiés indépendamment.
- **Source** : https://www.techrepublic.com/de/article/news-tencent-hy4-ai-model-vision-computer-use/ ; https://braindetox.kr/en/posts/tencent_hy4_multimodal_model.html

### Cognition lance SWE-2 Flash, un modèle de codage rapide et économique pour Devin
- **Catégorie** : Sortie majeure / agents de codage
- **Date de publication** : 04/11/2026
- **Résumé** : Cognition a lancé SWE-2 Flash, un modèle de codage dérivé d'un post-entraînement sur la base ouverte Inkling-Small de Thinking Machines Lab (276 Md de paramètres au total, 12 Md actifs, poids publiés en Apache 2.0 le 30/07/2026). Cognition revendique environ un cinquième du prix et trois fois la vitesse de son modèle SWE-2 plus large, avec un score de 24,0 % sur FrontierCode 2.0 (chiffre fourni par l'entreprise). Le checkpoint entraîné de SWE-2 Flash lui-même n'est pas public ; il reste accessible via les produits Devin de Cognition, gratuitement pour les utilisateurs payants jusqu'au 30/11/2026 selon une source.
- **Source** : https://runtimewire.com/article/cognition-swe-2-flash-devin-launch ; https://hermes-ai.net/news/cognition-s-swe-2-flash-runs-3x-faster-at-one-fifth-the-cost/

### OpenAI déploie GPT-6 Cyber auprès de clients restreints du programme Daybreak Red
- **Catégorie** : Sortie majeure / agents appliqués à la cybersécurité
- **Date de publication** : 05/11/2026
- **Résumé** : OpenAI a annoncé le déploiement de GPT-6 Cyber, un modèle spécialisé dans la recherche de vulnérabilités logicielles et la construction d'exploits dans un cadre de tests autorisés, limité pour l'instant aux clients approuvés du niveau "Daybreak Red" (accès sur candidature). Le modèle succède à GPT-5.6-Cyber (sorti en août 2026) et serait classé "Critical" sur le cadre de préparation (Preparedness Framework) d'OpenAI pour le risque cybersécurité, contre "High" précédemment — classification rapportée par la presse, non confirmée directement sur une fiche système consultée. OpenAI indique accompagner le déploiement de contrôles spécifiques (surveillance, bac à sable, restriction d'IP, supervision humaine).
- **Source** : https://digg.com/tech/seb75mp1 ; https://the-decoder.com/openai-launches-gpt-5-6-cyber-to-help-defenders-find-vulnerabilities-before-attackers-do/

---

**Catégories sans actualité fraîche confirmée cette semaine** (exclues pour éviter du contenu daté ou non vérifiable) : baisses de prix de modèles/API (les baisses identifiées — Mistral Large 4 début octobre, promotions GPT-5.6 Sol, Claude Haiku 5.5 — sont toutes antérieures au 02/11/2026), hardware IA grand public (puces, NPU — aucune annonce datée trouvée cette semaine), avancées spécifiques en quantisation GGUF/GPTQ/AWQ (hors mention de checkpoints NVFP4/GGUF communautaires pour Ripple-65B, intégrée ci-dessus).

**Note méthodologique** : plusieurs informations trouvées lors de la recherche (Mistral cutting API rates le 30/10/2026, dépréciation de Gemini 2.5 Pro/Flash par Google le 02/11/2026, lancement de Claude Haiku 5.5 le 07/10/2026) ont été volontairement exclues ou mentionnées seulement en négatif car leur date de publication est antérieure à la fenêtre des 7 derniers jours ou n'a pas pu être confirmée avec certitude.
