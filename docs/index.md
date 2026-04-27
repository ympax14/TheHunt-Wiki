# THE HUNT : ABYSS PROTOCOL — Wiki Joueur

> Bienvenue dans l'Abysse, Chasseur. Ce wiki couvre tout ce que vous devez savoir pour survivre,
> progresser et dominer dans **The Hunt : Abyss Protocol**.

---

## Table des matières

1. [Histoire & univers](#1-histoire--univers)
2. [Game Loop : comment fonctionne le jeu](#2-game-loop--comment-fonctionne-le-jeu)
3. [Les Plongées : donjons procéduraux](#3-les-plongées--donjons-procéduraux)
4. [Types de salles](#4-types-de-salles)
5. [La Corruption](#5-la-corruption)
6. [Le Système d'Échos](#6-le-système-déchos)
7. [Items & Équipement](#7-items--équipement)
8. [Attributs & Synergies](#8-attributs--synergies)
9. [Progression : Prestige & Level](#9-progression--prestige--level)
10. [Factions](#10-factions)
11. [Caisses & Cristallisation](#11-caisses--cristallisation)
12. [Battle Pass Saisonnier](#12-battle-pass-saisonnier)
13. [Contrats de Chasse](#13-contrats-de-chasse)
14. [Guildes](#14-guildes)
15. [PvP : Invasions Spectrales](#15-pvp--invasions-spectrales)
16. [Arènes de Chasse (PvP)](#16-arènes-de-chasse-pvp)
17. [Classements](#17-classements)
18. [Le Codex](#18-le-codex)
19. [La Boutique](#19-la-boutique)
20. [Échanges entre joueurs](#20-échanges-entre-joueurs)
21. [Commandes utiles](#21-commandes-utiles)
22. [Conseils & Stratégies](#22-conseils--stratégies)
23. [FAQ](#23-faq)

---

## 1. Histoire & univers

### L'Abysse

Il y a des siècles, les cités souterraines prospéraient grâce à l'énergie des cristaux abyssaux, gemmes formées au cœur de la terre par une pression indicible. Mais les mineurs creusèrent trop profond. Ils réveillèrent quelque chose.

L'Abysse n'est pas un lieu physique — c'est un état de la matière. Une corruption qui ronge les pierres, transforme les hommes en spectres et redéfinit les lois de la mort. Les donjons que vous explorez sont des fragments d'Abysse solidifiés : des architectures impossibles où le temps n'a plus de sens et où la mort laisse des traces.

### Les Chasseurs

Vous êtes un Chasseur — l'un des rares individus capables de plonger dans l'Abysse et d'en revenir. Votre objectif : explorer les donjons, affronter les monstres et récupérer les artéfacts abyssaux avant que la Corruption ne vous engloutisse.

### Les Factions

Quatre factions se disputent le contrôle des artéfacts abyssaux :

- **L'Ordre Abyssal** — Croit que la Corruption peut être domestiquée et utilisée comme arme
- **Le Conseil Spectral** — Cherche à communiquer avec les esprits piégés dans l'Abysse
- **La Confrérie Céleste** — Veut sceller l'Abysse pour toujours, au prix de tout sacrifice
- **Les Primordiaux** — Gardiens de l'équilibre, ils ne croient ni à la domination ni à la destruction

---

## 2. Game Loop : comment fonctionne le jeu

The Hunt fonctionne sur **3 niveaux de temps** :

### Loop court — La Plongée (5-15 min)
Chaque fois que vous lancez un donjon, c'est une **Plongée**. Vous descendez dans les profondeurs, affrontez des monstres, explorez les salles et tentez de vaincre le boss final. Si vous mourez, vous perdez vos items du run.

### Loop moyen — La Session (1-3h)
Au fil de plusieurs Plongées, vous progressez dans vos **Contrats de Chasse**, gagnez de la réputation auprès de votre **Faction**, accumulez de l'EXP et de l'Or.

### Loop long — L'Ère (4 semaines)
Chaque **Ère** est une saison complète avec son propre Battle Pass, ses récompenses exclusives et son chapitre narratif. À la fin de l'Ère, certains éléments de progression sont partiellement réinitialisés.

---

## 3. Les Plongées : donjons procéduraux

### Comment lancer un donjon

Utilisez `/thehunt dungeon` pour lancer une Plongée. Vous pouvez spécifier :
- Un **seed** (pour rejouer exactement le même donjon)
- Un **thème** visuel
- Une **difficulté**

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

### Modificateurs de donjon

Des modificateurs spéciaux peuvent s'appliquer à un run :
- **FLOODED** : Le donjon est partiellement inondé — nagez pour avancer
- **CURSED** : Vos soins sont réduits de 50%
- **VOLCANIC** : Des geysers de lave jaillissent périodiquement
- **CORRUPTED** : La Corruption monte deux fois plus vite
- **POISONED** : L'air du donjon vous empoisonne légèrement
- **FROZEN** : Ralentissement permanent, mais les mobs sont plus lents

### Topologies de donjons

La **topologie** détermine la forme du donjon :

| Topologie | Description | Conseil |
|-----------|-------------|---------|
| LINEAR | Couloir avec embranchements | Idéal pour débuter |
| BRANCHING | 2-4 branches qui se rejoignent | Explorez tout pour le loot |
| WEB | Réseau avec boucles | Vous pouvez vous perdre, prenez la carte |
| SPIRAL | Anneaux en spirale | Le boss est au cœur |
| LABYRINTH | Labyrinthe, chemin unique | Très difficile, récompenses élevées |
| CONCENTRIC | Anneaux concentriques, boss au centre | Portails raccourcis disponibles |
| FRACTAL | Salles spéciales fréquentes | Build-crafting intense |
| ASYMMETRIC | Deux moitiés miroir | Idéal pour les arènes PvP |

### La carte `/thehunt map`

En cours de Plongée, `/thehunt map` affiche une grille 9×9 autour de votre position. Symboles :
- ⛺ Spawn, ☠ Boss, ★ Trésor, ⚡ Piège, ♕ Mini-boss
- $ Marché Noir, ⚖ Jugement, ◈ Miroir, ⌚ Nexus Temporel
- ♥ Sacrifice, ⚒ Forge Abyssale, ☽ Crypte, ✦ Éveil

### Déconnexion

Si vous vous déconnectez pendant une Plongée, vous avez **2 minutes** pour vous reconnecter avant que votre donjon soit perdu.

---

## 4. Types de salles

### Salles de combat
- **Salle d'Arène (ARENA)** : Combat de base contre des vagues de monstres
- **Salle des Pièges (TRAP)** : Monstres et lave. Des coffres sont cachés au centre de sécurité
- **Mini-Boss (MINIBOSS)** : Un ennemi puissant qui garde un trésor
- **Boss Arena (BOSS)** : La salle finale — anneau de lave, piliers massifs, le boss vous attend

### Salles de loot
- **Salle au Trésor (TREASURE)** : Coffres sans combat ou presque
- **Bibliothèque (LIBRARY)** : Fragments de lore + coffres de livres

### Salles spéciales ABYSS PROTOCOL

#### Le Marché Noir
Un marchand spectral vous propose des items rares en échange d'Âmes (ressource gagnée en tuant des monstres). Les items disponibles changent à chaque run. N'hésitez pas si vous voyez un attribut rare — il ne reviendra pas.

#### La Salle du Jugement
Une épreuve morale : le donjon vous pose une question ambiguë. La bonne réponse réduit la Corruption de 10% et octroie un buff pour le run. La mauvaise donne une malédiction. Il n'y a pas toujours de "bonne" réponse évidente.

#### La Salle des Miroirs
Affrontez un **clone de vous-même** avec vos propres attributs et équipement (légèrement réduits). Vaincre votre double rapporte une récompense unique.
!!! danger "Attention"
    le clone connaît vos stratégies.

#### Le Nexus Temporel
Le temps se ralentit. Précision et timing sont cruciaux. Des projectiles bougent au ralenti — esquivez-les ou renvoyez-les. Compléter le Nexus donne un Éclat de Temps : fragment rare pour la Forge.

#### La Salle des Sacrifices
Échangez une partie de vos PV maximum contre des buffs permanents pour le run : +dégâts, +vitesse, +résistance. Chaque sacrifice est définitif pour ce run.

#### La Forge Abyssale
Améliorez vos items en utilisant des ressources trouvées dans le donjon :
- Fragments minéraux → améliore un attribut aléatoire de l'équipement
- Noyaux abyssaux → monte la rareté d'un item
- Cristaux de corruption → ajoute un attribut ABYSSAL aléatoire

#### La Crypte des Prédécesseurs
Une salle générée depuis les **Échos** de vrais joueurs morts avant vous. Les fantômes reproduisent leur dernière séquence de combat. Apprenez de leurs erreurs et récupérez leurs affaires.

#### La Salle de l'Éveil
Un tutoriel dynamique adapté à votre niveau. Débutant : rappel des mécaniques de base. Expert : défis avancés avec récompenses selon la performance. Toujours utile, jamais ennuyeux.

---

## 5. La Corruption

La Corruption est l'horloge invisible du donjon. Elle monte en permanence et crée une pression temporelle : vous ne pouvez pas farmer indéfiniment.

### Comment la Corruption monte

- **Passive** : +0.08% par seconde (100% en ~21 minutes)
- **En combat** : +0.15% par seconde supplémentaire tant que vous combattez
- **Piège activé** : +2.5% immédiatement
- **Mob tué** : +0.5% immédiatement (anti-farming)

### Les paliers de Corruption

| Palier | % | Effets |
|--------|---|--------|
| **PURE** | 0-19% | Aucun effet |
| **TAINTED** | 20-39% | Message d'avertissement. Les monstres sentent votre présence |
| **CORRUPTED** | 40-59% | Légère cécité + mobs infligent +25% de dégâts |
| **DEFILED** | 60-79% | Ralentissement + mobs infligent +50% de dégâts |
| **ABYSSAL** | 80-100% | Wither actif + mobs infligent ×2 dégâts |

### Comment réduire la Corruption

- **Cristal de Purification** : item craftable ou achetable, réduit la Corruption de 25% instantanément
- **Salle du Jugement** (succès) : -10%
- Il n'existe pas d'autre moyen de réduire la Corruption en dehors de ces deux sources

### Survivre à haute Corruption

Les attributs **ABYSSAL** s'activent ou scalent avec le niveau de Corruption. Si vous portez de l'équipement Abyssal, les hauts niveaux de Corruption peuvent devenir un avantage tactique.

---

## 6. Le Système d'Échos

Quand un joueur meurt dans un donjon, il laisse un **Écho** — une empreinte spectrale à l'endroit de sa mort.

### Types d'Échos

| Type | Couleur | Ce que vous trouvez |
|------|---------|---------------------|
| ⚠ Avertissement | Blanc | Un message d'alerte sur le danger |
| ♦ Survivant | Vert | Soins (+2 HP) en interagissant |
| ⚡ Piège | Rouge | Information sur un piège proche |
| ✦ Loot | Jaune | Indice sur un coffre caché |
| ☠ Boss Info | Violet | Information sur le boss de ce donjon |

### Détecter et interagir

Approchez-vous à moins de **8 blocs** d'un Écho pour être notifié. La notification apparaît au maximum toutes les **5 secondes**. Utilisez `/thehunt echo interact` pour obtenir les informations.

### Récupérer son propre Écho

Si vous mourez dans un donjon, vous pouvez revenir dans le même donjon (même seed) et retrouver votre Écho. Utilisez `/thehunt echo claim` à proximité de votre Écho pour récupérer **50% de vos items perdus**.

### Conseils

- Créez un Écho informatif avant d'explorer une zone dangereuse (mort volontaire et retour)
- Les Échos de la Crypte des Prédécesseurs sont générés depuis de vrais Échos de joueurs
- Les Échos SURVIVOR d'autres joueurs sont vos meilleurs amis dans les runs difficiles

---

## 7. Items & Équipement

### Raretés

Les items custom de The Hunt ont 8 niveaux de rareté :

| Rareté | Couleur | Slots d'attributs max |
|--------|---------|----------------------|
| COMMUN | §a Vert | 1 |
| RARE | §9 Bleu | 2 |
| ÉPIQUE | §5 Violet | 3 |
| LÉGENDAIRE | §e Jaune | 4 |
| MYTHIQUE | §6 Or | 5 |
| EXOTIQUE | §c Rouge | 5 |
| DIVIN | §8 Gris foncé | 6 |
| UNIQUE | §f Blanc | 7 |

### Lire le lore d'un item

Chaque item The Hunt affiche dans son lore :
1. La rareté
2. Le niveau de Cristallisation (si issu d'une caisse)
3. Les attributs par catégorie avec leur niveau
4. La description custom (si elle existe)

### Le Forgeron

Le Forgeron (`/thehunt forge`) vous permet de :
- **Ajouter un attribut** à un item (avec un Fragment d'Attribut)
- **Améliorer un attribut** au niveau suivant (avec des ressources)
- **Retirer un attribut** (sans remboursement)
- **Monter la rareté** d'un item (coût important)

### Attributs Living (Évolutifs)

Certains attributs spéciaux peuvent **évoluer** avec l'usage. Leur niveau monte automatiquement en jouant :

| Stade | Condition | Apparence |
|-------|-----------|-----------|
| INERT | Niveau 1 | Texte gris |
| AWAKENED | 100 kills | Texte blanc |
| SENTIENT | 500 kills | Texte jaune |
| ANCIENT | 2000 kills | Texte or avec étoile |
| LEGENDARY | 5000 kills | Texte arc-en-ciel animé |

!!! danger **Attention**
    Les attributs vivants perdent leur progression si l'item est vendu ou échangé. Réfléchissez avant de vous en séparer.

---

## 8. Attributs & Synergies

### Catégories d'attributs

| Catégorie | Couleur | Description |
|-----------|---------|-------------|
| COMBAT | §c Rouge | Améliorent vos attaques |
| DÉFENSE | §3 Cyan | Réduisent les dégâts reçus |
| RÉGÉNÉRATION | §c Rouge | Soins et survie |
| UTILITÉ | §e Jaune | Mobilité, exploration |
| FARM | §6 Or | Optimisent le loot |
| ABYSSAL | §4 Rouge foncé | Interagissent avec la Corruption |
| SPECTRAL | §5 Violet | Interagissent avec les Échos |
| SOCIAL | §b Bleu ciel | Scalent avec les alliés proches |

### Attributs notables

**HÉMORRAGIE** (COMBAT) : Vos attaques causent des saignements — dégâts sur la durée.

**GARDIEN** (DÉFENSE) : Génère un bouclier d'absorption quand vous subissez des dégâts importants.

**AGILITÉ** (UTILITÉ) : Vitesse de déplacement augmentée. Plus utile qu'il n'y paraît dans un labyrinthe.

**PACTE ABYSSAL** (ABYSSAL) : Convertit la Corruption en dégâts bonus. Risqué mais dévastateur à hauts niveaux de Corruption.

**RÉSISTANCE ABYSSALE** (ABYSSAL) : Réduit les malus de Corruption. Indispensable pour survivre aux runs longs.

**FRÉNÉSIE CORROMPUE** (ABYSSAL) : Vitesse d'attaque augmentée proportionnellement à la Corruption.

**MÉMOIRE DE L'ÉCO** (SPECTRAL) : Vous alertez plus tôt des Échos proches. Rayon de détection étendu.

**RÉSONANCE SPECTRALE** (SPECTRAL) : Les Échos SURVIVOR vous soignent plus. Puissant en Crypte.

**SYNERGIE DE GROUPE** (SOCIAL) : Bonus de dégâts +5% par allié dans un rayon de 20 blocs.

**BOUCLIER PARTAGÉ** (SOCIAL) : Quand un allié proche subit des dégâts, une partie est absorbée par le groupe.

### Synergies

Certaines **combinaisons d'attributs** sur votre équipement total déclenchent des **Synergies** :

- Quand une synergie devient active, un message s'affiche dans le chat
- Les synergies actives sont visibles dans le lore de vos items (icône spécial)
- Expérimenter les combinaisons fait partie du plaisir du jeu — découvrez-les vous-même !

!!! info "**Conseil**"
    Le Forgeron vous permet de tester différentes combinaisons. Ne vous enfermez pas dans une seule façon de jouer.

---

## 9. Progression : Prestige & Level

### Niveaux

Vous gagnez des niveaux (1 à 120) en tuant des monstres, complétant des donjons et des contrats. L'XP requise par level augmente progressivement.

### Prestige

À level 120, vous pouvez atteindre le **Prestige** suivant. Votre level repart à 1 mais votre prestige augmente (0 à 3999). Chaque prestige rend le jeu légèrement plus difficile mais augmente les récompenses.

**Couleurs de prestige** :
- P0 : Gris — Chasseur novice
- P1-4 : Bleu — Chasseur expérimenté
- P5-9 : Jaune — Éclaireur de l'Abysse
- P10-14 : Or — Vétéran
- P15-19 : Rouge — Maître Chasseur
- P20+ : Violet → Rose → Blanc → Cyan...

### Souls

Les Âmes (`souls`) sont une monnaie spéciale gagnée en tuant des monstres abyssaux. Elles servent exclusivement au Marché Noir dans les donjons.

### Or

L'Or est la monnaie principale du jeu. Utilisée pour le Forgeron, la boutique et les échanges entre joueurs.

**Gains d'Or en donjon** :

| Action | Or gagné | EXP gagnée |
|--------|----------|------------|
| Tuer un mob normal | ~10 Or | ~10 EXP |
| Tuer le boss final | ~100 Or | ~100 EXP |

> Ces valeurs de base évoluent en fonction de votre level et prestige. Les kills comptent aussi vers vos contrats `COLLECT_GOLD` et le classement `GOLD_EARNED`.

---

## 10. Factions

Les Factions offrent des **bonus passifs** et des **missions exclusives**. Rejoignez-en une avec `/thehunt faction`.

| Faction | Bonus principal | Idéal pour |
|---------|----------------|-----------|
| Ordre Abyssal | Attributs ABYSSAL +15% efficacité | Runs longs et haute Corruption |
| Conseil Spectral | Attributs SPECTRAL +15% efficacité, Échos plus fréquents | Explorez et récupérez des Échos |
| Confrérie Céleste | Résistance à la Corruption +20% | Nouveaux joueurs, survie |
| Primordiaux | Loot +10%, EXP +10% | Farm et progression |

Changer de faction est possible mais coûte de l'Or. Vous ne pouvez rejoindre qu'une faction à la fois.

---

## 11. Caisses & Cristallisation

### Les 6 caisses

| Caisse | Obtention | Tier de loot |
|--------|-----------|-------------|
| **Chasseur** | Gratuite, farmable (drop monstres) | Commun–Rare |
| **Abyssale** | Fragments farmables ou clé (0.99€) | Rare–Épique |
| **Légendaire** | Clé achetable (4.99€) | Épique–Légendaire exclusifs |
| **Éternelle** | Clé achetable (19.99€) | Mythique + skins |
| **Saisonnière** | Pendant l'Ère active (BP ou 9.99€) | Cosmétiques exclusifs à l'Ère |
| **Abomination** | Drop rare depuis boss de fin d'Ère | Tier UNIQUE (un seul par serveur) |

### Le Pity System

Si vous ouvrez X caisses du même type sans obtenir de récompense rare, le système garantit une récompense de rareté supérieure. La caisse vous indique quand vous approchez d'un palier "pity".

### Cristallisation

Chaque item obtenu dans une caisse a un niveau de **Cristallisation** (C1 à C5) tiré aléatoirement :

| Niveau | Probabilité | Bonus de stats |
|--------|-------------|----------------|
| C1 | 50% | +0% |
| C2 | 25% | +5% |
| C3 | 15% | +12% |
| C4 | 8% | +25% |
| C5 | 2% | +40% |

Le niveau de Cristallisation est affiché dans le lore de l'item et ne peut pas être changé après ouverture.

### Fusion de Cristaux

En combinant deux items **identiques** au Forgeron, vous fusionnez leurs cristaux. Deux C2 → un C3. Cela encourage l'ouverture multiple de la même caisse.

---

## 12. Battle Pass Saisonnier

Le Battle Pass dure **4 semaines** (une Ère). Il comporte **100 niveaux** avec des récompenses gratuites (niveaux pairs) et premium (tous les niveaux si vous avez le pass premium).

### Comment monter dans le Battle Pass

- Tuer des monstres dans les donjons
- Compléter des donjons (bonus important)
- Ouvrir des caisses
- Compléter des contrats

### Récompenses typiques

- Niveaux 1-25 : Items Communs et Rares, Or
- Niveaux 26-50 : Équipements Épiques, skins cosmétiques
- Niveaux 51-75 : Items Légendaires, effets de particules
- Niveaux 76-99 : Cosmétiques exclusifs, Fragments d'attributs rares
- Niveau 100 : Skin exclusif à l'Ère — **jamais reobtainable**

### Prix du Battle Pass Premium

Le Battle Pass Premium est obtenu dans la boutique. Il donne accès à toutes les récompenses premium sans rien changer au gameplay (aucun avantage PvE/PvP direct — uniquement des cosmétiques et des accélérateurs de progression).

---

## 13. Contrats de Chasse

Les Contrats sont des **objectifs quotidiens et hebdomadaires** avec des récompenses en Or, XP et EXP Battle Pass.

### Types de contrats

| Type | Exemple | Difficulté |
|------|---------|-----------|
| KILL_MOBS | Tuer 50 monstres dans un donjon | Facile |
| KILL_BOSS | Vaincre un boss de donjon | Moyen |
| OPEN_CRATES | Ouvrir 3 caisses | Variable |
| COMPLETE_DUNGEONS | Compléter 2 donjons | Moyen |
| REACH_CORRUPTION | Survivre à 60% de Corruption | Difficile |

Accédez à vos contrats via `/thehunt contract`.

---

## 14. Guildes

Les guildes rassemblent **5 à 50 joueurs** autour d'objectifs communs.

### Créer ou rejoindre une guilde

```
/thehunt guild create <nom>       — créer une guilde
/thehunt guild invite <joueur>    — inviter un joueur
/thehunt guild join <nom>         — rejoindre une guilde
/thehunt guild leave              — quitter la guilde
```

### Rangs

| Rang | Droits |
|------|--------|
| Membre | Participe aux raids, accès à la banque |
| Recruteur | Peut inviter des membres |
| Officier | Gestion des membres, contrats de guilde |
| Chef | Contrôle total, peut dissoudre la guilde |

### Récompenses de guilde

- Chaque donjon complété contribue **200 XP de guilde**
- Les contrats de guilde rapportent des récompenses à tous les membres
- La guilde apparaît dans le **Classement inter-guildes** de l'Ère

### Raids de guilde

5 joueurs de la même guilde peuvent lancer un **Raid** (donjon partagé avec boss upscalé). Les récompenses sont proportionnellement plus élevées.

---

## 15. PvP : Invasions Spectrales

Si vous activez le **Mode Chassé** avant de lancer un donjon, vous ouvrez votre run aux invasions d'autres joueurs. En échange, vos récompenses sont augmentées de **+30%**.

### Conditions d'invasion

- L'envahisseur doit être d'un niveau proche du vôtre
- Vous devez être dans le donjon depuis au moins 3 minutes
- Aucun boss ne doit être déjà engagé
- L'envahisseur entre dans une salle non-visitée

### Mécaniques PvP

- L'envahisseur a des **capacités spéciales d'assassin** (invisibilité temporaire, téléport)
- Le défenseur connaît le donjon et peut utiliser les pièges à son avantage
- Les monstres attaquent les deux joueurs indépendamment

### Récompenses

- **Défenseur vainqueur** : loot bonus + réputation de faction
- **Défenseur vaincu** : perd ses items de run, mais garde ses items d'inventaire hors-donjon
- **Envahisseur vainqueur** : Or bonus + points de classement ELO
- **Envahisseur vaincu** : Perte de points ELO légère

---

## 16. Arènes de Chasse (PvP)

Mode PvP compétitif : **deux équipes** (1v1 à 4v4) s'affrontent dans un donjon partagé (topologie ASYMMETRIC).

### Objectif

Atteindre et vaincre le **boss central** en premier. L'équipe qui tue le boss gagne, peu importe les kills PvP.

### Phase de draft

Avant chaque match, les deux équipes peuvent **bannir et choisir** des modificateurs de donjon. Stratégie méta importante.

### Classement ELO

Les Arènes ont leur propre classement ELO, réinitialisé chaque Ère. Les TOP 10 de chaque Ère reçoivent un titre exclusif.

---

## 17. Classements

Six classements vous permettent d'exceller dans différents domaines :

| Classement | Ce qu'il mesure | Reset |
|-----------|----------------|-------|
| ELO PvP | Points d'arène | Hebdomadaire |
| Speed Run | Temps pour compléter un donjon (par seed) | Permanent |
| Boss Kills | Nombre de boss tués | Par Ère |
| Corruption Max | Niveau de Corruption le plus élevé survécu | Par Ère |
| Or Gagné | Total d'Or accumulé | Par Ère |
| Héritage des Échos | Échos les plus utiles à la communauté (voté) | Par Ère |

Consultez les classements avec `/thehunt lb [type]`.

---

## 18. Le Codex

Le Codex est votre **collection de fragments de lore**. Chaque fragment révèle un morceau de l'histoire de l'Abysse.

Accédez-y avec `/thehunt codex`. Les fragments se débloquent automatiquement :
- En complétant des donjons pour la première fois
- En ouvrant certaines caisses
- En interagissant avec des Échos
- En accomplissant des exploits spécifiques

Compléter entièrement une catégorie donne une **récompense exclusive**.

---

## 19. La Boutique

La boutique mensuelle tourne chaque semaine. Elle propose :
- **2 cosmétiques** (skins, particules, trails)
- **2 items fonctionnels** (Fragments d'attributs, Cristaux de Purification)
- **1 boost** (drop rate +20% pendant 24h, non-stackable)
- **1 Wildcard** (item surprise de la semaine)

La boutique accepte les **Fragments d'Abysses** — une monnaie premium achetable ou farmable lentement (1 Fragment/heure de jeu actif).

**Wish List** : Marquez les items qui vous intéressent avec le clic droit. Vous serez notifié quand ils apparaissent en rotation.

---

## 20. Échanges entre joueurs

Proposez un échange avec `/thehunt trade <joueur>`. Le système de trading :

1. Les deux joueurs confirment la transaction
2. Les items sont bloqués pendant la session
3. Une taxe de 5% est prélevée sur la valeur des items (sink économique)
4. Certains items de caisses premium sont **intransférables**

---

## 21. Commandes utiles

| Commande | Description |
|----------|-------------|
| `/thehunt dungeon` | Lancer un donjon |
| `/thehunt dungeon <seed> <theme> <difficulty>` | Donjon précis |
| `/thehunt map` | Afficher la minimap du donjon actif |
| `/thehunt echo interact` | Interagir avec l'Écho le plus proche |
| `/thehunt echo claim` | Récupérer vos items depuis votre propre Écho |
| `/thehunt forge` | Ouvrir le Forgeron |
| `/thehunt crate <id>` | Ouvrir une caisse |
| `/thehunt bp` | Battle Pass |
| `/thehunt contract` | Contrats de Chasse |
| `/thehunt faction` | Choisir sa faction |
| `/thehunt guild create <nom>` | Créer une guilde |
| `/thehunt guild invite <joueur>` | Inviter dans la guilde |
| `/thehunt shop` | Boutique |
| `/thehunt trade <joueur>` | Proposer un échange |
| `/thehunt lb [type]` | Classements |
| `/thehunt codex` | Votre Codex |

---

## 22. Conseils & Stratégies

### Pour débuter
1. Commencez par les donjons en difficulté **EASY** pour apprendre les mécaniques
2. Rejoignez une faction dès le début — les bonus passifs s'accumulent vite
3. Ouvrez les Caisses Chasseur que vous trouvez pour démarrer votre équipement
4. Complétez vos contrats quotidiens : l'XP Battle Pass accumule rapidement

### Gérer la Corruption
- Gardez au moins un **Cristal de Purification** en réserve
- Les runs longs sont plus rentables — apprenez à survivre en TAINTED longtemps
- L'équipement ABYSSAL transforme la Corruption en avantage : testez-le dès que possible
- Ne tuez pas les mobs inutilement (chaque kill ajoute 0.5% de Corruption)

### Maximiser le loot
- Les **topologies LABYRINTH** et **FRACTAL** donnent plus de salles spéciales
- La difficulté NIGHTMARE ×1.8 loot vaut le risque si vous maîtrisez votre build
- Explorez TOUT avant de vous diriger vers le boss — les trésors secondaires valent le détour
- Les **coffres du Marché Noir** sont souvent les meilleurs du run

### Construire son build
- Priorisez la **cohérence** des attributs : 3 ABYSSAL fonctionnent mieux que 1 de chaque catégorie
- Lisez les **descriptions de synergies** dans le lore de vos items
- Un item RARE avec 2 bons attributs synergiques vaut souvent plus qu'un LÉGENDAIRE avec 4 attributs dispersés
- Les attributs **SOCIAL** ne servent que lors des raids de guilde — ne les prioritisez pas en solo

### PvP
- En Invasion, utilisez les monstres comme alliés contre l'envahisseur
- En Arène, la course au boss prime sur les kills PvP
- Mémorisez le plan du donjon ASYMMETRIC : chaque Ère utilise les mêmes seeds de maps compétitives

---

## 23. FAQ

**Q : Que se passe-t-il si je meurs dans un donjon ?**
R : Vous perdez les items qui étaient dans votre inventaire au moment de la mort. Votre équipement hors-donjon (coffre, inventaire de base) est sauvegardé. Un Écho est laissé à l'endroit de votre mort — vous pouvez tenter de le récupérer.

**Q : Puis-je rejouer le même donjon ?**
R : Oui ! Notez le seed affiché après la génération et utilisez `/thehunt dungeon <seed> <theme> <difficulty>` pour le reproduire exactement.

**Q : Est-ce que les caisses sont pay-to-win ?**
R : Les caisses premium donnent des items esthétiquement différents et potentiellement plus puissants visuellement, mais ils sont **plafonnés en stats** pour rester comparables aux items farmables. En arène PvP, des coefficients d'équilibrage s'appliquent automatiquement.

**Q : Comment rejoindre une guilde sans en avoir une ?**
R : Demandez une invitation à un joueur qui a une guilde, ou créez la vôtre. La commande `/thehunt guild create <nom>` coûte un peu d'Or.

**Q : Le Battle Pass expire-t-il ?**
R : Les récompenses de Battle Pass qui ne sont pas réclamées avant la fin de l'Ère sont **perdues définitivement**. Connectez-vous régulièrement !

**Q : Pourquoi mes attributs ne s'activent-ils pas ?**
R : Vérifiez que l'item est bien dans votre main ou sur vous en armure. Les attributs ne s'activent que sur l'équipement **equippé**, pas dans l'inventaire.

**Q : Comment fonctionne le Pity System des caisses ?**
R : Chaque caisse a un compteur d'ouvertures par joueur. Au-delà d'un certain nombre d'ouvertures sans drop rare, la prochaine ouverture garantit au minimum une récompense RARE. Ce compteur est affiché dans l'interface de la caisse.

**Q : Puis-je changer de faction ?**
R : Oui, mais cela coûte de l'Or et vous perdez votre progression de réputation avec l'ancienne faction. Choisissez bien !

---

*Wiki mis à jour le 2026-04-27 — à tenir à jour à chaque modification du mode de jeu.*
