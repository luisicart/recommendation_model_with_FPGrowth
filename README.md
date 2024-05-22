# recommendation_model_with_FPGrowth
Modelo de Recomendação de Cestas com FPGrowth

### O que é FPGrowth?

O FPGrowth é um modelo de Machine Learning voltado para a criação de recomendações baseadas em **cestas**. 
Nesse contexto, uma cesta são itens que possuem uma ação em conjunto. 

O modelo é formidável quando temos essa característica de 'itens' em conjunto, sendo um limitando caso os dados não tenham esse comportamento.

Vale ressaltar que o FPGrowth não possui hiperparâmetros, apenas parâmetros de **cortes**, isso significa que é preciso um entendimento maior da base de dados utilizada e os critérios que queremos aplicar.

Ao longo do notebook será possível entender melhor esses parâmetros de cortes e seus motivos.

Além disso, busco exemplificar e elucidar alguns desafios e solução encontradas durante o processo de implementação.

### Considerações Finais

A beleza desse modelo está no entendimento e na flexibilidade dos parâmetros de cortes, podendo ser ajustados de acordo com suas necessidades e objetivos.