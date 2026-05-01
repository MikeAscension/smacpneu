# ASCENT PNEU — Cahier des charges produit (PRD)

> Version 1.0 · Périmètre MVP uniquement · Site vitrine B2B bilingue FR / EN

---

## 1. Problème

**Absence de crédibilité et de surface de contact pour les acheteurs internationaux.**

Ascent Pneu opère sans présence web. Un négociant international qui reçoit une sollicitation commerciale ne peut pas vérifier l'existence, le sérieux ou l'offre de l'entreprise. L'absence de site génère de la friction commerciale, allonge les cycles de vente et disqualifie Ascent Pneu avant même le premier échange.

| # | Friction |
|---|---|
| 1 | Pas de preuve d'existence : sans site, pas de légitimité perçue |
| 2 | Pas de présentation de l'offre : volumes, origines, certifications disponibles |
| 3 | Pas de canal de contact structuré pour initier une demande d'offre |

---

## 2. Utilisateur cible

**Responsable achats ou gérant d'une société de négoce de pneus usagés.**

| Attribut | Détail |
|---|---|
| Géographie | Afrique, Moyen-Orient, Asie du Sud |
| Comportement | Visite sur mobile, lit en diagonale, décide vite |
| Langue | Français ou anglais selon le marché |
| Attente primaire | Comprendre l'offre en moins de 60 secondes |
| Déclencheur de contact | Volume disponible, origine France, prix compétitif |

> Cet utilisateur ne lit pas : il scanne. Il cherche trois signaux — **qui vous êtes, ce que vous vendez, comment vous contacter**. Si l'un manque, il repart.

---

## 3. Fonctionnalités MVP

Le site est un **one-pager bilingue FR / EN**. Rien de plus.

### 3.1 Structure des pages

| Page | Contenu |
|---|---|
| `/fr/` | Version française complète |
| `/en/` | Version anglaise complète |

- Sélecteur de langue `FR | EN` visible dans la navbar
- Langue par défaut : français
- Toutes les sections sont traduites dans les deux langues — aucune exception

### 3.2 Blocs de contenu

**Bloc Hero**
- Nom de marque + tagline bilingue
- FR : *"Collecté en France. Livré au monde."*
- EN : *"Sourced in France. Delivered worldwide."*
- CTA principal : "Demander un devis" / "Request a quote"

**Bloc Offre**
- Description de l'activité : achat de pneus usagés auprès des sous-traitants Aliapur en France, revente à des négociants internationaux
- Catégories disponibles : tourisme, utilitaire, poids lourd
- Conditionnement et volumes indicatifs

**Bloc Preuve**
- Lien au réseau Aliapur
- Zone géographique de collecte (France)
- SIRET et mentions légales visibles

**Bloc Contact**
- Formulaire : nom, entreprise, pays, email, message
- Envoi par email — pas de back-office
- Email direct en clic (mailto)
- WhatsApp en clic direct (wa.me)
- Coordonnées accessibles depuis toutes les sections

**Footer**
- Mentions légales
- Langue : FR / EN
- Email + WhatsApp

---

## 4. Critères de réussite

| Critère | Mesure |
|---|---|
| Compréhension autonome | Un négociant comprend l'offre seul, sans échange préalable |
| Performance mobile | Chargement < 3 secondes sur connexion 4G |
| Génération de contact | Au moins 1 demande qualifiée dans les 30 jours post-lancement |
| Indexation | Site référencé sur Google sous "Ascent Pneu" dans les 60 jours |
| Couverture bilingue | 100 % des contenus disponibles en FR et EN au lancement |

---

## 5. Domaine

**ascentpneu.com** — enregistré sur Namecheap.

| URL | Contenu |
|---|---|
| `https://www.ascentpneu.com` | Redirection vers `/fr/` (langue par défaut) |
| `https://www.ascentpneu.com/fr/` | Version française |
| `https://www.ascentpneu.com/en/` | Version anglaise |

- Configurer les DNS Namecheap pour pointer vers l'hébergeur (Vercel ou Netlify)
- Certificat SSL activé automatiquement via l'hébergeur
- Redirection `ascentpneu.com` → `www.ascentpneu.com` (avec www)

---

## 6. Contraintes techniques

- Site statique ou SSG (ex. Next.js, Astro, ou HTML/CSS pur) — pas de CMS en v1
- Hébergement : Vercel, Netlify ou équivalent
- Traduction manuelle uniquement — pas de widget de traduction automatique (Google Translate, Weglot)
- Formulaire de contact : service tiers simple (Formspree, EmailJS) — pas de back-office
- Optimisé mobile-first (marché cible = Afrique de l'Ouest, Moyen-Orient)
- Images compressées, pas de vidéo en autoplay

---

## 6. Hors périmètre v1

Les éléments suivants ne font pas partie du MVP. Ils seront évalués en v2 après validation que le site génère des contacts entrants.

| Exclu | Raison |
|---|---|
| Catalogue produit dynamique | Complexité inutile en v1 |
| Espace client / login | Pas de besoin utilisateur identifié |
| Prise de commande en ligne | Hors modèle commercial actuel |
| Module de collecte | Futur métier, pas encore opérationnel |
| Blog / actualités | Charge éditoriale non justifiée |
| CRM intégré | Prématuré avant volume de leads |
| Chat en temps réel | WhatsApp suffit en v1 |
| Langues supplémentaires (arabe, portugais…) | Évalué selon marchés actifs en v2 |
| Calculateur de prix | Prix négociés au cas par cas |
| Vidéo de présentation | Hors budget et scope MVP |

---

*Ascent Pneu · PRD v1.0 · Site bilingue FR / EN*
