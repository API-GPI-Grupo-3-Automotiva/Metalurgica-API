# 🚢 Análise do Comércio Exterior: Cadeia Metalúrgica (Usinagem)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Scrum](https://img.shields.io/badge/Scrum-0081A7?style=for-the-badge&logo=agile&logoColor=white)

**Estudo da Balança Comercial (2021-2025) nas cidades de Caçapava, Jacareí, São José dos Campos e Taubaté.** *Projeto Integrador I - Gestão de Produção Industrial | FATEC São José dos Campos*

---

# Índice
* [Sobre o Projeto](#Sobre-o-Projeto)
* [Tecnologias e Ferramentas](#Tecnologias-e-Ferramentas)
* [Equipe do Projeto](#Equipe-do-Projeto)
* [Orientadores](#Orientadores)
* [Principais Indicadores Globais (2021-2025)](#Principais-Indicadores-Globais-(2021-2025))
* [Insights e Conclusões Estratégicas](#Insights-e-Conclusões-Estratégicas)
* [Backlog do produto](#Product-Backlog)
* [Gantt](#Gantt)
* [Arquivo Google Colab](#Arquivo-Google-Colab)
* [Arquivo.csv de Importação e Exportação.](#Arquivo.csv-de-Importação-e-Exportação.)
* [Visualização dos Dashboards Importação, Exportação e balança comercial da Cadeia Produtiva (usinagem)](#Prints-Dashboards)
* [Dashboard Power BI](#Dashboard-(Power-BI))
* [Apresentação da XII Feira de soluções](#Apresentação-da-XII-Feira-de-soluções)
* [Relatório](#Relatório)
* [Registro das Sprints](#Registro-das-Sprints)

---

## Sobre o Projeto

Este projeto analisa os fluxos de importação e exportação da **cadeia produtiva metalúrgica**, especificamente no setor de **usinagem**. O estudo foca no impacto econômico regional do Vale do Paraíba, utilizando dados oficiais do sistema **Comex Stat (MDIC)**.

O objetivo foi transformar grandes volumes de dados brutos em inteligência estratégica, identificando o papel da usinagem como elo vital para os setores automotivo, aeroespacial e médico, além de diagnosticar o déficit estrutural da balança comercial regional e criar um Dashboard da "Cadeia Produtiva Metalúrgica".
* Analisar dados abertos do governo de exportação e importação da cadeia produtiva metalúrgica (usinagem).
* Analisar as cidades de Caçapava, São José dos Campos, Jacareí e Taubaté do estado de SP. 
* Indicar valores de importação e exportação, dos anos de (2021-2025).
* Top dez - Produtos da cadeia produtiva mais importados e exportados.
* Top dez - Maiores parceiros comerciais dessas cidades analisadas.
  
---

## Tecnologias e Ferramentas

- **Tratamento de Dados:** Python (Google Colab) utilizando bibliotecas para higienização de códigos NCM e SH4.
- **Visualização de Dados:** Microsoft Power BI (Criação de Dashboards interativos).
- **Gestão do Time:** Framework Ágil Scrum.
- **Fontes:** Comex Stat (Dados Governamentais).

---

## Equipe do Projeto

| Integrante | Função (Scrum) | LinkedIn | GitHub |
| :--- | :--- | :---: | :---: |
| **Anderson Santos** | Product Owner | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/santos-31473141) | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/SantosGuarilha) |
| **José Sérgio dos Santos** | Scrum Master | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jos%C3%A9-s%C3%A9rgio-dos-santos-a841ba36a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoseSergio414) |
| **Luis Carlos dos Santos** | Scrum Team |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luiscarlosjacare%C3%AD?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/orgs/API-GPI-Grupo-6-Metalurgica/people/cantiliolc-LuisCarlos) |
| **Sebastião Leandro** | Scrum Team | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/leandro-leandro-78a273387?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/sebastiao82) |

---

## Orientadores

**Prof. Rubens Barreto da Silva e Prof. Me. Marcus Vinícius do Nascimento.**

---

## Principais Indicadores Globais (2021 - 2025)

Os dados consolidados revelam um cenário de forte dependência externa na cadeia de usinagem regional:

* 📥 **Importação Total:** US$ 35,34 Bilhões (73,96% do fluxo).
* 📤 **Exportação Total:** US$ 12,44 Bilhões (26,04% do fluxo).
* ⚖️ **Saldo Comercial:** Déficit de **US$ 22,89 Bilhões**.
* 📦 **Volume Transacionado:** 5 Bilhões de KG importados contra 2 Bilhões de KG exportados.

---

## Insights e Conclusões Estratégicas

* **O "Vilão" do Déficit:** O item **Veios e Eixos (Árvores de Transmissão)** é o principal responsável pelo saldo negativo, com massiva importação vinda da China.
* **Destaque Positivo:** O segmento de **Partes Reconhecíveis** apresentou superávit, sendo o grande motor das exportações regionais.
* **Parceiros Comerciais:** 
    * 🇺🇸 **EUA:** Principal comprador do setor (US$ 3,7 Bi), sendo o caminho mais rápido para aumento de receita em dólar.
    * 🇨🇳 **China:** Maior fornecedor e maior fonte de déficit.
    * 🇲🇽 **México:** Único parceiro estratégico com o qual a região mantém uma relação comercial equilibrada/superavitária.
* **Alerta 2025:** As projeções indicam uma retração crítica de **27,29% nas exportações**, sugerindo a necessidade urgente de políticas de incentivo à competitividade internacional.

---

# Product Backlog

<img width="1256" height="1284" alt="image" src="https://github.com/user-attachments/assets/5aefad53-4685-4cba-bb25-f4db06fa129e" />

---

# Gantt

> Atividades realizadas pelos integrantes

<img width="1839" height="739" alt="Captura de tela 2025-12-04 181758" src="https://github.com/user-attachments/assets/54e284ee-3493-40a1-9ad5-04f5d2d90abc" />

> Link

https://github.com/API-GPI-Grupo-3-Automotiva/Metalurgica-API/blob/main/Docs/Novo%20Gantt.xlsx

---

# Arquivo Google Colab

<img width="1217" height="927" alt="image" src="https://github.com/user-attachments/assets/6cae3066-bdca-4a2f-abea-600f251e548c" />

**Primeiro passo - Dados exportação e tabelas auxiliares.**

>Link

https://colab.research.google.com/drive/1xmrA1FQHD_sVnGs5TDI1SR1zNOG8fqQh?usp=sharing

**Segundo passo - Juntando todos os dados de importação em um único arquivo e o mesmo para exportação.**
 
>Link

https://colab.research.google.com/drive/1UCa-sUD44SGleC2Q_fuByw4G_dOxTlQR?usp=drive_link

**Terceiro passo - Unindo todos em um único arquivo.**

>Link

https://colab.research.google.com/drive/11xS76rw55ZOBzjL-1zlrca465_SGmVLh?usp=drive_link

**Quarto passo - Criando uma coluna de valor para exportação, outra importação e uma para balança comercial.**

>Link

https://colab.research.google.com/drive/1UPbPGwr2CO3U8kikfb1ZwxlJU3VDV-wo?usp=drive_link

# Arquivo.csv de Importação e Exportação.

>Link

https://drive.google.com/file/d/1HefH3W592buE94sP21tCunExZTfiIpj0/view?usp=drive_link

---

## Visualização dos Dashboards Importação, Exportação e balança comercial da Cadeia Produtiva (usinagem)

> Dados importação, Exportação e balança Comercial

<img width="1439" height="807" alt="Captura de tela 2025-12-01 004349" src="https://github.com/user-attachments/assets/d4244194-deec-4640-b400-edb7f8c5b2bf" />

> Gráfico de KPI.

<img width="1434" height="802" alt="Captura de tela 2025-12-01 205914" src="https://github.com/user-attachments/assets/99bd32d2-e79a-402a-97ce-6fac5f710a03" />

> Dados mensais do ano de 2024 da cidade de (SJC)

<img width="1433" height="801" alt="Captura de tela 2025-12-01 004309" src="https://github.com/user-attachments/assets/582fce70-234a-4007-858c-45388cccdacf" />

> Parceiros comerciais e produtos comercializados.

<img width="1426" height="794" alt="Captura de tela 2025-12-01 004212" src="https://github.com/user-attachments/assets/09a7e08d-ce3c-49da-b688-b9e561ee60a8" />

> Gravação do Dashboard.
 
>Link

https://github.com/user-attachments/assets/3d0d2770-751f-4e12-8255-bb24acf0e7ed

---

# Dashboard (Power BI)

>Link

https://app.powerbi.com/view?r=eyJrIjoiYTdkYWViNDYtN2ViYi00ODVlLWFhYTktZjI1MGJiNWZmMGFjIiwidCI6ImNmNzJlMmJkLTdhMmItNDc4My1iZGViLTM5ZDU3YjA3Zjc2ZiIsImMiOjR9

---


# Apresentação da XII Feira de soluções

> Slides da apresentação

<img width="1919" height="1076" alt="Captura de tela 2025-12-03 210902" src="https://github.com/user-attachments/assets/69992510-9b41-40aa-97e3-f4c05b3d332a" />

>Link

https://github.com/API-GPI-Grupo-3-Automotiva/Metalurgica-API/blob/main/Docs/Modelo_Feira_Solucoes%202025-grupo_6_novo.pdf

---

# Relatório
<img width="558" height="785" alt="Captura de tela 2025-12-04 183223" src="https://github.com/user-attachments/assets/cd8cbfab-693a-4c2c-a30f-47c9893291f7" />

> Link

https://github.com/API-GPI-Grupo-3-Automotiva/Metalurgica-API/blob/main/Docs/Relat%C3%B3rio%20-%20Projeto%20Integrador.pdf

---

# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 06/10/2025 |  Concluído| [MVP](MVP/sp1.md)  |
| 02                | 10/11/2025 | Concluído | [MVP](MVP/sp2.md)  |
| 03                | 24/11/2025 | Concluído  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 04/12/2025 | A fazer | [MVP](#)|

---

*Este projeto faz parte da jornada de formação em Gestão da Produção Industrial, conectando análise de dados com a realidade do mercado global.*

---
