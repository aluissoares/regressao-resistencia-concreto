![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)

# Predição da Resistência à Compressão do Concreto

Este projeto é parte de um desafio prático de Regressão aplicada à Engenharia de Materiais usando Python e Machine Learning.
O objetivo é prever a resistência à compressão de diferentes amostras de concreto com base em sua composição química.
   
---

## 📊 Objetivo do Projeto

Desenvolver um modelo de Machine Learning capaz de prever a resistência à compressão (MPa) com base nos componentes do concreto:

| Variável                        | Descrição                                           | Unidade    |
|---------------------------------|-----------------------------------------------------|------------|
| `Cement`                        | Quantidade de cimento                               | kg/m³      |
| `Blast Furnace Slag`            | Escória de alto-forno                               | kg/m³      |
| `Fly Ash`                       | Cinzas volantes                                     | kg/m³      |
| `Water`                         | Quantidade de água                                  | kg/m³      |
| `Superplasticizer`              | Superplastificante (aditivo)                        | kg/m³      |
| `Coarse Aggregate`              | Agregado graúdo                                     | kg/m³      |
| `Fine Aggregate`                | Agregado miúdo                                      | kg/m³      |
| `Age`                           | Idade da amostra                                    | dias       |
| `Concrete compressive strength` | Resistência à compressão do concreto                | MPa        |
| `Strength Category`             | Classificação da resistência (Baixa, Média, Alta)   | Categórica |

---

## 🧠 Técnicas Utilizadas

- Python (pandas, numpy, matplotlib, seaborn);
- Scikit-learn;
- Regressão Linear e outros modelos de regressão;
- Avaliação com MAE, MSE e R².

---

## 📁 Arquivos no Repositório

- `notebook.ipynb` – Análise exploratória, tratamento dos dados e construção dos modelos
- `concrete_data.csv` – Base de dados original
- `README.md` – Apresentação do projeto

---

## 📌 Resultado

O modelo final alcançou bons resultados preditivos, com desempenho avaliado por métricas estatísticas de regressão.

- MAE: 5.01
- R²: 0.82

---

## 🚀 Como Executar

1. Clone este repositório
2. Instale os pacotes necessários (consulte o `requirements.txt`)
3. Execute o notebook `notebook.ipynb`

---

## 👨‍💻 Autor

André Luis Soares  
[LinkedIn](https://www.linkedin.com/in/andre-luis-soares-05312016a) | [GitHub](https://github.com/aluissoares)

---

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
