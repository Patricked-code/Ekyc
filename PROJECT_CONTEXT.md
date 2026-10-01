# PROJECT_CONTEXT

- Repository: Patricked-code/Ekyc
- Project: Ekyc
- Owner: @Patricked-code
- Canonical branch: main
- Baseline subject HEAD: 4bf80309313f3d34f74ffca183bd540583d2e87f
- First governed agent: ChatGPT via CHATGPT

## Mission

Plateforme KYC/eKYC comparable à Onfido, avec un parcours d’identification et de vérification totalement automatisé de bout en bout.

## Scope

### In scope
- onboarding KYC/eKYC entièrement automatisé
- capture et vérification de pièces d’identité
- OCR et extraction automatique des données
- contrôle d’authenticité des documents
- selfie / vidéo / preuve de vie (liveness)
- comparaison biométrique visage ↔ document
- détection de fraude et anomalies
- vérification des données d’identité
- orchestration automatique des contrôles
- score de risque / décision automatique
- API KYC pour intégration avec des applications tierces
- webhooks et suivi du statut des vérifications
- portail client / back-office de supervision
- journalisation, preuves et audit des décisions
- gestion du consentement et protection des données
- architecture permettant d’ajouter ensuite AML, PEP, sanctions et autres contrôles réglementaires

### Out of scope
- services bancaires ou de paiement
- conservation ou gestion de fonds
- octroi de crédit
- trading / investissement
- gestion de comptes bancaires
- développement des applications métiers des clients qui consommeront l’API

## Architecture / stack

Profile selection: chainsolutions-fullstack-web. See docs/ARCHITECTURE.md.

## Infrastructure / deployment

Declared baseline status: UNKNOWN_TO_DISCOVER.

## External systems

- None declared

## Initial constraints

- Le parcours KYC/eKYC doit être automatisé de bout en bout autant que possible.
- Les données d’identité et biométriques doivent être protégées, avec gestion du consentement et traçabilité.
- Chaque décision et contrôle doit être journalisable, explicable et auditable avec ses preuves.
- La plateforme doit exposer une API et des webhooks pour intégration avec des applications tierces.
- Les services bancaires, paiements, conservation de fonds, crédit, trading et gestion de comptes bancaires sont hors périmètre.
- Aucun serveur, domaine, répertoire, base ou fournisseur externe ne doit être considéré comme existant ou choisi tant qu’il n’est pas observé ou explicitement décidé.

## Governed repository setup

Workflow model: STANDARD_GOVERNED_FLOW
MCP linked: True
Domain binding: {"mode": "UNRESOLVED", "kind": "ROOT_DOMAIN", "reason": "DISCOVER_AVAILABLE_NAMES", "server": "S1"}
Deployment binding: null
