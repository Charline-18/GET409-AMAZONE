## Backlog S3 — AMAZONE

### HMW Définitif

"Comment pourrions-nous permettre aux patients des zones rurales d’obtenir rapidement une orientation médicale fiable à distance, même avec une connectivité limitée, afin d’accélérer leur prise en charge ?"

---

## User Stories MUST

*(À construire obligatoirement en S3)*

---

#### US-01

**Story :** En tant qu’Alpha, je veux appeler un service de santé pour décrire mes symptômes afin d’obtenir une orientation rapide en cas d’urgence
**Priorité :** MUST
**Outil :** SMS API / Appels vocaux (Dify + téléphonie Twilio ou équivalent local)
**Effort :** moyen
**Adresse :** Pain Reliever → “orientation sans diagnostic définitif + escalade médicale”
**Critère d'acceptation :** L’utilisateur peut appeler un numéro et recevoir une orientation (urgence / non urgence / redirection) sans internet

---

#### US-02

**Story :** En tant qu’Alpha, je veux répondre à des questions simples guidées pour décrire mon état de santé afin de réduire les erreurs d’interprétation
**Priorité :** MUST
**Outil :** Dify (flow de triage) + interface SMS/USSD ou chatbot léger
**Effort :** moyen
**Adresse :** Pain Reliever → “questionnaire structuré pour limiter les erreurs”
**Critère d'acceptation :** Le système pose au moins 5 questions standardisées et génère une orientation cohérente

---

#### US-03

**Story :** En tant qu’Alpha, je veux que le service fonctionne même avec une mauvaise connexion afin de pouvoir l’utiliser en situation critique
**Priorité :** MUST
**Outil :** SMS API + logique offline-first (Bolt.new backend léger)
**Effort :** élevé
**Adresse :** Pain Reliever → “service fonctionnant avec faible ou sans connectivité”
**Critère d'acceptation :** Le service reste utilisable via SMS ou appel même sans internet mobile actif

---

## User Stories SHOULD

*(À construire si le temps le permet)*

---

#### US-04

**Story :** En tant qu’Alpha, je veux être redirigé vers un centre de santé adapté en cas de gravité afin d’être pris en charge rapidement
**Priorité :** SHOULD
**Outil :** Dify + base de données centres de santé (Bolt.new)
**Effort :** moyen
**Adresse :** Gain Creator → “orientation rapide des cas graves”
**Critère d'acceptation :** Une réponse inclut une recommandation claire de structure de santé locale

---

#### US-05

**Story :** En tant qu’Alpha, je veux obtenir une réponse rapide sans me déplacer afin d’éviter des déplacements inutiles
**Priorité :** SHOULD
**Outil :** App mobile légère (Bolt.new)
**Effort :** moyen
**Adresse :** Gain Creator → “réduction des déplacements inutiles”
**Critère d'acceptation :** L’utilisateur obtient une réponse sans quitter son village

---

## User Stories COULD

*(Roadmap post-MVP)*

---

#### US-06

**Story :** En tant qu’Alpha, je veux pouvoir passer par une personne du village formée pour m’aider à utiliser le service afin de mieux comprendre mes symptômes
**Priorité :** COULD
**Outil :** Organisation terrain + app support simple
**Effort :** élevé
**Adresse :** Gain Creator → amélioration de l’adoption (connectivité + littératie)
**Critère d'acceptation :** Au moins un relais villageois peut assister un utilisateur dans l’usage du service

---

#### US-07

**Story :** En tant qu’Alpha, je veux recevoir des conseils de prévention simples après mon orientation afin d’éviter l’aggravation de ma situation
**Priorité :** COULD
**Outil :** Dify (messages automatisés)
**Effort :** faible
**Adresse :** Gain Creator (indirect) → amélioration continue de la prise en charge
**Critère d'acceptation :** Un message de suivi est envoyé après chaque triage

---

## Sprint S3

**Semaine 1 :** US-01, US-02, US-03 (MVP core triage + accessibilité + low connectivity)

**Semaine 2 :** US-04, US-05 (orientation médicale + expérience utilisateur complète)

**Démo S6 :** US-01 + US-02 + US-03 (preuve du triage fonctionnel en contexte rural + faible réseau)

