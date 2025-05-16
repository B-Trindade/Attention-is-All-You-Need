**Attention Is All You Need: Reproduction and Explanation Repository**

![Cover Slide](./presentation/imgs/cover/first%20slide%20attention.png)

![First Slide of Presentation](./presentation/Seminário___Attention_is_All_You_Need.pdf#page=1)

---

## 📖 Overview (English)

This repository provides:

1. **Reproduction** of the Transformer architecture from the seminal paper [Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762) using PyTorch.
2. **Detailed explanations** of each component (Multi-Head Self-Attention, Positional Encoding, Feed-Forward sublayers, Residual Connections, Layer Normalization).
3. **Jupyter Notebooks** with step-by-step code cells, mathematical derivations in LaTeX, and visualizations of attention weights.
4. **Complementary Presentation** in PDF format; first slide shown above.
5. **Additional References**—video lectures, popular science deep-dives, and textbook chapters to deepen understanding.

### 🔗 Presentation

* PDF: [Download the complementary presentation](./presentation/Transformer_Presentation.pdf)

### 🚀 Getting Started

```bash
# Clone repository
git clone https://github.com/B-Trindade/Attention-is-All-You-Need.git
cd Attention-is-All-You-Need

# Create and activate virtual environment 
python -m venv .venv
source .venv/bin/activate
```

### ⚙️ Dependency Installation

Before you begin, ensure you install all required Python packages listed in `requirements.txt`. We strongly recommend doing this inside your activated virtual environment for reproducibility:

```bash
pip install -r requirements.txt
```

### 📂 Repository Structure

```
├── presentation/            # PDF and slide images
│   ├── Transformer_Presentation.pdf
│   └── slide1.png
├── notebooks/               # Jupyter Notebooks for each module
│   ├── 01_positional_encoding.ipynb
│   ├── 02_self_attention.ipynb
│   └── 03_transformer_full.ipynb
├── src/                     # PyTorch implementations
│   ├── positional_encoding.py
│   ├── self_attention.py
│   └── transformer.py
├── requirements.txt
└── README.md
```

### 📚 Textbook Reference

* Prince, S. J. D. (2021). *Understanding Deep Learning*, Chapter 12: Transformers.

### 🎥 Video References

* University of Waterloo Lecture on Transformers: [https://www.youtube.com/watch?v=OyFJWRnt\_AY](https://www.youtube.com/watch?v=OyFJWRnt_AY)
* 3Blue1Brown: "Transformers" [https://www.youtube.com/watch?v=wjZofJX0v4M&](https://www.youtube.com/watch?v=wjZofJX0v4M&)
* 3Blue1Brown: "Self-Attention Deep Dive" [https://www.youtube.com/watch?v=eMlx5fFNoYc&](https://www.youtube.com/watch?v=eMlx5fFNoYc&)
* Brief Overview: [https://www.youtube.com/watch?v=e9-0BxyKG10](https://www.youtube.com/watch?v=e9-0BxyKG10)
* Math of Self-Attention: [https://www.youtube.com/watch?v=UPtG\_38Oq8o&](https://www.youtube.com/watch?v=UPtG_38Oq8o&)
* Attention Mechanism Math: [https://www.youtube.com/watch?v=hsu\_5DyHj7I](https://www.youtube.com/watch?v=hsu_5DyHj7I)


---

## 📖 Visão Geral (Português - Brasil)

Este repositório oferece:

1. **Reprodução** da arquitetura Transformer do artigo seminal [Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762) usando PyTorch.
2. **Explicações detalhadas** de cada componente (Multi-Head Self-Attention, Codificação Posicional, subcamadas Feed-Forward, Conexões de Resíduo, Normalização de Camada).
3. **Notebooks Jupyter** com células de código passo a passo, derivadas matemáticas em LaTeX e visualizações dos pesos de atenção.
4. **Apresentação Complementar** em formato PDF; primeira lâmina mostrada acima.
5. **Referências Adicionais**—aulas em vídeo, explicações populares e capítulo de livro para aprofundamento.

### 🔗 Apresentação

* PDF: [Baixar apresentação complementar](./presentation/Transformer_Presentation.pdf)

### 🚀 Como Começar

```bash
# Clonar repositório
git clone https://github.com/B-Trindade/Attention-is-All-You-Need.git
cd Attention-is-All-You-Need

# Criar e ativar ambiente virtual 
python -m venv .venv
source .venv/bin/activate

# Instalar dependências
pip install -r requirements.txt
```

### 📂 Estrutura do Repositório

```
├── presentation/            # PDF e imagens das lâminas
│   ├── Transformer_Presentation.pdf
│   └── slide1.png
├── notebooks/               # Notebooks Jupyter por módulo
│   ├── 01_positional_encoding.ipynb
│   ├── 02_self_attention.ipynb
│   └── 03_transformer_full.ipynb
├── src/                     # Implementações em PyTorch
│   ├── positional_encoding.py
│   ├── self_attention.py
│   └── transformer.py
├── requirements.txt
└── README.md
```

---

### 📚 Livro de Referência

* Prince, S. J. D. (2021). *Understanding Deep Learning*, Capítulo 12: Transformers.

### 🎥 Vídeos de Referência

* Aula Universidade de Waterloo: [https://www.youtube.com/watch?v=OyFJWRnt\_AY](https://www.youtube.com/watch?v=OyFJWRnt_AY)
* 3Blue1Brown: "Transformers" [https://www.youtube.com/watch?v=wjZofJX0v4M&](https://www.youtube.com/watch?v=wjZofJX0v4M&)
* 3Blue1Brown: "Autoatenção em Detalhes" [https://www.youtube.com/watch?v=eMlx5fFNoYc&](https://www.youtube.com/watch?v=eMlx5fFNoYc&)
* Visão Breve: [https://www.youtube.com/watch?v=e9-0BxyKG10](https://www.youtube.com/watch?v=e9-0BxyKG10)
* Matemática da Autoatenção: [https://www.youtube.com/watch?v=UPtG\_38Oq8o&](https://www.youtube.com/watch?v=UPtG_38Oq8o&)
* Matemática de Mecanismos de Atenção: [https://www.youtube.com/watch?v=hsu\_5DyHj7I](https://www.youtube.com/watch?v=hsu_5DyHj7I)

### ✨ Contribuições

Contribuições são bem-vindas! Por favor, abra *issues* ou *pull requests* para sugerir melhorias, correções de bugs ou novas funcionalidades.

### 📄 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.
