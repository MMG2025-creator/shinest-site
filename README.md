# SHINEST — Site web

## État courant — version instable (11 novembre 2026)

- **Version de travail :** `unstable-2026-11-11`
- **Statut :** déployée en production, mais non déclarée stable ni validée comme version finale.
- **Site public :** https://shinest.app
- **Dépôt Git :** https://github.com/MMG2025-creator/shinest-site
- **Branche :** `main`
- **Commit de référence :** `727aa852bf4a2b6dbe455cad80471ddcd10d389a`
- **Hébergement :** Vercel — projet `shinest-site`

## État réel du site publié

Le site est une page vitrine SHINEST en français, avec une direction visuelle claire et contemporaine, une mise en page responsive et des interactions de navigation.

Sections actuellement présentes :
1. Accueil — « Imaginer de nouvelles opportunités. Construire les solutions de demain. »
2. Bloc de présentation — vision indépendante, produits propriétaires, valeur mesurable.
3. Notre vision — innovation, création de valeur et Blue Ocean Strategy.
4. Trois piliers — Explorer, Concevoir, Développer.
5. Nos réalisations — BEP et MakeMeGlow.
6. Notre approche — comprendre, différencier, expérimenter.
7. Bloc Blue Ocean Strategy.
8. Conclusion et pied de page.

L’ancienne formulation de positionnement a été retirée de l’ensemble du site et ne doit pas être réintroduite.

## Identité visuelle et logo

- Le logo transmis par le fondateur est utilisé dans le header et le footer.
- Le symbole est également défini comme favicon et image de partage.
- L’image du symbole est servie depuis l’asset Vercel : `https://dmmcy0pwk6bqi.cloudfront.net/ff2590d65d2b175116ca935b798e6f86f7d717ad`.
- Le mot « Shinest » affiché à côté du symbole est actuellement rendu en Georgia (serif) dans le HTML ; le logotype complet original n’est donc pas encore intégré comme une seule image.

## Réalisations présentées

- **BEP** — présenté comme une expérience numérique de structuration du budget et des dépenses. Lien actuel : https://bep-mobile.onrender.com/
- **MakeMeGlow** — présenté comme un univers beauté et progression personnelle. La page indique que sa présentation publique est en préparation.

## Éléments techniques présents

- Fichier de page : `src/index.html` (également déployé à la racine sous `index.html`).
- HTML, CSS et JavaScript intégrés dans une page statique.
- Navigation fixe, menu mobile interactif, défilement fluide et animations d’apparition avec prise en compte de `prefers-reduced-motion`.
- Métadonnées SEO et Open Graph.
- Déploiement Vercel en production sur `shinest.app`.

## Contrôles effectués

- Déploiement Vercel marqué `READY`.
- Vérification du domaine public : réponse HTTP 200.
- Vérification du HTML publié : la formulation exclue n’est plus présente.
- Les vérifications visuelles exhaustives sur appareils réels, l’accessibilité approfondie et les tests fonctionnels complets restent à mener.

## Historique récent

- **11 novembre 2026** — refonte éditoriale publiée sur le domaine de production.
- **11 novembre 2026** — intégration du symbole du logo fourni, dans le header, le footer, le favicon et les métadonnées de partage.
- **11 novembre 2026** — suppression globale de la formulation explicitement refusée.
- **11 novembre 2026** — état enregistré comme **version instable** : le site est en ligne, mais ne doit pas être considéré comme une version stable ou définitivement validée.

## Prochaines vérifications

- [ ] Intégrer le logotype original complet, sans recomposer le mot-symbole en typographie de substitution.
- [ ] Vérifier visuellement le rendu mobile et desktop.
- [ ] Tester tous les liens et interactions.
- [ ] Réaliser un contrôle d’accessibilité et des métadonnées SEO/Open Graph.
- [ ] Effectuer une validation finale avant de déclarer une version stable.
