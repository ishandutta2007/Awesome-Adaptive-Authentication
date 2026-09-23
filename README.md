# Awesome-Adaptive-Authentication

## Top Adaptive Authentication Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Risk-Based Authentication, Adaptive MFA, Contextual Access, Behavioral Signals & Intelligent Identity Protection*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Adaptive Authentication**. These systems evaluate login and access context (device, location, behavior, risk signals) in real time and dynamically adjust authentication requirements—stepping up MFA when risk is high and reducing friction when risk is low.



**Examples** include Cisco Duo, Silverfort, PingOne Protect, Okta Adaptive MFA, Microsoft Entra ID Protection, RSA Adaptive Authentication, ForgeRock Intelligent Access, SecureAuth, IBM Verify, and OneLogin SmartFactor (the category leaders).



**Open-source emphasis**: Full commercial adaptive/risk engines with global threat intelligence and polished policy UIs dominate enterprises. Open-source options include **Keycloak extensions**, **Apereo CAS risk-based authentication**, behavioral biometrics projects, and general open identity platforms that can be extended with custom risk logic. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cisco Duo](https://duo.com/)**  

  Widely adopted MFA and adaptive access platform with device trust, risk-based policies, and strong integration across applications and VPNs.



- **[Microsoft Entra ID Protection](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id-protection)**  

  Risk-based identity protection within Microsoft Entra, detecting anomalous sign-ins and automating remediation and conditional access.



- **[Okta Adaptive MFA / Okta Identity]**(https://www.okta.com/)**  

  Adaptive multi-factor and risk-based authentication capabilities within the Okta Identity Cloud, using contextual signals to adjust challenges.



- **[PingOne Protect, ForgeRock Intelligent Access, RSA Adaptive Authentication](https://www.pingidentity.com/)**  

  Enterprise adaptive and risk-based authentication solutions evaluating device, behavior, and threat signals for step-up decisions.



- **[Silverfort, SecureAuth, IBM Verify, OneLogin SmartFactor](https://www.silverfort.com/)**  

  Platforms extending adaptive MFA and risk-based controls to legacy systems, cloud apps, and diverse authentication scenarios.



- **[Other commercial adaptive authentication & identity protection platforms](https://duo.com/)**  

  Solutions focused on continuous risk evaluation, behavioral biometrics, and intelligent access policies.



## Open-Source GitHub Projects



- **[Keycloak Adaptive Authentication extension](https://github.com/mabartos/keycloak-adaptive-authn)**  

  Extension for Keycloak that enables real-time changes to authentication requirements based on context and risk, with optional AI-assisted evaluation and integration of remote risk signals.



- **[Apereo CAS Risk-Based Authentication](https://apereo.github.io/cas/)**  

  Built-in risk-based authentication support in Apereo CAS—evaluates authentication attempts against historical behavior and configurable risk criteria, then mitigates high-risk events (e.g., force MFA).



- **[Open behavioral / risk-based auth experiments](https://github.com/search?q=risk-based+authentication+OR+adaptive+MFA+OR+behavioral+biometrics)**  

  Research and prototype projects implementing dual-agent risk scoring, keystroke/mouse behavioral signals, and adaptive thresholds for frictionless MFA.



- **[OpenBehavior-Auth & similar behavioral engines](https://github.com/rugadameghanath/OpenBehavior-Auth)**  

  Privacy-oriented open engines that capture interaction rhythms (keystroke dynamics, pointer velocity) for passive, adaptive risk scoring without storing typed content.



- **[Keycloak, Authentik, Authelia, Ory](https://github.com/keycloak/keycloak)**  

  Leading open-source identity and access management platforms that support MFA, conditional flows, and custom authenticators—forming the base for many self-hosted adaptive setups.



- **[Custom risk engines & policy frameworks](https://github.com/search?q=authentication+risk+engine+OR+adaptive+access+open+source)**  

  Libraries and frameworks for calculating risk scores from device, geo, velocity, and behavioral signals that can be plugged into open IdPs.



- **[WebAuthn / passkey open tooling](https://github.com/search?q=WebAuthn+OR+passkey+open+source)**  

  Open components for phishing-resistant authenticators often used as step-up factors in adaptive policies.



- **[SIEM / detection open stacks used for auth risk](https://github.com/search?q=authentication+anomaly+detection)**  

  Open detection rules and pipelines that surface anomalous login behavior for adaptive decisioning.



### Additional Strong Open-Source Options



- **Keycloak + adaptive extension**: Most practical path for adding risk-based step-up to a mature open IdP.

- **CAS risk-based auth**: Mature open SSO platform with explicit risk evaluation and mitigation actions.

- **Behavioral biometrics**: Emerging open engines for passive signals that reduce reliance on active MFA.

- **Composable stacks**: Open IdP (Keycloak/Authentik) + custom risk service + WebAuthn/MFA providers.

- Full commercial adaptive platforms still lead in global threat intelligence, polished policy UX, and broad app coverage.



**Frameworks for building custom systems**:  

**Keycloak** (with adaptive extensions) and **Apereo CAS** (native risk-based authentication) are the strongest open foundations.  

Behavioral open projects add passive risk signals.  

Commercial platforms (Duo, Entra ID Protection, Okta, Ping, RSA, ForgeRock, Silverfort, etc.) provide managed risk engines, threat intelligence, and enterprise policy administration.  

Many organizations run open IdPs for core authentication and layer commercial adaptive/risk services, or build custom risk logic on top of Keycloak/CAS. Fully open adaptive stacks are feasible for teams that can develop and maintain risk models and signal pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Adaptive authentication decisions affect security and user experience. Poorly tuned risk models can lock out legitimate users or fail to challenge attackers. Test thoroughly and monitor false positives/negatives.

- Open-source solutions offer transparency and control but require you to design risk signals, maintain models, and handle high availability. Commercial platforms shift operational and intelligence burden to the vendor. Align any solution with your threat model and compliance requirements.



---



**Made for identity architects, security engineers, and IAM teams implementing risk-based and adaptive access.**  

Let's expand open options for contextual authentication while recognizing the intelligence, scale, and support that leading commercial adaptive authentication platforms deliver.
