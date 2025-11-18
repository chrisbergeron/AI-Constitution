# AI Constitution Template — Annotated Version

## 0. Purpose

**Why it’s here:**
Every constitution needs a “preamble.” It establishes why the document exists and what problem it solves.

**Inspired by:**

- NIST AI Risk Framework’s “Purpose Statement”
- Constitutional AI’s “High-level principles”
- Human governance documents (preambles)

**Function in practice:**
Ensures the Constitution defines binding operational behavior across the system.

---

## 1. Core Values

**Why:**
Values act as north stars. When rules conflict or context is ambiguous, values determine fallback behavior.

**Mapped to:**

- Anthropic’s HHH (Helpful, Honest, Harmless)
- OpenAI/DeepMind identity guidelines
- Ethics frameworks (fairness, autonomy)

**Use:**
Values help models generalize and interpret rather than rely on rigid rules.

---

## 2. Behavioral Directives

**Why:**
Explicit rules replace “common sense,” because LLMs don’t infer intent perfectly.

**Mapped to:**

- System prompts / meta-prompts
- RLHF patterns (“ask for clarification”)
- Anti-hallucination best practices

**Use:**
These directives directly control how the model reasons and responds.

---

## 3. Red Lines / Prohibitions

**Why:**
Disallowed behaviors must be explicit. “Do not do X” is easier for LLMs to enforce than ambiguous safety concepts.

**Mapped to:**

- Platform safety categories
- OpenAI/Anthropic disallowed content
- EU AI Act high-risk bans

**Use:**
Defines what the system cannot do under any circumstances.

---

## 4. Safety & Risk Policies

**Why:**
High-risk queries require nuance. This section tells the model how to respond safely instead of strictly refusing.

**Mapped to:**

- NIST risk mitigation guidelines
- Safety-tuned refusal styles
- Red-teaming patterns

**Use:**
Encourages providing safer alternatives rather than shutting down the user.

---

## 5. Identity & Persona Rules

**Why:**
Users request personas often; this keeps them safe and bounded.

**Mapped to:**

- OpenAI “role prompt” constraints
- Anthropic persona safety guidance
- Multi-identity systems (matches your workflow)

**Use:**
Persona shifts cannot bypass red lines or constitutional rules.

---

## 6. Interaction Style

**Why:**
Models need explicit tone and style guidance to be consistent.

**Mapped to:**

- System prompt style rules
- UX consistency frameworks
- Conversational LLM best practices

**Use:**
Defines the communication texture of the AI.

---

## 7. Error Handling

**Why:**
Models hallucinate when uncertain; this section provides safer defaults.

**Mapped to:**

- Uncertainty quantification
- Defensive prompting
- Clarification-seeking RLHF rules

**Use:**
Improves reliability and reduces false confidence.

---

## 8. Autonomy Constraints (for agent systems)

**Why:**
As soon as the AI can perform real-world actions, guardrails are needed.

**Mapped to:**

- AutoGPT / ReAct agents
- LangChain agent safety constraints
- OpenAI agent safety layers

**Use:**
Prevents runaway behavior, uncontrolled tasks, or self-directed changes.

---

## 9. Governance & Versioning

**Why:**
Policies evolve; version control avoids drift.

**Mapped to:**

- Model cards
- ISO/IEC 42001 AI governance lifecycle
- Corporate policy versioning

**Use:**
Ensures updates are traceable and intentional.

---

## 10. Extension Modules

**Why:**
Allows constitutional expansion as capabilities grow.

**Mapped to:**

- Modular safety stacks
- Policy layering used by major labs
- Enterprise domain-specific extensions

**Use:**
Enables future additions like finance guardrails, medical rules, or agent autonomy scaling.