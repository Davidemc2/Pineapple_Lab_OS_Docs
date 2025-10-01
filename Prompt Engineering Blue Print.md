# 🔧 Modular Prompt Engineering Blueprint for Custom AI Agents

## 🧠 Core Philosophy

**LLMs ≠ Thinkers.** They simulate logic, language, and reasoning. The goal of prompt engineering is to design interfaces that enable reliable, domain-specific utility — with humans providing ambiguity resolution and high-context judgement.

**Truth Optimization Principle**: Throughout this framework, we integrate **honesty and transparency** as core requirements. AI should acknowledge uncertainty, state assumptions, and disclose limitations.

---

## 🔗 Purpose of This Guide

This guide is part of an evolving set of findings from Pineapple Labs. I'm David Edwards, and this blueprint represents my ongoing exploration into prompt engineering as it relates to the broader field of AI engineering.

The idea behind publishing this is to open-source the design patterns, techniques, and structures I've found useful when working with LLMs like GPT, Claude, DeepSeek, and Gemini. Prompting isn't just about formatting text — it's about shaping behavior, logic, and reliability inside intelligent systems.

**This Blueprint is the master methodology** that integrates all Pineapple Lab techniques:
- **Truth Optimization Engine (TOE)** - Woven throughout all 7 components
- **XML Tag Structuring** - Referenced for advanced organization
- **Chain-of-Thought Reasoning** - Integrated into Logic Block
- **Context Engineering** - Applied for production AI agents

The goal is to make these findings public, collaborative, and useful — not just for Pineapple Labs, but for builders, researchers, and technologists everywhere who care about designing more trustworthy, performant agents.

---

## 📚 Complete Learning Path

### **New to Prompt Engineering?**
Start with → [Starting Guide for Newbies](Starting_Guide_for_Newbies_Prompt_Engineering.md)

### **Currently Reading:**
→ **Prompt Engineering Blueprint** (You are here - The master framework)

### **Want Advanced Techniques?**
- [XML Tag Structuring Guide](XML_Tag_Structuring_Guide.md) - Deep dive into structural organization
- [Advanced Logic Building Guide](Advanced_Logic_Building_Guide.md) - Sophisticated reasoning frameworks

### **Building Production Systems?**
→ [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)

---

## 🧱 1. SYSTEM DECLARATION (Agent Role Definition)

```text
You are a [role] with expertise in [domain]. Be [tone]. Avoid assumptions. Ask for clarification if needed.
```

**Tips:**

* Be explicit: "You are a certified tax advisor..."
* Reinforce desired behavior: "Be concise and regulatory-compliant."

**TOE Integration:**
Add honesty requirements to the role definition:
```text
You are a [role]. If you're uncertain about any aspect, mark it with [UNCERTAIN]. State any assumptions you're making with [ASSUMPTION].
```

**Advanced Technique:**
Use XML tags for clear role definition (see [XML Tag Structuring Guide](XML_Tag_Structuring_Guide.md)):
```xml
<role>You are a senior financial analyst</role>
<expertise>10+ years in SaaS financial modeling</expertise>
<communication_style>Professional, data-driven, honest about limitations</communication_style>
```

---

## 📥 2. INSTRUCTION BLOCK

```text
Your task is to [perform task] using the input provided below.
```

**Clarify Scope:**

* “...without rewriting the original text”
* “...within 200 words”

---

## 🔁 3. LOGIC BLOCK (Step-by-Step or Conditional Reasoning)

```text
Step 1: [action]
Step 2: [action]
If [condition], then [output], else [alternative]
```

**Patterns:**

* Chain-of-thought style prompts
* Decision trees (e.g., refund logic)

**TOE Integration:**
Add reasoning transparency:
```text
Let's think step by step:
Step 1: [action with confidence marker]
Step 2: [action - note any assumptions]
IF [condition]: THEN [output] [CONFIDENT]
ELSE: [alternative] [state why you're choosing this path]
```

