% Un jour dans la vie d'un développeur moderne
% Clément Delafargue
% 2016-01-15

--------------------------------------------------------------------------------

 - CTO [clever cloud](http://clever-cloud.com)
 - [\@clementd](https://twitter.com/clementd) on twitter
 - [cltdl.fr/blog](http://cltdl.fr/blog)

--------------------------------------------------------------------------------

### Programme de la journée

<details>
09h - 12h30
14h - 17h00
</details>

--------------------------------------------------------------------------------

### Contexte

<details>
Le cloud lève des contraintes opérationelles et permet plus de flexibilité,
hétérogénéité.
Automatisation, reproductibilité. Les solutions propres deviennent aussi les
solutions les plus simples à implémenter.
</details>

--------------------------------------------------------------------------------

### Objectifs

--------------------------------------------------------------------------------

## Maitriser les bases communes au <span class="red">cloud</span> et au legacy

--------------------------------------------------------------------------------

## Acquérir une <span class="red">vision d'ensemble</span> des outils du développeur

--------------------------------------------------------------------------------

## Connaître les règles de base d'une architecture <span class="red">cloud</span>

<details>
</details>

--------------------------------------------------------------------------------

## Maitriser les bases communes au <span class="red">cloud</span> et au legacy

--------------------------------------------------------------------------------

### Les règles de base

--------------------------------------------------------------------------------

### Vous travaillez en équipe

--------------------------------------------------------------------------------

### La politesse

--------------------------------------------------------------------------------

### Le versionnement

<details>
Versionnement
Pas de code en dehors du version control

Faire crééer les comptes github
Setup SSH
Creation dépôt
</details>

--------------------------------------------------------------------------------

### <https://github.com>

--------------------------------------------------------------------------------

### Les build tools / package managers

<details>
Indépendance vis-à-vis de l'IDE
Éviter la vendorisation
Builds reproductibles et automatisables
Pas de dépendances cachées
Pas de dépendances SNAPSHOT sans très bonne raison et sans limitation dans le
temps
Per-project environment
</details>

--------------------------------------------------------------------------------

### NVM

<https://github.com/creationix/nvm>

--------------------------------------------------------------------------------

### La documentation

<details>
At least: readme-driven development
Comment installer, commment lancer, comment contribuer
</details>

--------------------------------------------------------------------------------

### Les tests

<details>
Automatiser au max, utiliser un test runner
</details>

--------------------------------------------------------------------------------

## Acquérir une <span class="red">vision d'ensemble</span> des outils du développeur

--------------------------------------------------------------------------------

### `try-*`, REPL, fiddle, web IDEs

<details>
Plus besoin d'avoir un full environnement de dev sur sa machine
Possibilité de tester depuis le navigateur

try-redis pour la persistence des conversions
</details>

--------------------------------------------------------------------------------

### Database as a Service

<details>
Plus besoin d'avoir l'environnement de dev complet sur sa machine
Possibilité de partager une partie des briques en mode dev

redis sur clever + redsmin
redshift
</details>

--------------------------------------------------------------------------------

### Platform as a Service

<details>
Hosting, encourage bonne archi, bon process de dev & déploiement
</details>

--------------------------------------------------------------------------------

### Backend as a Service

<details>
Parse, etc
</details>

--------------------------------------------------------------------------------

### Communication & Physical APIs

<details>
Mailjet, Twilio
</details>

--------------------------------------------------------------------------------

## Connaître les règles de base d'une architecture <span class="red">cloud</span>

--------------------------------------------------------------------------------

### 12factor

