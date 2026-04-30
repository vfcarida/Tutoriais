# 🧠 Tutoriais de Inteligência Artificial e Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/)

Bem-vindo(a) ao repositório central de **Tutoriais de IA, Machine Learning, Deep Learning, Transformers e Agentes**. 

Este projeto foi cuidadosamente curado e organizado para servir como um portfólio prático e um recurso de aprendizado abrangente. Aqui você encontrará desde conceitos básicos (como embeddings e TF-IDF) até os modelos de linguagem mais avançados (LLMs), sistemas RAG, finetuning e processamento de áudio/visão.

---

## 📂 Estrutura do Repositório

O repositório está dividido em áreas temáticas para facilitar a navegação. Cada diretório contém notebooks focados em demonstrações práticas, explicações passo a passo e casos de uso reais:

*   **`01_Basics_and_Core_Concepts/`**: Fundamentos de IA, mecanismos de atenção (Self-Attention passo a passo), visualização de gradientes e métricas (TF-IDF, BM25).
*   **`02_NLP_and_Transformers/`**: Processamento de Linguagem Natural clássico e moderno. Finetuning de BERT/Electra, Sentence Transformers, BERTopic e classificação de intenções.
*   **`03_Large_Language_Models_and_Agents/`**: O estado da arte em IA Generativa. Finetuning de Llama 3/Qwen com Unsloth/PEFT, construção de agentes e estratégias de *Prompt Engineering*.
*   **`04_RAG_and_Information_Retrieval/`**: Geração Aumentada por Recuperação. Tutoriais com LlamaIndex, LangChain e Weaviate para recuperar informações de documentos e grafos.
*   **`05_Computer_Vision/`**: Visão computacional com CNNs, GradCAM, extração de texto de imagens (DocQVA) e AnimeGAN.
*   **`06_Recommender_Systems/`**: Sistemas de recomendação com AutoEncoders, DLRM (Deep Learning Recommendation Model), ALS e modelos para *Learning to Rank*.
*   **`07_Audio_and_Speech/`**: Processamento de fala e áudio. Finetuning de modelos Wav2Vec2 para reconhecimento de fala e clonagem de voz.
*   **`08_Tabular_Data/`**: Aplicação de ML tradicional e redes neurais em dados tabulares (Census, Titanic).
*   **`09_Misc_and_Data_Engineering/`**: Truques avançados com Pandas, manuseio de grandes datasets e deploys rápidos usando Streamlit.
*   **`assets/`**: Arquivos auxiliares, apresentações e slides de referência.

---

## 🚀 Como Começar

Para rodar os tutoriais na sua própria máquina, recomendo a criação de um ambiente virtual para não conflitar com outras bibliotecas do seu sistema.

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/Tutoriais.git
   cd Tutoriais
   ```

2. **Crie e ative um ambiente virtual (exemplo com `venv`):**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # No Windows, use: .venv\Scripts\activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o Jupyter Lab ou Notebook:**
   ```bash
   jupyter lab
   ```

> [!TIP]
> **Dica de Hardware**: Muitos notebooks na pasta `03_Large_Language_Models_and_Agents` e `07_Audio_and_Speech` exigem aceleração via GPU. Se você não possui uma GPU local, recomendo rodar estes notebooks específicos no **Google Colab**.

---

## 🤝 Contribuições e Feedback

Sinta-se à vontade para abrir **Issues** caso encontre algum bug ou tenha dúvidas sobre a implementação de algum algoritmo, ou **Pull Requests** se quiser sugerir melhorias. Feedback é sempre muito bem-vindo!

---

## 👨‍💻 Autor e Contato

Desenvolvido e mantido por **Vinicius Caridá**. 

Para acompanhar meus projetos, tutoriais e discussões sobre IA:
- 💼 **LinkedIn**: [https://www.linkedin.com/in/viniciuscarida/](https://www.linkedin.com/in/viniciuscarida/)
- 🐦 **Twitter/X**: [https://twitter.com/vfcarida](https://twitter.com/vfcarida)
- 📺 **YouTube**: [https://www.youtube.com/@ViniciusFCarida](https://www.youtube.com/@ViniciusFCarida)
