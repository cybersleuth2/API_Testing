├── 00_Index.md
│   └─ Overview, tags, and table of contents

├── 01_Reconnaissance.md
│   ├─ Host & subdomain discovery
│   ├─ Endpoint enumeration
│   ├─ Swagger/OpenAPI parsing
│   └─ Tags: #recon #subdomain #swagger

├── 02_Authentication.md
│   ├─ Token types (JWT, OAuth, API keys)
│   ├─ Token leakage & replay attacks
│   ├─ Weak token generation / guessable IDs
│   └─ Tags: #auth #token #oauth #jwt

├── 03_Authorization.md
│   ├─ Insecure Direct Object Reference (IDOR)
│   ├─ Broken object-level auth (BOLA)
│   ├─ Role-based access bypass
│   └─ Tags: #authz #idor #rbac #abac

├── 04_Endpoint-Testing.md
│   ├─ Hidden/undocumented endpoints
│   ├─ HTTP method fuzzing (GET/POST/etc.)
│   ├─ REST vs GraphQL differences
│   └─ Tags: #endpoint #graphql #rest

├── 05_Input-Validation.md
│   ├─ JSON/XML injection
│   ├─ Mass assignment / parameter pollution
│   ├─ Path traversal in API params
│   └─ Tags: #input #injection #validation

├── 06_Rate-Limiting-and-DOS.md
│   ├─ Brute-force detection
│   ├─ Resource exhaustion (slowloris, recursion)
│   ├─ Abuse of async/massive payloads
│   └─ Tags: #ratelimit #dos #abuse

├── 07_Data-Exposure.md
│   ├─ Excessive data exposure
│   ├─ Leaky verbose errors / debug info
│   ├─ Misconfigured CORS & headers
│   └─ Tags: #data #exposure #cors

├── 08_Logging-and-Monitoring.md
│   ├─ Tampering with logs via crafted inputs
│   ├─ Missing audit trails
│   └─ Tags: #logging #monitoring #audit

├── 09_Security-Misconfigurations.md
│   ├─ HTTP headers & cache control
│   ├─ TLS misconfigurations
│   ├─ Directory browsing or sensitive files
│   └─ Tags: #misconfig #headers #tls

├── 10_Tools.md
│   ├─ Postman, Burp Suite, Insomnia
│   ├─ Amass, ffuf, nuclei, jwt_tool
│   ├─ GraphQL Voyager, GraphQLmap
│   └─ Tags: #tools #burp #postman #graphql

├── 11_Exploitation-Chains.md
│   ├─ Token theft → privilege escalation
│   ├─ Endpoint fuzzing → IDOR → data dump
│   └─ Tags: #chaining #attackpath #api-exploitation

├── 12_Defense-and-Mitigation.md
│   ├─ API gateway & WAF rules
│   ├─ Rate limiting and throttling
│   ├─ Input validation & schema enforcement
│   └─ Tags: #defense #waf #schema #ratelimit

├── 13_References-and-Reading.md
│   ├─ OWASP API Security Top 10
│   ├─ RFCs, whitepapers, case studies
│   └─ Tags: #owasp #rfc #casestudy