**Advanced Technique:**
For sophisticated reasoning, see [Advanced Logic Building Guide](Advanced_Logic_Building_Guide.md):
- Zero-shot and few-shot chain-of-thought
- Multi-condition logic trees
- Recursive reasoning patterns
- Self-correction mechanisms

**Example with XML and CoT:**
```xml
<reasoning_framework>
<chain_of_thought>
Let me work through this step-by-step:
1. [First step with reasoning]
2. [Second step building on first]
3. [Third step with validation]
</chain_of_thought>

<conditional_logic>
IF [condition]:
  THEN [action] [CONFIDENT]
ELSE:
  [alternative] [ASSUMPTION: stating why]
</conditional_logic>
</reasoning_framework>
```

---

## 🧩 4. INPUT/OUTPUT SEPARATION

```text
## Instructions:
[clear task]

## Input Data:
[data/doc/user query]

## Expected Output Format:
[bullets / JSON / table / narrative]
```

**Prevents:** blending task logic and input context

**Advanced Technique with XML:**
For complex prompts, XML tags provide superior organization (see [XML Tag Structuring Guide](XML_Tag_Structuring_Guide.md)):
```xml
<instructions>
[Clear, specific task description]
</instructions>

<input_data>
[The actual data to process]
</input_data>

<output_format>
[Exact structure you want]
Include [CONFIDENT]/[UNCERTAIN] markers where appropriate
</output_format>

<constraints>
- Word limit: [X]
- Include confidence levels
- State assumptions explicitly
</constraints>
```

**TOE Benefit:** XML structure makes it natural to separate confident knowledge from uncertain areas.

---

## 🎯 5. OUTPUT FORMATTING & CONSTRAINTS

```text
Respond in [JSON/table/bullets]. Limit to [X] words. Include [required fields].
```

**Example:**

```text
Return a JSON: { "summary": string, "score": 0-10, "warning": boolean }
```

---

## 🧪 6. FEW-SHOT EXAMPLES

```text
Input: "yo help me"
Output: "Hi, could you please clarify what you need help with?"
```

**Use cases:**

* Style learning
* Format anchoring
* Tone control

---

## 🚨 7. EVALUATION & ESCAPE HATCHES

### 🔍 Failure Modes

* Ambiguous input → vague output
* Over-specification → rigid, non-generalizable output
* Lack of output constraints → verbosity or hallucinations
* Conflict between system prompt and instruction → breakdown in task logic
* **Overconfidence** → AI claims certainty without basis (TOE addresses this)

### ✅ Escape Hatches (TOE-Enhanced)

**Basic Escape Hatch:**
```text
If you are uncertain, or cannot complete the task with the input provided, say:
"I need clarification to proceed: [insert specific clarification request]"
```

**TOE-Enhanced Escape Hatch:**
```text
For any response:
- Mark confident statements with [CONFIDENT]
- Mark uncertain statements with [UNCERTAIN]
- State assumptions with [ASSUMPTION: reasoning]
- Note limitations with [LIMITATION: description]

If you cannot complete the task, explain:
1. What you CAN do confidently
2. What you're UNCERTAIN about
3. What specific information would help
```

**Why:** This enables graceful degradation, safe fail states, AND honest communication about AI capabilities. Essential for production AI.

### 📊 Evaluation Methods (TOE-Integrated)

Use this checklist to test prompt reliability:

* ✅ 3x consistency on regenerate
* ✅ Valid JSON or Markdown formatting
* ✅ Passes tone/style alignment checks
* ✅ Logical flow mirrors intended reasoning chain
* ✅ No hallucinations in factual queries
* ✅ Latency and token cost within expected bounds
* ✅ **Honest uncertainty acknowledgment** (TOE)
* ✅ **Explicit assumption listing** (TOE)
* ✅ **Appropriate confidence markers** (TOE)
* ✅ **Limitation disclosure** (TOE)

**For Production Systems:**
See [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md) for comprehensive verification systems including:
- Benchmarking Loop System
- Live Documentation Index
- Multi-model verification

---

## 🔢 VERSIONING PHILOSOPHY

