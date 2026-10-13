Version: NAFATH-V3
Track: Networking 

## Overview
A mobile application powered by an AI chat assistant can make government services easier for citizens to access. Building this service requires several technical disciplines to work together. Software engineering establishes the structure of the system and manages changes to its API. Artificial intelligence processes users’ questions and helps provide relevant answers. Mobile development creates the interface through which citizens interact with the assistant. Networking enables data exchange between the mobile application, servers, and other services, making reliable communication essential. Cybersecurity reduces risks such as unauthorized access and malicious activity, while data management helps ensure that conversation records are handled appropriately. The success of the service depends on how well these areas are integrated. Networking is especially important because the growing number of connected devices increases the need for IP addresses, making IPv6 an important part of the Internet’s continued growth.
## Software
Software versioning helps developers communicate changes clearly between releases. When an application exposes a public API, a change that breaks compatibility requires a MAJOR version update. New functionality that remains compatible with existing integrations requires a MINOR update, while backward-compatible bug fixes require a PATCH update. Applying these rules consistently helps developers assess the potential impact of a release before updating systems that depend on it.

Resource: Semantic Versioning 2.0.0 - https://semver.org/spec/v2.0.0.html
## AI
Retrieval-Augmented Generation (RAG) connects a language model to a searchable information source. When a user asks a question, the application retrieves relevant content and includes it in the model’s input. This gives the model evidence to use when generating its response and can help reduce unsupported answers. The quality of the result still depends on retrieving useful information and interpreting it correctly, so RAG cannot guarantee complete accuracy.

Resource: Retrieval augmented generation (RAG) and indexes - Microsoft Learn - https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/retrieval-augmented-generation
## Mobile
App Transport Security (ATS) is an Apple platform feature that helps protect the privacy and integrity of app network connections. It requires connections made through the standard URL Loading System to use HTTPS and meet minimum security requirements. If an app attempts to load an unencrypted HTTP resource, ATS can deny the connection by default. Developers can configure exceptions, but these should be used cautiously because they may weaken network security.

Resource: NSAppTransportSecurity - Apple Developer Documentation - https://developer.apple.com/documentation/BundleResources/Information-Property-List/NSAppTransportSecurity


## Networking

IPv4 and IPv6 are versions of the Internet Protocol that provide addresses for devices communicating over networks. IPv4 uses 32-bit addresses and supports about 4.3 billion unique addresses, while IPv6 uses 128-bit addresses and provides a vastly larger address space. As more phones, computers, smart devices, and servers connect to the Internet, IPv6 helps meet the growing need for unique addresses. Both versions can operate alongside each other.

Resource: What is My IP Address? - Cloudflare - https://www.cloudflare.com/learning/dns/glossary/what-is-my-ip-address/
## Cybersecurity

Prompt injection is an attack in which malicious instructions attempt to make an AI model ignore its intended instructions or perform unintended actions. Direct injection comes from a user’s input, whereas indirect injection is hidden in external content, such as webpages or documents. Defences include treating external content as untrusted, filtering suspicious instructions, and limiting the model’s access to tools and sensitive information. Multiple safeguards are needed because no single defence prevents every attack.

Resource: Prompt Injection (Direct / Indirect) - Microsoft Learn - https://learn.microsoft.com/en-us/security/zero-trust/catalog-ai-attack-techniques/prompt-injection
## Data

Anonymization and pseudonymization help reduce the risk of identifying people in datasets, but they have different legal implications. Anonymization makes individuals no longer identifiable through means reasonably likely to be used. Pseudonymization replaces identifying details with alternative values, but a person may still be identified using additional information. Under the GDPR, truly anonymized data is no longer considered personal data, while pseudonymized information that can be linked back to a person remains protected.

Resource: Application of the GDPR - European Commission - https://commission.europa.eu/law/law-topic/data-protection/information-business-and-organisations/application-gdpr_en
## Misconception in My Track
A common misconception is that IPv6 is simply a newer version of IPv4 that works in exactly the same way. Although both protocols are used to address devices and route data across networks, IPv6 introduces a much larger address space and changes in how addresses are represented and networks operate. Another misconception is that IPv6 automatically replaces IPv4 everywhere. In practice, both protocols can coexist, and organisations may need to support both during the transition.

Resource: IPv6 - Google - https://www.google.com/intl/en/ipv6/
## Open Question
How can organisations transition from IPv4 to IPv6 while maintaining reliable communication with devices and services that still depend on IPv4?
