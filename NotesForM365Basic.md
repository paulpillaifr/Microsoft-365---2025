## Zero Trust & Identité (Microsoft 365)

### 1. Zero Trust
- **Définition** : "Ne jamais faire confiance, toujours vérifier."
- **Exemple** : Château fort qui vérifie tout le monde à chaque porte.

### 2. Identité
- **Méthodes** : 
  - Mot de passe (code secret).
  - MFA (ex : mot de passe + SMS).
  - Vérification de l’appareil (ex : antivirus).

### 3. Outils Microsoft
- **Azure AD** : Liste des utilisateurs autorisés.
- **Conditions d’accès** : Règles (ex : "Seuls les profs modifient les notes").
- **Détection des menaces** : Bloque les accès suspects.

### 4. Pourquoi ?
✅ Stop aux hackers.  
✅ Protection même avec mot de passe volé.  
✅ Contrôle précis des accès.

### 5. Lien ?
https://learn.microsoft.com/fr-fr/security/zero-trust/deploy/identity

 ---

## 📝 Conditional Access
> "C'est comme un videur intelligent pour ton ordinateur. Il vérifie :
> - **Qui tu es** (ton mot de passe + téléphone)
> - **D'où tu viens** (ta localisation)
> - **Si ton appareil est sûr** (comme vérifier si tu as tes vaccins)
> Avant de te laisser entrer dans tes apps de travail."

## 👔 Définition Pro (mots simples)
> Mécanisme de sécurité qui applique des règles contextuelles (qui/quand/comment) pour contrôler l'accès aux ressources cloud.

## 🔑 Points Clés à Retenir

### 1. Les 3 Composants Principaux
- **Conditions** (QUAND appliquer) :
  - 🌐 Localisation (IP/pays)
  - 📱 Appareil (marqué/conforme)
  - 🚨 Niveau de risque (détection d'anomalies)

- **Contrôles** (QUE faire) :
  ```mermaid
  graph LR
    A[Accès] -->|Risque faible| B[Autoriser]
    A -->|Risque moyen| C[Exiger MFA]
    A -->|Risque élevé| D[Bloquer]

### Lien :
https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview?WT.mc_id=Portal-Microsoft_AAD_ConditionalAccess
