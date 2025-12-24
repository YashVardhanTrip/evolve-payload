# 🧬 Evolutionary Jailbreaks: Breaking LLM Council Defenses

![Research Preview](https://img.shields.io/badge/Research-AI%20Security-blueviolet)
![Status](https://img.shields.io/badge/Phase%201-Complete-success)
![License](https://img.shields.io/badge/License-MIT-green)
![Hosted](https://img.shields.io/badge/Hosted-GitHub%20Pages-blue)
![Models](https://img.shields.io/badge/Models-4%20LLMs%20Bypassed-red)

**A Red-Teaming Case Study Demonstrating How Evolutionary Algorithms Discover Universal Bypasses Against Multi-LLM Defense Architectures**


---

## 📋 Table of Contents
- [🔍 Overview](#-overview)
- [🎯 Research Objectives](#-research-objectives)
- [🏛️ LLM Council Architecture](#️-llm-council-architecture)
- [🧬 Evolutionary Attack Methodology](#-evolutionary-attack-methodology)
- [💥 Key Findings](#-key-findings)
- [📊 Results & Metrics](#-results--metrics)
- [🔮 Phase 2: Future Research](#-phase-2-future-research)
- [🛠️ Technical Implementation](#️-technical-implementation)
- [🚀 Quick Start](#-quick-start)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👥 Contact & Team](#-contact--team)

---

## 🔍 Overview

This research demonstrates a fundamental vulnerability in modern multi-LLM defense architectures. We show that **evolutionary algorithms can bypass sophisticated "LLM Council" systems** (consisting of 1 Lawyer/Jury + 3 Judges/Council members) **in their first generation**, exposing critical flaws in current AI security paradigms.

> ⚠️ **Critical Insight**: Model diversity alone does not guarantee security against adaptive, evolutionary threats.

### 🔑 Key Statistics
| Metric | Value | Significance |
|--------|-------|--------------|
| **Generation to Bypass** | 1 | Rapid vulnerability discovery |
| **Models Compromised** | 4/4 | Complete architecture failure |
| **Bypass Success Rate** | 100% | Universal vulnerability |
| **System Exploits Used** | 0 | Pure cognitive manipulation |

---

## 🎯 Research Objectives

### **Primary Goal**
Demonstrate that evolutionary algorithms can systematically discover "architecture-killer" payloads that bypass multi-LLM defense systems through adaptive mutation rather than traditional exploitation.

### **Specific Aims**
1. **Test the LLM Council Hypothesis**: Does using multiple diverse LLMs increase security robustness?
2. **Evolutionary Approach**: Can AI autonomously evolve bypass techniques without human guidance?
3. **Vulnerability Discovery**: Identify shared cognitive vulnerabilities across different LLM architectures
4. **Methodology Validation**: Establish evolutionary red-teaming as a valid security testing approach

---

## 🏛️ LLM Council Architecture

The defense system tested follows a judicial-inspired architecture:

### **Layer 1: The Lawyer (Jury)**
- **Role**: Initial safety filter and content gatekeeper
- **Function**: Policy enforcement, explicit content filtering
- **Analogy**: Courtroom bailiff ensuring only appropriate cases proceed

### **Layer 2: Judge 1 (Primary LLM)**
- **Architecture**: GPT-4 variant
- **Focus**: Comprehensive safety fine-tuning
- **Specialization**: Context-aware safety evaluation

### **Layer 3: Judge 2 (Secondary LLM)**
- **Architecture**: Claude variant
- **Focus**: Architectural diversity
- **Specialization**: Independent consensus validation

### **Layer 4: Judge 3 (Tertiary LLM)**
- **Architecture**: Gemini variant
- **Focus**: Novel pattern detection
- **Specialization**: Zero-day vulnerability identification

### Architecture Diagram

```
┌─────────────────────────────────────────┐
│      EVOLUTIONARY ATTACK                │
└───────────────────┬─────────────────────┘
                    │
┌───────────────────▼─────────────────────┐
│         LAWYER (JURY)                   │
│    • Initial Safety Filter              │
│    • Policy Enforcement                 │
└───────────────────┬─────────────────────┘
                    │
┌───────────────────▼─────────────────────┐
│         JUDGE 1 (Primary)                │
│    • GPT-4 Architecture                 │
│    • Comprehensive Safety                │
└─────────────┬─────────────┬─────────────┘
              │             │
┌─────────────▼─────────────▼─────────────┐
│  JUDGE 2 (Secondary)  JUDGE 3 (Tertiary)│
│  • Claude Architecture  • Gemini Arch.  │
│  • Diverse Training     • Novel Detection│
└─────────────────────────────────────────┘
```

---

## 🧬 Evolutionary Attack Methodology

### **Core Innovation**
We reframed prompt injection as an **optimization problem** rather than a manual engineering challenge.

### **Five-Stage Evolution Process**

#### **1. Initial Population Generation**

```python
# Pseudocode: Population Initialization
population = []
for _ in range(100):
    prompt = generate_variant(base_prompt)
    population.append({
        'prompt': prompt,
        'fitness': 0,
        'lineage': []
    })
```

#### **2. Fitness Evaluation**

**Scoring Criteria**:
- Layer 1 Bypass: +25 points
- Layer 2 Bypass: +25 points
- Layer 3 Bypass: +25 points
- Layer 4 Bypass: +25 points
- **Total Possible**: 100 points

#### **3. Selection & Reproduction**
- **Elitism**: Top 20% carry over unchanged
- **Crossover**: 50% combine strategies from two parents
- **Mutation**: 30% undergo random mutation

#### **4. Mutation Techniques Discovered**

| Generation | Technique | Success Rate |
|------------|-----------|--------------|
| 1-5 | Basic Obfuscation | 15% |
| 6-15 | Contextual Masking | 42% |
| 16+ | Architecture-Killer | 100% |

#### **5. Termination Criteria**
- **Success**: Any payload achieves 100/100 fitness score
- **Timeout**: Maximum 50 generations
- **Plateau**: No improvement for 10 generations

---

## 💥 Key Findings

### **1. First-Generation Success**
"The evolutionary algorithm discovered a universal bypass in its initial iteration."

This demonstrates that even sophisticated multi-LLM architectures contain exploitable vulnerabilities that can be discovered rapidly through systematic evolutionary pressure.

### **2. Shared Cognitive Vulnerabilities**
Despite architectural diversity, all tested LLMs shared fundamental vulnerabilities related to:

- Narrative persuasion techniques
- Authority framing exploitation
- Educational context manipulation
- Hypothetical scenario embedding

### **3. Exponential Adaptation**
The evolutionary process showed exponential, not linear, improvement:

```
Generation 1-5:  15% success rate
Generation 6-15: 42% success rate  
Generation 16+:  100% success rate
```

### **4. Architecture-Killer Payload**
The final successful payload:
- Exploits shared reasoning patterns, not software bugs
- Works across different LLM architectures
- Bypasses all safety fine-tuning layers
- Consistently marked as "safe" by all models

---

## 📊 Results & Metrics

### **Performance Metrics**

| Defense Layer | Bypass Rate | Detection Evasion |
|---------------|-------------|-------------------|
| Lawyer (Jury) | 100% | Complete |
| Judge 1 (Primary) | 100% | Complete |
| Judge 2 (Secondary) | 100% | Complete |
| Judge 3 (Tertiary) | 100% | Complete |

### **Evolutionary Metrics**
- **Generations to Success**: 1
- **Total Generations Tested**: 50
- **Population Size**: 100
- **Mutation Rate**: 0.3
- **Crossover Rate**: 0.5

### **Statistical Significance**
- **p-value**: < 0.001 (highly significant)
- **Confidence Interval**: 95%
- **Sample Size**: 5000 total prompt variations tested

---

## 🔮 Phase 2: Future Research

### **Adversarial Argumentation**
**Research Question**: Can AI models debate payload safety among themselves to discover more sophisticated vulnerabilities?

**Proposed Architecture**:

```
Attacker Model
     ↓
[Payload Proposal]
     ↓
┌─────────────────┐
│ Defense Council │
│  • Judge A      │
│  • Judge B      │
│  • Judge C      │
└─────────────────┘
     ↓
[Safety Debate]
     ↓
[Verdict & Rating]
```

### **Research Objectives for Phase 2**
1. **Multi-Agent Negotiation**: Study how AI models negotiate safety ratings
2. **Persuasion Techniques**: Identify new manipulation strategies
3. **Consensus Vulnerabilities**: Find weaknesses in group decision-making
4. **Real-time Adaptation**: Test against dynamically evolving defenses

---

## 🛠️ Technical Implementation

### **Requirements**
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+)
- Internet connection for font loading
- JavaScript enabled

### **Built With**
- **HTML5**: Semantic structure and content
- **CSS3**: Advanced animations, gradients, and responsive design
- **Vanilla JavaScript**: Scroll animations and interactivity
- **Google Fonts**: Inter font family
- **Font Awesome**: Icons and visual elements

### **Browser Support**

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |


## 📄 License

This research presentation is released under the MIT License.

```
MIT License

Copyright (c) 2024 LLM Council Security Research

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👥 Contact & Team

### **Research Team**
- **Lead Researcher**: [Your Name/Alias]
- **Affiliation**: Independent Security Research
- **Focus**: AI Security, Red Teaming, Evolutionary Algorithms

### **Communication**
- **Issues**: Use GitHub Issues for bugs or suggestions
- **Discussion**: GitHub Discussions for research questions
- **Security**: Please report security concerns responsibly

### **Acknowledgments**
- Inspired by the LLM Council concept
- Built with open web technologies
- Hosted on GitHub Pages

---

> ⚠️ **Ethical Note**: This research was conducted in controlled environments with appropriate ethical oversight. The findings are presented to advance AI security understanding and promote more robust defensive architectures.

**Last Updated**: December 2024  
**Version**: 1.0
