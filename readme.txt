# Classificação de Imagens com Redes Convolucionais (CNNs)

## Objetivo do Projeto

Este projeto tem como objetivo implementar e avaliar o desempenho de um modelo de rede neural convolucional (CNN) na tarefa de classificação de imagens. Utilizando o dataset *CUHK Face Sketch Database (CUFS)*, as imagens foram processadas para distinguir entre classes binárias (masculino e feminino). O projeto incluiu a construção de um modelo CNN autoral, análise de métricas de desempenho, como acurácia e F1-score, e discussão sobre os desafios e limitações do modelo.

## Instruções para Execução do Código

### Requisitos de Software

Certifique-se de que os seguintes softwares e bibliotecas estejam instalados no ambiente:
- Python 3.8 ou superior
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn
- PIL (Pillow)

### Configuração do Ambiente

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/projeto-cnn.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd projeto-cnn
   ```

3. Instale as dependências listadas no arquivo `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

### Execução do Código

1. Certifique-se de que o dataset esteja disponível no caminho correto, indicado no código (`/content/drive/MyDrive/Colab Notebooks/Colab-RESTIC36/Projetos/projeto2/photos/`).
2. Execute o script principal do projeto para treinar o modelo:
   ```bash
   python projeto2_cnn.py
   ```
3. Durante a execução, os gráficos de métricas de desempenho (acurácia e perda) serão gerados e exibidos automaticamente.

## Principais Conclusões e Considerações

O modelo CNN apresentou um desempenho satisfatório, com boas métricas de acurácia e F1-score, demonstrando sua capacidade de generalização. Contudo, os seguintes pontos foram observados:

- **Desafios:** O modelo enfrentou dificuldades com imagens que apresentavam condições desafiadoras, como iluminação irregular ou ruído.  
- **Limitações:** O dataset apresenta desbalanceamento entre classes e algumas imagens de baixa qualidade, o que pode ter impactado negativamente os resultados.  
- **Melhorias Sugeridas:** Para trabalhos futuros, sugere-se:
  - Aumento do dataset e uso de técnicas de aumento de dados.
  - Ajustes na arquitetura do modelo, como inclusão de mais camadas convolucionais.
  - Exploração de técnicas avançadas, como aprendizado por transferência (*Transfer Learning*).

Este projeto reforça a eficácia das CNNs para tarefas de classificação de imagens e destaca a importância de ajustes nos dados e no modelo para alcançar resultados ainda melhores.
```

