# Razor Pay AI Experiments/UCs

| Use Case               | Description                                                  | Benefit                                 |
|------------------------|--------------------------------------------------------------|-----------------------------------------|
| Automated KYC          | To power fast and accurate KYC                               | Enhanced on-boarding experience         |
| Docs AI                | AI generated integration code, ready for testing and go-live | Improving integration experience        |
| Fraud Suite            | Fraud Shield, RTO protection                                 | Reducing merchant frauds                |
| Dynamic Routing Engine | To route transactions via fastest and most reliable pipe     | Ensuring most efficient routing         |
| AI Recon               | To identify unreconciled transactions                        | Improving reconciliation experience     |
| Tax                    | To simplify payroll and taxation processes                   | Improving payroll experience            |
| RAY                    | Conversational chatbot for merchants                         | Less service volume and more cross sell |
| Traffic Prediction     | Traffic prediction using AI, to pre-warm infra               |                                         |

# DDD & AI for better developer experience
- Consistent [DDD modeling](../../HLD-System-Designs/7b_ArchitecturePatterns/DevPatterns/DomainDrivenDevelopment.md)
- Consistent Arch Patterns defined - for all services a consistent arch patterns with [protobuffs](../../HLD-System-Designs/8_APIStandards/SerializationFrameworks/ProtocolBuffers.md), standard api definitions & event driven architecture was defined.
- Domain specific language model for code gen 

# Security in AI Modeling
- No PI shared with AI engines
- Self hosted [LLM/SLM models](https://www.splunk.com/en_us/blog/learn/language-models-slm-vs-llm.html)