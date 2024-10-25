# ANÁLISE PARA ALAVANCAGEM DE RECEITA - RESORT

![Imagem do Resort](https://digital.ihg.com/is/image/ihg/intercontinental-bali-9719167392-2x1)

## 1. Descrição do Projeto

O projeto de análise de dados para o resort tem como objetivo identificar e implementar estratégias que aumentem as receitas e reduzam a taxa de cancelamento de reservas. Dada a crescente competitividade no setor hoteleiro e as mudanças nas preferências dos consumidores, torna-se fundamental utilizar análises de dados para entender o comportamento dos clientes e otimizar as operações do resort.

O processo de análise começa com uma pesquisa de mercado, visando compreender os principais fatores que impulsionam o crescimento do setor, os KPIs relevantes e os problemas sistêmicos enfrentados. Com essa base, realiza-se uma análise exploratória dos dados, que permite mapear possíveis lacunas e oportunidades de melhoria. Em seguida, será construída uma árvore de hipóteses para investigar as causas dos cancelamentos e identificar potenciais alavancas para o aumento da receita anual.

## 2. Problema de Negócio e Objetivos

### 2.1 Qual o problema de negócio deste projeto?

No atual cenário de intensa competição por market share, a ascensão de plataformas online para a venda de reservas e a mudança no comportamento do público-alvo em resposta à ampla gama de opções disponíveis, o resort enfrenta desafios significativos. A taxa de cancelamento de reservas tem aumentado, enquanto a receita anual apresenta uma tendência de queda.

### 2.2 Quais são os objetivos e benefícios do projeto?

A principal tarefa deste projeto é identificar as causas subjacentes desse cenário preocupante. Para isso, nossos objetivos são:

**Objetivos:**

- Analisar os fatores que contribuem para o aumento da taxa de cancelamento, entendendo os motivos específicos que levam os hóspedes a cancelar suas reservas.
- Identificar oportunidades para melhorar a experiência do cliente, garantindo que o resort se destaque em um mercado cada vez mais competitivo.
- Desenvolver estratégias que aumentem a receita anual, explorando novas abordagens de marketing, pacotes e promoções que atendam às necessidades e preferências do público-alvo.

**Benefícios:**

- Fornecer uma compreensão mais clara dos fatores que afetam a taxa de cancelamento de reservas.
- Ajudar na formulação de estratégias que alavanquem a receita anual do resort.

### 2.3 Quais são os conceitos importantes a conhecer no contexto de ocupação imobiliária, mobilidade urbana, saneamento e assuntos correlatos?

**Conceitos Importantes:** (INSERIR AQUI OS CONCEITOS DOS INDICADORES RELEVANTES PARA O SEGMENTO HOTELEIRO)

Ao abordar esses desafios, o projeto busca não apenas reverter a tendência de queda na receita, mas também posicionar o resort como uma opção preferencial para os hóspedes, promovendo a fidelização e a satisfação do cliente.

- **Taxa de Ocupação de Imóveis:** Percentual de imóveis ocupados em relação ao total de imóveis disponíveis, influenciado por fatores como localização, tamanho e condições do imóvel.
- **Mobilidade Urbana:** Relaciona-se à facilidade com que os residentes podem se deslocar dentro da cidade, impactando a atratividade de uma localização para ocupação de imóveis.
- **Saneamento:** Refere-se à infraestrutura para gestão de resíduos e fornecimento de água limpa, afetando diretamente a qualidade de vida e, consequentemente, a taxa de ocupação dos imóveis.

## 3. Pipeline de Solução

- **Entendimento do Problema de Negócio:** Nesta etapa inicial, buscamos compreender profundamente os desafios enfrentados pelo resort, incluindo o aumento da taxa de cancelamento e a queda na receita. Isso envolve a definição clara dos objetivos do projeto e a identificação dos principais fatores que podem influenciar o comportamento dos clientes e os resultados financeiros.

- **Análise Exploratória dos Dados:** Realizamos uma análise detalhada dos dados disponíveis, investigando padrões de comportamento, sazonalidade e variáveis que possam impactar os cancelamentos de reservas e o desempenho financeiro. Essa análise preliminar nos ajudará a identificar possíveis correlações e hipóteses a serem validadas.

- **Preparação e Limpeza dos Dados:** Os dados coletados passam por um processo de preparação, que inclui limpeza, tratamento de valores ausentes e formatação para garantir sua integridade e usabilidade nas próximas etapas. Dados consistentes são essenciais para garantir a qualidade das análises e modelos subsequentes.

- **Modelagem dos Dados:** Nesta fase, utilizamos modelos estatísticos para testar as hipóteses levantadas durante a análise exploratória. O objetivo é identificar padrões e variáveis preditoras que possam explicar o comportamento de cancelamento e destacar oportunidades de aumento de receita.

- **Criação de Visuais e Indicadores:** Com base nas análises e modelagens, são desenvolvidos visuais claros e indicadores-chave (KPIs) que permitam uma visão objetiva dos resultados obtidos. Esses elementos serão utilizados para apresentar os principais insights de forma acessível e compreensível.

- **Storytelling e Apresentação aos Stakeholders:** Por fim, os insights obtidos serão estruturados em uma narrativa clara e coerente, alinhada aos objetivos de negócio do resort. A apresentação focará em fornecer recomendações práticas e estratégicas para os stakeholders, ajudando na tomada de decisões embasadas.

## 4. Tecnologias e Ferramentas

- Power BI
- Power Query
- DAX
- Power BI Helper
- Excel

## 5. Modelagem e Resultados

### Primeira Etapa: Validação dos Dados e Overview

Iniciei pela validação dos dados fornecidos pela equipe de gestão do resort. Após o entendimento do problema de negócio exposto nos tópicos acima, foi necessário identificar o motivo dos cancelamentos de reservas e averiguar possíveis alavancas na receita anual.

Com o problema de negócio em mãos e a base de dados disponibilizada, iniciei uma análise exploratória para validar os dados presentes na base, uma espécie de overview dos dados. Tracei algumas perguntas nesta primeira etapa, que compartilho aqui:

### Overview - Entendimento do Negócio

1. **O que é um resort?**  
   Estabelecimento de hospedagem que oferece uma experiência de férias completa, com diversos serviços de lazer e entretenimento inclusos, atendendo todas as necessidades do hóspede em um só local.

2. **Qual a diferença entre um resort e um hotel?**  
   O foco principal de um hotel é ser uma acomodação para dormir, enquanto o resort conta com diversos serviços adicionais e acomodações mais sofisticadas.

3. **O que é importante para uma empresa de resort?**  
   - Experiência do cliente (vínculo com a sua finalidade) como atendimento, qualidade das instalações e serviços de lazer.
   - Entender as preferências dos clientes para oferecer o melhor serviço.
   - Capacitação de funcionários para melhor atender os clientes.
   - Localização atraente para os clientes.
   - Marketing e parcerias para divulgação.
   - Reputação online (indicações vs. reclamações) que pode impactar na demanda.
   - Fidelização de clientes.
   - Diversificação de receita por meio de serviços e pacotes oferecidos, inclusive eventos corporativos.
   - Gestão operacional (controle de custos e maximização de demanda por meio de estratégias comerciais).

### Validação dos Dados

Segui então para a validação dos dados e cheguei a algumas conclusões:

- **Receita**
  
  1. **Por que existem valores negativos na receita_por_noite?**  
  Observou-se que se trata de um registro referente a um cliente recorrente, possivelmente atrelado a algum desconto. Este valor foi mantido na visão, pois não impacta significativamente no resultado final.

  2. **Por que temos tantas reservas sem pagamento (valor R$ 0)?**  
  Essa categoria corresponde a aproximadamente 96% de todas as reservas e 99% das reservas confirmadas, impactando diretamente no resultado da análise como um todo. Não há informações de desconto, e o maior volume é referente a clientes não recorrentes.

  3. **Oportunidades:**  
  Buscar mais informações sobre os motivos de um volume tão alto de reservas sem pagamento. Pode ser um erro ou uma estratégia de marketing para aumentar o volume de clientes e vendas, especialmente para atrair novos clientes com promoções de primeira reserva. Contudo, é necessário considerar o impacto financeiro dessas campanhas.

- **Desdobramento por Agência**

  1. **Por que existem reservas sem informação de agência?**  
  Dos 8.058 itens sem a informação de agência de turismo vinculada, a maioria está relacionada a segmentos diferentes de agências (Corporativo, Direta e Grupos).

- **Reservas e Estadia**

  1. **Por que temos reservas que não informam a quantidade de adultos, crianças e bebês?**  
  É necessário confirmar se isso é um erro, pois há 13 reservas nessa situação, que podem estar distribuídas entre as demais categorias de perfil. Esse dado não representa um impacto significativo e, por isso, não foi retirado da análise.

## Hipóteses e Oportunidades de Melhoria

Após a análise inicial da base de dados e possíveis insights, formulei algumas hipóteses para embasar a análise.

### Hipóteses

#### H1: Redução do Tempo de Antecedência entre a Reserva e o Check-in Diminui a Taxa de Cancelamentos?
- **Conclusão:** Falso. A redução do tempo de antecedência aumenta a taxa de cancelamentos devido à falta de planejamento.
- **Oportunidades:** Estruturar campanhas com desconto para reservas realizadas com uma maior antecedência.

#### H2: O Impacto da Previsibilidade de Cancelamentos da Reserva Está Relacionado ao Valor da Diária?
- **Conclusão:** Sim, pois observou-se que as diárias abaixo de R$ 200 são as que apresentam os maiores índices de cancelamento.
- **Oportunidades:** Rever estratégias de preço para o período e rever a política de preços para aumentar a atratividade e reduzir o índice de cancelamento.

#### H3: Reservas com Alimentação Têm Menor Taxa de Cancelamento
- **Conclusão:** Falso. Reservas com alimentação apresentam maior taxa de cancelamento.
- **Oportunidades:**  
  - Vincular à campanha de H1, oferecendo um upgrade de alimentação para reservas confirmadas até 30 dias antes do check-in.

#### H4: Reservas com Crianças Têm Maior Taxa de Cancelamento
- **Conclusão:** Verdadeiro.
- **Oportunidades:**  
  - Oferecer serviços voltados para crianças, como atividades do tipo "kids", semelhantes às oferecidas em hotéis da Disney, onde as crianças pedem para ir e influenciam as decisões dos pais.

#### H5: A Presença de Pedidos Especiais Está Associada a uma Maior Taxa de Cancelamento
- **Conclusão:** Falso. Pedidos especiais têm uma taxa de cancelamento menor, e clientes recorrentes apresentam ainda menos cancelamentos, uma vez que já conhecem o serviço.

#### H6: Quartos Mais Baratos Têm Menor Taxa de Cancelamento
- **Conclusão:** Verdadeiro. Quartos mais caros apresentam maiores taxas de cancelamento (ex.: categorias H e G).
- **Oportunidades:**  
  - Implementar ofertas de upsell para quartos mais baratos, como um upgrade do quarto X para o quarto Y com desconto de 5%, destacando os benefícios da troca (ex.: quarto mais confortável).

### Oportunidades Adicionais para Reduzir Cancelamentos

1. **Revisar Políticas de Reserva:**  
   Considerar que reservas realizadas com menos de 7 dias de antecedência precisem ter valores pagos no momento da reserva, protegendo parte da receita em casos de cancelamento ou no-show.

2. **Estruturar um Programa de Fidelidade:**  
   Oferecer benefícios para clientes que realizarem 5 ou 10 reservas sem cancelamento.

3. **Revisar Contratos com Agências de Turismo:**  
   Avaliar o aumento das taxas para agências com maior taxa de cancelamento, incentivando uma melhor gestão das reservas.

### Receita

### Qual é a Tendência da Receita? Está Aumentando ou Caindo?
- Observou-se que a receita cai entre os meses de setembro a novembro, aumenta em dezembro, cai em janeiro e cresce de fevereiro a agosto. Apesar das sazonalidades observadas, durante todo o período houve um aumento na receita.

### Qual é o Ticket Médio de Estadia (Receita Média por Estadia)?
- R$ 302,13.
- **Oportunidades:**  
  - Explorar e melhorar a experiência do segmento AT Online, que apresenta o maior volume de receitas, reservas e cancelamentos. O foco deve ser na redução de cancelamentos e no aumento da receita.  
  - Analisar padrões de cancelamento, ajustar políticas e atendimento, além de criar campanhas de vendas direcionadas a esse público com maior potencial de consumo.

### Qual é o Segmento que Mais Contribui com a Receita?
- O segmento AT Offline é o que mais contribui, com a normalidade das reservas variando entre R$ 157 e R$ 710 (considerando apenas a receita de reservas confirmadas).

### Outros Insights sobre a Receita
1. **Receita:**  
   - O segmento "2-0-0" apresenta o maior volume de reservas, mas não é o perfil responsável pela maior contribuição em termos de receita.

### Cancelamentos

### Qual é a Tendência dos Cancelamentos? Estão Aumentando ou Diminuindo?
- Observou-se que os cancelamentos estão aumentando ao longo do período de análise e acompanham o aumento da receita.
- Existem dois tipos de cancelamentos, mas o "no-show" tem pouca representatividade; por isso, não foram feitas análises específicas para esse tipo.

### Qual Segmento Mais Cancela?
- O segmento que mais cancela é o AT Online.
- Há um volume muito alto de cancelamentos sem pagamento prévio.
- O Produto A, que é o mais barato, também é o que mais apresenta cancelamentos.

## Oportunidades

- **Revisar Políticas de Cancelamento:**  
  - Reavaliar as políticas para reduzir o número de reservas canceladas, com foco nos segmentos Grupos e AT Online, que apresentam o maior índice de cancelamentos.

- **Oferecer Incentivos para Manter a Reserva:**  
  - Implementar flexibilização de tarifas e ofertas de última hora para incentivar a manutenção das reservas.

### Análise das Possíveis Alavancas de Crescimento da Receita

### Reservas e Estadia

### Qual é o Tempo Médio Entre a Reserva e a Atualização de Status (Confirmada ou Cancelada)?
- **Reservas Confirmadas:** Normalidade entre 8 (Q1) e 138 (Q3) dias, com mediana de 43 dias.
- **Reservas Canceladas:** Normalidade entre 6 (Q1) e 88 (Q3) dias, com mediana de 26 dias.

### Qual é o Tempo Médio Entre a Reserva e a Estadia (Check-in)?
- **Reservas Confirmadas:** Normalidade entre 5 (Q1) e 138 (Q3) dias, com mediana de 38 dias.
- **Reservas Canceladas:** Normalidade entre 54 (Q1) e 235 (Q3) dias, com mediana de 102 dias.
- Observou-se que quem confirma faz o processo de reserva antes daqueles que cancelam.

### Qual Segmento Cancela Mais Próximo da Reserva?
- O segmento Corporativo tende a cancelar mais próximo da data de reserva.

### Qual é o Tempo Médio de Estadia?
- **Geral:** Normalidade entre 2 (Q1) e 6 (Q3) dias, com mediana de 3 dias.
- **Diferença por Segmento:**
  - **Maior Estadia:** AT Offline (mediana de 7 dias).
  - **Menor Estadia:** Corporativo (mediana de 1 dia).

### Existe Diferença Entre o Tempo Médio de Estadia por Perfil de Cliente?
- **Sim.**
  - **Maior Estadia:** Perfil 2-0-0 (mediana de 4 dias).
  - **Menor Estadia:** Perfil 1-2-1.

### Demanda

### Existe um Período de Maior Demanda?
- **Dia do Mês:** 12 (check-in) e 29 (check-out).
- **Dia da Semana:** Sábado (check-in) e Domingo (check-out).
- **Meses de Alta Demanda:** Abril, Maio e Outubro (acima do percentil 75 e padrão anual de alta).

- **Oportunidades:**
  - Aumentar tarifas durante os períodos de alta demanda (impacto: aumento de preço e receita).
  - Incentivar a venda de serviços adicionais (upgrade de quarto, pacotes de alimentação) para perfis com maior propensão a gastar, como 2-0-0 (casais - maior ticket médio).

### Qual é o Perfil de Cliente que Mais Consome Nossos Serviços?
1. **Dois Adultos:** 70% do Pareto, com 27.942 reservas, sendo o maior volume no segmento AT Online (13.107 reservas).
2. **Um Adulto:** 87% do Pareto, com 6.923 reservas, sendo o maior volume no segmento AT Online (1.762 reservas).
   - **Observação:** O maior volume de reservas é sem filhos, indicando preferência por instalações que atendam a esse público.

### Qual é o Ticket Médio de Estadia por Perfil de Cliente?
1. **Dois Adultos:** R$ 309,73.
2. **Um Adulto:** R$ 136,60.
   - **Observação:** Casais tendem a gastar mais (maior ticket).

### Qual é o Nosso Produto Mais Vendido?
- **Produto A (mais barato):** Indicativo de que o fator determinante para a compra é o preço.

### Qual é o Segmento que Mais Consome Nossos Serviços?
- **AT Online:** Preferência por quartos do tipo A e alimentação do tipo BB.

### Existe Diferença Entre o Produto Mais Vendido por Segmento?
- **Sim.**
  - **Tipo de Quarto:**
    - Quarto A: 23.279 reservas (9.002 AT Online).
    - Quarto D: 7.416 reservas (3.512 AT Online).
    - Quarto E: 4.960 reservas (2.743 AT Online).
  - **Alimentação:**
    - BB: 29.840 reservas (14.757 AT Online).
    - HB: 8.027 reservas (2.901 AT Online).

### Existe Diferença Entre o Produto Mais Vendido por Tipo de Cliente?
- **Sim.**
  - **Tipo de Quarto:**
    - Quarto A: 23.279 reservas (15.976 perfil 2-0-0).
    - Quarto D: 7.416 reservas (6.287 perfil 2-0-0).
    - Quarto E: 4.960 reservas (4.277 perfil 2-0-0).
  - **Alimentação:**
    - BB: 29.840 reservas (20.538 perfil 2-0-0).
    - HB: 8.027 reservas (5.942 perfil 2-0-0).

- **Oportunidades:**
  - Incentivar a venda de serviços adicionais para perfis com maior propensão a gastar, como upgrades e pacotes especiais.

## 6.Conclusão Final

A análise dos dados revela um problema de qualidade no serviço prestado, evidenciado pela baixa taxa de retenção, mesmo entre clientes com maior volume de reservas. Isso sugere uma dificuldade em fidelizar os hóspedes, o que pode estar impactando diretamente o crescimento sustentável da receita.

Além disso, identificou-se que o principal fator que atrai clientes para este resort é o preço. Há uma preferência clara por reservas em quartos de menor custo, como o quarto A, o que indica que a proposta de valor está mais alinhada a um perfil de hotel econômico do que a um resort de luxo. O padrão de consumo não aponta para uma demanda por serviços adicionais de alto valor, como massagens ou eventos de lazer, nem há sinais de uma forte atração para famílias.

### Oportunidades de Melhoria

Para abordar essas questões e melhorar a experiência do cliente, recomenda-se a implementação de uma pesquisa de Net Promoter Score (NPS) para avaliar a satisfação dos hóspedes e identificar pontos de melhoria. Além disso, a análise das reclamações em canais como o "Reclame Aqui" pode fornecer insights valiosos para ajustes nos processos e aprimoramento dos serviços oferecidos.

Essas iniciativas podem ajudar a alinhar a proposta de valor do resort às expectativas dos clientes, além de aumentar a retenção e a fidelização, melhorando a qualidade percebida e, consequentemente, a receita.
