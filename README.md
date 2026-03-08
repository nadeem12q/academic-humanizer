# Academic Humanizer 🎓
> *Elevating AI Drafts to Academic Excellence with Integrity*

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](file:///d:/1_CodeBsae/academic%20humanizer/SKILL.md)
[![Category](https://img.shields.io/badge/category-Writing--Utility-green.svg)]()
[![Optimization](https://img.shields.io/badge/optimization-Academic--First-orange.svg)]()

**Academic Humanizer** is an advanced AI writing editor skill designed to identify, remove, and rewrite obvious signs of AI-generated text. While it excels at humanizing all types of writing, it is **heavily optimized for academic integrity**, including essays, research papers, reports, and theses.

This skill is a heavily modified and expanded version of the original [Humanizer](https://github.com/blader/humanizer) by [blader](https://github.com/blader), tailored specifically for tone preservation and adding "soul" to sterile AI outputs without compromising professional standards.

---

## ✨ Key Features & Enhancements

### 🎓 Academic Core
- **Specialized Rules:** Preserves citations (APA, MLA, etc.), technical terminology, and legitimate hedging.
- **Discipline-Specific:** Supports conventions for Sciences (Passive), Humanities (Reflective), and Business (Active).
- **Integrity Shield:** Strictly prohibits the generation of fake citations or hallucinated sources.

### 🧠 Personality & Soul
- **Burstiness Control:** Manually varies sentence length (Mix of ≤10 and ≥25 words) to bypass statistical detectors.
- **Rhythmic Variation:** Teaches AI to avoid repetitive "AI-typical" structures.
- **Context-Aware:** Switches between "Professional Soul" (Logic-focused) and "Casual Soul" (Personality-focused).

### 🔍 Detection & Quality
- **29 AI Patterns:** Scans for "pivotal", "delve", "testament", and 26 other common AI tells.
- **Semantic Anchor Check:** Ensures logical paragraph connectivity to prevent topic drift.
- **Multi-Lingual Auditing:** Internal prompts double-check tone consistency in real-time.

---

## 🛠️ The Humanization Pipeline

The Academic Humanizer follows a highly systematic **9-Step Process** to ensure quality and bypass detection:

```mermaid
graph TD
    A[Context Detection] --> B[Pattern Identification]
    B --> C[Drafting & Rewrite]
    C --> D[Burstiness & Perplexity Pass]
    D --> E[Quality Check]
    E --> F[Self-Audit / Anti-AI Pass]
    F --> G[Final Revision]
    G --> H[Final Tone Check]
    H --> I[Final Humanized Output]
```

---

## 📝 Pattern Comparison

| AI Pattern | Humanized Alternative | Why? |
|:---|:---|:---|
| *"It marks a pivotal moment..."* | *"This change is important because..."* | Avoids inflated symbolism. |
| *"Delving into the landscape..."* | *"When examining current research..."* | Replaces overused AI vocabulary. |
| *"Challenges and prospects..."* | *"Traffic increased due to X..."* | Specificity beats vague outlines. |
| *"In order to achieve..."* | *"To achieve..."* | Removes "AI fluff" filler phrases. |

---

## 📦 Installation & Usage

To use this skill locally in your AI CLI or agent environments (like Claude Code):

1. **Download the file:** Simply download the `SKILL.md` file from this repository.
2. **Place it in your workspace:** Move `SKILL.md` into your project's skills directory.
3. **Invoke:** 
   ```bash
   /academic-humanizer "Paste your text here"
   ```
   *Or prompt:* "Review this essay according to the Academic Humanizer skill."

---

## 📜 Update History

### v1.1.0 - Anti-Detection & Integrity Update
- **🚀 Burstiness Engine:** Mandatory sentence length variation for detector evasion.
- **🛡️ Integrity Shield:** "No Fake Citations" rule implemented.
- **📏 Word Count Engine:** ±10% preservation for assignment compliance.
- **⚙️ Technical Compatibility:** Renamed to `academic-humanizer` for Claude consistency.
- **🔗 Semantic Anchor:** Logical flow verification between paragraphs.

---

## ⚠️ The Reality of AI Detectors

No humanizer tool can guarantee a 100% bypass of AI detectors (like GPTZero, Turnitin, or Originality.ai). 
- **Detectors Evolve:** What bypasses them today might get flagged tomorrow.
- **False Positives:** Human writing is frequently flagged as AI.
- **Best Practice:** Use this tool as an *assistant*, not a replacement. Always add your unique voice and review outputs for institutional policy alignment.

---

## 🌟 Acknowledgements & Credits
> **Base Project:** Originally built upon **[blader/humanizer](https://github.com/blader/humanizer)** (MIT License). Based on Wikipedia's "Signs of AI writing" guide.
> 
> **Modifications:** Significantly expanded by **Nadeem** with academic pipelines, burstiness controls, and tone-checking mechanisms tailored for professional requirements.

---

## 👨‍💻 About the Author
Modified and maintained by **Nadeem**.
*   **GitHub:** [@nadeem12q](https://github.com/nadeem12q)

***Disclaimer:** Use this tool responsibly to improve readability and natural tone, not to facilitate academic misconduct.*
