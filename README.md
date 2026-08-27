<h1 align="center">Hi, I'm building ML systems from first principles 👋</h1>

<p align="center">
Final-year B.Tech (AI & Data Science) student in Chennai — I like understanding the math beneath the frameworks, not just calling the API.
</p>

---

### About Me

- 🎓 Graduating 2027, Anna University-affiliated college, Chennai
- 🛠️ Opted out of campus placements — chasing ML/AI Engineer internships at early-stage Chennai startups instead
- 🔍 Prefer building things end-to-end and debugging *why* something fails, not just shipping what works
- 📫 Reach me here on GitHub or via the links below

---

### Featured Projects

**🔎 Industrial Anomaly Detection (MVTec AD)**
Multi-phase pipeline that started with a PyTorch autoencoder (surface-crack detection, ~0.95 AUC) and hit a wall scaling to six MVTec categories — reconstruction-based scoring capped out at 0.63–0.70 AUC because a high-capacity bottleneck reconstructs defects almost as cleanly as healthy images. Pivoted to **PatchCore**: frozen ResNet-18 backbone, multi-scale patch embeddings, 10% coreset subsampling, nearest-neighbor memory bank, Youden's J threshold optimization. Integrated into my portfolio app with HuggingFace Hub model loading.

**💳 Fraud Detection Pipeline**
LightGBM + CalibratedClassifierCV on 6.3M transactions, SMOTE for class imbalance, SHAP waterfall plots for explainability — 99.75% recall. Deployed as a Gradio app on HuggingFace Spaces.

**🧠 Neural Network from Scratch (NumPy only)**
4-layer network (784→90→30→10) trained on MNIST — He initialization, hand-derived backpropagation, L2 regularization, softmax + cross-entropy gradients. No autograd, no shortcuts.

**🌐 ML Portfolio App**
Streamlit app hosting the above projects — custom theming system with CSS variables, model assets pulled from a private HuggingFace Hub repo, CPU-only torch wheel to cut cold-start time on Streamlit Cloud.

---

### Currently Exploring

Transformer internals (Q/K/V projections, decoder-only vs. encoder-decoder tradeoffs), RAG vs. LoRA tradeoffs, KV caching, and attention mechanisms like CBAM.

---

<p align="center"><i>Open to ML/AI Engineer internship opportunities — let's talk.</i></p>

<!--
**NLCfpeaccount/NLCfpeaccount** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
