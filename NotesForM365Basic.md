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

## Conditional Access (Microsoft Entra ID)

### 1. Définition
- **Concept** : "Vérifie toujours avant d'accorder l'accès."
- **Exemple** : Comme un aéroport avec passeport + scan de sécurité.

### 2. Composants Clés
- **Conditions** :
  - Localisation (pays/réseau)
  - Appareil (sécurisé/conforme)
  - Risque (activité suspecte)
  
- **Actions** :
  - Autoriser (accès complet)
  - Bloquer (accès refusé)
  - Exiger MFA (double vérification)

### 3. Exemples de Règles
- "MFA obligatoire hors du bureau"
- "Bloquer les connexions depuis des pays à risque"
- "Limiter l'accès aux appareils non-enregistrés"

### 4. Pourquoi ?
✅ Adapte la sécurité au contexte  
✅ Empêche les accès non autorisés  
✅ Complète la stratégie Zero Trust

### 5. Lien ?
https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview
