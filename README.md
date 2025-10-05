# 🧠 Pineapple Lab OS Docs

Welcome to **Pineapple Lab OS Docs** — a practitioner's guide to prompt engineering, compiling and organizing techniques from Anthropic, Google, OpenAI, and academic research.

This repository shares how I've learned, organized, tested, and applied prompt engineering best practices while building AI products at Pineapple Lab. From beginner-friendly introductions to advanced reasoning frameworks, this is a comprehensive learning resource built on the shoulders of giants.

> 🧪 **I'm David Edwards.** I'm 21, building AI products in South Africa, and I love to learn. This repo is where I organize what I learn from brilliant researchers and engineers, test it in real projects, and share it so others don't have to spend months reading scattered documentation like I did.

You're welcome to fork, clone, copy, remix, and apply this material to your work.

**Contributions, feedback, and honest corrections are all welcome — I'm learning in public.**

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

This repo is where I organize and share what I'm learning about prompt engineering as I build AI products.

At its core, this is about **learning in public and helping others**. The documents here are based on studying official documentation from AI labs (Anthropic, Google, OpenAI), reading academic papers (Wei et al., Kojima et al., and others), and testing everything while building real products like RITA and OS Brick.

### This Project Exists To:

- 📚 Organize **tested, reusable prompting patterns** for GPT, Claude, DeepSeek, and Gemini
- 🏗️ Share a **systematic framework** for prompt engineering that I've found helpful
- 🔬 Compile **techniques from research and industry** in one accessible place
- 🤝 Invite **open-source contributions** from fellow builders and learners
- 🚀 Make prompt engineering **accessible and practical** for everyone

This is not a static spec — it's an **evolving learning journal**, and an open invitation to learn together.

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

---

## 🎯 What This Repository IS and IS NOT

### ✅ What This IS:
- **A practitioner's synthesis** of prompt engineering techniques from multiple authoritative sources
- **Organized documentation** of what works in real production applications
- **Real-world examples** from building AI products (RITA, OS Brick, and other Pineapple Lab projects)
- **Learning resource** structured from beginner to advanced
- **My personal framework** for organizing and applying prompt engineering knowledge
- **Honest curation** of brilliant work by researchers and engineers at major AI labs

### ❌ What This IS NOT:
- Novel academic research (I cite the researchers who did that work)
- Peer-reviewed or scientifically validated findings  
- Claims of breakthrough innovations or inventions
- Replacement for official documentation from AI labs
- Formal benchmarking studies with controlled experiments

### 🎓 My Contribution:
I'm a 21-year-old builder learning in public. I've spent months reading documentation from Anthropic, Google, and OpenAI. I've studied academic papers like Wei et al.'s Chain-of-Thought (19,810+ citations) and Kojima et al.'s Zero-Shot CoT. I've tested these techniques extensively while building real AI products.

**What I'm sharing:** My organization of this knowledge, practical examples from my work, and patterns I've found effective. I didn't invent these techniques — I learned them from the brilliant researchers and engineers who did the hard work. I'm just organizing and documenting practical application.

**Standing on the shoulders of giants:** All core techniques come from researchers at institutions and companies doing groundbreaking work. This repo is my way of climbing that mountain and documenting the path for others.

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
- **🏗️ Structure > Style** — Treat prompts like functions, not text
- **🔒 Security-Aware** — Special attention to injection risks and ambiguity
- **🌐 Multi-Model** — Tested across Claude, GPT, DeepSeek, and Gemini
- **🔬 Learning in Public** — Sharing what I learn as I build
- **📊 Research-Based** — Built on peer-reviewed research (properly cited) and real-world testing

---

## 🔬 Core Frameworks

### **Seven-Component Blueprint**

The [Prompt Engineering Blueprint](Prompt_Engineering_Blueprint.md) I've organized provides a systematic framework based on best practices from multiple sources:

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

A systematic framework for encouraging AI honesty and reliability:

**What it is:** A collection of prompt engineering techniques that encourage models to express uncertainty, state assumptions, and acknowledge limitations. This builds on AI safety research, model calibration work (Guo et al., 2017), and standard software documentation practices.

**Core Techniques:**
- **Explicit Uncertainty Acknowledgment**: `[CONFIDENT]`, `[LIKELY]`, `[UNCERTAIN]` markers
- **Assumption Transparency**: Making AI assumptions explicit
- **Limitation Disclosure**: Honest about what AI can't do
- **Honest Reporting Framework**: Structured honesty in responses
- **Validation Requirements**: Built-in self-checking mechanisms

