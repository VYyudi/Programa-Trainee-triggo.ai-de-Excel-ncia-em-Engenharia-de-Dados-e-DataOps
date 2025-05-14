# Programa Trainee triggo.ai - Excelência em Engenharia de Dados e DataOps
# 1. Análise Exploratória de Dados
# Volume de Pedidos por Mês
A análise do volume de pedidos ao longo do tempo mostra variações sazonais, com picos em novembro e dezembro (Natal e Black Friday).

# Distribuição do Tempo de Entrega (delivery_time)
O histograma revela que a maioria dos pedidos é entregue em até 20 dias, com concentração entre 1 e 10 dias. Há uma cauda longa, com poucos casos de entregas acima de 200 dias, indicando que atrasos extremos são exceção.

# Valor do Frete vs Distância Cliente-Vendedor
O gráfico de dispersão indica que o valor do frete tende a aumentar com a distância, mas não de forma linear. A maioria dos pedidos está concentrada em até 2.000 km e frete abaixo de R$ 150. Outliers mostram que outros fatores além da distância influenciam o valor do frete.

# Categorias de Produtos Mais Vendidas (Faturamento)
* Líder: beleza_saude (acima de R$ 1.200.000)

* Destaques: relogios_presentes (> R$ 1.000.000), cama_mesa_banho

* Diversidade: Top 10 inclui esporte_lazer, informatica_acessorios, moveis_decoracao, entre outros.

* Potencial de crescimento: moveis_decoracao, cool_stuff, utilidades_domesticas, automotivo, ferramentas_jardim.

# Insights Estratégicos:
Investir nas categorias líderes, promover intermediárias e explorar nichos com campanhas segmentadas.

# Estados com Maior Valor Médio de Pedido
* Paraíba (PB)

* Acre (AC)

* Amapá (AP)

Esses estados apresentam valores médios mais altos, possivelmente devido à distância logística ou ao tipo de produto.
# Taxa de retenção
Nenhum cliente recorrente registrado:

A taxa de clientes recorrentes está em 0%, o que significa que nenhum cliente fez mais de uma compra ou interação registrada.

Possíveis causas para a ausência de clientes recorrentes:

* Produto ou serviço não incentiva recompra: Pode ser que o produto ou serviço seja de compra única, ou que não tenha um apelo para que o cliente volte.

* Problemas na experiência do cliente: Atendimento, qualidade, preço ou outros fatores podem estar desestimulando a fidelização.

* Falta de estratégias de retenção: Não há programas de fidelidade, descontos para clientes antigos, comunicação pós-venda, etc.


# 2. Visualização e Dashboards
# Relatório de Vendas por Categoria no Estado de SP
* Crescimento Geral: Tendência de crescimento nas vendas, com pico entre o final de 2017 e início de 2018.

* Destaques por Categoria:

* beleza_saude: Crescimento consistente, pico em agosto/2018 (> R$ 50.000/mês).

* cama_mesa_banho: Forte entre 2017-2018, depois perdeu força.

* informatica_acessorios: Cresceu até 2018, depois caiu.

* relogios_presentes: Picos expressivos, mas volátil.

* esporte_lazer e moveis_decoracao: Crescimento modesto.

# Análise de Satisfação do Cliente
# Avaliação do Cliente x Tempo de Entrega
Relação inversa entre tempo de entrega e avaliação do cliente.

* Notas baixas (1 e 2): Tempos de entrega mais altos e dispersos.

* Notas altas (4 e 5): Entregas rápidas e avaliações melhores.

Outliers mais frequentes nas notas baixas.

# Análise Comparativa por Cidade do Vendedor
# Total de Vendas (Top 10 Cidades)
* São Paulo lidera (> R$ 300.000)

* Guarulhos, Ibitinga e outras cidades relevantes no top 10.

# Avaliação Média
* Melhores avaliações: Vitória, Auriflama, Triunfo, Tiradentes, Bahia.

Não há sobreposição entre cidades líderes em vendas e avaliação.

# Tempo Médio de Entrega
* Maiores tempos: Congonhal (> 35 dias), Campo Bom, Osvaldo Cruz.

Cidades com maior tempo de entrega não são líderes em vendas ou avaliação.

# Principais Insights
* Centralização de vendas: Forte concentração em São Paulo.

* Satisfação do cliente: Operações menores podem oferecer melhor atendimento.

* Logística: Atrasos impactam negativamente avaliação e vendas.

# Como Reproduzir a Análise
* Clone este repositório.

* Instale as dependências necessárias (listar se houver).

* Execute os scripts de análise.

* Visualize os dashboards conforme instruções.