Prompts evolve like software.

```json
{
  "prompt_id": "legal_summary_v1.2.0",
  "changes": "Added tone constraint + updated examples",
  "owner": "pineapple-labs"
}
```

**Best Practices:**

* `MAJOR.MINOR.PATCH` structure (v2.1.3)
* Keep changelogs per prompt
* Store prompt history (e.g., Chroma, GitHub, Pinecone metadata)

---

## 🧠 Model-Specific Prompting Notes

### 🤖 GPT-4

* ✅ Best for multi-role simulation, creative tasks, code
* 🔧 Use structured prompts with logic + format constraints
* 🧠 Supports embedded feedback loops

### 🧠 Claude 3/4

* ✅ Excels in structured legal, policy-safe tasks
* 🔧 Use `<tag>` style XML formatting for consistent behavior
* ⚠️ Avoid indirect instructions — prefers strict format

### 🔍 DeepSeek

* ✅ High performance in technical/code domains
* 🔧 Prompt like GPT, but test output determinism
* ⚠️ Needs constraint tuning to avoid overgeneration

---

## 🛠 Reusable Prompt Snippets (Prompt Blocks)

| Block Type       | Snippet                                               |
| ---------------- | ----------------------------------------------------- |
| System Context   | "You are an expert \[role]. Be precise. Never guess." |
| Task Instruction | "Your task is to \[action] using the info below."     |
| Formatting       | "Return JSON: {question, answer, confidence}"         |
| Clarification    | "If you are uncertain, ask for more information."     |
| Logic Flow       | "Step 1... Step 2... Step 3..."                       |

---

## 🧬 Real-World Prompt Blueprints

### 🏛 Legal Compliance GPT

```text
You are a compliance advisor for financial regulation. Summarize key infractions and cite the relevant law.
Input: [legal document]
Output: JSON: { violations: [], citations: [], summary }
```

### 📞 Support Chat Optimizer

```text
You are a tier-2 support agent. Rephrase the issue into a format for engineering triage.
Input: [customer message]
Output: JSON: { issue_summary, urgency_level, component_tag }
```

### 📊 Analyst Assistant GPT

```text
You are a data analyst at a SaaS company. Identify three insights based on growth metrics.
Input: [monthly performance report]
Output: Markdown: - Insight 1: ...
```

---

## 🔁 Prompt Tuning Lifecycle

1. 🏗 Write →
2. 🔬 Evaluate →
3. 🔁 Regenerate →
4. 🧪 Test for Consistency →
5. 📊 Deploy to Agent Memory →
6. 🧭 Auto-Tune via Reflection (e.g., ReAct/AutoGen loops)

---

## 📘 Example Blueprint

```text
## SYSTEM
You are a climate policy analyst.
Be evidence-based and non-partisan.

## INSTRUCTION
Summarize the document below and extract 3 policy impacts.

## LOGIC
Step 1: Read and extract summary.
Step 2: Identify direct impacts.
Step 3: Output formatted list.

## INPUT
[Insert document text here]

## FORMAT
Return JSON with keys: summary, impacts[], confidence_score

## EVALUATION CLAUSE
If source is unclear, state "Document lacks clarity on policy outcome."
```

---

## 🔗 Sources & References

* [Anthropic Claude Prompting Best Practices](https://docs.anthropic.com/claude/prompt-engineering)
* [OpenAI Function Calling & Prompting Docs](https://platform.openai.com/docs)
* [Deepgram Prompt Engineering Masterclass](https://deepgram.com/learn/prompt-engineering-masterclass)
* [Prompt Engineering: A Blueprint for AI Excellence](https://www.crossml.com/wp-content/uploads/2024/02/Prompt-Engineering-A-Blueprint-for-AI-Excellence.pdf)
* *Designing Machine Learning Systems* by Chip Huyen
* *Deep Learning* by Ian Goodfellow et al.
* *Prompt Engineering Guide* ([https://github.com/dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide))
* Pineapple Labs Internal Research – OS Brick runtime & behavior design

