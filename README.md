# Academic Humanizer 🎓

**Academic Humanizer** is an advanced AI writing editor skill designed to identify, remove, and rewrite obvious signs of AI-generated text. While it excels at humanizing all types of writing, it is **heavily optimized for academic writing**, including essays, research papers, reports, and theses.

This skill is a heavily modified and expanded version of the original [Humanizer](https://github.com/blader/humanizer) by [blader](https://github.com/blader), tailored specifically for academic integrity, tone preservation, and adding "soul" to sterile AI outputs.


---

## ✨ Key Features & Enhancements

- **🎓 Academic Mode (New):** Specialized rules to preserve citations (APA, MLA, etc.), technical terminology, legitimate hedging (e.g., "suggests that"), and passive voice common in scientific methods sections.
- **🧠 Personality & Soul Injection:** Doesn't just strip out AI words; it teaches the AI how to vary rhythm, acknowledge complexity, and sound genuinely human without losing professionalism.
- **🔍 29 AI Detection Patterns:** Expands upon the original 24 patterns to include 5 new Academic-Specific patterns (Citation Preservation, Technical Terms, Hedging, Passive Voice, Discipline Conventions).
- **📝 9-Step Rigorous Process:** Uses a strict multi-step pipeline including Context Detection, Pattern Identification, Quality Checks, Self-Auditing ("Anti-AI Pass"), and a Final Tone Consistency Check.
- **🗣️ Multi-Lingual Tone Auditing:** Features integrated internal tone-checking prompts (using conversational elements like *"Kya yeh abhi bhi formal tone mein hai?"*) to ensure the AI rigorously double-checks its own output character.

---

## 🛠️ How It Works

The Academic Humanizer doesn't just rewrite text blindly. It follows a highly systematic approach:
1. **Context Detection:** Analyzes if the text is Academic, Business, Casual, or Creative to apply the correct ruleset.
2. **Pattern Stripping:** Scans for 29 known AI tells (e.g., "delve", "pivotal", em-dash overuse, shiny promotional words, outline-like structures).
3. **Drafting:** Rewrites the text focusing on natural transitions and copula verbs ("is/are").
4. **Self-Audit:** The skill prompts itself to find what still looks AI-generated and does a second revision.
5. **Final Sanity Check:** Ensures the tone hasn't become inappropriately casual for an academic setting.

---

## 📦 Installation & Usage

To use this skill locally in your AI CLI or agent environments (like Claude Code):

1. **Download the file:** Simply download the `SKILL.md` file from this repository.
2. **Place it in your workspace:** Move `SKILL.md` into your project's skills directory or provide it as a system prompt to your preferred LLM.
3. **Invoke:** Ask your AI assistant to "humanize this text" or "review this essay according to the Academic Humanizer skill."

---

## ⚠️ The Reality of AI Detectors

No humanizer tool can guarantee a 100% bypass of AI detectors (like GPTZero, Turnitin, or Originality.ai). 
- **Detectors Evolve:** What bypasses them today might get flagged tomorrow.
- **False Positives:** Human writing (especially formal academic writing and non-native English) is frequently flagged as AI.
- **Best Practice:** Use this tool as an *assistant*, not a replacement for your own work. Always add your own research, maintain your unique voice, and review the output line-by-line before submission to ensure it aligns with your institution's academic integrity policies.

---

## 🌟 Acknowledgements & Credits
> **Base Project:** This project was originally built upon the open-source **[blader/humanizer](https://github.com/blader/humanizer)** repository, which is licensed under the MIT License. A huge thanks to the original creator for building the foundational patterns based on Wikipedia's "Signs of AI writing" guide. 
> 
> **Modifications:** I (Nadeem) have downloaded the base `SKILL.md` and significantly expanded it by adding new academic-focused roles, step-by-step processing pipelines, specific rules for essays/thesis, and comprehensive tone-checking mechanisms tailored to my unique workflow and requirements.

---

## 👨‍💻 About the Author

Modified and maintained by **Nadeem**.

* **GitHub:** [@nadeem12q](https://github.com/nadeem12q)

***Disclaimer:** Use this tool responsibly. It is designed to improve the flow, readability, and natural tone of AI-assisted drafting, not to facilitate academic misconduct.*
