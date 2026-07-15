# Mission Codex — livrer une V1 présentable du site TMC

## But de la mission
Transformer le socle Astro actuel en une V1 crédible et publiable du site officiel de Tennis Mentors Club, déployée automatiquement sur GitHub Pages.

## Priorité absolue
Obtenir ce soir une page d’accueil complète, responsive et professionnelle, avec un logo officiel correctement intégré et une URL exploitable dans la signature email.

## Travail demandé

1. Auditer le dépôt actuel et corriger toute erreur de structure Astro ou de configuration GitHub Pages.
2. Mettre en place un design system léger dans le CSS global : couleurs TMC, typographie, espacements, rayons, ombres, boutons et largeurs de contenu.
3. Créer ou finaliser les composants réutilisables :
   - `Header`
   - `Footer`
   - `Hero`
   - `SectionHeading`
   - `ProgramCard`
   - `CTA`
4. Construire une page d’accueil avec les sections suivantes :
   - hero institutionnel avec logo officiel et baseline ;
   - mission de Tennis Mentors Club ;
   - présentation des programmes Mentorship Access et Mentorship Talents ;
   - services et outils : information, matériel/cordage, transmission, communauté, Live Score ;
   - appel aux clubs, entreprises, mécènes et marques ;
   - boutons Contact, HelloAsso et Live Score ;
   - footer complet.
5. Ajouter les pages minimales :
   - `/association`
   - `/programmes/mentorship-access`
   - `/programmes/mentorship-talents`
   - `/partenaires`
   - `/contact`
   - `/mentions-legales`
6. Ajouter une route publique stable pour le logo utilisé dans les emails :
   - `/assets/images/tmc-logo-email.png`
7. Vérifier :
   - responsive mobile/tablette/desktop ;
   - liens internes et externes ;
   - accessibilité de base ;
   - métadonnées SEO et Open Graph ;
   - favicon ;
   - aucune image cassée ;
   - aucun contenu fictif ;
   - `npm run build` réussi.
8. Faire un commit clair, puis ouvrir une pull request ou pousser sur `main` selon le mode de travail disponible.

## Contenus validés à respecter

### Mentorship Access
Programme pour mieux s’équiper, mieux comprendre et mieux avancer. Il facilite l’accès au matériel, aux connaissances, aux outils et aux ressources nécessaires pour progresser dans de meilleures conditions. Axes : informer les familles, faciliter l’accès au matériel, former et transmettre, développer des outils utiles, créer une communauté d’entraide. Objectif indicatif de collecte : 14 000 € pour une année pilote.

### Mentorship Talents
Programme pilote 2026-2027 pour accompagner quatre jeunes joueurs du Bas-Rhin afin que le coût d’une saison intensive ne freine pas leur progression. Axes : s’entraîner, s’équiper et se déplacer. Objectif indicatif de collecte : 12 000 €.

## Liens officiels
- Email : `contact@tennismentorsclub.fr`
- Site : `https://tennismentorsclub.fr`
- Instagram : `https://www.instagram.com/tennismentorsclub/`
- HelloAsso : `https://www.helloasso.com/associations/tennis-mentors-club`
- Live Score : `https://live.tennismentorsclub.fr`

## Critères d’acceptation
- Le site se construit sans erreur avec `npm ci && npm run build`.
- La page d’accueil paraît finalisée, pas « en construction ».
- La charte TMC est cohérente sur toutes les pages.
- Le logo officiel est utilisé sans modification.
- Le déploiement GitHub Pages fonctionne.
- Le fichier du logo email est publiquement accessible sur le domaine final.
- Aucun secret ni donnée personnelle n’est commité.