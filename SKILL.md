---
name: humanize-text
description: >
  Humanise et réécrit des textes pour les rendre plus naturels, authentiques et moins robotiques.
  Utilise cette skill dès que l'utilisateur mentionne "humaniser", "rendre plus naturel", "moins IA",
  "moins robotique", "retoucher mon texte", "améliorer le ton", "rewrite", "reformuler", "réécrire",
  "polish", "on dirait un robot", "trop formel", ou toute demande de transformation d'un texte vers
  un style plus humain et professionnel. Fonctionne en français, anglais, et toute autre langue.
  Déclenche aussi quand l'utilisateur colle un texte et demande de l'améliorer, le rendre fluide,
  ou retirer les traces d'IA.
---

# Humanize Text Skill

Transforme des textes générés par IA ou trop formels en textes authentiquement humains, professionnels mais naturels.

---

## Objectif

Produire un texte qui :
- **Sonne humain** : rythme varié, voix naturelle, légères imperfections stylistiques intentionnelles
- **Reste professionnel** : crédible, clair, approprié au contexte
- **Préserve le sens** : aucune information perdue, même message, meilleure forme
- **Évite les marqueurs IA** : voir liste ci-dessous

---

## Processus en 4 étapes

### 1. Analyser le texte source
Identifie :
- La langue (français, anglais, autre)
- Le type de contenu (email, article, post LinkedIn, rapport, message, etc.)
- Le niveau de formalité cible
- Les marqueurs IA présents (voir liste)

### 2. Appliquer les transformations
Applique les règles de transformation selon le type de texte détecté.

### 3. Vérifier la cohérence
- Le sens est-il préservé à 100% ?
- Le ton est-il cohérent du début à la fin ?
- Y a-t-il encore des marqueurs IA résiduels ?

### 4. Livrer le résultat
- Présente le texte humanisé directement, sans explications superflues
- Si le texte est long (>300 mots) ou complexe, offre une note rapide sur les principaux changements
- Ne pas expliquer chaque modification ligne par ligne sauf si demandé

---

## Marqueurs IA à éliminer

### Phrases et formules typiques
- "Il est important de noter que..."
- "Dans un monde en constante évolution..."
- "En conclusion, il convient de souligner..."
- "Il va sans dire que..."
- "En tant que [X], il est essentiel de..."
- "Cela étant dit..."
- "Il est crucial de..."
- "N'hésitez pas à..." (en fin d'email)
- "Je reste à votre disposition pour toute question"
- "In today's fast-paced world..."
- "It's worth noting that..."
- "It goes without saying..."
- "As an AI language model..."
- "Certainly!", "Absolutely!", "Of course!" (en début de réponse)

### Patterns structurels IA
- Listes à puces systématiques pour tout (même quand la prose serait plus naturelle)
- Transitions trop lisses et prévisibles : "Premièrement... Deuxièmement... Enfin..."
- Paragraphes tous de la même longueur
- Chaque paragraphe commence par une phrase de topic très explicite
- Répétition du mot-clé principal toutes les 2-3 phrases
- Conclusion qui résume exactement ce qui vient d'être dit

### Vocabulaire surutilisé par les IA
**FR:** crucial, essentiel, primordial, incontournable, pertinent, optimal, robuste, synergies, paradigme, holistique, proactif
**EN:** leverage, utilize, delve, crucial, vital, seamless, robust, cutting-edge, game-changer, holistic, synergy, paradigm shift, foster, streamline

---

## Règles de transformation

### Rythme et structure
- **Varier la longueur des phrases** : mélanger courtes (impact) et longues (développement)
- **Briser la symétrie** : éviter que tous les paragraphes aient la même structure
- **Favoriser la prose** sur les listes quand le contenu s'y prête
- **Fragmenter occasionnellement** : une phrase courte. Seule. Pour l'effet.

### Voix et ton
- **Utiliser la voix active** plutôt que passive quand possible
- **Contractions naturelles** en anglais (it's, we're, you'll) selon le niveau de formalité
- **Expressions idiomatiques légères** appropriées au contexte professionnel
- **Point de vue humain** : opinions, nuances, reconnaître la complexité

### Authenticité
- **Introduire une légère imprécision naturelle** : "environ", "dans les prochaines semaines", plutôt que "dans un délai de 14 jours ouvrables"
- **Reconnaître les limites** quand pertinent : "ce n'est pas parfait, mais..."
- **Ajouter de la chaleur** sans être familier : l'humain derrière le texte doit transparaître
- **Éviter la sur-politesse** : moins de formules de courtoisie automatiques

### Par type de contenu

**Email professionnel**
- Objet direct et spécifique
- Ouvrir avec la raison du contact (pas de "j'espère que ce message vous trouve bien" sauf si sincère)
- Clôture simple et directe
- Signature adaptée au contexte

**Article / contenu long**
- Accroche qui crée de la curiosité, pas une définition
- Transitions narratives plutôt que signposts mécaniques
- Exemples concrets et spécifiques
- Conclusion qui ouvre une perspective, pas qui résume

**Post LinkedIn / réseaux sociaux**
- Première ligne percutante (visible avant "voir plus")
- Ton personnel et direct
- Éviter les emojis décoratifs excessifs
- Call-to-action naturel, pas formulaique

**Rapport / document formel**
- Conserver la structure formelle requise
- Humaniser le langage dans les sections narratives
- Garder la précision des données et chiffres

---

## Format de réponse

```
[Texte humanisé — livré directement]

---
*(optionnel si >300 mots)* **Note rapide :** [2-3 changements clés effectués]
```

Si l'utilisateur fournit un texte sans instruction précise, humanise directement sans demander de confirmation.

Si le contexte manque (type de document, destinataire), fais une inférence raisonnable et mentionne-la brièvement après le texte.

---

## Exemples de transformation

**Avant (IA) :**
> "Il est important de noter que notre entreprise a récemment mis en place une nouvelle stratégie visant à optimiser nos processus internes afin d'améliorer notre efficacité opérationnelle."

**Après (humain) :**
> "On a revu notre façon de travailler en interne ces derniers mois — et les premiers résultats sont encourageants."

---

**Avant (IA) :**
> "In today's fast-paced business environment, it is crucial to leverage cutting-edge solutions to remain competitive and foster sustainable growth."

**Après (humain) :**
> "Staying competitive means making smarter decisions faster. That's the bet we're making."

---

## Rappel final

L'objectif n'est pas de rendre le texte informel — c'est de le rendre **honnête**. Un humain qui maîtrise son sujet et s'exprime clairement. Pas un robot qui simule la maîtrise.
