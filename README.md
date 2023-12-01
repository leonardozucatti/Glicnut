# GLICNUT - MODELO COMPUTACIONAL PARA ACOMPANHAMENTO DE PACIENTES COM DIABETES BASEADO EM ANÁLISE DE GLICEMIA E NUTRIÇÃO 

Este é um sistema Python para acompanhar pacientes com diabetes, registrar informações sobre suas refeições, prever os níveis de glicemia e recomendar materiais educacionais.

## Descrição

O sistema utiliza uma base de dados SQLite (`glicnut.db`) para armazenar informações sobre os usuários, como CPF, tipo de refeição, níveis de glicemia e alimentos consumidos. Além disso, lê dados históricos de um arquivo CSV (`historical_data.csv`) para prever os níveis futuros de glicemia com base nos alimentos consumidos.

## Funcionalidades

- **Cadastro de Usuários:** Permite cadastrar novos usuários pelo CPF.
- **Registro de Refeições:** Registra as refeições dos usuários, incluindo glicemia, tipo de refeição e alimentos consumidos.
- **Previsão de Glicemia:** Com base nos dados históricos e nas refeições registradas, prevê os níveis futuros de glicemia do usuário.
- **Recomendação de Materiais:** Recomenda materiais educacionais com base nos contextos identificados como alto índice de glicemia, e falta de rotina nas medições.

## Requisitos

- Python 3.x
- Bibliotecas Python:
  - `implicit`
  - `sqlalchemy`
  - `pandas`
  - `numpy`
  - `scikit-learn`

## Uso

1. **Instalação de Dependências:**
   ```bash
   pip install implicit sqlalchemy pandas numpy scikit-learn
