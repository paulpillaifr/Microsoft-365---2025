## 🔒 Zero Trust Access Flow
*"Never trust, always verify" security model that checks every access request like a strict bouncer*
```mermaid
graph TD
    A[Access Request] --> B{Verify All}
    B --> C[User Identity]
    B --> D[Device Health]
    B --> E[Network Location]
    C -->|Multi-Factor Auth| F[Grant Access]
    D -->|Patch Level/Encryption| F
    E -->|Geo/IP Restrictions| F
```

## 🌐 Microsoft Entra App Gallery  
*Centralized enterprise app store where Microsoft pre-verifies business applications for security and compatibility. you can sell app to other enterprise or you can keep your app for interne only*
```mermaid
graph LR
    A[Developer]-->B{Microsoft Check}
    B-->|Approved|C[(Gallery)]
    B-->|Rejected|D[Fix]
    C-->E[Internal Use]
    C-->F[Public Sale]
```

## 🛡️ Conditional Access (Microsoft Entra ID)  
Automatically enforces security rules before granting access to resources.
```mermaid
graph TD
    A[Login Attempt] --> B{Check Conditions}
    B --> C[Location?]
    B --> D[Device?]
    B --> E[Risk?]
    C -->|Allowed IP| F[Action]
    D -->|Compliant| F
    E -->|Low Risk| F
    F --> G[Grant Access]
    F --> H[Block]
    F --> I[Require MFA]
```
## Administrative unit:
![image](https://github.com/user-attachments/assets/f7f4ba5c-1cfe-4f0f-b8e3-55aed7467ddd)
