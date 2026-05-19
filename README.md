# 🎨 GAN Projects — Generative Adversarial Networks

Implementation of **Generative Adversarial Networks (GANs)** from scratch using Python and deep learning frameworks. This repo includes experiments on generating synthetic eye images and general GAN architectures.

---

## 📂 Projects Inside

| Notebook | Description |
|----------|-------------|
| `eyes gan.ipynb` | GAN trained to generate realistic synthetic eye images |
| `gangs.ipynb` | General GAN architecture experiments and training loops |

---

## 🧠 What is a GAN?

A GAN consists of two neural networks competing against each other:

```
Real Data ──► Discriminator ◄── Generator ◄── Random Noise
                   │                  ▲
                   └── Loss Signal ───┘
```

- **Generator** — creates fake images trying to fool the discriminator
- **Discriminator** — learns to tell real from fake
- Both improve together until generated images are indistinguishable from real ones

---

## 🚀 Key Concepts Covered

- Generator and Discriminator architecture design
- Adversarial training loop implementation
- Binary cross-entropy loss for GAN training
- Training stability techniques
- Visualizing generated outputs at each epoch

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| TensorFlow / Keras | GAN model building |
| NumPy | Data handling |
| Matplotlib | Visualizing generated images |
| Jupyter Notebook | Development environment |

---

## ⚙️ Setup

```bash
git clone https://github.com/jawadsatti320/Gan-work.git
cd Gan-work
pip install tensorflow numpy matplotlib jupyter
jupyter notebook
```

Open any `.ipynb` and run all cells sequentially.

---

## 📊 Results

The `eyes gan.ipynb` model generates synthetic eye images after training — useful for data augmentation in computer vision pipelines where real labeled data is scarce.

---

## 👨‍💻 Author

**Jawad Ahmed** — AI Engineer & ML Specialist  
BS Computer Science (AI) — PMAS Rawalpindi | Currently at DEVROLIN
