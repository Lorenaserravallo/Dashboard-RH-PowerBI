# 📈 Dashboard de RH - Power BI
<img width="1199" height="662" alt="image" src="https://github.com/user-attachments/assets/dbdd1874-0122-43d6-9f75-985ca3d56a8f" />
Projeto desenvolvido durante o **Intensivão de Power BI** da Hashtag Treinamentos com foco em análise de indicadores de Recursos Humanos.

O dashboard foi construído utilizando Power BI, aplicando tratamento de dados no Power Query, criação de medidas em DAX e construção de visuais interativos.

---

##  Objetivo do Projeto

Criar um Dashboard de RH para análise estratégica de:

* Total de Contratações
* Funcionários Ativos
* Demissões
* Turnover
* Distribuição por Cidade
* Distribuição por Gênero
* Análise Hierárquica por Área e Cargo

---
## Ferramentas Utilizadas

* Power BI
* Power Query (tratamento de dados)
* DAX (criação de medidas)
* Excel (base de dados)

---

##  Etapas do Projeto

###  1. Importação e Tratamento de Dados (Power Query)

* Importação da base `BaseFuncionarios.xlsx`
* Remoção de linhas em branco
* Criação da coluna **Ano da Contratação**
* Extração da **Cidade** a partir do endereço utilizando Coluna de Exemplos
* Tratamento de valores nulos (Data de Demissão)

---

###  2. Criação de Medidas em DAX

Foram criadas medidas estratégicas como:

* `Total Contratações` → COUNTROWS
* `Funcionários Ativos`
* `Demissões`
* `% Turnover`
* Indicadores percentuais formatados corretamente

Aplicação de lógica condicional baseada em valores nulos (Data de Demissão).

---

###  3. Construção do Dashboard

###  Cards (Indicadores Principais)

* Total de Contratações
* Funcionários Ativos
* Demissões
* Turnover (%)

###  Sparkline

Análise da evolução das contratações por ano.

###  Gráfico de Funil

Distribuição de funcionários por cidade.

###  Gráfico de Rosca

Distribuição por gênero (M/F).

###  Árvore Hierárquica

Análise dinâmica por:

* Área
* Cargo

Com possibilidade de expansão para detalhamento interno.

---

###  Diferencial do Projeto

Implementação de **Tooltip personalizada**
Página criada exclusivamente para detalhamento ao passar o mouse sobre o gráfico de funil.

Isso permite:

* Análise mais detalhada
* Dashboard limpo e profissional
* Melhor experiência do usuário

---

##  Habilidades Desenvolvidas

* Power Query
* Modelagem de Dados
* Criação de Medidas em DAX
* Tratamento de valores nulos
* Formatação avançada de visuais
* Criação de Tooltip personalizada
* Design de Dashboard
* Escolha estratégica de cores e layout

---

##  Preview do Dashboard
### Visão Geral
<img width="1199" height="662" alt="image" src="https://github.com/user-attachments/assets/dbdd1874-0122-43d6-9f75-985ca3d56a8f" />

### Tooltip
<img width="1144" height="639" alt="image" src="https://github.com/user-attachments/assets/92c4948a-6ec7-4b83-bcc4-63e8c95d631a" />

---

##  Aprendizados

Esse projeto reforçou conceitos importantes como:

* Pensar em indicadores antes de criar gráficos
* Criar medidas antes da etapa visual
* Trabalhar layout e design como parte estratégica do projeto
* Melhorar experiência do usuário com Tooltip

---

## 🦋 Autora
Lorena Serravallo Estudante de Análise e Desenvolvimento de Sistemas com foco em Análise de Dados.

Projeto desenvolvido para fins de estudo e prática em Análise de Dados durante o Intensivão de Power BI - Hashtag Treinamentos.

