# Python Insights: Analisando dados com python
    Segunda aula da Jornada Python da Hashtag Programação utilizando Python e Jupyter Notebook

# Desafio
    Foi percebido que a maior parte dos clientes na base de dados são clientes inativos, ou seja, que cancelaram o serviço, precisa-se saber o motivo dos cancelamentos e quais ações podem ser realizadas para diminuir esses cancelamentos ou evitá-los.

# Base de dados
Colunas:
- float CustomerID
- float idade
- string sexo (Female, Male)
- float tempo_como_cliente
- float frequencia_uso
- float ligacoes_callcenter
- float dias_atraso
- string assinatura (Basic, Standard, Premium)
- string duracao_contrato (Monthly, Quaterly, Annual)
- float total_gasto
- float meses_ultima_interacao
- float cancelou (1.0 = sim, 0.0 = não)

# Bibliotecas utilizadas

- pandas
- plotly
- nbformat
- ipykernel

## Bibliotecas extras
- matplotlib
- seaborn

# Passos
- Passo 1: Importar a base de dados
- Passo 2: Visualizar a base de dados
    - Entender a base de dados
    - Verificar os erros na base de dados
        - Visualizando a tabela
        - Descrição das colunas (Contagem, média, desvio padrão, min, quartis, max)
        - Informações da tabela (Tipos das colunas e números não-nulos)
- Passo 3: Tratamento dos dados
    - Excluir colunas que não tem valor
    - Corrigir erros no formato da tabela
    - Corrigir valores vazios
    - Corrigir duplicatas
- Passo 4: Análise inicial
    - Descobrir o percentual e quantidade de clientes que cancelaram e que não cancelaram
- Passo 5: Análise de causas do cancelamento dos clientes
    - Impacto das colunas na quantidade de cancelamentos
        - Criação de gráficos de histograma para cada coluna, separando por cor com base se cancelou ou não
    - Criar respostas com base na análise dos gráficos de histograma e perguntas ou soluções de como resolver os problemas vistos 
    - Criar a diferença da quantidade de cancelamentos, caso o problema seja resolvido

- Extra:
    - Análise de relações lineares com gráfico de correlação utilizando seaborn + matplotlib