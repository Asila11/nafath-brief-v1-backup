Version: NAFATH-V1

Track: Networking

Overview

A government single sign-on (SSO) service allows people 
to use one trusted digital identity to access multiple public services. 
Software connects applications to the identity provider, 
while mobile apps provide convenient access. 
Networking carries authentication requests reliably 
between users and government systems. 
Cybersecurity protects credentials, sessions, and services 
from attacks. Data practices govern how identity information is collected, 
shared, and protected. AI may help detect suspicious activity, 
but its decisions require testing and oversight. 
These six areas work together to make government SSO services secure, 
reliable, and trustworthy.


Software

A government SSO integration should use established identity standards 
instead of creating its own login protocol. OpenID Connect (OIDC) adds 
an identity layer on top of OAuth 2.0, allowing an application to verify 
a user’s identity through an identity provider. Applications should validate 
tokens, restrict redirect URIs, and protect user sessions.

Resource: OpenID Connect Core 1.0 - https://openid.net/specs/openid-connect-core-1_0.html


AI

AI can help an SSO service detect unusual sign-in patterns and identify 
potentially fraudulent activity. However, AI alerts may be incorrect, 
so they should be evaluated carefully and should not automatically be 
treated as proof of fraud. Organizations should assess risks, 
monitor system performance, protect user privacy, and maintain human oversight.

Resource: NIST AI Risk Management Framework Playbook - https://www.nist.gov/itl/ai-risk-management-framework/nist-ai-rmf-playbook


Mobile

Mobile SSO apps should protect user information while providing a convenient sign-in experience. 
Apps should request sensitive device permissions only when needed, explain why each permission is required, 
and handle permission denial gracefully. Device permissions should remain separate from authentication, 
because granting access to a device feature does not prove a user’s identity.

Resource: Android Developers - Request runtime permissions - https://developer.android.com/training/permissions/requesting


Networking


Cybersecurity

Data

Misconception in My Track

Open Question