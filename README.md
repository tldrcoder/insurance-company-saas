
# About

*Inxurenz* is a B2B SaaS helping insurance companies.



# Entities

**User** A User who is an inhouse employee of the Insurer. This can be an executive, actuary or adjuster.

**Insurer** An insurance company. Our SaaS is aimed at these kind of businesses.

**Employee** Defines a relationship between a User and an Insurer where the User is an employee of the Insurer.

**SalesChannel** Defines a relationship between a User and an Insurer where the User sells policies on behalf of the Insurer.

**Person** A person can be either a natural person or a juridical person. A Person record is typically a policyholder entered by the sales agent or else a damaged party entered in by the claims adjuster. It is possible that there are multiple records for the same person. For example suppose John Doe buys a policy from Insurer A and a policy from Insurer B. Both insurer A and insurer B register John Doe on the system and a separate record is kept for both insurers like this they can manage their own data.

**NaturalPerson** A human being

**JuridicalPerson** A company or organization

**InsurancePlan** A policy template which a sales agent can use to create a custom policy personalized to a specific client's individual needs

**Policy** An insurance policy

**Coverage** A coverage option

**PolicyCoverage** A coverage option specific to a Policy. The coverage offered by the Policy can be standard or special.