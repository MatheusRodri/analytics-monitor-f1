# 🏎️ F1 Data Pipeline & Analytics

## 📋 Summary

- [📖 About Project](#about-project)
- [🛠️ Technologies used](#technologies-used)
- [🏗️ Achitecture](#architecture)
- [🚀 How to run](#how-to-run)
- [👨‍💻 Authors](#authors)

## 📖 About Project <a id="about-project"></a>

The project automatically extracts data from the FastF1 library, transforms it and stores it in a structured format for analysis. The data is then analyzed to provide insights into driver performance, team strategies, and race-related metrics.

## 🛠️ Technologies used <a id="technologies-used"></a>

- Python
    - FastF1
    - Pandas
- Power BI

## 🏗️ Achitecture <a id="architecture"></a>

```mermaid
graph LR
    A[🏎️ FastF1 ] -->| Ingestion | B(🐼 Pandas )
    
    
    style A fill:#8B0000,stroke:#333,stroke-width:2px,color:#fff
    style B fill:#FFFF00,stroke:#333,stroke-width:2px,color:#000
```
## 🚀 How to run <a id="how-to-run"></a>

This project can be run in two ways: using Databricks or locally.
- Locally:
    - Clone the repository
    - Open the project in terminal
    - Execute the followings commands:
        - Create a virtual environment: `python -m venv .venv`
        - Activate the virtual environment:
            - Windows: `.venv\Scripts\activate`
            - Linux/Mac: `source .venv/bin/activate`
        - Install the dependencies: `pip install -r requirements.txt`
    - Run the `data.ipynb` notebook to extract and transform the data
- Databricks:


## 👨‍💻 Authors <a id="authors"></a>

[Matheus Rodrigues](hhttps://www.linkedin.com/in/matheus-rodrigues-mrj/)

Ideias
Posição de largada (Grid) vs. Posição final de chegada.

Tempos de volta corrida a corrida (Ritmo de prova / Race pace).

Estratégia de pneus (qual composto foi usado e em quais voltas).

Tempo gasto nos Pit Stops e quantidade de paradas.

Velocidade máxima atingida por cada piloto na pista (Speed trap).

Status final do carro (Se completou a prova, bateu, quebrou o motor, etc.).

Diferença de tempo exata de cada piloto para o Pole Position (Gap to Pole) no Q1, Q2 e Q3.

Confronto direto (Head-to-head) de posições de largada apenas entre companheiros da mesma equipe.

Temperatura do ar e do asfalto ao longo da corrida (ajuda a explicar o desgaste dos pneus).

Ocorrência de chuva ou variação de umidade (crucial para cruzar com o momento em que os pilotos trocam para pneus intermediários ou de chuva extrema).

Piloto dono da volta mais rápida da corrida (Fastest Lap), que rende um ponto extra.

Quantidade de voltas passadas sob intervenção de Safety Car ou Virtual Safety Car (VSC).

Melhores tempos por setor (Setor 1, Setor 2 e Setor 3) para identificar qual carro domina trechos de alta velocidade vs. trechos sinuosos.