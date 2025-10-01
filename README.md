# 🧠 Pineapple Lab OS Docs

Welcome to **Pineapple Lab OS Docs** — the definitive open-source resource for advanced prompt engineering, context engineering, and AI agent design.

This repository shares Pineapple Labs' research, methodologies, and practical frameworks for building reliable, production-ready AI systems. From beginner-friendly introductions to advanced reasoning frameworks, we provide comprehensive, research-backed guidance for engineering AI behavior.

> 🧪 **I'm David Edwards.** This repo is where I collect findings, test ideas, and publish what works — and what doesn't — in building composable, safe, and production-minded AI agents.

You're welcome to fork, clone, copy, remix, and apply this material to your engineering teams, research work, or agent runtime stacks.

**Contributions, feedback, and wild ideas are all welcome — this is a lab, not a product.**

---

## 🎯 Who This Is For

### **Complete Beginners**
Never done prompt engineering before? Start with our [Starting Guide for Newbies](Starting_Guide_for_Newbies_Prompt_Engineering.md) to learn the fundamentals in 30 minutes.

### **Intermediate Practitioners**
Know the basics? Jump to the [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md) for the complete 7-component framework with Truth Optimization integrated throughout.

### **Advanced Engineers**
Building production AI systems? Explore our specialized guides on [XML Tag Structuring](XML_Tag_Structuring_Guide.md), [Advanced Logic Building](Advanced_Logic_Building_Guide.md), and [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md).

---

## 🌍 Purpose

This repo is part of the **Pineapple Lab OS** — a growing open-source hub for publishing Pineapple Labs' research, tooling, and findings around AI systems.

At its core, Pineapple Lab OS is about **building a public R&D hub for the AI community**. The documents and blueprints here are based on real experiments, systems design efforts, and exploratory research. We believe in transparent collaboration and open sourcing not just code, but thinking.

### This Project Exists To:

- 📚 Publish **tested, reusable prompting patterns** for GPT, Claude, DeepSeek, and Gemini
- 🏗️ Develop a **modular design system** for sophisticated AI agent behavior
- 🔬 Share **research-backed methodologies** for improving AI reliability and honesty
- 🤝 Invite **open-source contributions** from fellow builders and researchers
- 🚀 Advance the **state of the art** in prompt engineering and context engineering

This is not a static spec — it's an **evolving playbook** for how we build LLM systems, and an open call for collaboration.

---

## 📦 What's Inside

### **📖 Core Documentation**

| Document | Description | For Who? |
|----------|-------------|----------|
| **[Starting Guide for Newbies](Starting_Guide_for_Newbies_Prompt_Engineering.md)** | 30-minute introduction to prompt engineering fundamentals | Complete beginners |
| **[Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md)** | Complete 7-component framework with TOE integration | Intermediate+ practitioners |
| **[TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)** | Truth Optimization Engine for production AI systems | Advanced engineers |

### **🎓 Advanced Technique Guides**

| Guide | Description | Referenced From |
|-------|-------------|-----------------|
| **[XML Tag Structuring Guide](XML_Tag_Structuring_Guide.md)** | Advanced prompt organization using XML tags | Blueprint Component 4 |
| **[Advanced Logic Building Guide](Advanced_Logic_Building_Guide.md)** | Chain-of-thought, conditional logic, prompt chaining | Blueprint Component 3 |

### **🤝 Community**

| Resource | Description |
|----------|-------------|
| **[Contribution Guide](Contribution_Guide.md)** | How to contribute improvements, research, and examples |
| **[LICENSE](LICENSE)** | Apache 2.0 - Use freely, attribute appropriately |

---

## 🚀 Quickstart

### **For Complete Beginners:**
1. Start with → [Starting Guide for Newbies](Starting_Guide_for_Newbies_Prompt_Engineering.md)
2. Build your first structured prompt
3. Move to → [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md) when ready

### **For Intermediate Users:**
1. Read → [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md)
2. Master the 7-component framework with TOE integration
3. Explore specialized guides → [XML Tags](XML_Tag_Structuring_Guide.md) or [Advanced Logic](Advanced_Logic_Building_Guide.md)

### **For Advanced Practitioners:**
1. Review → [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)
2. Apply specialized techniques from [XML](XML_Tag_Structuring_Guide.md) and [Logic](Advanced_Logic_Building_Guide.md) guides
3. Test in production and [contribute improvements](Contribution_Guide.md)

---

## 🧠 Design Principles

