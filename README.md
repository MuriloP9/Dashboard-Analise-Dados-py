# Dashboard-Analise-Dados-py
Este projeto consiste em um dashboard interativo desenvolvido com Streamlit, voltado para a análise de salários na área de dados ao longo dos últimos anos. A aplicação permite explorar informações salariais de forma dinâmica, utilizando filtros inteligentes e visualizações claras para apoiar análises e tomadas de decisão.
Os dados são carregados diretamente de um dataset público e tratados com Pandas, enquanto as visualizações interativas são geradas com Plotly, garantindo uma experiência fluida e responsiva.

🚀 Funcionalidades

📅 Filtros dinâmicos por:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

📈 Métricas principais (KPIs):

Salário médio anual (USD)

Salário máximo

Total de registros

Cargo mais frequente

📊 Visualizações interativas:

Top 10 cargos com maior salário médio

Distribuição salarial (histograma)

Proporção dos tipos de trabalho (remoto, híbrido, presencial)

Mapa mundial com salário médio de Data Scientists por país

🧠 Tratamento inteligente de filtros vazios, exibindo mensagens amigáveis ao usuário em vez de erros técnicos

📋 Tabela detalhada com todos os dados filtrados

🛠️ Tecnologias Utilizadas

Python

Streamlit

Pandas

Plotly

CSV (dataset público)

🎯 Objetivo do Projeto

O objetivo deste projeto é praticar análise de dados, visualização interativa e desenvolvimento de dashboards,
simulando um cenário real de mercado. Ele demonstra boas práticas como:

organização de código,

tratamento de exceções,

foco em experiência do usuário (UX),

e apresentação clara de informações.

▶️ Como executar o projeto
# Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse a pasta do projeto
cd seu-repositorio

# Crie e ative o ambiente virtual
python -m venv .venv
source .venv/bin/activate  # Windows: 
.venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
streamlit run app.py
