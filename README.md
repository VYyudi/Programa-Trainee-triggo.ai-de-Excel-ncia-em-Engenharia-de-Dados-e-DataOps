# Programa-Trainee-triggo.ai-de-Excel-ncia-em-Engenharia-de-Dados-e-DataOps

# Resultados da Análise Exploratória
a) Volume de pedidos por mês
A análise do volume de pedidos ao longo do tempo mostra a tendência mensal de compras. Observou-se variações sazonais, com picos em determinados meses (ex.: novembro e dezembro, próximos ao Natal e Black Friday).

b) Distribuição do tempo de entrega
A maioria dos pedidos foi entregue em cerca de 8 a 12 dias, com uma concentração em torno desse intervalo. Também há casos de entregas muito rápidas e outras com prazos bastante longos, sugerindo outliers ou exceções.

c) Relação entre valor do frete e distância
Ao cruzar a distância geográfica entre clientes e vendedores com o valor do frete, percebeu-se uma correlação positiva: quanto maior a distância, maior tende a ser o valor do frete. Porém, há dispersão nos dados, indicando que outros fatores (como tipo de produto ou transportadora) também influenciam o valor.

d) Categorias mais vendidas em faturamento
As 10 categorias de produtos com maior faturamento foram identificadas, com destaque para:
-cama_mesa_banho
-relogios_presentes
-moveis_decoracao
Essas categorias lideram o ranking de receita total gerada.

e) Estados com maior valor médio de pedido
Os estados com maior valor médio de pedido foram:
-RR (Roraima)
-AC (Acre)
-AM (Amazonas)
Esses valores médios mais altos podem estar relacionados à distância logística ou à natureza dos produtos adquiridos nessas regiões.

# Visualização e Dashboards
# Relatório de Análise de Vendas por Categoria no Estado de SP
Crescimento Geral
Observa-se uma tendência clara de crescimento nas vendas totais ao longo do período analisado, com oscilações sazonais marcantes.
O pico geral de vendas ocorreu entre o final de 2017 e o início de 2018, seguido de certa volatilidade nos meses subsequentes.

Destaque por Categoria
beleza_saude: Apresentou crescimento consistente, atingindo o maior pico de vendas em agosto de 2018, superando R$ 50.000 no mês, tornando-se a categoria líder ao final do período.
-cama_mesa_banho: Teve forte desempenho, especialmente entre o final de 2017 e o início de 2018, com alguns dos maiores picos mensais, mas perdeu força relativa nos últimos meses.
-informatica_acessorios: Mostrou forte crescimento a partir de 2017, com picos próximos a R$ 40.000, mas apresentou queda acentuada após março de 2018.
-relogios_presentes: Teve grande variação, com picos expressivos, especialmente em abril de 2018, mas também quedas bruscas.
-esporte_lazer e moveis_decoracao: Mantiveram-se entre as menores em volume de vendas, com crescimento mais modesto e menor volatilidade.

# Análise: Avaliação do Cliente x Tempo de Entrega
Principais Observações
-Tendência Geral: Existe uma clara relação inversa entre o tempo de entrega e a avaliação do cliente. Pedidos com avaliações mais baixas (nota 1) apresentam tempos de entrega medianos e máximos significativamente maiores do que pedidos com avaliações mais altas (nota 5).
-Notas Baixas (1 e 2): Pedidos avaliados com 1 ou 2 estrelas têm medianas de tempo de entrega mais altas, além de uma maior dispersão dos dados (caixas mais altas e mais outliers). Isso indica que atrasos ou entregas demoradas estão fortemente associados à insatisfação do cliente.
-Notas Altas (4 e 5): Pedidos com avaliações 4 e 5 apresentam tempos de entrega medianos menores e menor dispersão, sugerindo que entregas rápidas e dentro do prazo contribuem para uma melhor experiência do cliente.
-Outliers: Todas as avaliações apresentam outliers, mas são mais frequentes e extremos nas notas baixas, indicando que alguns pedidos com atrasos muito acima da média impactam negativamente a percepção do cliente.

# Análise Comparativa: Vendas, Avaliação e Tempo de Entrega por Cidade do Vendedor
1. Total de Vendas (Top 10 Cidades)
São Paulo lidera com ampla vantagem, apresentando o maior volume de vendas, superando R$ 300.000, muito acima das demais cidades.
Guarulhos e Ibitinga aparecem em seguida, mas com volumes bem menores, mostrando forte concentração de vendas em poucos polos urbanos.
Outras cidades relevantes no top 10 incluem Curitiba, Campinas, Ribeirão Preto, Rio de Janeiro, Itaquaquecetuba, Recife e Sumaré.
A diferença entre São Paulo e as demais cidades evidencia a centralização do comércio eletrônico em grandes centros urbanos.

2. Avaliação Média
As cidades com melhores avaliações médias dos clientes são: Vitória, Auriflama, Triunfo, Tiradentes e Bahia, todas com notas próximas ao máximo (5).
Não há sobreposição entre as cidades líderes em vendas e as líderes em avaliação, indicando que alto volume de vendas não necessariamente resulta em melhores avaliações.
Cidades como Bandeirantes, Barra Velha, Cachoeirinha, Buritama e Barretos também se destacam positivamente em satisfação do cliente.

3. Tempo Médio de Entrega
Congonhal apresenta o maior tempo médio de entrega, superando 35 dias, seguido por Campo Bom e Osvaldo Cruz, todos com tempos significativamente acima da média.
Outras cidades com entregas mais lentas incluem Pinhalao, Mombuca, Andira-PR, Portao, Lagoa da Prata, Curitibanos e Luiz Alves.
O tempo de entrega elevado nessas cidades pode indicar desafios logísticos, distância dos grandes centros ou menor eficiência operacional.

Principais Insights
-Centralização de Vendas: São Paulo é o principal polo de vendas, enquanto outras cidades têm participação bem menor.
-Satisfação do Cliente: As cidades com melhor avaliação média não coincidem com as de maior volume de vendas, sugerindo que operações menores podem oferecer atendimento mais personalizado e eficiente.
-Logística: As cidades com maior tempo médio de entrega não estão entre as líderes de vendas ou avaliação, indicando que atrasos impactam negativamente o desempenho geral e potencialmente a satisfação do cliente.

















