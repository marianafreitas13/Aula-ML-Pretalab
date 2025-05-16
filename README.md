# PRETALAB - CURSO IA (CICLO 13)  
## Projeto de Aprendizado de Máquina (ML)  
### Classificação de Imagens: Mulheres Brancas vs. Mulheres Pretas

Este projeto utiliza técnicas de Machine Learning e Visão Computacional para classificar imagens de mulheres em duas categorias: **brancas** ou **pretas**. O modelo é treinado com imagens previamente organizadas e pode ser testado com novas imagens, inclusive da internet.

---

## 🧠 Contexto Geral

O código realiza as seguintes etapas:
- Organização das imagens em pastas por classe (`brancas` e `pretas`)
- Pré-processamento e aumento de dados com `ImageDataGenerator`
- Treinamento de um modelo de rede neural convolucional (CNN) simples usando Keras
- Salvamento do modelo treinado
- Testes com imagens externas e exibição da predição com porcentagem de confiança

O objetivo é aplicar conhecimentos básicos de IA para treinar um modelo binário de classificação de imagens de rostos humanos.

---

## 💻 Tecnologias Utilizadas

- **Python 3.x (Google Colab)**
- **TensorFlow / Keras** – construção e treinamento do modelo
- **Pillow (PIL)** – processamento de imagens
- **Matplotlib** – visualização dos resultados
- **Requests** – download de imagens da internet
- **OS / shutil** – manipulação de arquivos e pastas

---

## ▶️ Como Executar no Google Colab

1. **Monte o Google Drive:**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

2. **Organize suas imagens com a função `organize_images()`,** separando por classes:
   ```
   /content/drive/MyDrive/projeto_ml/
   └── treinamento/
       ├── brancas/
       └── pretas/
   ```

3. **Execute todas as células do notebook Colab:**
   - Carregue e prepare os dados
   - Treine o modelo (CNN simples ou MobileNetV2)
   - Teste com imagens usando links da internet

4. **Visualize os resultados** com a classe predita e o nível de confiança.

---

> Projeto desenvolvido durante o curso de Inteligência Artificial da Pretalab – Ciclo 13.
