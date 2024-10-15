# Análise de Cancelamentos de Clientes

Este projeto realiza uma análise detalhada sobre os cancelamentos de clientes de uma empresa, com o objetivo de entender as razões por trás da alta taxa de cancelamentos e propor soluções para reduzir essa taxa.

## Problema
A empresa enfrenta uma alta taxa de cancelamento entre seus clientes. O objetivo desta análise é identificar padrões e fatores que levam ao cancelamento e testar possíveis soluções para reduzir esses índices.

## Dados
Os dados utilizados para esta análise estão no arquivo `cancelamentos.csv`, que contém as seguintes informações:

- **CustomerID**: ID único do cliente
- **idade**: Idade do cliente
- **sexo**: Gênero do cliente
- **tempo_como_cliente**: Duração de tempo que o cliente está com a empresa (em meses)
- **frequencia_uso**: Frequência de uso dos serviços
- **ligacoes_callcenter**: Número de ligações feitas para o call center
- **dias_atraso**: Dias de atraso no pagamento
- **assinatura**: Tipo de assinatura do cliente (e.g., Basic, Standard)
- **duracao_contrato**: Duração do contrato (e.g., Mensal, Trimestral, Anual)
- **total_gasto**: Total gasto pelo cliente
- **meses_ultima_interacao**: Meses desde a última interação com o cliente
- **cancelou**: Indicador se o cliente cancelou o serviço (1 para cancelado, 0 para ativo)

## Etapas da Análise
1. **Importação e Tratamento de Dados**:
   - Leitura e limpeza dos dados, removendo colunas irrelevantes e tratando valores nulos.
   
2. **Verificação das Taxas de Cancelamento**:
   - Análise inicial para identificar padrões de cancelamento, com destaque para clientes de contratos mensais.

3. **Simulações para Redução de Cancelamentos**:
   - **Remoção de Planos Mensais**: Simulação que resultou em uma redução de 7,1% na taxa de cancelamentos.
   - **Limitação de Chamadas ao Call Center**: Ajustes para reduzir a quantidade de ligações, resultando em uma redução de 27,4% nos cancelamentos.
   - **Ações para Clientes em Atraso**: Propostas para notificar clientes diariamente após 20 dias de atraso e oferecer desconto para pagamentos antecipados.

## Ferramentas Utilizadas
- **Python**: Para manipulação e análise de dados.
- **Pandas**: Manipulação e limpeza de dados.
- **Plotly Express**: Visualização de dados através de gráficos.
- **Jupyter Notebook**: Documentação e execução do código.

## Resultados
A análise identificou que clientes com contratos mensais eram mais propensos a cancelar, e várias simulações foram realizadas para reduzir essa taxa, resultando em propostas práticas para mitigação dos problemas identificados.

## Como Executar o Projeto
1. Clone este repositório:
git clone  https://github.com/FernandoKoch11/seu-repositorio.git

####2. Certifique-se de ter todas as bibliotecas necessárias instaladas:
####3. Execute o Jupyter Notebook para visualizar e modificar a análise:


## Autor
Fernando Koch - [WebSite](https://my-dev-site-ob7f.vercel.app/)
