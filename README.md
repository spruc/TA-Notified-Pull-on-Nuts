# TA-Notified-Pull-on-Nuts
Nuts-implementation of Twiin 1.2 TA Notified Pull

# Introduction
This specification describes how to use the Twiin Technical Agreement (TTA) when the involved actors make use of Nuts-specification for implementing digital trust. It is a generic specfication that does not contain use case specific information. Use case specific specifications are described in use case profiles. E.g. the Nuts-use-case-profile "bgz-referral" describes how to use this specification in the context of a medical specialist referral (commonly reffered to in Dutch as a BgZ-verwijzing).

# Relation to other documents
- *Twiin Technical Agreement FHIR Notified Pull* (abbreviated as TTA FHIR - Notified pull): https://twiin-afsprakenstelsel.scrollhelp.site/ta12/10-2-3-tta-fhir-notified-pull
  TTA FHIR - Notified pull offers clear specifications for the use of FHIR at the data layer. However, TTA FHIR - Notified pull also describes specifications for the generic functions 'authentication' and 'authorization'. These specifications are not compatible with Trust over IP based infrastructures such as Nuts. In addition, TTA FHIR - Notified pull does not describe specifications for the generic function 'addressing'. This means that additional agreements are required for each implementation. The goal of TA-Notified-Pull-on-Nuts is to achieve scalability by expanding Twiin Technical Agreement FHIR Notified Pull with an unambiguous and Trust over IP compliant specfication use of the above generic functions.
- *Twiin Technical Agreement FHIR - Authentication & Authorization* (abbreviated as TTA FHIR - Authentication & Authorization): https://twiin-afsprakenstelsel.scrollhelp.site/ta12/10-2-5-tta-fhir-authentication-authorization
  TTA FHIR - Authentication & Authorization specifies the generic functions 'authentication' & 'authorization'. The abovementioned TTA FHIR - Notified pull refers to this specification.  TA-Notified-Pull-on-Nuts replaces TTA FHIR - Authentication & Authorization for a specfication that is aligned with the Nuts-specifications.
- *Twiin Technical Agreement FHIR - Addressing* (abbreviated as TTA FHIR - Addressing): https://twiin-afsprakenstelsel.scrollhelp.site/ta12/10-2-8-tta-addressing
  TTA FHIR - Addressing specifies the generic functions 'addressing'. The abovementioned TTA FHIR - Notified pull refers to this specification.  TA-Notified-Pull-on-Nuts replaces TTA FHIR - Addressing for a specfication that is aligned with the Nuts-specifications.
 
- *Nuts-use-case-profile "bgz-referral"*
  The Nuts-use-case-profile "bgz-referral" describes how to use the specification 'TA-Notified-Pull-on-Nuts' in the context of a medical specialist referral (commonly reffered to in Dutch as a BgZ-verwijzing).

# Key differences with TTA FHIR - Notified pull
- All references to TTA FHIR - Authentication & Authorization have to be ignored and replaced by the information provided in this document
- All references to TTA FHIR - Addressing have to be ignored and replaced by the information provided in this document

# Test
