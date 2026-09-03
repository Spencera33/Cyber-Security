# Digital Identity 

*Concepts, Components & the NIST Standard*

*Review of class*

---
*What is Digital Identity* 


Digital identity is far more than a username and password


It is the full collection of attributes, credentials, and behaviors that uniquely represent a person in a digital system


Organizations rely on identity systems to control access, enforce accountability, and meet legal obligations.

Identity decisions touch privacy, security, equity, and civil liberties at the same time.


Authoritative U.S. standard: NIST Special Publication 800-63-4 (2024 Final)



**Three Assurance Level Hierachies** 
---
1. IAL — Identity Assurance Level: how rigorously the identity was proved

2. AAL — Authentication Assurance Level: strength of the authentication mechanism

3. FAL — Federation Assurance Level: trustworthiness of federated identity assertions




**Identity Proofing**
---
*Establishing who you are* 

IAL2 (Remote): document scan + live facial comparison — verifies identity without in-person visit

IAL3 (In-person): trained staff review original documents; biometric capture on-site

Proofing failures create critical vulnerabilities — impostors gain access to high-value systems


**Authentication Proving Control of an Identity** 
---
Three factor categories:

*Something You Know — password, PIN, security question (weakest)* 

*Something You Have — OTP app, hardware token, smart card*

*Something You Are — fingerprint, face, voice (biometrics)*  


**Fderation trusted Identity across Domains** 
---
*Federation: identity established by one system (Identity Provider / IdP) accepted by another (Relying Party)*

*Common protocols: SAML 2.0, OpenID Connect (OIDC), OAuth 2.0*

*Example: "Sign in with Google" — Google asserts your identity to a third-party app*

*FAL levels: FAL1 (no encryption required) → FAL2 (assertion encrypted) → FAL3 (holder-of-key)*


# Biometrics 
*Capabilities, Error Rates, Bias & Ethics* 





**Extra information** 
