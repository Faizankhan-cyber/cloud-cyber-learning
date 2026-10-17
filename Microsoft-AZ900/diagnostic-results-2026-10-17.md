# AZ-900 Diagnostic Results

- **Date:** October 17, 2026
- **Assessment:** 50-question conversational practice diagnostic
- **Score:** **46/50 (92%)**
- **Purpose:** Identify topics to revise before taking an official AZ-900 practice assessment or exam.

> This was a practice diagnostic, not an official Microsoft assessment. The questions were not a standardized exam form, and this score does not establish official exam readiness or predict an official scaled score.

## Result summary

The diagnostic covered cloud concepts, Azure architecture and services, and Azure management and governance. Performance was strong across the topics tested. The main weaknesses were distinctions between similar networking services and the IaaS/PaaS responsibility boundary.

No official domain-level scores were calculated from this diagnostic, so the observations below are qualitative rather than percentages by exam domain.

## Incorrect answers to review

| Question | Selected answer | Correct answer | Key distinction |
|---|---|---|---|
| 37 | Azure Load Balancer | **Azure Traffic Manager** | Traffic Manager provides DNS-based routing across endpoints and can use performance routing and endpoint health monitoring. Azure Load Balancer distributes Layer 4 TCP/UDP traffic. |
| 40 | Platform as a Service (PaaS) | **Infrastructure as a Service (IaaS)** | IaaS gives the customer control over the guest operating system and installed software. With PaaS, the provider manages the underlying OS and platform. |
| 44 | Azure VPN Gateway | **Azure ExpressRoute** | ExpressRoute provides private connectivity through a connectivity provider. VPN Gateway commonly provides an encrypted tunnel over the public internet. |
| 48 | Azure Traffic Manager | **Azure Application Gateway** | Application Gateway supports Layer 7 HTTP/HTTPS routing, including URL-path routing. Traffic Manager routes through DNS. |

## Revision priorities

### 1. Distinguish Azure traffic-routing services

- **Azure Traffic Manager:** DNS-based routing across endpoints, including endpoints in multiple regions.
- **Azure Application Gateway:** Layer 7 HTTP/HTTPS load balancing and URL-path routing.
- **Azure Load Balancer:** Layer 4 TCP/UDP traffic distribution.
- When reviewing scenarios, identify the routing layer, protocol, scope, and whether routing is DNS-based or HTTP-aware.

### 2. Review cloud service models

- **IaaS:** The customer manages the guest OS and installed software.
- **PaaS:** The provider manages the infrastructure and underlying platform; the customer focuses on the application and data.
- **SaaS:** The customer uses a provider-managed application.

For scenario questions, look for explicit control over the OS as a clue for IaaS.

### 3. Compare private connectivity options

- **ExpressRoute:** Private connection through a connectivity provider.
- **VPN Gateway:** VPN connectivity using an encrypted tunnel, commonly over the public internet.

### 4. Retest with new scenarios

Complete a fresh set of scenario-based questions on these distinctions. For each answer, explain why it fits and why the closest distractor does not. Avoid reusing the same questions as evidence that the concept has been mastered.

## Confidence calibration

Questions 37, 44, and 48 were answered with **very high confidence** but were incorrect. Question 40 was answered with somewhat lower confidence and was also incorrect. Confidence alone therefore should not be used to mark these topics as secure.

Before marking a topic as secure, answer new questions correctly and explain the underlying distinction in your own words.

## Strengths observed

The diagnostic answers showed good recognition of several concepts, including hybrid cloud and cloud bursting, consumption-based pricing, Azure Functions, Azure App Service, Azure SQL Database, Azure Key Vault, Availability Zones, Management Groups, Azure Policy effects, resource locks, Azure Activity Log, Azure Advisor, and the Azure Pricing Calculator.

These are observations from the specific questions asked, not a claim that every objective in the official AZ-900 blueprint has been fully assessed.

## Next steps

1. Review the three priority areas above.
2. Use the [official AZ-900 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900) to cross-check objective coverage.
3. Take a fresh practice assessment and record the date, score, scope, and concepts missed.
4. Keep exam readiness marked **not yet assessed** until performance is consistent across the full set of official skills measured.
