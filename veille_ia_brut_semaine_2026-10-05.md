# Veille IA brute — semaine du 2026-10-05

Période couverte : 28/09/2026 - 05/10/2026 (7 derniers jours). Seules les informations dont la date de publication a pu être clairement identifiée sont listées.

## Sorties majeures de modèles + benchmarks

### Claude Sonnet 5.5 (Anthropic)
- **Date de publication** : 28/09/2026
- **Résumé** : Anthropic a lancé Claude Sonnet 5.5, deuxième modèle de la famille Claude 5.5. Il génère ses réponses plus de 30 % plus vite et coûte jusqu'à 30 % moins cher par tâche dans les tests internes, tout en conservant la tarification de Sonnet 5 (2 $/M tokens en entrée, 10 $/M en sortie).
- **Lien source** : https://www.unite.ai/anthropic-releases-claude-sonnet-5-5-at-unchanged-sonnet-5-pricing/

### GPT-6.1 Sol (OpenAI)
- **Date de publication** : 29/09/2026
- **Résumé** : Annoncé lors de l'OpenAI DevDay 2026, GPT-6.1 Sol atteint un taux d'erreur de 7,7 % (contre 11,4 % précédemment) et approche les performances de GPT-6 Astra sur le codage agentique, l'usage d'ordinateur et les tâches professionnelles, pour un cinquième du prix (2 $/10 $ par million de tokens entrée/sortie).
- **Lien source** : https://www.lindy.ai/blog/gpt-6-1-sol

### Dots, agents autonomes "always-on" (OpenAI)
- **Date de publication** : 29/09/2026
- **Résumé** : Lors du DevDay, OpenAI a lancé Dots, des agents personnels toujours actifs tournant sur GPT-6 Astra, dotés chacun d'un ordinateur cloud et d'un navigateur, capables de poursuivre des objectifs en arrière-plan et d'être contactés par texte, appel, Slack ou email. Déploiement initial pour les abonnés Pro et Business Premium (hors UE/Suisse/UK).
- **Lien source** : https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/

### Gemini 4 Argon (Google DeepMind)
- **Date de publication** : 30/09/2026
- **Résumé** : Nouveau modèle frontière de Google DeepMind axé sur le codage à long horizon, le droit, la finance et la cyberdéfense, capable de trouver, valider et corriger seul des vulnérabilités critiques. Déploiement initial réservé aux défenseurs de confiance du programme Fairwind avant l'accès API payant et Ultra.
- **Lien source** : https://datanorth.ai/news/google-releases-gemini-4-argon

### Griffin (Tavus) — modèle vidéo "full-duplex"
- **Date de publication** : 01/10/2026
- **Résumé** : Tavus présente Griffin, un "Human Interaction Model" vidéo-à-vidéo full-duplex qui perçoit, décide et génère la parole/vidéo simultanément en conversation face-à-face, avec une latence audio-vidéo moyenne de 0,43s sur H100. Disponible uniquement en preview de recherche pour testeurs sélectionnés (Griffin-Lite).
- **Lien source** : https://finance.yahoo.com/technology/ai/articles/tavus-introduces-griffin-first-face-163000466.html

### MAI-Transcribe-2-Streaming et MAI-Voice-2.1 (Microsoft AI)
- **Date de publication** : 01/10/2026
- **Résumé** : Microsoft AI lance son premier modèle de transcription en streaming (60 langues, 2,5 % de taux d'erreur, premiers mots affichés en ~100ms) accompagné de deux modèles text-to-speech (MAI-Voice-2.1 et sa variante Flash) couvrant 23 langues et 26 locales.
- **Lien source** : https://www.unite.ai/microsoft-launches-mai-transcribe-2-streaming-and-two-mai-voice-models/

## Nouveaux modèles locaux et open-source

### Index-Translate (Bilibili / Index Team)
- **Date de publication** : 30/09/2026
- **Résumé** : Famille de modèles de traduction open-source (licence Apache 2.0) bâtie sur Qwen3.5, menée par un modèle MoE de 35 Mds de paramètres (3 Mds actifs/token), supportant 150 langues. Inclut des variantes spécialisées : doublage (Index-Echo), contrôle syllabique (Index-Homura) et traduction de documents longs (Index-NativeLong). Poids disponibles sur Hugging Face et ModelScope.
- **Lien source** : https://pandaily.com/bilibili-index-translate-open-source-qwen3-5-150-languages

### Clef et Clef-flash (Cloudflare)
- **Date de publication** : 01/10/2026
- **Résumé** : Cloudflare publie en open-weight (Apache 2.0) Clef, un modèle de décision de 27 Mds de paramètres qui renvoie des probabilités plutôt que du texte (et bat le créateur de la catégorie sur 7 benchmarks sur 10), ainsi que Clef-flash qui décide en 38,8 ms médian. Les deux modèles gèrent un contexte de 64k tokens et lisent image/vidéo.
- **Lien source** : https://datanorth.ai/news/cloudflare-releases-clef-and-clef-flash

### Strands Decider 2B (Amazon / Strands Labs)
- **Date de publication** : 01/10/2026
- **Résumé** : Amazon publie en open-weight (Apache 2.0) un modèle de décision de 2 Mds de paramètres répondant par des probabilités à des questions typées sur un état donné, avec données et scripts d'entraînement publiés également.
- **Lien source** : https://startupfortune.com/amazon-releases-its-own-jev-clone-as-the-ai-decision-model-race-turns-into-a-pile-up/

### Kolibri-1 (Aleph Alpha)
- **Date de publication** : 03/10/2026
- **Résumé** : Modèle souverain germano-anglais en architecture MoE (78,1 Mds de paramètres, 3,46 Mds actifs/token), fenêtre de contexte native de 1 048 576 tokens, poids FP8 publiés sous licence Apache 2.0 sur Hugging Face. Entraîné entièrement sur infrastructure allemande et finlandaise, conforme RGPD/AI Act, avec un tokenizer UniBPE dédié à la morphologie allemande.
- **Lien source** : https://aleph-alpha.com/en/blog/kolibri-has-landed-a-sovereign-open-weight-model/

## Note méthodologique

Plusieurs pistes identifiées cette semaine (accord de licence de brevets Qualcomm-Apple, lancement des PC Windows ARM "RTX Spark" de Nvidia) n'ont pas été retenues : la première concerne des brevets modem/5G sans lien direct avec l'IA, et la seconde n'a pas encore de date de lancement précise confirmée au sein des 7 derniers jours (annonce initiale du calendrier remontant au 03/09/2026).
