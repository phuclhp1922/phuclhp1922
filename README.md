## Hi there, I'm Nguyen Song Thien Phuc

Final-year CS student at Vietnamese-German University, working on applied LLM engineering.

Most of what I build starts because something was tedious to do by hand — translating commentary,
curating a medical reasoning dataset, tracking money across a group chat. I'm most interested in the
unglamorous half of LLM work: getting data into decent shape, and building the evaluation loops that
decide whether output is good enough to keep.

---

### What I'm building

**[Medical Multi-modal Reasoning Dataset Curator](https://github.com/phuclhp1922/Bible_Commentary_Translator)**
A graph-based pipeline that extracts clinical reasoning from case reports, scores each trace with an
LLM judge, and sends failures back through a refine-and-retry loop. Built for a VGU research project on
multimodal clinical decision support; currently rebuilding it from a Colab notebook into a proper repo.
`Python` `LangGraph` `LLM-as-judge`

**[Bible Commentary Translator (EN → VI)](https://github.com/phuclhp1922/Medical_Data_Extractor)**
LoRA fine-tuning of a small Qwen model, trained in two stages: general Vietnamese translation, then the
commentary domain. Aligns English and Vietnamese verses to locate quoted excerpts so the output matches
Vietnamese scriptural idiom instead of translating them literally. In weekly use by my family.
`LoRA / PEFT` `dataset curation`

📫 nguyensongthienphuc@gmail.com · [LinkedIn](https://www.linkedin.com/in/thien-phuc-nguyen-song-bab6962aa/)

<!--
**phuclhp1922/phuclhp1922** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
