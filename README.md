# AI-Playground

**This is a personal public journey into understanding, reproducing, and building AI systems.**

Represents a collection of small, self-contained AI projects and experiments.  
Each project lives in its own folder and can be used independently or as part of the playground.

# Projects

### 01_micrograd_pro
**Micrograd Pro** — an enhanced teaching/experimental re-implementation of Karpathy's micrograd, expanded with extra modules, research papers references and mathematical explanations throughout the notebooks.

Features:
- scalar autodiff `Value` engine
- extra activations: GELU, LeakyReLU, etc.
- simple `Layer`, `Linear`, `Sequential`, `LayerNorm`, `Dropout`
- small example notebooks and visualizations (gradient flow, loss slices, decision boundaries)

![Dropout Viz](https://raw.githubusercontent.com/0lekz/micrograd_pro/main/pics/flow/output6.png)
![GELU Example](https://raw.githubusercontent.com/0lekz/micrograd_pro/main/pics/flow/output11.png)

**Try experiencing yourself by forking micrograd_pro repo**

### 02_mimic_recognition
**Mimic Recognition** — a lightweight real-time facial emotion recognition demo built with a custom CNN, trained first on FER2013 and then fine-tuned on my own webcam data.

Features:
- custom 3-layer CNN on 48×48 grayscale faces (no pretrained backbone)
- FER2013 base training + fine-tuning on a small personal dataset
- real-time webcam inference with OpenCV face detection
- live class probability overlay, reaction images, and emotion-based sound effects
- CSV logging of predictions with timestamps and confidence scores

[YouTube demo](https://www.youtube.com/shorts/j7u5kU45kwE)

# Philosophy
This repository is a living record of my learning process in artificial intelligence, deep learning, machine learning, research engineering and similar topics.
Each subfolder represents a step in that journey; from basic neural networks to transformers, large language models, agents and more.

Note:
  * While this is a personal project, I hope it can also serve as a **roadmap or reference** for anyone who wants to learn AI hands-on, by building, experimenting, and reflecting.

Key Values:
- **Learn by doing:** every concept is implemented, not just read about.
- **Understand deeply:** code from scratch, analyze, and question every layer.
- **Document openly:** share notes, mistakes, insights, and resources.
- **Grow continuously:** each project tries to build on the previous one, thought not always in order of complexity.

Note:
  * All projects are added **chronologically**, not by difficulty, I share as I go.
  * This reflects how I actually learned, possibly often circling back, sometimes jumping ahead.


# Current Focus (Updated Oct 20, 2025)

I am currently working on:

- Experimenting with **micrograd and makemore** to reinforce fundamentals
- Fine-tuning and evaluating **DeBERTa-v3-large** on the MAP competition dataset (Kaggle)
- Understanding **transformer internals** through Karpathy's "GPT from scratch" series and other sources

# Long-Term Vision

I will try my best to grow this repository into a structured open resource with:
- **Theory:** (some-what)clear explanations and linked research
- **Practice:** reproducible code experiments
- **Transparency:** all resources I've used, plus possibly additional links to explore
- **Reflection (possibly):** honest documentation and additional blogs of how concepts "clicked" for me, not just raw data and resources.

# Related Links

- [My Kaggle Profile](https://www.kaggle.com/zhukovoleksiy) - (more projects and competition's solutions there)
- [LinkedIn](https://www.linkedin.com/in/oleksiizhukov/)
- [Telegram](https://t.me/zhukovoleksii) & [X](https://x.com/oleksii_zh) - if you wish to contact / have questions about this repo

# License

MIT License.
