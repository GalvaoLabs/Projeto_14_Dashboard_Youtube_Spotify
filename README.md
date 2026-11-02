# Dashboard Musical — Análise Spotify & YouTube

Projeto desenvolvido em Python como atividade prática proposta pelo professor **Mateus de Sousa** ([@msousa07](https://github.com/msousa07)). A implementação do dashboard foi realizada por **Miguel Henrique** ([@GalvaoLabs](https://github.com/GalvaoLabs)).

A atividade teve como objetivo aplicar conceitos de manipulação, análise e visualização de dados utilizando uma base de informações musicais do Spotify e do YouTube.

## Sobre o projeto

O dashboard apresenta informações de um catálogo com mais de **20 mil registros de músicas**, reunindo métricas de desempenho em diferentes plataformas, dados de artistas e álbuns e características das faixas.

O cenário da atividade utiliza a empresa fictícia **Mateus Music** como contexto para propor uma situação prática de análise de dados. O projeto é uma atividade educacional, não uma ferramenta desenvolvida para uma contratação ou cliente real.

## Funcionalidades

### 1. Filtro por artista
- Seleção de um artista específico.
- Opção para visualizar os dados de todo o catálogo.
- Atualização das métricas e visualizações conforme o filtro selecionado.

### 2. Indicadores principais
- Quantidade de músicas no conjunto filtrado.
- Total de visualizações no YouTube.
- Total de reproduções (*streams*) no Spotify.

### 3. Visualizações
- No modo geral, exibição dos cinco artistas com maior quantidade de músicas.
- No modo de artista específico, visualização das músicas do artista no YouTube.
- Comparação entre visualizações no YouTube e reproduções no Spotify.

### 4. Ranking musical
- Tabela com as dez músicas de maior número de streams no Spotify.
- Exibição dos dados em formato tabular interativo.

## Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| Python | Desenvolvimento da aplicação e lógica do projeto |
| Pandas | Leitura, filtragem, agrupamento e análise dos dados |
| Streamlit | Construção da interface interativa |

## Conceitos aplicados

Durante a resolução da atividade, foram utilizados recursos do Pandas, como:

- `pd.read_csv()` — leitura de arquivos CSV;
- `unique()` — identificação de artistas disponíveis;
- Filtragem de DataFrames — seleção de registros por artista;
- `groupby()` e `sum()` — agrupamento e agregação de métricas;
- `nlargest()` — identificação dos maiores valores;
- `value_counts()` — contagem de ocorrências.

Também foram aplicados conceitos de construção de dashboards, organização de indicadores, filtros interativos e apresentação visual de informações.

## Como executar

### Pré-requisitos

- Python instalado;
- Bibliotecas Streamlit e Pandas.

Instale as dependências:

```bash
pip install streamlit pandas
```

### Execução

Com o arquivo da aplicação e a base de dados na estrutura esperada pelo projeto, execute:

```bash
streamlit run dashboard_musical.py
```

## Estrutura esperada

```text
projeto/
├── dashboard_musical.py
├── Dados_Artistas.csv
└── README.md
```

## Contexto educacional e créditos

Este repositório registra a resolução de uma atividade prática proposta pelo professor **Mateus Sousa** ([@msousa07](https://github.com/msousa07)).

- **Proposta e orientação da atividade:** Mateus de Sousa — [@msousa07](https://github.com/msousa07).
- **Desenvolvimento da solução:** Miguel Henrique — [@GalvaoLabs](https://github.com/GalvaoLabs).

O projeto faz parte do meu registro de aprendizagem em Python, análise de dados e desenvolvimento de aplicações com Streamlit.

---

**Python · Pandas · Streamlit · Análise de dados**