**Where it comes from:** I've synthesized these techniques from AI safety research, Anthropic's work on AI honesty, and standard software practices. My contribution is organizing them into a coherent framework and providing practical examples.

**Real-world testing:** In my experience building AI agents for Pineapple Lab products, these structured approaches have significantly reduced instances where AI generates non-functional code or makes overconfident claims. I haven't conducted formal benchmarking yet, so I can't provide quantitative metrics.

**Learn more** → [TOE Context Engineering for Agents](Pineapple_Lab_TOE_Context_Engineering_for_Agents.md)

---

### **Advanced Techniques**

**XML Tag Structuring** (Anthropic Best Practice) ([Guide](XML_Tag_Structuring_Guide.md))
- **Source:** Documented by Anthropic in their official prompt engineering guide
- **My contribution:** Extensive testing and practical examples from building AI agents
- Semantic organization of prompt components
- Particularly powerful with Claude models
- Improves parseability and accuracy
- Enables complex multi-component prompts

**Chain-of-Thought Reasoning** (Wei et al., 2022; Kojima et al., 2022) ([Guide](Advanced_Logic_Building_Guide.md))
- **Source:** Introduced by Wei et al. (2022) with 19,810+ citations, extended by Kojima et al. (2022)
- **My contribution:** Practical application patterns and production examples
- Explicit step-by-step problem solving
- Zero-shot and few-shot CoT patterns
- Validation and self-correction mechanisms

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
Practical guide to Anthropic's XML tag technique:
- Core tag categories and best practices
- Chain-of-thought integration with XML
- Multi-component prompt patterns
- Conditional logic with XML structure
- Real-world implementation examples from my projects

### **Advanced Logic Building Guide** ✨ NEW
Application of research-backed reasoning frameworks:
- Zero-shot and few-shot chain-of-thought (Wei et al., Kojima et al.)
- Multi-condition logic trees
- Recursive reasoning patterns
- Prompt chaining (sequential and parallel)
- Self-correction and validation mechanisms
- Error detection and recovery patterns

---

## 🧱 In Progress

- `prompt_registry.json` — Structured schema for prompts-as-code
- `tests/` — Prompt regression + consistency tests
- `agent_templates/` — Blueprints for repeatable, role-specific agents
- **Integration examples** — Demonstrating XML + CoT + TOE together
- **Formal benchmarks** — Proper testing methodology with controlled experiments
- **Case studies** — Detailed examples from production systems with real data
- **Video tutorials** — Walking through techniques with practical demonstrations
- **Community patterns** — Collection of patterns from other practitioners

---

## 🧬 A Note from David

Hey, I'm David Edwards. I'm 21, living in South Africa, and building AI products like RITA and OS Brick at Pineapple Lab.

**Here's the honest truth:** I'm not a PhD researcher or an AI scientist. I'm a builder who loves to learn. When I started with prompt engineering, I spent months reading scattered docs from Anthropic, Google, and OpenAI. I studied papers by Wei, Kojima, and others. It was overwhelming.

This repo is what I wish existed when I started: everything organized, practical examples from real projects, and a clear path from "complete beginner" to "building production systems."

**What makes this valuable:**
- **Starting Guide** — I distilled months of learning into 30 minutes
- **XML Tag Structuring** — Anthropic's technique with my real-world examples
- **Advanced Logic Building** — Wei & Kojima's research applied to actual products
- **Truth Optimization Engine** — My framework for AI honesty, synthesized from multiple sources

**I didn't invent these techniques.** But I've tested them for hundreds of hours, organized them coherently, and documented what actually works in production.

**Why I'm sharing:** I believe in learning in public. I'm standing on the shoulders of giants and documenting the climb so you don't have to figure it all out alone like I did.

**Feedback is gold:** If you spot errors, have suggestions, or discover better patterns — please contribute. I'm learning too, and honest corrections make this better for everyone.

Thanks for being curious and learning with me,

**– David Edwards**  
*21-year-old builder, learning in public*  
*Pineapple Lab, South Africa*

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

## 🏆 Why This Guide Exists

