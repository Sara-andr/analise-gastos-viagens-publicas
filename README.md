# Análise de Gastos com Viagens Públicas

Este projeto realiza uma análise exploratória de dados públicos sobre gastos com viagens realizadas por órgãos do governo federal.

## Principais funcionalidades
- Limpeza e tratamento de dados com pandas
- Análises por órgãos, cidades e períodos
- Gráficos prontos para relatórios e apresentações

## Dados
Os dados utilizados são públicos e foram fornecidos em formato CSV.

## Visualizações
As seções abaixo apresentam os principais destaques em forma de gráficos.

---
# 🧳 Análise de Diárias e Passagens

Este projeto realiza uma análise exploratória de dados públicos relacionados a diárias e passagens, com foco em identificar padrões de gastos, destinos mais frequentes, evolução temporal e outros insights.

## 📊 Objetivos

- Identificar servidores e órgãos que mais gastam
- Mapear os destinos mais comuns
- Avaliar a evolução dos gastos ao longo do tempo
- Observar duração média das viagens
- Gerar visualizações de fácil entendimento

## ⚠️ Limitação dos Dados

Os dados analisados cobrem um período limitado. Por isso, as análises se concentram em métricas de distribuição (ranking, médias e somatórios) em vez de tendências de longo prazo. Mesmo com essa limitação, o projeto demonstra domínio das etapas de análise de dados com base em dados reais.

## 📁 Estrutura

- `viagens.csv`: Base de dados original
- `analise_viagens.ipynb`: Código com análises e gráficos
- `requirements.txt`: Bibliotecas necessárias
- `README.md`: Documentação do projeto

## 🚀 Como Rodar

1. Clone o repositório
2. Instale as dependências:
```bash
pip install -r requirements.txt
```
3. Abra o notebook com Jupyter:
```bash
jupyter notebook analise_viagens.ipynb
```

## Análise: Top 10 Órgãos por Gastos com Viagens

O gráfico abaixo apresenta os 10 órgãos superiores que mais gastaram com viagens públicas, com base nos dados disponíveis no arquivo `viagens.csv`.

![Top 10 Órgãos por Gastos com Viagens](images/top10_orgaos.png)

## Análise: Top 10 Cidades por Gastos com Viagens

Este gráfico mostra as cidades que mais receberam recursos públicos com viagens, considerando todos os registros no dataset.

![Top 10 Cidades por Gastos com Viagens](images/top10_cidades.png)

## Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/analise-gastos-viagens-publicas.git
cd analise-gastos-viagens-publicas
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute o notebook:
Abra o arquivo `notebooks/analise_viagens.ipynb` em um Jupyter Notebook para explorar a análise.
