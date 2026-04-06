# Mécanique Kling 3.0 — Référence Tablecho

## Structure de prompt universelle
[PLAN N – Xs] Type de plan. Sujet + action précise.
Mouvement caméra. SFX: sons. No cut. No transition.

## Règles fondamentales
- Durée par plan : 1s à 5s maximum
- Toujours préciser : angle caméra, mouvement, SFX
- "No cut. No transition." = plan unique sans rupture
- @image1, @image2 = référence visuelle fixe pour cohérence personnage
- @video = vidéo source pour restyle ou changement d'angle
- @NomPersonnage = personnage sauvegardé dans Kling Omni

## Types de plans
- Fixed camera : caméra fixe
- Fast forward tracking : travelling avant rapide
- Fast backward tracking : travelling arrière rapide
- First-person POV : vue subjective
- Slow orbital motion : mouvement orbital lent autour du sujet
- Dynamic third-person tracking : suivi troisième personne
- Tight low dynamic angle : contre-plongée serrée dynamique
- High-angle aerial overhead : plongée aérienne

## Dialogues intégrés
[Sujet] murmure/dit/crie en français : "[texte exact]"
SFX: [ambiance sonore].

## Fonctions Omni 3.0
- Subject Reference : image fixe par personnage → cohérence entre sessions
- @NomPersonnage : personnage sauvegardé, réutilisable dans tous les plans
- Restyle @video : change le style visuel d'une vidéo existante
- Edit @video : remplace un élément, change l'angle, modifie l'environnement
- Storyboard : génère N plans animés depuis N images dans l'ordre

## Template feuilleton Tablecho

(Plan 1 – 2s)
[Type de plan]. @Personnage dans [lieu]. [Action précise].
SFX: [sons restaurant/ambiance]. No cut.

(Plan 2 – 3s)
[Type de plan]. @Personnage [action/dialogue en français].
SFX: [sons]. No cut.

(Plan 3 – 3s)
[Type de plan]. @Personnage [émotion/réaction].
SFX: [sons]. No cut. No transition.

## Couleurs identitaires personnages
Marco = ocre | Sophie = vert Provence | Karim = terracotta | Chloé = bleu nuit

## Limites techniques
- Max par génération : 15 secondes
- 6 shots maximum par requête
- Visages humains réalistes : bloqués sur Seedance 2.0, OK sur Kling
