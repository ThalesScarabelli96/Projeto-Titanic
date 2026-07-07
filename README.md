# Projeto Titanic: Análise Exploratória de Dados (EDA)

Este é um projeto prático de Ciência de Dados voltado para iniciantes, focado na exploração, limpeza e análise visual dos dados dos passageiros do famoso navio Titanic. O objetivo principal é entender quais fatores influenciaram as chances de sobrevivência dos passageiros.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python** (Linguagem de programação principal)
* **Pandas** (Manipulação e limpeza de dados)
* **Seaborn** (Visualização de dados e gráficos)
* **Matplotlib** (Customização de gráficos)
* **Jupyter Notebook / VS Code** (Ambiente de desenvolvimento)

---

## 📋 Estrutura do Repositório

* `notebooks/`: Pasta contendo o arquivo `Projeto_Titanic.ipynb` com o código-fonte e análises.
* `README.md`: Este documento com a explicação geral e insights do projeto.

---

## 📊 Principais Insights Obtidos

Após processar e analisar os dados (incluindo o tratamento de idades ausentes pela média), foram extraídas as seguintes conclusões:

* **Gênero:** As mulheres apresentaram uma taxa de sobrevivência significativamente maior do que os homens, confirmando a política de "mulheres e crianças primeiro".
* **Classe Social:** Os passageiros hospedados na 1ª classe tiveram chances de sobrevivência muito superiores aos que viajavam na 3ª classe.
* **Idade Média:** * A idade média dos passageiros que **sobreviveram** foi de **28.34 anos**.
  * A idade média dos passageiros que **não sobreviveram** foi ligeiramente superior, fixando-se em **30.63 anos**.
* **Preço Médio do Bilhete (Fare):**
  * O preço médio pago pelos **sobreviveram** foi consideravelmente maior: **£48.40**.
  * O preço médio pago por quem **não sobreviveu** foi de apenas **£22.12**.

💡 *Nota de Data Science:* O valor pago pelo bilhete reforça diretamente o impacto da classe social na taxa de sobrevivência, demonstrando que os sobreviventes pagaram, em média, mais do que o dobro do valor daqueles que não resistiram ao desastre.

---



🚀 Como Executar e Configurar o Projeto

Seja para configurar o seu próprio ambiente local ou para testar o código em outra máquina, siga o passo a passo abaixo para garantir o funcionamento correto:

### 1. Clone o repositório

Abra o terminal do seu computador e execute o comando abaixo para clonar o projeto:

```bash
git clone [https://github.com/ThalesScarabelli96/Projeto-Titanic](https://github.com/ThalesScarabelli96/Projeto-Titanic)

### 2. Instale as dependências necessárias no terminal do VS Code:
(Obrigatório caso você ou outro usuário ainda não possua as bibliotecas instaladas na máquina)

pip install pandas seaborn matplotlib jupyter


💻 Nota para Windows: Se o comando pip apresentar erros, utilize:

python -m pip install pandas seaborn matplotlib jupyter


### 3. Abra e execute o Notebook:
Navegue até a pasta notebooks/, abra o arquivo Projeto_Titanic.ipynb no VS Code e execute as células sequencialmente.

### ✒️ Autor

Thales Scarabelli - @ThalesScarabelli96
