# THE HUNT : ABYSS PROTOCOL — Wiki Joueur

!!! abstract "Bienvenue, Chasseur"
    Ce wiki couvre tout ce que vous devez savoir pour survivre, progresser et dominer dans
    **The Hunt : Abyss Protocol**. Utilisez la table des matières pour naviguer.

---

## Table des matières

1. [Histoire & univers](#1-histoire--univers)
2. [Game Loop](#2-game-loop)
3. [Les Plongées : donjons procéduraux](#3-les-plongées--donjons-procéduraux)
4. [Types de salles](#4-types-de-salles)
5. [La Corruption](#5-la-corruption)
6. [Le Système d'Échos](#6-le-système-déchos)
7. [Items & Équipement](#7-items--équipement)
8. [Attributs & Synergies](#8-attributs--synergies)
9. [Archétypes de Build](#9-archétypes-de-build)
10. [Progression : Niveaux & Prestige](#10-progression--niveaux--prestige)
11. [Perks Passifs](#11-perks-passifs)
12. [Factions](#12-factions)
13. [Succès & Titres](#13-succès--titres)
14. [Événements Mondiaux](#14-événements-mondiaux)
15. [Caisses & Cristallisation](#15-caisses--cristallisation)
16. [Battle Pass Saisonnier](#16-battle-pass-saisonnier)
17. [Contrats de Chasse](#17-contrats-de-chasse)
18. [Guildes](#18-guildes)
19. [PvP : Invasions Spectrales](#19-pvp--invasions-spectrales)
20. [Arènes de Chasse](#20-arènes-de-chasse)
21. [Classements](#21-classements)
22. [Le Codex](#22-le-codex)
23. [La Boutique](#23-la-boutique)
24. [Échanges entre joueurs](#24-échanges-entre-joueurs)
25. [Camp Personnel](#25-camp-personnel)
26. [Pêche Abyssale](#26-pêche-abyssale)
27. [Hôtel des Ventes](#27-hôtel-des-ventes)
28. [Tableau de Chasse](#28-tableau-de-chasse)
29. [Commandes utiles](#29-commandes-utiles)
30. [Conseils & Stratégies](#30-conseils--stratégies)
31. [FAQ](#31-faq)

---

## 1. Histoire & univers

### L'Abysse

Il y a des siècles, les cités souterraines prospéraient grâce à l'énergie des cristaux abyssaux, gemmes formées au cœur de la terre par une pression indicible. Mais les mineurs creusèrent trop profond. Ils réveillèrent quelque chose.

L'Abysse n'est pas un lieu physique — c'est un état de la matière. Une corruption qui ronge les pierres, transforme les hommes en spectres et redéfinit les lois de la mort. Les donjons que vous explorez sont des fragments d'Abysse solidifiés : des architectures impossibles où le temps n'a plus de sens et où la mort laisse des traces.

### Les Chasseurs

Vous êtes un Chasseur — l'un des rares individus capables de plonger dans l'Abysse et d'en revenir. Votre objectif : explorer les donjons, affronter les monstres et récupérer les artéfacts abyssaux avant que la Corruption ne vous engloutisse.

### Les Factions

Quatre factions se disputent le contrôle des artéfacts abyssaux :

- **L'Ordre des Chasseurs** — Croit que la Corruption peut être domestiquée et utilisée comme arme
- **Les Corrompus** — S'alimentent de la Corruption pour devenir plus puissants
- **Les Spectres** — Cherchent à communiquer avec les esprits piégés dans l'Abysse
- **Les Forgerons Abyssaux** — Maîtrisent l'art de transformer les artéfacts en armes redoutables

---

## 2. Game Loop

The Hunt fonctionne sur **3 niveaux de temps** :

!!! info "Loop court — La Plongée (5-15 min)"
    Chaque fois que vous lancez un donjon, c'est une **Plongée**. Vous descendez dans les
    profondeurs, affrontez des monstres, explorez les salles et tentez de vaincre le boss final.

!!! danger "Roguelite partiel"
        Si vous mourez dans un donjon, vous perdez les items équipés pendant le run.
        Votre inventaire hors-donjon est conservé.

!!! info "Loop moyen — La Session (1-3h)"
    Au fil de plusieurs Plongées, vous progressez dans vos **Contrats de Chasse**, gagnez de
    la réputation auprès de votre **Faction** et accumulez de l'Or.

!!! info "Loop long — L'Ère (4 semaines)"
    Chaque **Ère** est une saison complète avec son propre Battle Pass, ses récompenses
    exclusives et son chapitre narratif.

---

## 3. Les Plongées : donjons procéduraux

### Lancer un donjon

Utilisez `/thehunt dungeon` pour lancer une Plongée (ou depuis le Portail des Donjons au Hub).

!!! tip "Reproduire un donjon"
    Notez le **seed** affiché après la génération. Utilisez
    `/thehunt dungeon seed <seed>` pour rejouer exactement le même donjon.

### Thèmes disponibles

| Thème | Ambiance | Ennemis typiques |
|-------|----------|-----------------|
| Ruines | Pierres usées, lierre | Squelettes, araignées |
| Infernal | Lave, obsidienne | Blaze, pigmen |
| Glacial | Glace, neige | Loups des neiges |
| Aquatique | Eau, coraux | Guardians |
| Champignon | Mycelium, spores | Champignons géants |
| Void | Obsidienne, endstone | Endermen, Shulkers |

### Difficultés

| Difficulté | Bonus HP mobs | Bonus dégâts | Multiplicateur loot |
|-----------|--------------|-------------|---------------------|
| EASY | ×0.8 | ×0.75 | ×0.9 |
| NORMAL | ×1.0 | ×1.0 | ×1.0 |
| HARD | ×1.5 | ×1.5 | ×1.3 |
| NIGHTMARE | ×2.5 | ×2.0 | ×1.8 |

!!! warning "NIGHTMARE"
    La difficulté NIGHTMARE est débloquée au niveau 80. Elle requiert un build solide —
    ne vous y aventurez pas avant de maîtriser vos mécaniques.

### Modificateurs de donjon

Des modificateurs spéciaux peuvent s'appliquer à un run :

| Modificateur | Effet |
|---|---|
| FLOODED | Donjon partiellement inondé |
| CURSED | Soins réduits de 50% |
| VOLCANIC | Geysers de lave périodiques |
| CORRUPTED | Corruption monte 2× plus vite |
| POISONED | Air du donjon empoisonne légèrement |
| FROZEN | Ralentissement permanent (mobs aussi) |

### Topologies de donjons

| Topologie | Description | Conseil |
|-----------|-------------|---------|
| LINEAR | Couloir avec embranchements | Idéal pour débuter |
| BRANCHING | 2-4 branches qui se rejoignent | Explorez tout pour le loot |
| WEB | Réseau avec boucles | Prenez la carte `/thehunt map` |
| SPIRAL | Anneaux en spirale | Le boss est au cœur |
| LABYRINTH | Labyrinthe, chemin unique | Très difficile, récompenses élevées |
| CONCENTRIC | Anneaux concentriques | Portails raccourcis disponibles |
| FRACTAL | Salles spéciales fréquentes | Build-crafting intense |
| ASYMMETRIC | Deux moitiés miroir | Idéal pour les arènes PvP |

### La carte `/thehunt map`

En cours de Plongée, `/thehunt map` affiche une grille 9×9 autour de votre position.

| Symbole | Salle |
|---------|-------|
| ⛺ | Spawn |
| ☠ | Boss final |
| ★ | Trésor |
| ⚡ | Piège |
| ♕ | Mini-boss |
| $ | Marché Noir |
| ⚖ | Jugement |
| ◈ | Miroir |
| ⌚ | Nexus Temporel |
| ♥ | Sacrifice |
| ⚒ | Forge Abyssale |
| ☽ | Crypte |
| ✦ | Éveil |

!!! warning "Déconnexion"
    Si vous vous déconnectez pendant une Plongée, vous avez **2 minutes** pour vous
    reconnecter avant que votre donjon soit perdu.

---

## 4. Types de salles

### Salles de combat

- **Arène (ARENA)** — Combat de base contre des vagues de monstres
- **Pièges (TRAP)** — Monstres et lave. Coffres cachés dans les zones de sécurité
- **Mini-Boss (MINIBOSS)** — Un ennemi puissant qui garde un trésor
- **Boss Arena (BOSS)** — La salle finale. Anneau de lave, piliers massifs, le boss vous attend

### Salles de loot

- **Trésor (TREASURE)** — Coffres sans combat ou presque
- **Bibliothèque (LIBRARY)** — Fragments de lore + coffres de livres

### Salles spéciales ABYSS PROTOCOL

#### Le Marché Noir

Un marchand spectral vous propose des items rares en échange d'**Âmes**.
Les items disponibles changent à chaque run.

!!! tip "Conseil Marché Noir"
    N'hésitez pas si vous voyez un attribut rare — il ne reviendra pas dans ce run.

#### La Salle du Jugement

Une épreuve morale : le donjon vous pose une question ambiguë. La bonne réponse réduit la
Corruption de 10% et octroie un buff. La mauvaise donne une malédiction.

!!! note "Pas toujours évident"
    Il n'y a pas toujours de "bonne" réponse évidente. Faites confiance à votre instinct.

#### La Salle des Miroirs

Affrontez un **clone de vous-même** avec vos propres attributs et équipement (légèrement réduits).
Vaincre votre double rapporte une récompense unique.

!!! danger "Le clone vous connaît"
    Le clone utilise exactement les mêmes stratégies que vous. Soyez imprévisible.

#### Le Nexus Temporel

Le temps se ralentit. Précision et timing sont cruciaux. Compléter le Nexus donne un
**Éclat de Temps** : fragment rare pour la Forge.

#### La Salle des Sacrifices

Échangez une partie de vos PV maximum contre des buffs permanents pour le run.

!!! danger "Définitif pour le run"
    Chaque sacrifice est irréversible pour cette Plongée. Réfléchissez avant d'accepter.

#### La Forge Abyssale

Améliorez vos items en utilisant des ressources trouvées dans le donjon :

- **Fragments minéraux** → améliore un attribut aléatoire
- **Noyaux abyssaux** → monte la rareté d'un item
- **Cristaux de corruption** → ajoute un attribut ABYSSAL aléatoire

#### La Crypte des Prédécesseurs

Une salle générée depuis les **Échos** de vrais joueurs morts avant vous. Les fantômes
reproduisent leur dernière séquence de combat. Apprenez de leurs erreurs.

#### La Salle de l'Éveil

Un tutoriel dynamique adapté à votre niveau. Débutant : rappel des mécaniques. Expert :
défis avancés avec récompenses selon la performance.

---

## 5. La Corruption

La Corruption est l'**horloge invisible** du donjon. Elle monte en permanence et crée une
pression temporelle : vous ne pouvez pas farmer indéfiniment.

### Comment la Corruption monte

| Source | Hausse |
|--------|--------|
| Passive | +0.08%/s |
| En combat | +0.15%/s supplémentaire |
| Piège activé | +2.5% immédiat |
| Mob tué | +0.5% immédiat (anti-farming) |

### Paliers de Corruption

| Palier | % | Effets |
|--------|---|--------|
| **PURE** | 0-19% | Aucun |
| **TAINTED** | 20-39% | Avertissement. Les monstres vous sentent |
| **CORRUPTED** | 40-59% | Cécité légère + mobs +25% dégâts |
| **DEFILED** | 60-79% | Ralentissement + mobs +50% dégâts |
| **ABYSSAL** | 80-100% | Wither actif + mobs ×2 dégâts |

### Réduire la Corruption

!!! info "Deux seules sources de réduction"
    - **Cristal de Purification** : réduit de 25% instantanément (craftable ou achetable)
    - **Salle du Jugement** (succès) : réduit de 10%

### Survivre à haute Corruption

!!! tip "Transformer le risque en avantage"
    Les attributs **ABYSSAL** scalent avec le niveau de Corruption. Un build ABYSSAL bien construit
    fait de la Corruption à 80% un avantage plutôt qu'une punition.

---

## 6. Le Système d'Échos

Quand un joueur meurt dans un donjon, il laisse un **Écho** — une empreinte spectrale à l'endroit
de sa mort.

### Types d'Échos

| Type | Couleur | Ce que vous trouvez |
|------|---------|---------------------|
| ⚠ Avertissement | Blanc | Message d'alerte sur le danger |
| ♦ Survivant | Vert | Soins (+2 HP) en interagissant |
| ⚡ Piège | Rouge | Information sur un piège proche |
| ✦ Loot | Jaune | Indice sur un coffre caché |
| ☠ Boss Info | Violet | Information sur le boss de ce donjon |

### Détecter et interagir

Approchez-vous à moins de **8 blocs** d'un Écho pour être notifié (toutes les 5 secondes max).

!!! tip "Récupérer ses propres items"
    Si vous mourez dans un donjon, vous pouvez revenir dans le même donjon (même seed) et
    retrouver votre Écho. Approchez-vous pour récupérer **50% de vos items perdus**.

---

## 7. Items & Équipement

### Raretés

| Rareté | Couleur | Slots d'attributs max |
|--------|---------|----------------------|
| COMMUN | Vert | 1 |
| RARE | Bleu | 2 |
| ÉPIQUE | Violet | 3 |
| LÉGENDAIRE | Jaune | 4 |
| MYTHIQUE | Or | 5 |
| EXOTIQUE | Rouge | 5 |
| DIVIN | Gris foncé | 6 |
| UNIQUE | Blanc | 7 |

### Le Forgeron

Le Forgeron vous permet de :

- **Ajouter un attribut** à un item (avec un Fragment d'Attribut)
- **Améliorer un attribut** au niveau suivant
- **Retirer un attribut** (sans remboursement)
- **Monter la rareté** d'un item

!!! warning "Coût important"
    Monter la rareté d'un item est très coûteux en Or et ressources. Assurez-vous que l'item
    en vaut la peine avant d'investir.

### Attributs Living (Évolutifs)

Certains attributs spéciaux **évoluent** avec l'usage. Leur niveau monte automatiquement :

| Stade | Condition | Apparence |
|-------|-----------|-----------|
| INERT | Niveau 1 | Texte gris |
| AWAKENED | 100 kills | Texte blanc |
| SENTIENT | 500 kills | Texte jaune |
| ANCIENT | 2 000 kills | Texte or avec étoile |
| LEGENDARY | 5 000 kills | Texte arc-en-ciel animé |

!!! danger "Progression irréversible"
    Les attributs vivants perdent leur progression si l'item est vendu ou échangé.
    Réfléchissez à deux fois avant de vous en séparer.

---

## 8. Attributs & Synergies

### Catégories d'attributs

| Catégorie | Description |
|-----------|-------------|
| **COMBAT** | Améliorent les attaques — dégâts, crits, finishers |
| **DÉFENSE** | Réduisent les dégâts reçus, boucliers, HP |
| **RÉGÉNÉRATION** | Soins, lifesteal, regen passif |
| **UTILITÉ** | Mobilité, exploration, vitesse |
| **FARM** | Optimisent le loot, Or et EXP bonus |
| **ABYSSAL** | Interagissent avec la Corruption |
| **SPECTRAL** | Interagissent avec les Échos |
| **SOCIAL** | Scalent avec les alliés proches |

### Attributs COMBAT

| Attribut | Effet | Niveaux |
|----------|-------|---------|
| **Hémorragie** | Proc dégâts +10-30% sur la cible (chance 15-25%) | 1-3 |
| **Contre-Attaque** | Riposte 29-65% des dégâts reçus (chance 12-28%) | 1-5 |
| **Brise-Armure** | Fracture l'armure : prochains coups +10-30% (chance 30-50%) | 1-3 |
| **Exécuteur** | +37-71% dégâts sur cibles à < 30% HP | 1-3 |
| **Précision** | Crits ×1.5-×1.9 (chance 10-30%) | 1-5 |
| **Furie** | +3-8% par stack (max 5 stacks), reset si on change de cible | 1-5 |

### Attributs DÉFENSE

| Attribut | Effet | Niveaux |
|----------|-------|---------|
| **Gardien** | Mitigation 15-75% sur proc (chance 10-30%) | 1-5 |
| **Égide** | Absorption I/II/III pendant 4s sur kill | 1-3 |
| **Rempart** | Réduction flat 2-10% de tous les dégâts reçus | 1-5 |
| **Bastion** | +4/+8/+12 HP maximum (HealthBoost passif) | 1-3 |

### Attributs RÉGÉNÉRATION

| Attribut | Effet | Niveaux |
|----------|-------|---------|
| **Vampirisme** | Lifesteal 3-15% des dégâts infligés | 1-5 |
| **Méditation** | Regen I/II/III hors donjon (hub, voyage) | 1-3 |
| **Régénération Abyssale** | Regen en donjon si Corruption ≥ 30/20/10% | 1-3 |

### Attributs UTILITÉ / FARM

| Attribut | Effet | Niveaux |
|----------|-------|---------|
| **Agilité** | Speed I/II passif permanent | 1-2 |
| **Pilleur** | +15/30/45% Or par kill | 1-3 |
| **Éveillé** | +15/30/45% EXP par kill | 1-3 |
| **Collecteur** | 5/10/15% de chance de doubler le butin Or | 1-3 |

### Attributs ABYSSAL

| Attribut | Effet |
|----------|-------|
| **Pacte de Corruption** | +dégâts proportionnel à la Corruption (max niv 5) |
| **Résistance Abyssale** | Réduit les malus de Corruption |
| **Frénésie Corrompue** | Vitesse d'attaque augmentée selon Corruption |
| **Drain Obscur** | Vol de vie depuis les monstres corrompus |
| **Vortex Abyssal** | Aspire les monstres à proximité et draine leur vie |
| **Communion des Ténèbres** | Lien avec l'Abysse — bonus passif unique |

### Synergies

Certaines **combinaisons d'attributs** sur votre équipement total déclenchent des **Synergies** :

| Synergie | Attributs requis | Bonus |
|----------|-----------------|-------|
| Pacte Abyssal | Pacte + Frénésie | Speed II + Strength I en corruption |
| Éco-Spectral | Mémoire Écho + Résonance Spectrale | Regen si Échos présents |
| Fraternité de Sang | Bouclier Partagé + Soutien Tactique | Absorption passif |
| Vortex Spectral | Vortex Abyssal + Âme Moissonnée | Réduction corruption passive |
| Communion Totale | Communion + Lien Tombe + Synergie Groupe | Strength II + Regen + Résistance |
| Lame Vampire | Hémorragie + Vampirisme | Regen I en combat |
| Exécuteur Abyssal | Exécuteur + Pacte Corruption | Strength I en haute corruption |
| Forteresse | Rempart + Gardien + Bastion | Résistance aux dégâts permanente |
| Pilleur Chanceux | Pilleur + Collecteur | Haste I passif |
| Riposte Furieuse | Contre-Attaque + Furie | Speed I en combat |

!!! info "Découvrez les synergies vous-même"
    Expérimenter les combinaisons fait partie du plaisir. Le Forgeron vous permet de
    tester différentes configurations sans perdre vos items.

---

## 9. Archétypes de Build

Voici **9 archétypes** éprouvés pour vous inspirer. Chacun est viable et repose sur des
attributs + une synergie centrale. Ce ne sont pas des règles — adaptez à votre style.

!!! example "Glass Cannon"
    **Attributs clés :** Précision + Exécuteur + Furie + Hémorragie  
    **Synergie :** Aucune (chaque slot est offensif)  
    **Faction idéale :** Ordre des Chasseurs  
    **Playstyle :** Maximum DPS, aucune survie. Tuez avant d'être tués. Redoutable en FRACTAL avec des packs de mobs.

!!! example "Tank Impénétrable"
    **Attributs clés :** Rempart + Gardien + Bastion + Méditation  
    **Synergie :** Forteresse (Résistance permanente)  
    **Faction idéale :** Ordre des Chasseurs  
    **Playstyle :** Quasi-immortel mais lent. Idéal pour les runs NIGHTMARE et les topologies LABYRINTH.

!!! example "Vampire de Combat"
    **Attributs clés :** Vampirisme + Hémorragie + Exécuteur + Bastion  
    **Synergie :** Lame Vampire (Regen en combat)  
    **Faction idéale :** Ordre des Chasseurs  
    **Playstyle :** Auto-sustain offensif. Les ennemis vous soignent. Optimal dans les runs longs.

!!! example "Bombardier Abyssal"
    **Attributs clés :** Pacte de Corruption + Frénésie Corrompue + Vortex Abyssal + Drain Obscur  
    **Synergie :** Pacte Abyssal + Vortex Spectral  
    **Faction idéale :** Les Corrompus  
    **Playstyle :** Jouer à 70%+ de Corruption. Dangereux mais dévastateur. Nécessite un Cristal de Purification de secours.

!!! example "Spectre des Échos"
    **Attributs clés :** Mémoire de l'Écho + Résonance Spectrale + Lien Tombe + Âme Moissonnée  
    **Synergie :** Éco-Spectral + Vortex Spectral  
    **Faction idéale :** Les Spectres  
    **Playstyle :** Exploite chaque Écho du donjon. Meilleur dans les donjons rejoués (mêmes Échos, mêmes informations).

!!! example "Raid Social"
    **Attributs clés :** Synergie de Groupe + Bouclier Partagé + Soutien Tactique + Aura de Réputation  
    **Synergie :** Fraternité de Sang + Communion Totale  
    **Faction idéale :** Peu importe  
    **Playstyle :** Réservé aux raids de guilde (5 joueurs). Inutile en solo. En groupe : dominance absolue.

!!! example "Roi du Farm"
    **Attributs clés :** Pilleur + Collecteur + Éveillé + Agilité  
    **Synergie :** Pilleur Chanceux (Haste I)  
    **Faction idéale :** Forgerons Abyssaux  
    **Playstyle :** Maximiser Or et EXP par session. Idéal pour monter en level rapidement ou accumuler des ressources.

!!! example "Riposteur"
    **Attributs clés :** Contre-Attaque + Furie + Gardien + Rempart  
    **Synergie :** Riposte Furieuse (Speed en combat)  
    **Faction idéale :** Ordre des Chasseurs  
    **Playstyle :** Survivre aux coups pour renvoyer la damage. Plus les ennemis frappent fort, plus vous devenez dangereux.

!!! example "Tank Corrompu"
    **Attributs clés :** Résistance Abyssale + Rempart + Bastion + Régénération Abyssale  
    **Synergie :** Forteresse  
    **Faction idéale :** Les Corrompus  
    **Playstyle :** Immunité partielle à la Corruption + HP maximum élevé. Peut rester en zone DEFILED indéfiniment.

---

## 10. Progression : Niveaux & Prestige

### Niveaux (1 → 120)

Vous gagnez des niveaux en tuant des monstres, complétant des donjons et des contrats.
L'XP requise par level augmente progressivement. Les **milestones** sont annoncés au serveur.

| Level | Déblocage | Récompense automatique |
|-------|-----------|------------------------|
| 5 | — | Titre "Apprenti" |
| 10 | Perk Slot 1 + Camp Personnel | 100 Or |
| 20 | Profondeur 3-4 + Kill Streak | Titre "Chasseur" |
| 30 | Perk Slot 2 + Forge de Surface | 300 Or |
| 35 | Création de Guilde | — |
| 50 | Mode Invasion + Profondeur 5-7 | Titre "Chasseur Confirmé" + 500 Or |
| 60 | Double XP quotidienne (1h/jour) | — |
| 70 | Perk Slot 3 | 1 000 Or |
| 80 | Difficulté NIGHTMARE + Profondeur 8-10 | Titre "Éclaireur de l'Abysse" |
| 100 | Perk Slot 4 | Titre "Maître Chasseur" + 2 000 Or |
| 120 | Prestige éligible | Annonce serveur |

### Kill Streak

Enchaîner des kills sans prendre de gros dégâts construit une **Kill Streak** :

| Streak | Multiplicateur Or & EXP |
|--------|------------------------|
| 5 kills | +10% |
| 10 kills | +25% |
| 25 kills | +50% |
| 50 kills | +100% (FRENZY) |

!!! warning "Réinitialisation"
    La streak se réinitialise si vous prenez **≥ 15%** de votre vie maximale en un seul coup.

### Prestige

À level 120, tapez `/thehunt prestige` puis `/thehunt prestige confirm` pour valider.

!!! danger "Ce que vous perdez"
    - Votre niveau (repart à 1)
    - Votre EXP courante
    - Votre Or courant

!!! success "Ce que vous gagnez"
    - Prestige +1 (couleur de nametag améliorée)
    - Les récompenses futures scalent avec le prestige (+5% par prestige, plafonné P20)
    - Cosmétiques, titres et réputation de faction sont **conservés**

**Couleurs de prestige :**

| Prestige | Couleur | Rang |
|----------|---------|------|
| P0 | Gris | Chasseur novice |
| P1-4 | Bleu | Chasseur expérimenté |
| P5-9 | Jaune | Éclaireur de l'Abysse |
| P10-14 | Or | Vétéran |
| P15-19 | Rouge | Maître Chasseur |
| P20+ | Violet → Rose → Blanc | Légende |

Les jalons P1, P5, P10, P20, P50, P100, P1000 sont annoncés à tout le serveur.

### Connexion Quotidienne

Connectez-vous chaque jour pour recevoir une récompense croissante :

| Jour | Récompense |
|------|------------|
| 1 | 50 Or |
| 2 | 100 Or + 50 EXP |
| 3 | 150 Or + Fragment Abyssal |
| 4 | 200 Or + Rune de Protection |
| 5 | 300 Or + 200 EXP |
| 6 | 500 Or + Potion de Clarté |
| 7 | 1 000 Or + Crate Chasseur |
| 30 | Cosmétique exclusif de saison |

!!! warning "Streak brisée"
    Manquer une connexion remet le compteur à 1.

---

## 11. Perks Passifs

Les **Perks** sont des bonus passifs permanents équipés dans des **slots** débloqués par la progression.

| Level | Slots débloqués |
|-------|----------------|
| 10 | Slot 1 |
| 30 | Slot 2 |
| 70 | Slot 3 |
| 100 | Slot 4 |

### Liste des Perks disponibles

| Perk | Effet |
|------|-------|
| **Instinct du Chasseur** | +5% chance de Fragment Abyssal sur kill |
| **Acharnement** | Conservation de 25% de l'EXP à la mort en donjon |
| **Vigilance** | Alerte de Corruption 100 ticks plus tôt |
| **Économe** | -10% coût Or au Forgeron |
| **Résistance à l'Abysse** | -15% accumulation de Corruption passive |
| **Collecte Améliorée** | +1 item max par coffre de donjon |
| **Combattant Né** | +5% dégâts de base en donjon |
| **Esprit d'Équipe** | +20% XP de guilde contribuée |
| **Chasseur Furtif** | Invisibilité 1s sur kill en donjon |
| **Récupération** | +3 HP quand la Corruption descend d'un palier |
| **Vif** | +15% vitesse hors-combat en donjon |
| **Mémoire Abyssale** | +4 blocs de rayon de détection des Échos |
| **Appétit de Combat** | +1 HP tous les 5 kills (plafonné à HP max) |
| **Sceau du Prestige** | +2% bonus par prestige (max +40% à P20) |

!!! tip "Construisez votre identité"
    Les perks renforcent votre archétype. Un **Tank** prendra Résistance à l'Abysse + Récupération.
    Un **Farm King** prendra Pilleur + Collecte Améliorée. Pas d'erreur irréversible — les perks sont rééquipables.

---

## 12. Factions

Les Factions offrent des **bonus passifs** et un axe de progression à long terme.
Rejoignez-en une avec `/thehunt faction`.

| Faction | Bonus principal | Idéal pour |
|---------|----------------|-----------|
| **Ordre des Chasseurs** | Strength I permanent en donjon | Combat offensif |
| **Les Corrompus** | Dégâts × palier de Corruption | High risk/reward |
| **Les Spectres** | Regen en zones sombres + Échos ×1.5 | Exploration/support |
| **Forgerons Abyssaux** | 2× utilisations Forge Abyssale | Craft/équipement |

**Réputation de Faction** : gagnez de la réputation en jouant selon les principes de votre faction.
Les paliers (Recrue → Soldat → Élite → Champion → Légende) débloquent des bonus croissants.

!!! warning "Changement de faction"
    Vous ne pouvez changer de faction qu'**une fois par Ère** (= une fois par Prestige).
    Changer réinitialise votre réputation dans l'ancienne faction.

---

## 13. Succès & Titres

### Succès

Les **Succès** sont des objectifs permanents qui récompensent l'exploration de tout le contenu.

| Catégorie | Exemples |
|-----------|---------|
| Progression | Atteindre L10, L50, L100, L120, P1, P5, P20 |
| Combat | Premier kill, 100 kills, 1000 kills, KillStreak 10/50 |
| Donjons | Premier donjon, 50 donjons, Run parfait (sans dégâts) |
| Richesse | Accumuler 1k/10k/100k Or |
| Social | Rejoindre une guilde, rejoindre une faction |
| Connexion | Streak 7/30/100 jours |
| Spéciaux | Salle secrète, Gagner un événement mondial |

Consultez vos succès avec `/thehunt achievements`.

### Titres cosmétiques

Certains succès débloquent des **titres** affichés au-dessus de votre tête.

| Succès | Titre débloqué |
|--------|---------------|
| Niveau 50 | `§6[Confirmé]` |
| Niveau 100 | `§c[Maître]` |
| Niveau 120 | `§5[Légende]` |
| Prestige 1 | `§d[Préstigié]` |
| 50 donjons | `§6[Vétéran]` |
| Run parfait | `§6§l[Parfait]` |
| Streak 100 jours | `§5§l[Fanatique]` |

!!! tip "Gérer vos titres"
    - `/thehunt titles` — voir vos titres débloqués
    - `/thehunt titles set [titre]` — équiper un titre
    - `/thehunt titles clear` — retirer le titre actif

---

## 14. Événements Mondiaux

Des **Événements Mondiaux** se déclenchent automatiquement toutes les 2-4 heures selon les disponibilités.
Un seul événement est actif à la fois. Chaque événement dure 10-30 minutes.

| Événement | Durée | Effet |
|-----------|-------|-------|
| **⚡ Double XP** | 20 min | Toutes les récompenses EXP ×2 |
| **☠ Heure Sombre** | 15 min | Donjons commencent à 50% Corruption. Butins ×1.5 |
| **💰 Chasse à la Prime** | 30 min | Or et EXP par kill +25% |
| **⚡ Invasion Abyssale** | 10 min | Créatures spéciales dans le hub. Kills → Âmes |
| **💰 Tornade d'Or** | 10 min | Butins Or ×3 |
| **◆ Nuit des Spectres** | 20 min | Effets des attributs SPECTRAL doublés |

!!! success "Soyez alertes"
    Les événements sont annoncés à tout le serveur avec un titre NMS. Connectez-vous
    régulièrement pour ne pas les rater.

!!! info "Invasion Abyssale"
    L'Invasion Abyssale est un événement majeur — un grand titre apparaît à l'écran de
    tous les joueurs connectés au moment du déclenchement.

---

## 15. Caisses & Cristallisation

### Les 6 caisses

| Caisse | Obtention | Tier de loot |
|--------|-----------|-------------|
| **Chasseur** | Gratuite, farmable (drop monstres) | Commun–Rare |
| **Abyssale** | Fragments farmables ou clé (0.99€) | Rare–Épique |
| **Légendaire** | Clé achetable (4.99€) | Épique–Légendaire exclusifs |
| **Éternelle** | Clé achetable (19.99€) | Mythique + skins |
| **Saisonnière** | Pendant l'Ère active (BP ou 9.99€) | Cosmétiques exclusifs à l'Ère |
| **Abomination** | Drop rare boss fin d'Ère | Tier UNIQUE (un seul par serveur) |

!!! note "Pay-to-win ?"
    Les caisses premium donnent des items potentiellement plus puissants visuellement, mais
    **plafonnés en stats** pour rester comparables aux items farmables. En arène PvP, des
    coefficients d'équilibrage s'appliquent automatiquement.

### Le Pity System

Si vous ouvrez X caisses du même type sans obtenir de récompense rare, le système garantit
une récompense de rareté supérieure. Le compteur est affiché dans l'interface de la caisse.

### Cristallisation

Chaque item obtenu dans une caisse a un niveau de **Cristallisation** (C1 à C5) :

| Niveau | Probabilité | Bonus de stats |
|--------|-------------|----------------|
| C1 | 50% | +0% |
| C2 | 25% | +5% |
| C3 | 15% | +12% |
| C4 | 8% | +25% |
| C5 | 2% | +40% |

!!! tip "Fusion de Cristaux"
    En combinant deux items **identiques** au Forgeron, vous fusionnez leurs cristaux.
    Deux C2 → un C3. Encouragez l'ouverture multiple de la même caisse.

---

## 16. Battle Pass Saisonnier

Le Battle Pass dure **4 semaines** (une Ère), avec **100 niveaux** de récompenses.

| Niveaux | Récompenses |
|---------|------------|
| 1-25 | Items Communs et Rares, Or |
| 26-50 | Équipements Épiques, skins cosmétiques |
| 51-75 | Items Légendaires, effets de particules |
| 76-99 | Cosmétiques exclusifs, Fragments rares |
| 100 | Skin exclusif à l'Ère — **jamais reobtainable** |

!!! danger "Récompenses non réclamées"
    Les récompenses non réclamées avant la fin de l'Ère sont **perdues définitivement**.
    Pensez à claim régulièrement avec `/thehunt bp claim`.

---

## 17. Contrats de Chasse

Les Contrats sont des **objectifs quotidiens et hebdomadaires** avec des récompenses en Or, XP et BP XP.

| Type | Exemple | Difficulté |
|------|---------|-----------|
| KILL_MOBS | Tuer 50 monstres dans un donjon | Facile |
| KILL_BOSS | Vaincre un boss de donjon | Moyen |
| OPEN_CRATES | Ouvrir 3 caisses | Variable |
| COMPLETE_DUNGEONS | Compléter 2 donjons | Moyen |
| REACH_CORRUPTION | Survivre à 60% de Corruption | Difficile |
| COLLECT_GOLD | Accumuler X Or en une session | Variable |

Accédez à vos contrats via `/thehunt contracts`.

---

## 18. Guildes

Les guildes rassemblent **5 à 50 joueurs** autour d'objectifs communs.

```
/thehunt guild create <nom> <tag>   — créer une guilde
/thehunt guild invite <joueur>       — inviter un joueur
/thehunt guild join <nom>            — rejoindre une guilde
/thehunt guild leave                 — quitter la guilde
/thehunt guild info [nom]            — voir les infos d'une guilde
```

### Rangs de guilde

| Rang | Droits |
|------|--------|
| Membre | Participe aux raids, accès à la banque |
| Recruteur | Peut inviter des membres |
| Officier | Gestion des membres |
| Chef | Contrôle total |

### Bonus passifs de guilde

Les bonus dépendent du niveau de la guilde (expérience accumulée via donjons et contrats) :

| Niveau guilde | Bonus |
|---|---|
| 1-2 | Health Boost I |
| 3-4 | Health Boost I + Strength I |
| 5-6 | Health Boost II + Strength I + Speed I |
| 7-8 | Health Boost II + Strength II + Speed I |
| 9-10 | Health Boost III + Strength II + Speed II |

!!! tip "Raids de guilde"
    5 joueurs de la même guilde peuvent lancer un **Raid** (donjon partagé avec boss upscalé).
    Les récompenses sont proportionnellement plus élevées qu'un run solo.

---

## 19. PvP : Invasions Spectrales

Si vous activez le **Mode Chassé** avant de lancer un donjon, vous ouvrez votre run aux invasions.
En échange, vos récompenses sont augmentées de **+30%**.

### Conditions d'invasion

- L'envahisseur doit être d'un niveau proche du vôtre
- Vous devez être dans le donjon depuis au moins 3 minutes
- Aucun boss ne doit être déjà engagé

### Récompenses

| Résultat | Récompense |
|----------|-----------|
| Défenseur vainqueur | Loot bonus + réputation de faction |
| Défenseur vaincu | Perd ses items de run (hors-donjon conservé) |
| Envahisseur vainqueur | Or bonus + points ELO |
| Envahisseur vaincu | Perte ELO légère |

!!! tip "Le donjon est votre allié"
    En tant que défenseur, utilisez les monstres et les pièges contre l'envahisseur.
    Vous connaissez le terrain — c'est votre plus grand avantage.

---

## 20. Arènes de Chasse

Mode PvP compétitif : **deux équipes** (1v1 à 4v4) s'affrontent dans un donjon partagé.

### Objectif

Atteindre et vaincre le **boss central** en premier. L'équipe qui tue le boss gagne,
peu importe les kills PvP.

### Phase de draft

Avant chaque match, les deux équipes peuvent **bannir et choisir** des modificateurs
de donjon. La méta-stratégie est importante.

### Classement ELO

Les Arènes ont leur propre classement ELO, réinitialisé chaque Ère.
Les TOP 10 de chaque Ère reçoivent un titre exclusif.

---

## 21. Classements

| Classement | Ce qu'il mesure | Reset |
|-----------|----------------|-------|
| ELO PvP | Points d'arène | Hebdomadaire |
| Speed Run | Temps pour compléter un donjon (par seed) | Permanent |
| Boss Kills | Nombre de boss tués | Par Ère |
| Corruption Max | Niveau de Corruption le plus élevé survécu | Par Ère |
| Or Gagné | Total d'Or accumulé | Par Ère |
| Héritage des Échos | Échos les plus utiles à la communauté | Par Ère |

Consultez les classements avec `/thehunt leaderboard [type]`.

---

## 22. Le Codex

Le Codex est votre **collection de fragments de lore**. Chaque fragment révèle un morceau de
l'histoire de l'Abysse. Accédez-y avec `/thehunt codex`.

Les fragments se débloquent automatiquement :
- En complétant des donjons pour la première fois
- En ouvrant certaines caisses
- En interagissant avec des Échos
- En accomplissant des exploits spécifiques

!!! success "Récompense de collection complète"
    Compléter entièrement une catégorie du Codex donne une récompense exclusive.

---

## 23. La Boutique

La boutique mensuelle tourne chaque semaine. Elle propose :

- **2 cosmétiques** (skins, particules, trails)
- **2 items fonctionnels** (Fragments d'attributs, Cristaux de Purification)
- **1 boost** (drop rate +20% pendant 24h, non-stackable)
- **1 Wildcard** (item surprise de la semaine)

La boutique accepte les **Fragments d'Abysses** — monnaie premium achetable ou farmable
lentement (1 Fragment/heure de jeu actif).

---

## 24. Échanges entre joueurs

Proposez un échange avec `/thehunt trade <joueur>`.

1. Les deux joueurs confirment la transaction
2. Les items sont bloqués pendant la session
3. Une taxe de **5%** est prélevée (sink économique)

!!! warning "Items intransférables"
    Certains items de caisses premium sont **SOULBOUND** (non-transférables).
    Ils sont indiqués dans leur lore.

---

## 25. Commandes utiles

### Commandes joueurs

| Commande | Description |
|----------|-------------|
| `/thehunt stats [joueur]` | Voir ses statistiques |
| `/thehunt dungeon` | Démarrer un donjon |
| `/thehunt dungeon seed <seed>` | Rejouer un donjon exact |
| `/thehunt map` | Minimap du donjon actif |
| `/thehunt bp [claim\|status]` | Battle Pass |
| `/thehunt contracts` | Contrats de Chasse |
| `/thehunt invade <joueur>` | Envahir un donjon |
| `/thehunt leaderboard [type]` | Classements |
| `/thehunt faction [id]` | Rejoindre une faction |
| `/thehunt shop` | Boutique hebdomadaire |
| `/thehunt codex` | Votre Codex |
| `/thehunt arena [join\|leave]` | Arène de Chasse |
| `/thehunt trade <joueur>` | Proposer un échange |
| `/thehunt guild` | Gérer votre guilde |
| `/thehunt prestige [confirm]` | Effectuer votre Prestige |
| `/thehunt titles [set\|clear]` | Gérer vos titres cosmétiques |
| `/thehunt achievements` | Voir vos succès |

### Commandes admin (`thehunt.admin`)

!!! info "Accès admin"
    Ces commandes nécessitent la permission `thehunt.admin`. Elles sont conçues pour
    tester les fonctionnalités et débugger sans restriction.

| Commande | Description |
|----------|-------------|
| `/thehunt admin info [joueur]` | Dump complet des stats d'un joueur |
| `/thehunt admin set <stat> <val> [joueur]` | gold/exp/level/prestige/souls/streak/corruption/loginstreak |
| `/thehunt admin forgeron` | Forger l'item en main (gratuit) |
| `/thehunt admin dungeon [thème] [diff]` | Lancer un donjon |
| `/thehunt admin dungeon seed <seed>` | Rejouer un donjon exact |
| `/thehunt admin spawn boss` | Spawner un boss |
| `/thehunt admin crate <id>` | Ouvrir une crate gratuitement |
| `/thehunt admin login [joueur]` | Forcer la récompense de connexion |
| `/thehunt admin faction <id> [joueur]` | Forcer une faction sans cooldown |
| `/thehunt admin corruption <0-100>` | Fixer la Corruption du donjon |
| `/thehunt admin complete` | Compléter le donjon instantanément |
| `/thehunt admin giveitem <rarity>` | Générer un item de la rareté donnée |
| `/thehunt admin bp [joueur]` | Ouvrir le Battle Pass d'un joueur |
| `/thehunt admin prestige [joueur]` | Forcer un prestige sans condition |
| `/thehunt admin event <id\|stop>` | Déclencher ou arrêter un événement mondial |

---

## 26. Conseils & Stratégies

### Pour débuter

!!! tip "Vos premiers pas"
    1. Commencez par un donjon **EASY** ou **NORMAL** pour apprendre les mécaniques
    2. Rejoignez une faction dès le début — les bonus passifs s'accumulent vite
    3. Ouvrez les Caisses Chasseur pour démarrer votre équipement
    4. Complétez vos contrats quotidiens — l'XP Battle Pass accumule rapidement
    5. Lisez chaque Écho rencontré — ils vous éviteront des morts inutiles

### Gérer la Corruption

!!! warning "Conseils Corruption"
    - Gardez toujours un **Cristal de Purification** en réserve
    - Les runs longs sont plus rentables — apprenez à survivre en TAINTED longtemps
    - Ne tuez pas les mobs inutilement (+0.5% par kill)
    - L'équipement ABYSSAL transforme la Corruption en avantage à partir de 40%

### Maximiser le loot

!!! tip "Loot efficacement"
    - Les topologies **LABYRINTH** et **FRACTAL** donnent plus de salles spéciales
    - La difficulté NIGHTMARE ×1.8 loot vaut le risque si vous maîtrisez votre build
    - Explorez TOUT avant le boss — les trésors secondaires valent le détour
    - Profitez des **Événements Mondiaux** (Double XP, Tornade d'Or) pour les sessions intenses

### Construire son build

!!! tip "Construire un build cohérent"
    - Priorisez la **cohérence** : 3 ABYSSAL > 1 de chaque catégorie
    - Un item RARE avec 2 bons attributs synergiques vaut souvent plus qu'un LÉGENDAIRE dispersé
    - Les attributs **SOCIAL** ne servent qu'en raids de guilde — ne les prioritisez pas en solo
    - Référez-vous aux **9 archétypes** de la section 9 pour des combinaisons éprouvées

### PvP

!!! tip "Conseils PvP"
    - En Invasion, utilisez les monstres comme alliés contre l'envahisseur
    - En Arène, la **course au boss** prime sur les kills PvP
    - Mémorisez le plan du donjon ASYMMETRIC — les maps compétitives utilisent les mêmes seeds par Ère

---

## 27. FAQ

??? question "Que se passe-t-il si je meurs dans un donjon ?"
    Vous perdez les items qui étaient dans votre inventaire au moment de la mort.
    Votre équipement hors-donjon (coffre, inventaire de base) est sauvegardé.
    Un Écho est laissé à l'endroit de votre mort — vous pouvez tenter de le récupérer.

??? question "Puis-je rejouer le même donjon ?"
    Oui ! Notez le seed affiché après la génération et utilisez
    `/thehunt dungeon seed <seed>` pour le reproduire exactement.

??? question "Les caisses sont-elles pay-to-win ?"
    Les caisses premium donnent des items potentiellement plus puissants visuellement,
    mais **plafonnés en stats** pour rester comparables aux items farmables.
    En arène PvP, des coefficients d'équilibrage s'appliquent automatiquement.

??? question "Comment rejoindre une guilde ?"
    Demandez une invitation à un joueur, ou créez la vôtre avec
    `/thehunt guild create <nom> <tag>`. La création coûte un peu d'Or.

??? question "Le Battle Pass expire-t-il ?"
    Les récompenses non réclamées avant la fin de l'Ère sont **perdues définitivement**.
    Connectez-vous régulièrement et claimez avec `/thehunt bp claim`.

??? question "Pourquoi mes attributs ne s'activent-ils pas ?"
    Vérifiez que l'item est bien dans votre **main** ou sur vous en **armure**.
    Les attributs ne s'activent que sur l'équipement équipé, pas dans l'inventaire.

??? question "Comment fonctionne le Pity System ?"
    Chaque caisse a un compteur d'ouvertures par joueur. Au-delà d'un certain nombre
    d'ouvertures sans drop rare, la prochaine ouverture garantit au minimum un RARE.
    Ce compteur est affiché dans l'interface de la caisse.

??? question "Puis-je changer de faction ?"
    Oui, mais vous perdez votre réputation dans l'ancienne faction et vous ne pouvez
    le faire qu'**une fois par Ère** (= une fois par Prestige). Choisissez bien !

??? question "Comment débloquer des titres ?"
    Les titres se débloquent en complétant des **Succès** spécifiques.
    Consultez `/thehunt achievements` pour voir tous les succès disponibles et leur état.
    Équipez un titre avec `/thehunt titles set [titre]`.

??? question "Qu'est-ce qu'un événement mondial ?"
    Des événements automatiques (Double XP, Tornade d'Or...) se déclenchent toutes les
    2-4h et sont annoncés à tout le serveur. Ils durent 10-30 minutes et modifient
    les récompenses ou les conditions de jeu globalement.

---

*Wiki mis à jour le 2026-04-28 — Rendu MkDocs avec Material for MkDocs + admonitions.*