# 📊 O Peso das Palavras: Análise Exploratória e Sentimento de Avaliações dos Clientes

## 📖 Sobre o Projeto

Este projeto foi desenvolvido a partir de um conjunto de dados disponibilizado pela **AWS** em parceria com o **SENAI Suíço-Brasileiro**, com o objetivo de investigar a relação entre as notas atribuídas por clientes e o sentimento presente em seus comentários textuais.

Por meio de técnicas de **Análise Exploratória de Dados (EDA)** e **Análise de Sentimentos**, buscamos identificar padrões de comportamento, inconsistências entre avaliações e oportunidades de melhoria na experiência do consumidor.

---

## 🎯 Problema de Negócio

Em marketplaces digitais, clientes avaliam produtos utilizando:

* Notas de 1 a 5 estrelas;
* Comentários textuais.

Nem sempre a nota atribuída reflete corretamente o conteúdo do comentário, o que pode gerar interpretações equivocadas sobre o nível real de satisfação do cliente.

Este projeto busca responder à seguinte pergunta:

> Existe coerência entre as notas atribuídas pelos clientes e os sentimentos expressos em seus comentários?

---

## 🚀 Objetivos

* Realizar a exploração e tratamento dos dados.
* Integrar informações de diferentes tabelas do banco.
* Aplicar técnicas de análise de sentimento.
* Identificar avaliações incoerentes.
* Descobrir padrões de satisfação e insatisfação dos clientes.
* Gerar insights para tomada de decisão baseada em dados.

---

## 🗃️ Estrutura do Dataset

O conjunto de dados é composto por 9 tabelas:

| Tabela              | Descrição                            |
| ------------------- | ------------------------------------ |
| vendedores.csv      | Informações dos vendedores           |
| produtos.csv        | Dados dos produtos                   |
| pedidos.csv         | Informações dos pedidos              |
| pagamentos.csv      | Dados de pagamento                   |
| itens_pedidos.csv   | Itens presentes em cada pedido       |
| geolocalizacao.csv  | Dados geográficos                    |
| clientes.csv        | Informações dos clientes             |
| avaliacoes.csv      | Avaliações e comentários             |
| tabela_auxiliar.csv | Tradução das categorias dos produtos |

---

## 🛠️ Tecnologias Utilizadas

### 💻 Linguagens

* Python

### 📚 Bibliotecas

* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud
* Collections (Counter)
* Transformers
* VaderSentiment
* LeIA

---

## 🔄 Etapas do Projeto

### 📊 1. Exploração dos Dados (EDA)

Foram realizadas análises para identificar:

* Estrutura das tabelas
* Tipos de variáveis
* Estatísticas descritivas
* Valores nulos
* Duplicidades
* Distribuições dos dados

---

### 🔗 2. Integração das Tabelas

As tabelas foram unificadas utilizando operações de **merge**, permitindo relacionar informações de:

* Clientes
* Produtos
* Pedidos
* Pagamentos
* Vendedores
* Avaliações

---

### 🧹 3. Tratamento dos Dados

Principais transformações:

* Conversão de tipos de dados
* Padronização textual
* Tratamento de datas
* Remoção de duplicatas
* Tratamento de valores nulos
* Otimização de memória

---

### 🤖 4. Análise de Sentimentos

Foram utilizados três modelos distintos:

#### 🔹 VADER

Modelo léxico voltado para análise de sentimentos.

#### 🔹 LeIA

Versão adaptada para português baseada na estrutura do VADER.

#### 🔹 Transformers (BERT)

Modelo baseado em Deep Learning utilizando:

```python
nlptown/bert-base-multilingual-uncased-sentiment
```

Capaz de compreender contextos mais complexos da linguagem.

---

## 🧠 5. Competências Demonstradas

* Análise Exploratória de Dados (EDA)
* Limpeza e tratamento de dados
* Manipulação de múltiplos DataFrames
* Análise de Sentimentos
* Visualização de Dados
* Python para Ciência de Dados
* Storytelling com Dados

---

## 👨‍💻 Autor

**Enzo Ribeiro**

Estudante de Inteligência e Análise de Dados pelo SENAI Suíço-Brasileiro, com interesse em:

* Ciência de Dados
* Analytics
* Business Intelligence
* Auditoria de TI
* Inteligência Artificial

Conecte-se comigo pelo LinkedIn e acompanhe meus projetos!
