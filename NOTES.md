## References and sources

### 1. Academic & Research Architectures (Layers 3–11)
    • Lu, Q., et al. (CSIRO/Data61). "A Reference Architecture for Designing Foundation Model based Systems" (arXiv:2304.11090).
        ◦ Contribution: Provided the foundational 3-layer pattern (System, Operation, Supply Chain) and the concept of "Responsible AI by Design."
        ◦ Limitation: Only covers ~7 layers; lacks Physical, FinOps, and Meta-Orchestration.
    • Lu, Q., et al. "Towards Responsible Generative AI: A Reference Architecture for Designing Foundation Model based Agents" (arXiv:2311.13148).
        ◦ Contribution: Extended the architecture to include Agents and Tool Use, informing the Orchestration and HITL layers.
### 2. Industry Standards & Governance (Layers 2, 12, 14)
    • Cloud Security Alliance (CSA). "AI Controls Matrix (AICM) v1.1" (July 2026).
        ◦ Contribution: The definitive source for the Security Guardrails, Formal Governance, and Model Security layers. Defines the 247 control objectives across 18 domains that map directly to our architecture.
    • NIST / UC Berkeley CLTC. "Agentic AI Risk-Management Standards Profile" (Draft 2026).
        ◦ Contribution: Informed the HITL, Kill Switch, and Scope Limitation logic within the Safety and Orchestration layers.
    • ISO/IEC 42001. "Artificial Intelligence Management System."
        ◦ Contribution: Provided the structure for the Model Registry and Feedback Loop layers (continuous improvement).
### 3. Emerging Protocols & Future Layers (Layer 18)
    • Linux Foundation / Google. "Agent2Agent Protocol (A2A) Specification v1.0" (2026).
        ◦ Contribution: The technical basis for Layer 18 (Meta-Orchestration). Defines how agents discover, delegate, and transact with external agents.
    • Model Context Protocol (MCP). "MCP Specification" (Anthropic/Community).
        ◦ Contribution: The standard for Layer 5 (Data Preparation) and tool connectivity, enabling the decoupled architecture.
### 4. Operational & Physical Reality (Layers 1, 15, 16)
    • Gartner. "Hype Cycle for ERP & Hybrid AI Infrastructure" (July 2026).
        ◦ Contribution: Validated the shift to Compound AI Systems and the rise of Neuro-Symbolic engines (Layer 10). Reported the 1,445% surge in multi-agent inquiries.
    • Infrastructure Vendors (NVIDIA, Vertiv, Eaton). "Blackwell Era Power & Cooling Guidelines" (2025–2026).
        ◦ Contribution: Established Layer 1 (Energy & Thermal) as a critical architectural constraint, noting that power density now limits compute density.
    • FinOps Foundation. "AI Cost Optimization Patterns" (2026).
        ◦ Contribution: Defined Layer 15 (FinOps Engine), specifically the need for dynamic model routing and token budgeting.
### 5. Specialized Capabilities (Layer 10, 7)
    • Uniphore / IBM. "Neuro-Symbolic AI in Production" (2026 Case Studies).
        ◦ Contribution: Validated Layer 10 (Neuro-Symbolic Engine) as a production-ready component for high-stakes reasoning, distinct from pure LLMs.
    • Vector & Graph DB Vendors (Neo4j, Pinecone). "Hybrid Memory Architectures" (2026).
        ◦ Contribution: Informed Layer 7 (Long-Term Memory), specifically the convergence of Vector (semantic) and Graph (relational) stores for persistent state.