### **Honest About Sources**
Every technique is properly attributed. I cite the researchers (Wei et al., Kojima et al.) and companies (Anthropic, Google, OpenAI) who did the original work. My contribution is organization and practical application.

### **Comprehensive Coverage**
From complete newbie to advanced production systems — I've organized the full learning journey with appropriate depth at each level. This is what I wish existed when I started.

### **Practical Focus**
Real-world examples from my work, production-tested patterns, and actionable guidance. No theoretical fluff — just what actually works.

### **Integration-First**
I show how techniques work together: XML tags + Chain-of-thought + Truth Optimization patterns = More reliable AI systems.

### **Learning in Public**
Built to share knowledge openly. Your contributions and corrections make this better for everyone.

### **Multi-Model**
Techniques I've tested across GPT (OpenAI), Claude (Anthropic), Gemini (Google), and DeepSeek.

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

## 🎓 My Actual Contributions

To be completely transparent about what I've added vs. what I learned from others:

### **Things I Learned From Others (With Credit):**
- **Chain-of-Thought reasoning** → Wei et al. (2022), Kojima et al. (2022)
- **XML tag structuring** → Anthropic official documentation
- **Few-shot prompting** → Brown et al. (2020)
- **System prompts, clear instructions** → Universal best practices from all major AI labs
- **Prompt chaining concepts** → ReAct paper, AutoGPT, and agent research
- **Model calibration** → Guo et al. (2017)

### **Things I've Contributed:**
1. **Organization:** Compiled scattered techniques from dozens of sources into one coherent framework
2. **Examples:** Created 50+ specific examples from building PropTech AI agents (RITA, OS Brick)
3. **Patterns:** Documented recurring patterns I've found effective in production
4. **Synthesis:** Connected techniques from different sources into integrated workflows
5. **Practical focus:** Emphasized what works in production vs. pure theory
6. **Domain application:** Showed how to apply general techniques to specific domains
7. **Learning path:** Created structured progression from beginner to advanced
8. **TOE Framework:** Organized AI honesty techniques into a systematic approach

### **The Real Value:**
You could spend months reading Anthropic's docs, Google's docs, OpenAI's docs, and 20+ research papers. 

Or you could read this guide where I've done that work and organized it for you.

**That's the service I'm providing: curation, synthesis, and practical application guidance.**

---

## 🛣️ Roadmap: From Documentation to Research

### **Current State (v2.0):**
This is a practitioner's guide based on synthesis of existing work.

### **Future Goals:**

#### Short-term (Next 6 months)
- [ ] Add 100+ more real-world examples from RITA and other Pineapple Lab products
- [ ] Create video tutorials demonstrating techniques
- [ ] Build community of practitioners sharing patterns
- [ ] Document failure cases and anti-patterns  
- [ ] Complete comprehensive bibliography with all sources

#### Medium-term (6-12 months)
- [ ] Conduct **formal benchmarking** with proper methodology
- [ ] Collaborate with researchers to **validate claims** with data
- [ ] Publish **case studies** with quantitative results from production
- [ ] Open-source example codebases showing techniques in action
- [ ] Present findings at conferences (as practitioner insights)

#### Long-term (1-2 years)
- [ ] If pursuing academic path: Partner with researchers on formal studies
- [ ] Develop novel techniques specific to my domain (if they emerge)
- [ ] Build tools that automate these patterns
- [ ] Publish peer-reviewed papers (if warranted by genuine novel findings)

### **The Journey:**
I'm starting as a documenter and practitioner. My goal is to eventually contribute original research if I discover something genuinely novel. But I'm not there yet, and I won't pretend I am.

**Honest positioning now → Credible voice later.**

---

## 🌟 About Pineapple Lab

📚 **Pineapple Lab – Learning in Public**

At Pineapple Lab, I believe in building openly and learning collaboratively. These resources are made freely available so others can learn from what I'm discovering, use what's helpful, and improve upon it.

**I'm not claiming to revolutionize AI. I'm just sharing what I learn as I build, hoping it helps others on the same journey.**

Learn with me.

---

**Last Updated**: October 2025  
**Version**: 2.1 (Honest repositioning - practitioner's guide, not research)  
**Previous**: v2.0 (Beginner guide, XML structuring, advanced logic)  
**Repository**: [github.com/pineapple-lab/docs](https://github.com/pineapple-lab/docs)

---

*Let's learn and build together, honestly.* 🚀
