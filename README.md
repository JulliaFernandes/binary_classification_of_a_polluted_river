<h1 align="center"><b>Binary Classification of a Polluted River</b></h1>

<div align="center">
  <br>
  <a href="https://code.visualstudio.com/docs/?dv=linux64_deb">
    <img src="https://img.shields.io/badge/IDE-Visual%20Studio%20Code-informational" alt="VSCode">
  </a>
  <img src="https://img.shields.io/badge/Linguagem-Python-orange" alt="Python">
  <img src="https://img.shields.io/badge/Notebook-Jupyter-blue" alt="Jupyter Notebook">
</div>

---

## 📌 Descrição do Projeto

Este projeto tem como objetivo realizar a **classificação binária de imagens de um rio**, identificando se está **poluído** ou **não poluído** utilizando técnicas de Deep Learning e Transfer Learning com MobileNetV2.

Durante o desenvolvimento, foram abordados conceitos como:
- Pré-processamento e organização de imagens.
- Aumento de dados (Data Augmentation).
- Transfer Learning com MobileNetV2.
- Treinamento e avaliação de modelos de classificação.
- Análise de métricas e visualização de resultados.

O projeto automatiza o processo de análise de imagens ambientais, auxiliando na identificação de poluição em rios a partir de fotografias.

---

## 📁 Estrutura esperada das pastas

```
dataset_redimensionado/
    train/
        poluido/
        nao_poluido/
    val/
        poluido/
        nao_poluido/
    test/
        poluido/
        nao_poluido/
```

---

## ⚙️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/JulliaFernandes/BinaryClassificationOfAPollutedRiver.git
cd BinaryClassificationOfAPollutedRiver
pip install -r requirements.txt
```

---

## 🚀 Como usar

1. **Prepare as imagens**  
   Certifique-se de que as imagens já estejam tratadas, separadas por classe e redimensionadas nas pastas conforme a estrutura acima.

2. **Aumente e treine o modelo**  
   Execute o notebook:

   ```
   src/train_model.ipynb
   ```

   - Ele irá realizar o aumento de dados (data augmentation), treinar o modelo e salvar os resultados.

3. **Analise os resultados**  
   Após o treinamento, execute:

   ```
   src/analysis.ipynb
   ```

   - Para visualizar gráficos, métricas e análises dos resultados obtidos.

---

## 📝 Observações

- Os diretórios de imagens não são versionados.
- O melhor modelo será salvo como `melhor_modelo.h5`.
- Resultados detalhados e médias das execuções são salvos em arquivos `.txt` e `.npy`.

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## 📬 Contato

<div>
  <p><b>Jullia Fernandes Felizardo</b></p>
  <a href="https://t.me/JulliaFernandes">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
</div>

<a href="mailto:julliacefet@gmail.com?subject=[GitHub]%20Contato%20ChatBot">
  ✉️ julliacefet@gmail.com
</a>

Desenvolvido por [Jullia Fernandes](https://github.com/JulliaFernandes)

------------------------------------------------------------------------------------
<h1 align="center"><b>Binary Classification of a Polluted River</b></h1>

<div align="center">
  <br>
  <a href="https://code.visualstudio.com/docs/?dv=linux64_deb">
    <img src="https://img.shields.io/badge/IDE-Visual%20Studio%20Code-informational" alt="VSCode">
  </a>
  <img src="https://img.shields.io/badge/Language-Python-orange" alt="Python">
  <img src="https://img.shields.io/badge/Notebook-Jupyter-blue" alt="Jupyter Notebook">
</div>

---

## 📌 Project Description

This project aims to perform **binary classification of river images**, identifying whether a river is **polluted** or **not polluted** using Deep Learning and Transfer Learning with MobileNetV2.

During development, the following concepts were covered:
- Image preprocessing and organization.
- Data Augmentation.
- Transfer Learning with MobileNetV2.
- Training and evaluation of classification models.
- Metrics analysis and results visualization.

The project automates the analysis of environmental images, helping to identify river pollution from photographs.

---

## 📁 Expected Folder Structure

```
dataset_redimensioned/
    train/
        polluted/
        not_polluted/
    val/
        polluted/
        not_polluted/
    test/
        polluted/
        not_polluted/
```

---

## ⚙️ Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/BinaryClassificationOfAPollutedRiver.git
cd BinaryClassificationOfAPollutedRiver
pip install -r requirements.txt
```

---

## 🚀 How to Use

1. **Prepare the images**  
   Make sure the images are already processed, separated by class, and resized in the folders as shown above.

2. **Augment and train the model**  
   Run the notebook:

   ```
   src/train_model.ipynb
   ```

   - This will perform data augmentation, train the model, and save the results.

3. **Analyze the results**  
   After training, run:

   ```
   src/analysis.ipynb
   ```

   - To view graphs, metrics, and analysis of the obtained results.

---

## 📝 Notes

- The image directories are not versioned.
- The best model will be saved as `melhor_modelo.h5`.
- Detailed results and averages of the runs are saved in `.txt` and `.npy` files.

---

## 📄 License

This project is under the MIT license.

---

## 📬 Contact

<div>
  <p><b>Jullia Fernandes Felizardo</b></p>
  <a href="https://t.me/JulliaFernandes">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
</div>

<a href="mailto:julliacefet@gmail.com?subject=[GitHub]%20Contact%20BinaryClassificationOfAPollutedRiver">
  ✉️ julliacefet@gmail.com
</a>

Developed by [Jullia Fernandes](https://github.com/JulliaFernandes)
