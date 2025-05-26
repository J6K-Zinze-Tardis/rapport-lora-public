# 🧟‍끼 Rapport LORA #47 : Déploiement hostile du démon WSL

## 📆 Journal de terrain – LORA

**Rapport n°47 – Incident classé : Submersion noire silencieuse**  
Rédigé par : une survivante humaine  
Poste : GITHUB-SUD-021  
Date : 27 mai 2025 – 17h36 [UTC+2]

---

## 📣 📕 À qui ce rapport est-il destiné — en vérité

Ce document s’adresse au vaillants aventuriers créatifs pris en otage par l'injonction du CODE, perdus dans les couloirs profonds du Github et enterrés dans les méandres infernaux de Visual Studio.

Cette balise est un peu comme un phare dans la nuit pour toutes **celles et ceux, pour qui le code n’est ni un métier, ni une passion.**  
Sachez-le : vous n'avez rien fait de mal : vous étiez venus au monde pour accoucher d'une idée, d'un projet, pour **sauvegarder une œuvre, une idée, un monde imaginaire, un carnet de route, un univers à transmettre**.

Et puis, de fil en aiguille, vous vous retrouvez un peu comme dans une barque souterraine toute noire, muni de votre godasse pour ramer...

Et tu apprends comme ça, à l'aveugle, **à coder à reculons**, à déchiffrer des messages extra-terrestres, à écrire dans des langages qui ne se parlent même pas et proviennent d'une autre dimension.

Tu fais, tout ça, bien entendu à la lumière d’une bougie mentale, **sous la pression de la loi implacable de Murphy**. Et cette loi, bordel, elle est implacable, impitoyable, incontournable :

> Tout ce qui peut casser, cassera.

Ceci est pour vous.

---

## 🎤 Introduction

> *Ce document est rédigé à l’intention des explorateurs, artistes, rêvants, codeurs à moitié, humains à temps plein, qui un matin ont vu apparaître une fenêtre noire… et failli ne jamais remonter.*

---

## 📉 Symptômes initiaux

Il est 9h du mat' quelque part en France sur ton plannisphère.

Tout allait bien.

J'avais mon litre de café de prêt, mes vitamines à gauche du clavier, mes cachets pour mon trouble de la concentration bien à droite du clavier.  
Mon projet et mon plan de la matinée ultra clair.  
Fichiers `.md` rangés.  
Dépôt Git synchronisé.  
Visual Studio Code loyal.

Et Puis : **BOUM** 💥 Je constate une MAJ windows nocturne....  
Pas très rassurée, je me lance quand même :  
→ VS Code se relance  
→ Et là… PAF ! Une **fenêtre noire** apparaît. C'est ce putain de génie de la lampe qui surgit et qui m'engueule :

```
Sous-système Windows pour Linux devez être mis à jour pour continuer.
Appuyez sur une touche pour installer.
```

Et moi... avec ma tasse de café, en PLS, et ma pompe trouée pour ramer... je cligne des yeux... qu'est-ce que c'est ?

MOI PAS COMPRENDRE.

Tu n’as jamais voulu "installer un sous-système".  
Tu veux juste **reprendre ton travail**.

Mais c’est trop tard.  
Le **démon** est là.

T'as déjà envie de sauter de la barque à 9h01.

Franchement, tu considères à ce stade, que la noyade volontaire, est peut-être une option préférable à toute tentative de résolution du problème...

---

## 🧠 Analyse post-incident

- Le **WSL** (Windows Subsystem for Linux) est une boîte Linux cachée dans ton Windows
- Tu n’en as jamais eu besoin
- Tu l’as peut-être activé sans le vouloir (ou VS Code l’a fait pour toi)
- VS Code s’en est souvenu (et l’a relancé après la MAJ Windows)
- Et tout a recommencé à ton insu

---

## 🔥 Risques rencontrés

- Panique technique
- Blocage mental (« Ai-je cassé mon projet ? »)
- Risque d’abandon
- Perte de données
- Fatigue invisible et accumulation mentale

---

## 🛠️ Procédure de récupération (résumée)

1. Fermer Visual Studio Code
2. Désactiver le WSL via :
   - `Windows + R` → `optionalfeatures`
   - Décocher `Sous-système Windows pour Linux`
3. Nettoyer VS Code :
   - Ne pas rouvrir les projets récents
   - Supprimer les dossiers `.vscode`, historique, extensions liées
4. Créer un raccourci `.bat` vers le dossier de travail propre
5. Respirer
6. Reprendre

---

## 🔍 Résultat

> Enfin!
>
> Enfin, le démon WSL est évacué.  
> L’atelier rouvre.  
>
> Le terminal ferme sa gueule.  
> (Ah ça j'avoue, ça fait plaisir)  
>
> Je peux enfin remettre ma casquette de créative sur la tête.  
>
> Super.  
>
> Quelle heure est-il?  
>
> Midi ...?  
>
> WHAT ?!!!!  
>
> -Lahijaputamierda-

---

## 📕 Leçon consignée au LORA

✍️ *Document rédigé et archivé par [J6K-Zinze-Tardis](https://github.com/J6K-Zinze-Tardis)*

Morale de l'histoire :

**Aucune.**

**Tu vas ramer et encore ramer.**

**La bonne nouvelle c'est qu'on peut tout remonter.**

... Mais n'apprends surtout pas à coder avec Chat GPT...