- **🎯 Clarity First** — Every prompt block is modular and intentional
- **🏗️ Structure > Style** — We treat prompts like functions, not text
- **🔒 Security-Aware** — Special attention to injection risks and ambiguity
- **🌐 Multi-Model** — Designed for Claude, GPT, DeepSeek, Gemini from the start
- **🔬 Open Research** — Pineapple Labs is an open-source-first R&D space
- **📊 Evidence-Based** — Methodologies backed by peer-reviewed research and real-world testing

---

## 🔬 Research Methodologies

### **Core Framework: Seven-Component Blueprint**

Our [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md) provides a complete framework:

1. **System Declaration** (Agent Role Definition) + XML `<role>` tags
2. **Instruction Block** with clear task separation + XML `<instructions>` tags
3. **Logic Block** enhanced with CoT and conditional logic + XML `<reasoning>` tags
4. **Input/Output Separation** using XML structural tags
5. **Output Formatting & Constraints** with XML `<format>` and `<constraints>` tags
6. **Few-Shot Examples** organized with XML `<examples>` tags
7. **Evaluation & Escape Hatches** with validation frameworks

**Each component integrates Truth Optimization principles throughout.**

---

### **Truth Optimization Engine (TOE)**

A breakthrough methodology for improving AI honesty and reliability:

- **Explicit Uncertainty Acknowledgment**: `[CONFIDENT]`, `[LIKELY]`, `[UNCERTAIN]` markers
- **Assumption Transparency**: Making AI assumptions explicit
- **Limitation Disclosure**: Honest about what AI can't do
- **Honest Reporting Framework**: Structured honesty in responses
- **Validation Requirements**: Built-in self-checking mechanisms

**Learn more** → [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)

---

### **Advanced Techniques**

**XML Tag Structuring** ([Guide](XML_Tag_Structuring_Guide.md))
- Semantic organization of prompt components
- Particularly powerful with Claude models
- Improves parseability and accuracy
- Enables complex multi-component prompts

**Chain-of-Thought Reasoning** ([Guide](Advanced_Logic_Building_Guide.md))
- Explicit step-by-step problem solving
- Zero-shot and few-shot CoT patterns
- Validation and self-correction mechanisms
- Research-backed (Wei et al. 2022, Kojima et al. 2022)

**Advanced Conditional Logic** ([Guide](Advanced_Logic_Building_Guide.md))
- Complex decision trees and branching logic
- Multi-condition evaluation frameworks
- Error detection and recovery patterns
- Production-ready reliability

**Prompt Chaining** ([Guide](Advanced_Logic_Building_Guide.md))
- Sequential task decomposition
- Parallel processing chains
- Complex workflow management
- Synthesis of multiple analyses

---

## 🆕 Latest Additions

### **Starting Guide for Newbies** ✨ NEW
A comprehensive 30-minute introduction for complete beginners covering:
- What prompt engineering actually is
- The difference between chatting and engineering
- Your first structured prompt (hands-on)
- Introduction to Truth Optimization
- Clear learning path from beginner to advanced

### **XML Tag Structuring Guide** ✨ NEW
Advanced methodology for organizing complex prompts:
- Core tag categories and best practices
- Chain-of-thought integration with XML
- Multi-component prompt patterns
- Conditional logic with XML structure
- Real-world implementation examples

### **Advanced Logic Building Guide** ✨ NEW
Sophisticated reasoning frameworks:
- Zero-shot and few-shot chain-of-thought
- Multi-condition logic trees
- Recursive reasoning patterns
- Prompt chaining (sequential and parallel)
- Self-correction and validation mechanisms
- Error detection and recovery

---

## 🧱 In Progress

- `prompt_registry.json` — Structured schema for prompts-as-code
- `tests/` — Prompt regression + consistency tests
- `agent_templates/` — Blueprints for repeatable, role-specific agents
- `whitepaper.md` — Outlining Pineapple Labs' approach to modular agents
- **Integration examples** — Demonstrating XML + CoT + TOE together
- **Performance benchmarks** — Empirical validation of methodologies
- **Industry comparisons** — How we compare to Google, OpenAI, Anthropic approaches

---

## 🧬 A Note from Me

This project is the backbone of how I build AI agents for products like OS Brick. Whether you're exploring prompt chaining, ReAct logic, memory containerization, or persona design — this repo is yours to explore, extend, and question.

The recent additions represent significant advances in the field:
- **Starting Guide** makes prompt engineering accessible to everyone
- **XML Tag Structuring** provides industrial-strength organization
- **Advanced Logic Building** enables sophisticated reasoning frameworks
- **Truth Optimization Engine** ensures AI honesty and reliability

