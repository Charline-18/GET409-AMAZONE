# GET409-AMAZONE

## Le problème 

Les populations sénégalaises ont une réelle difficulté à accéder aux soins notamment dans les zones reculées ou font face à un manque d'effectifs des médecins ou encore un accès limité à l'internet. 

## Notre réponse

**Comment pourrions-nous** permettre aux patients d'avoir accès à un diagnostic sans se déplacer et à etre pris en charge dans les meilleurs délai par une alternive aux médecins?


## L'équipe


| Prénom   | Nom     | Rôle                   | GitHub       |
| -------- | ------- | ---------------------- | ------------ |
| Ndeye Khadidiatou  | Aidara  | Chef de Produit        | @Khadija257  |
| Aichatou | Barakat | Master Prompt Engineer | @Charline-18 |
| Aissatou | Diallo  | Dev UI                 | @sewo04      |
| Adama    | Gueye   | Responsable impact     | @AdamaG244   |


## Documentation





## Prompt 1  DECOUVERTE du problème —Santé et telemedecine

'''
Tu es un expert en Santé et telemedecine au Sénégal.

Identifie les 3 principaux problemes que rencontrent
Les malades et les médecins dans l’organisation du système de santé au Sénégal.

Pour chaque probleme, indique :
- La cause principale
- L'impact sur la vie quotidienne
- Une piste de solution technologique accessible
'''


## Prompt 2  GUIDE D'INTERVIEW — Santé et telemedecine

'''
Tu es un UX Researcher specialise dans les usages
numeriques en Afrique de l'Ouest.

Je dois interviewer Alpha vivant à Bambey, se rendant à l'hopital de Toukar et qui fait face au probleme
suivant : Il doit faire 20km pour une consultation ou pour une urgence médicale; ce qui implique qu'il peut arriver trop tard pour une personne mal en point .

Genere un guide d'interview d'empathie avec :

1. 3 questions d'ouverture (briser la glace)
2. 5 questions d'exploration en profondeur
   (utilisant 'Pourquoi ?' et 'Racontez-moi...')
3. 2 questions sur les aspirations et les gains attendus

Format : questions numerotees, courtes, sans jargon technique.
'''

## Prompt 3 GENERATEUR DE HMW — Santé et telemedecine

'''
Tu es un facilitateur en Design Thinking.

Voici les observations cles de notre interview avec
, médecin généraliste à l’hopital de Fann :

Observation 1 : Les patients tombent le plus souvent malade durant l'hivernage surtout dans les zones reculées
Observation 2 : Les postes de santé à proximité manquent d'effectifs ou d'équipements nécessaires aux premiers soins 
Observation 3 : Ils ont du mal à trouver un moyen de transport rapide

La frustration principale identifiee est :
Le manque de moyen de transport rapide. 

Genere 5 enonces 'Comment pourrions-nous...' (HMW)
qui reformulent cette frustration en opportunite
de conception.

Criteres : ni trop vague, ni trop precis,
ne propose pas encore de solution.

Format : liste numerotee, 1 phrase par enonce.
'''

## Prompt 4 CARTE D'EMPATHIE 

'''
# ROLE
Tu es un UX Researcher expert en Design Thinking
pour des projets d'innovation sociale en Afrique.

## PERSONA DE NOTRE EQUIPE
- Prenom, age, profession : Alpha, 30ans, agriculteur
- Localisation : Bambey,Bakakak, SENEGAL
- Probleme principal : Le manque de moyen de transport rapide. 
- Equipement digital : Téléphone , manque de réseau...
- Revenus approximatifs : 100.000-250.000
- Contexte familial : Famille nombreuse à sa charge

## OBSERVATIONS DE NOS INTERVIEWS
- Ce qu'il/elle a dit : Il peine à se rendre à l'hopital
- Ce qu'il/elle a fait : Il est parti chercher une charette chez son voisin
- Emotion principale detectee : Frustration

## TACHE
Genere la Carte d'Empathie complete.

## FORMAT DE SORTIE STRICT

### 1. Ce qu'il/elle PENSE ET RESSENT
- Comment ne pas perdre l'un des membres de sa famille en cours de route
- Avoir accès aux soins à proximité 
- [Aspiration secrete]

### 2. Ce qu'il/elle VOIT
- 20Km
- Une charette en guise de transport

### 3. Ce qu'il/elle ENTEND
- Envoyer le malade chez un vieux guerisseur du village
- Faire de l'automédication

### 4. Ce qu'il/elle DIT ET FAIT
- Il panique
- Je cours chercher de l'aide

### 5. FRUSTRATIONS (Pains)
- Ne pas savoir quoi faire
- Trouver un moyen de transport

### 6. ASPIRATIONS (Gains)
- Bénéficier d'une aide soignante le plus rapidement possible
- Assistance lors des urgences
'''


