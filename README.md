# ANÁLISE PARA ALAVANCAGEM DE RECEITA - RESORT
![[[https__img migalhas com br__SL__gf_base__SL__empresas__SL__MIGA__SL__imagens__SL__2023__SL__02__SL__15__SL__d90cd13d-88c0-4f57-9aa5-c7878b109c0b jpg _PROC_CP65]](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6k0-dpN0QUyCWO8IjsvHIBtsMudn7XXcqfw&s)(https://github.com/user-attachments/assets/bff56a72-8584-40f8-b0a9-412dd4347128)](https://digital.ihg.com/is/image/ihg/intercontinental-bali-9719167392-2x1)
# 1. Descrição do projeto

O projeto de análise de dados para o resort tem como objetivo identificar e implementar estratégias que aumentem as receitas e reduzam a taxa de cancelamento de reservas. Dada a crescente competitividade no setor hoteleiro e as mudanças nas preferências dos consumidores, torna-se fundamental utilizar análises de dados para entender o comportamento dos clientes e otimizar as operações do resort.

O processo de análise começa com uma pesquisa de mercado, visando compreender os principais fatores que impulsionam o crescimento do setor, os KPIs relevantes e os problemas sistêmicos enfrentados. Com essa base, realiza-se uma análise exploratória dos dados, que permite mapear possíveis lacunas e oportunidades de melhoria. Em seguida, será construída uma árvore de hipóteses para investigar as causas dos cancelamentos e identificar potenciais alavancas para o aumento da receita anual.


# 2. Problema de negócio e objetivos
### 2.1 Qual o problema de negócio deste projeto?

No atual cenário de intensa competição por market share, a ascensão de plataformas online para a venda de reservas e a mudança no comportamento do público-alvo em resposta à ampla gama de opções disponíveis, o resort enfrenta desafios significativos. A taxa de cancelamento de reservas tem aumentado, enquanto a receita anual apresenta uma tendência de queda.

### 2.2 Quais são os objetivos e benefícios do projeto?
A principal tarefa deste projeto é identificar as causas subjacentes desse cenário preocupante. Para isso, nosso objetivo é:

**Objetivos:**
- Analisar os fatores que contribuem para o aumento da taxa de cancelamento, entendendo os motivos específicos que levam os hóspedes a cancelar suas reservas.
- Identificar oportunidades para melhorar a experiência do cliente, garantindo que o resort se destaque em um mercado cada vez mais competitivo
- Desenvolver estratégias que aumentem a receita anual, explorando novas abordagens de marketing, pacotes e promoções que atendam às necessidades e preferências do público-alvo.

**Benefícios:**
- Fornecer uma compreensão mais clara dos fatores que afetam a taxa de cancelamento de reservas.
- Ajudar na formulação de estratégias que alavanquem a receita anual do resort.
- 

### 2.3 Quais são os conceitos importantes a conhecer no contexto de ocupação imobiliária, mobilidade urbana, saneamento e assuntos correlatos?

**Conceitos Importantes:** (INSERIR AQUI OS CONCEITOS DOS INDICADORES RELEVANTES PARA O SEGMENTO HOTELEIRO)
Ao abordar esses desafios, o projeto busca não apenas reverter a tendência de queda na receita, mas também posicionar o resort como uma opção preferencial para os hóspedes, promovendo a fidelização e a satisfação do cliente.

- **Taxa de Ocupação de Imóveis:** Percentual de imóveis ocupados em relação ao total de imóveis disponíveis. Influenciado por fatores como localização, tamanho e condições do imóvel.
- **Mobilidade Urbana:** Relaciona-se à facilidade com que os residentes podem se deslocar dentro da cidade. Impacta a atratividade de uma localização para ocupação de imóveis.
- **Saneamento:** Refere-se à infraestrutura para gestão de resíduos e fornecimento de água limpa. Afeta diretamente a qualidade de vida e, consequentemente, a taxa de ocupação dos imóveis.
  
# 3. Pipeline de solução

- **Entendimento do Problema de Negócio**: Nesta etapa inicial, buscamos compreender profundamente os desafios enfrentados pelo resort, incluindo o aumento da taxa de cancelamento e a queda na receita. Isso envolve a definição clara dos objetivos do projeto e a identificação dos principais fatores que podem influenciar o comportamento dos clientes e os resultados financeiros.

- **Análise Exploratória dos Dados**: Realizamos uma análise detalhada dos dados disponíveis, investigando padrões de comportamento, sazonalidade e variáveis que possam impactar os cancelamentos de reservas e o desempenho financeiro. Essa análise preliminar nos ajudará a identificar possíveis correlações e hipóteses a serem validadas.

- **Preparação e Limpeza dos Dados**: Os dados coletados passam por um processo de preparação, que inclui limpeza, tratamento de valores ausentes e formatação para garantir sua integridade e usabilidade nas próximas etapas. Dados consistentes são essenciais para garantir a qualidade das análises e modelos subsequentes.

- **Modelagem dos Dados**: Nesta fase, utilizamos modelos estatísticos para testar as hipóteses levantadas durante a análise exploratória. O objetivo é identificar padrões e variáveis preditoras que possam explicar o comportamento de cancelamento e destacar oportunidades de aumento de receita.

- **Criação de Visuais e Indicadores**: Com base nas análises e modelagens, são desenvolvidos visuais claros e indicadores-chave (KPIs) que permitam uma visão objetiva dos resultados obtidos. Esses elementos serão utilizados para apresentar os principais insights de forma acessível e compreensível.

- **Storytelling e Apresentação aos Stakeholders**: Por fim, os insights obtidos serão estruturados em uma narrativa clara e coerente, alinhada aos objetivos de negócio do resort. A apresentação focará em fornecer recomendações práticas e estratégicas para os stakeholders, ajudando na tomada de decisões embasadas.

# 4. Tecnologias e ferramentas

- Power BI
- Power Query
- DAX
- Power BI Helper
- Excel

# 5. Modelagem e resultados

## Primeira Etapa: Validação dos Dados e Overview

Comecei pela validação dos dados fornecidos pela equipe de gestão do resort. Após o entendimento do problema de negócio exposto nos tópicos acima, foi necessário identificar o motivo dos cancelamentos de reservas e averiguar possíveis alavancas na receita anual.

Com o problema de negócio em mãos e a base de dados disponibilizada, iniciei uma análise exploratória para validar os dados presentes na base, uma espécie de overview dos dados. Tracei algumas perguntas nesta primeira etapa, que compartilho aqui:

### Overview - Entendimento do Negócio

1. **O que é um resort?**  
   Estabelecimento de hospedagem que oferece experiência de férias completa (diversos serviços de lazer e entretenimento incluídos, o hóspede tem todas as necessidades atendidas em um só local).

2. **Qual a diferença entre um resort e um hotel?**  
   O foco principal de um hotel é ser uma acomodação para dormir, enquanto o resort conta com diversos serviços adicionais e acomodações mais sofisticadas.

3. **O que é importante para uma empresa de resort?**  
   - Experiência do cliente (vínculo com a sua finalidade) como atendimento, qualidade das instalações e serviços de lazer.
   - Entender as preferências dos clientes (para oferecer o melhor serviço).
   - Capacitação de funcionários (para melhor atender os clientes).
   - Localização (tem que ser atraente para os clientes).
   - Marketing e parcerias (divulgação).
   - Reputação online (indicações x reclamações - pode impactar na demanda).
   - Fidelização de clientes.
   - Diversificação de receita por meio de serviços e pacotes oferecidos, inclusive eventos corporativos.
   - Gestão operacional (controle de custos e maximização de demanda por meio de estratégias comerciais).

### Validação dos Dados

Segui então para a validação dos dados e cheguei a algumas conclusões:

- **Receita**

1. **Por que existem valores negativos na `receita_por_noite`?**  
   Foi observado que se trata de um registro referente a um cliente recorrente, que pode estar atrelado a algum desconto. Mantido na visão, pois não tem grande impacto no resultado final.

2. **Por que temos tantas reservas sem pagamento (valor R$ 0)?**  
   Corresponde a aproximadamente 96% de todas as reservas e 99% das reservas confirmadas, ou seja, tem impacto direto no resultado dessa análise como um todo. Não há informações de desconto, e o maior volume é referente a clientes não recorrentes.

3. **Oportunidades:**  
   Buscar mais informações sobre os motivos de termos um volume tão alto de reservas sem pagamento. Pode ser um erro ou um movimento estratégico de marketing e comercial para aumentar o volume de clientes e vendas, especialmente para trazer novos clientes para a base com promoções de primeira reserva. Contudo, pode não estar sendo considerado o impacto financeiro dessas campanhas.

- **Desdobramento por Agência**

1. **Por que existem reservas sem informação de agência?**  
   Dos 8.058 itens sem a informação de agência de turismo vinculada, a maioria desses itens em branco está relacionada a segmentos diferentes de agências (Corporativo, Direta e Grupos).

- **Reservas e Estadia**

1. **Por que temos reservas que não informam a quantidade de adultos, crianças e bebês?**  
   É necessário confirmar se é um erro, pois há 13 reservas nessa situação, que podem estar distribuídas entre as demais categorias de perfil. Não representa um impacto significativo e, por isso, não foi retirado da análise.

## Hipóteses e Oportunidades de Melhoria

Após a análise inicial da base de dados e possíveis insights, formulei algumas hipóteses para embasar a análise.

### Hipóteses

#### H1: Redução do Tempo de Antecedência entre a Reserva e o Check-in Diminui a Taxa de Cancelamentos?
- **Conclusão:** Falso, a redução do tempo de antecedência aumenta a taxa de cancelamentos (devido à falta de planejamento).

- **Oportunidades:**  
  - Estruturar campanhas com desconto para reservas feitas com maior antecedência (relacionado à H3).

<img src="imagens/Captura de tela 2024-10-22 211408.png" alt="Produtos" width="700" />

#### H2: Clientes Recorrentes Têm Menor Taxa de Cancelamento
- **Conclusão:** Verdadeiro. Clientes recorrentes tendem a gostar do serviço e se programam melhor.

- **Oportunidades:**  
  - Para não recorrentes: Implementar comunicações direcionadas para lembrar da reserva.  
  - Para clientes recorrentes: Criar campanhas de desconto para a segunda reserva.

#### H3: Reservas com Alimentação Têm Menor Taxa de Cancelamento
- **Conclusão:** Falso, reservas com alimentação apresentam maior taxa de cancelamento.

- **Oportunidades:**  
  - Vincular à campanha de H1 (oferecer um upgrade de alimentação para reservas confirmadas até 30 dias antes do check-in).

#### H4: Reservas com Crianças Têm Maior Taxa de Cancelamento
- **Conclusão:** Verdadeiro.

- **Oportunidades:**  
  - Oferecer serviços voltados para crianças (ex.: atividades do tipo "kids", como em hotéis na Disney, onde as crianças pedem para ir e influenciam os pais).

#### H5: A Presença de Pedidos Especiais Está Associada a uma Maior Taxa de Cancelamento
- **Conclusão:** Falso, pedidos especiais têm uma taxa de cancelamento menor, e clientes recorrentes têm ainda menos cancelamentos (vantagem: o cliente já conhece o serviço).

#### H6: Quartos Mais Baratos Têm Menor Taxa de Cancelamento
- **Conclusão:** Verdadeiro, quartos mais caros apresentam maiores taxas de cancelamento (ex.: categorias H e G).

- **Oportunidades:**  
  - Implementar ofertas de upsell para quartos mais baratos (ex.: upgrade do quarto X para o quarto Y com desconto de 5%), destacando os benefícios da troca (ex.: quarto mais confortável).

### Oportunidades Adicionais para Reduzir Cancelamentos

1. **Revisar Políticas de Reserva:**  
   Considerar que reservas realizadas com menos de 7 dias de antecedência precisam ter valores pagos no momento da reserva, protegendo parte da receita em casos de cancelamento ou no-show.

2. **Estruturar um Programa de Fidelidade:**  
   Oferecer benefícios para clientes que realizarem 5 ou 10 reservas sem cancelamento.

3. **Revisar Contratos com Agências de Turismo:**  
   Avaliar o aumento das taxas para agências com maior taxa de cancelamento, incentivando uma melhor gestão das reservas.

   