These aren't just theoretical frameworks — they're battle-tested methodologies used in production AI systems.

Thanks for being curious,

**– David Edwards / Pineapple Labs**

---

## 📚 References

### **Official Documentation**
- [OpenAI Prompt Engineering Docs](https://platform.openai.com/docs/guides/prompt-engineering)
- [Anthropic Claude Prompting](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [Anthropic XML Tag Documentation](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/use-xml-tags)
- [Google Gemini Prompt Design](https://ai.google.dev/gemini-api/docs/prompting-strategies)
- [Microsoft Azure OpenAI Prompt Engineering](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/advanced-prompt-engineering)

### **Research Papers**
- Wei, J., et al. (2022). *Chain-of-thought prompting elicits reasoning in large language models*. [arXiv:2201.11903](https://arxiv.org/abs/2201.11903)
- Kojima, T., et al. (2022). *Large language models are zero-shot reasoners*. [arXiv:2205.11916](https://arxiv.org/abs/2205.11916)
- Zhang, Z., et al. (2022). *Automatic chain of thought prompting in large language models*. [arXiv:2210.03493](https://arxiv.org/abs/2210.03493)

### **Community Resources**
- [Prompt Engineering Guide – DAIR AI](https://www.promptingguide.ai/)
- [Chip Huyen – Designing ML Systems](https://huyenchip.com/ml-interviews-book/)

---

## 📬 Contributions

Contributions are **strongly encouraged** — especially from practitioners working in:

### **Priority Areas**
- 🧪 **Empirical validation** of methodologies with benchmarks
- 🏗️ **Integration examples** combining XML + CoT + TOE
- 🔒 **Prompt security** and safety research
- 🤖 **Multi-agent orchestration** patterns
- 🧠 **Context engineering** for complex domains
- 📊 **Performance optimizations** and efficiency improvements
- 🎯 **Industry-specific applications** and case studies

### **How to Contribute**

1. **Fork the repository**
2. **Create a feature branch** for your contribution
3. **Follow the existing documentation style** and structure
4. **Include practical examples** and real-world use cases
5. **Provide citations** for any research or methodologies referenced
6. **Test your prompts** across multiple models when possible (GPT, Claude, Gemini)
7. **Submit a pull request** with a clear description of your contribution

See our [Contribution Guide](Contribution_Guide.md) for detailed guidelines.

---

## 🚀 Coming Soon: Interactive Features

### **Prompt Engineering Benchmarking System** 🎯 (In Development)

We're building an interactive tool that will allow you to:

**📊 Benchmark Your Prompts**
- Paste your current prompt into our benchmarking system
- Analyze against Pineapple Lab best practices and guidelines
- Get scored on: Structure, Clarity, TOE Integration, Logic Framework, Security

**✨ Get Enhanced Versions**
- Receive AI-generated improvements based on our methodologies
- See side-by-side comparison: Your Prompt vs. Enhanced Prompt
- Understand exactly what was improved and why

**💾 Export for Your Tools**
- Download enhanced prompts as formatted Markdown files
- Ready to use in Cursor, Claude Code, GitHub Copilot, or any IDE
- Includes embedded comments explaining the improvements

**🔄 Iterative Improvement**
- Re-benchmark improved prompts to track progress
- Learn through practical application
- Build your prompt engineering skills over time

**📈 Community Leaderboard**
- See how your prompts compare (anonymously)
- Learn from top-performing prompt patterns
- Contribute your best prompts to help others

**🎓 Educational Mode**
- Step-by-step explanations of improvements
- Links to relevant documentation sections
- Suggested learning path based on your prompt analysis

### **How to Get Involved**

**Want to help build this?** We're looking for contributors with expertise in:
- Frontend development (React, Next.js)
- LLM integration and API design
- Prompt evaluation and scoring algorithms
- UX design for developer tools
- Testing and quality assurance

**Interested?** Open an issue with the tag `[Benchmarking System]` to discuss implementation ideas or volunteer to contribute.

### **Stay Updated**

⭐ Star this repository to get notified when the benchmarking system launches!

**Expected Launch**: Q2 2025

---

## 🎯 Learning Paths

### **Path 1: Beginner to Practitioner (Estimated: 2-4 weeks)**
1. Week 1: [Starting Guide for Newbies](Starting_Guide_for_Newbies_Prompt_Engineering.md)
2. Week 2-3: [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md)
3. Week 4: Practice with real projects, explore [XML Tags](XML_Tag_Structuring_Guide.md)

### **Path 2: Intermediate to Advanced (Estimated: 3-6 weeks)**
1. Review [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md)
2. Deep dive: [XML Tag Structuring Guide](XML_Tag_Structuring_Guide.md)
3. Deep dive: [Advanced Logic Building Guide](Advanced_Logic_Building_Guide.md)
4. Apply to production: [TOE Context Engineering](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)

### **Path 3: Production AI Systems (Ongoing)**
1. Master all core documents
2. Implement in production systems
3. Benchmark and validate
4. Contribute improvements back to the community

---

## 🏆 What Makes Pineapple Lab Different

### **Research-Backed**
Every methodology is supported by peer-reviewed research or extensive real-world testing. We cite sources and validate claims.

### **Comprehensive Coverage**
From complete newbie to advanced production systems — we cover the full spectrum with appropriate depth at each level.

### **Practical Focus**
Real-world examples, production-tested patterns, and actionable guidance. No theoretical fluff.

### **Integration-First**
All methodologies work together seamlessly. XML tags + Chain-of-thought + Truth Optimization = Powerful, reliable AI systems.

### **Open & Collaborative**
Built by the community, for the community. Your contributions make this better for everyone.

### **Multi-Model**
Techniques tested across GPT (OpenAI), Claude (Anthropic), Gemini (Google), and DeepSeek. Model-agnostic where possible.

---

## 📊 Repository Structure

```
Pineapple_Lab_OS_Docs/
│
├── README.md                                          # You are here
│
├── 📚 Core Learning Path
│   ├── Starting_Guide_for_Newbies_Prompt_Engineering.md    # Start here (beginners)
│   ├── Prompt_Engineering_Blueprint.md                      # Master framework
│   └── Pineapple_Lab_TOE_Context_Engineering_for_Agents.md # Production systems
│
├── 🎓 Advanced Technique Guides
│   ├── XML_Tag_Structuring_Guide.md                   # Advanced organization
│   └── Advanced_Logic_Building_Guide.md               # Sophisticated reasoning
│
└── 🤝 Community
    ├── Contribution_Guide.md                          # How to contribute
    └── LICENSE                                        # Apache 2.0
```

---

## 💡 Quick Wins

**Want immediate improvements?** Try these:

### **Quick Win #1: Add a Role**
```
Before: "Write marketing copy"
After: "You are an experienced email marketing specialist. Write marketing copy..."
```

### **Quick Win #2: Request Honesty**
```
Add to any prompt: "Use [CONFIDENT] for things you're sure about and [UNCERTAIN] for things you're not."
```

### **Quick Win #3: Structure with XML**
```xml
<instructions>
What you want done
</instructions>

<data>
The information to process
</data>

<format>
How you want the response
</format>
```

### **Quick Win #4: Add Chain-of-Thought**
```
Add to any complex problem: "Let's think step by step:"
```

### **Quick Win #5: Specify Format**
```
Before: "Analyze this"
After: "Analyze this and format as: Finding → Evidence → Recommendation"
```

---

## 🚀 Get Started Now

### **New to Prompt Engineering?**
→ [Start with the Newbies Guide](Starting_Guide_for_Newbies_Prompt_Engineering.md)

### **Ready to Learn the Framework?**
→ [Read the Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md)

### **Building Production AI?**
→ [Explore TOE Context Engineering](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)

### **Want to Contribute?**
→ [Read the Contribution Guide](Contribution_Guide.md)

---

## 📄 License

This project is licensed under the **Apache 2.0 License** - see the [LICENSE](LICENSE) file for details.

**TL;DR**: Use it freely. Modify it. Build on it. Just give attribution and don't sue us.

---

## 📬 Connect & Support

**Questions?** Open an issue on GitHub
**Improvements?** Submit a pull request  
**Collaboration?** Reach out through GitHub discussions

---

## 🌟 About Pineapple Lab

📚 **Pineapple Lab – Open Research & Publications**

At Pineapple Lab, we believe in building openly and collaboratively. Our research and technical blueprints are made freely available to the community to learn from, use, and improve upon. These resources are published to share our insights and experiments in AI, automation, and deep tech, advancing the field through transparent collaboration and evidence-based methodologies.

**We're not building a product. We're building a movement toward more reliable, honest, and sophisticated AI systems.**

Join us.

---

**Last Updated**: January 2025  
**Version**: 2.0 (Major upgrade with beginner guide, XML structuring, and advanced logic)  
**Repository**: [github.com/pineapple-lab/docs](https://github.com/pineapple-lab/docs)

---

*Let's build smarter, more reliable AI systems together.* 🚀
