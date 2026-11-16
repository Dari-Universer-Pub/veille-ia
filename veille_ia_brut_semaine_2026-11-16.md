# Veille IA brute — semaine du 2026-11-16

Période couverte : 09/11/2026 → 16/11/2026 (run exécuté le 16/11/2026). Seules les actus dont la date de publication a pu être identifiée avec certitude dans cette fenêtre sont retenues.

## Sorties majeures de modèles et tendances (multimodal, agents, MoE)

### Anthropic lance Claude Fable 5.2 et Claude Mythos 5.2
- **Catégorie** : Sortie majeure de modèle
- **Date de publication** : 09/11/2026
- **Résumé** : Anthropic a lancé Claude Fable 5.2 (accès grand public) et Claude Mythos 5.2 (accès restreint via les programmes de vérification cybersécurité et sciences de la vie), présentés comme un seul et même modèle sous-jacent avec deux niveaux de garde-fous. Les deux versions apportent des progrès en codage, raisonnement et vision, avec des sorties jusqu'à 30 % plus rapides que Fable/Mythos 5.1 ; le tarif annoncé est de 8 $ par million de tokens en entrée et 40 $ en sortie (mode rapide au double). Les chiffres de performance en cybersécurité (Mythos 5.2 détecterait 10,2 % de vulnérabilités de plus que Claude Opus 5.5) sont auto-déclarés par Anthropic et non vérifiés indépendamment.
- **Source** : https://www.constellationr.com/insights/news/anthropic-releases-mythos-52-fable-52 ; https://sdtimes.com/ai/anthropic-introduces-claude-fable-5-2-mythos-5-2/ ; https://www.testingcatalog.com/anthropic-launches-claude-fable-5-2-and-mythos-5-2/

### Google DeepMind lance Gemini Robotics 2.5
- **Catégorie** : Sortie majeure / IA appliquée à la robotique
- **Date de publication** : 10/11/2026
- **Résumé** : Google DeepMind a présenté Gemini Robotics 2.5, décrit comme son modèle vision-langage-action (VLA) le plus performant à ce jour, avec un taux de réussite revendiqué en hausse de 30 % à 100 % par rapport aux versions précédentes sur 200 tâches de manipulation. Le modèle a été testé sur des lignes d'assemblage actives de Mercedes-Benz en Allemagne et en Hongrie avec le robot humanoïde Apollo 2 d'Apptronik, atteignant un taux de réussite de 96 % selon DeepMind. DeepMind a également publié en parallèle un benchmark de sécurité ouvert, ASIMOV-Jailbreak.
- **Source** : https://deepmind.google/blog/gemini-robotics-2-5-accelerates-real-world-physical-intelligence/ ; https://www.automate.org/ai/industry-insights/google-deepmind-releases-gemini-robotics-2-5/anc

### Google DeepMind annonce AlphaGenome 2
- **Catégorie** : Sortie majeure / IA appliquée aux sciences de la vie
- **Date de publication** : 11/11/2026 (source unique identifiée, à confirmer sur le blog officiel)
- **Résumé** : Google DeepMind a annoncé AlphaGenome 2, nouvelle génération de modèle prédisant l'effet des séquences d'ADN et de leurs variations sur différents types cellulaires humains. La nouveauté principale par rapport à la version précédente serait une couverture de la méthylation de l'ADN et un niveau de détail plus fin par type et état cellulaire, ce qui pourrait révéler des effets liés à des maladies que des modèles au niveau tissu plus large ne détecteraient pas.
- **Source** : https://siliconangle.com/?p=853854

## Nouveaux modèles locaux et open-source

### Baidu publie ERNIE 5.5 Flash Preview (MoE 280 Md, poids ouverts annoncés avant le 25/11)
- **Catégorie** : Nouveaux modèles open-source
- **Date de publication** : 11/11/2026
- **Résumé** : Baidu a lancé ERNIE 5.5 Flash Preview, première version post-entraînement construite sur son modèle de base ERNIE 5.5 Flash Base (MoE épars, 280 milliards de paramètres au total, 14 milliards actifs par token, entraîné sur 33,5 T tokens), avec un contexte annoncé jusqu'à 1M de tokens. L'API est disponible dès maintenant sur la plateforme Qianfan de Baidu ; les poids ouverts du modèle de base sont publiés sous une licence propriétaire (ERNIE 5.5 Flash Base Model License Agreement v1.0, avec conditions territoriales et de revenus, à ne pas confondre avec une licence open-source standard), et les poids de la version Preview sont annoncés pour avant le 25/11/2026. Les scores de benchmarks avancés par Baidu ne sont pas vérifiés indépendamment.
- **Source** : https://letsdatascience.com/news/baidu-releases-ernie-55-flash-base-as-open-280b-moe-2ca582b4 ; https://phemex.com/news/article/baidu-releases-ernie-55-flash-preview-with-opensource-weights-coming-before-nov-25-103149

### Alibaba annonce Qwen 4 (préversion), sans date de disponibilité stable
- **Catégorie** : Nouveaux modèles open-source (annonce préliminaire)
- **Date de publication** : 11/11/2026 (source unique et peu établie — à vérifier sur les canaux officiels Qwen/Alibaba avant diffusion)
- **Résumé** : Selon une source unique de fiabilité non établie, Alibaba aurait annoncé Qwen 4 le 11/11/2026, avec une version "Qwen 4-Max-Preview" déjà accessible dans plusieurs applications Qwen, mais sans date de sortie stable ni poids ouverts confirmés à ce stade. Information à traiter avec prudence tant qu'elle n'est pas corroborée par une annonce officielle d'Alibaba ou de Hugging Face.
- **Source** : https://deepseekv4pro.com/deepseek-news

---

**Catégories sans actualité fraîche confirmée cette semaine** (exclues pour éviter du contenu daté ou non vérifiable) : baisses de prix de modèles/API (aucune baisse nouvelle datée de cette semaine identifiée — Claude Haiku 5.5 et les promotions GPT-5.6 Sol sont antérieures à la fenêtre), hardware IA grand public (NPU, puces Nvidia/Apple/Qualcomm — aucune annonce datée cette semaine, seulement des rumeurs/rapports sur un partenariat Apple-Nvidia M8 Ultra sans date de publication fiable), miniaturisation/quantisation GGUF/GPTQ/AWQ (aucune nouveauté datée identifiée cette semaine).

**Note méthodologique** : plusieurs informations trouvées lors de la recherche ont été volontairement exclues car leur date de publication est antérieure à la fenêtre des 7 derniers jours ou n'a pas pu être confirmée avec certitude : l'arrêt par OpenAI de la fourniture de ses modèles à Cursor (annoncé le 29/08/2026, effectif le 12/11/2026 — événement contractuel, pas une annonce de cette semaine), Mistral Large 4 (poids publiés le 29/10/2026), Kimi K3.1 Pro (poids ouverts du 04/11/2026), et diverses pages de trackers automatisés non datables avec certitude.
