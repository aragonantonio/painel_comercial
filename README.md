Dashboard comercial com dados fictícios da empresa também fictícia Prumo Gestão Empresarial. Nenhum dado real foi compartilhado para a criação desse projeto.  

Painel Comercial - Prumo Gestão Empresarial

Este repositório contém um painel comercial estático desenvolvido para a Prumo Gestão Empresarial, utilizando dados fictícios coletados até 09/11/2026. O objetivo do dashboard é monitorar a saúde do funil de vendas, avaliar o desempenho da equipe e analisar a eficiência de estratégias de abordagem.

📊 Estrutura e Apresentação dos Dados

O painel é dividido em seções estratégicas que cobrem desde a captação do lead até o fechamento do negócio:

1. Filtros Globais

Permitem segmentar as análises de todo o painel (com exceção do Teste A/B) por:
• Período de entrada do lead: Todo o período, últimos 6 meses ou últimos 3 meses.
• Segmento: Nicho de atuação do cliente.
• Origem: Canal por onde o lead chegou.

2. Visão Geral do Funil e Volume

• Funil Comercial: Apresenta a quebra de conversão visual de cada etapa do processo de vendas.
• Leads e Ganhos por Mês: Gráfico temporal baseado no mês de entrada do lead. Uma barra cinza rastreia o volume de novos leads, enquanto a barra verde monitora os negócios convertidos (ganhos).

3. Perfil do Cliente (Demografia dos Leads)

• Origem do Lead: Identifica os canais de marketing ou prospecção mais eficientes.
• Segmento: Mostra quais setores do mercado concentram o maior volume de leads ou receita.

4. Eficiência Operacional e Produtividade

• Tempo até o Primeiro Contato: Analisa a velocidade do time de atendimento e o impacto disso na taxa de qualificação do grupo.
• SDRs (Sales Development Representatives): Rastreia e compara a taxa de qualificação individual de leads por pré-vendedor.
• Closers (Vendedores): Mede a eficiência de fechamento apresentando a taxa de ganhos calculada sobre propostas que já tiveram uma decisão final.
• Negócios Parados há mais de 60 dias: Alerta de gargalos ou leads frios que precisam de atenção ou descarte no CRM.

5. Experimentos e Governança de Dados

• Teste A/B (Mensagem de Abertura no WhatsApp): Seção isolada baseada em um histórico fixo de 3.000 envios (maio a julho de 2026). Avalia três abordagens:
	• A: Apresentação genérica.
	• B: Pergunta focada na dor do cliente.
	• C: Texto longo explicativo.
• Qualidade dos Dados: Um indicador que exibe o volume de campos vazios nos negócios ativos do filtro, ajudando a garantir a higiene do CRM.
