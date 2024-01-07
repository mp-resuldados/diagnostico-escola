# Diagnóstico financeiro de uma escola



## Introdução

Uma escola de período integral recém comprada e prestes a fechar as portas solicitou uma avaliação das finanças para guiar uma tomada de decisão: fechar, vender ou investir.

Neste trabalho podemos ver como uma decisão baseada em dados pode afetar a saúde financeira de uma pequena empresa.


## Objetivos

- investigar as possíveis causas do prejuízo financeiro dos últimos 5 meses (junho a outubro de 2023);
- criar um plano de recuperação financeira através do cálculo das mensalidades para o ano seguinte (2024) de forma a cobrir os custos e manter valores atrativos para ganhar da concorrência;
- preparar a escola para uma possível venda;
- criar um plano para atrair investidores.

## Dados

Os dados reais de nome foram anonimizados e os dados de turma foram agrupados por faixa etária seguindo deliberação do Conselho Regional de Ensino. Os valores monetários foram anonimizados usando um fator de conversão.
Os dados disponíveis para a avaliação foram:
- tabela de mensalidades do ano 2023 em função das horas de permanência na escola;
- tabela com nome dos alunos, turma a qual pertence, horários de entrada e saída e valores de mensalidade pagos;
- extratos bancário das duas contas PJ dos 5 meses anteriores (junho a outubro de 2023).

Não havia dados financeiros disponíveis dos meses anteriores a junho. Dois programas de contabilidade estavam sendo usados pela nova gestão, porém os registros não estavam sendo feitos de forma adequada. As movimentações pessoais e empresariais do novo dono não estavam devidamente identificadas e separadas. Para conhecer as despesas da escola, classificamos os dados de movimentação bancária como gastos pessoais ou gastos da escola. Os dados que não conseguimos classificar foram computados como gastos da escola com a finalidade de obter um limite superior de gastos.


Os valores da tabela de mensalidades não foram praticados desde o início do ano letivo. A gestão anterior à compra forneceu descontos de mensalidades indiscriminadamente e sem alteração formal  no contrato. Os dados de mensalidades efetivamente pagas pelos alunos foram retirados dos extratos bancários, comprovantes de pix e registros informais no computador da escola. Não havia nenhum controle da taxa de inadimplência.


## Análise de dados


### Despesas

A partir dos extratos bancários obtivemos o limite superior de gastos mensais referentes às despesas da escola. Seguem os dados de gastos (fixos e variáveis) e número N de alunos por mês. As retiradas de pró-labore foram contabilizadas como despesas.

| MESES | DESPESAS      | N  |
| ----- | ------------- | -- |
| 6     |  R$ 58.136,22 | 43 |
| 7     |  R$ 73.274,51 | 43 |
| 8     |  R$ 74.271,44 | 40 |
| 9     |  R$ 64.923,11 | 33 |
| 10    |  R$ 55.771,65 | 33 |

Notamos uma perda de 3 alunos entre julho e agosto. Verificamos que pertenciam a uma mesma família. Supomos que a troca de gestão tenha gerado alguma insegurança ou insatisfação, culminando no encerramento dos 3 contratos. Notamos uma segunda fuga de alunos entre os meses de agosto e setembro. Verificamos que ocorreu a demissão de um professor, que prontamente se empregou em outra escola, incorrendo em uma migração de sete alunos. A demissão ocorreu com base na necessidade de corte de gastos, sem considerar as consequências do ato. 

Notamos uma elevação significativa dos gastos de junho para julho. Verificamos que, na tentativa de melhorar a arrecadação da escola, foi feita uma festa julina. Dada a falta de planejamento prévio, a festa gerou um prejuízo de mais de 7 mil reais.

De julho para agosto o gasto se manteve alto devido às demissões de diversos funcionários, dentre eles, o professor citado acima. Parte das recisões foi paga no mês de agosto e parte foi paga no mês de setembro.

Em outubro houve uma redução de custos devido a menor quantidade de funcionário e de alunos (redução dos gastos variáveis).


### Receitas

A única fonte de receitas da escola eram as mensalidades. Os valores tabelados variam de acordo com o número de horas que o aluno passa na escola. No gráfico abaixo comparamos a tabela de mensalidades proposta para o ano de 2023 com os valores efetivamente praticados no mês de agosto.

![gráfico de mensalidades em função das horas de permanência na escola](/imagens/plano_de_mensalidades_antigo.png?raw=true)

Devido aos descontos dados pela gestão anterior, os valores de mensalidade praticados ficaram bem abaixo do esperado. Além disso, não houve coerência na aplicação de descontos, resultando em pagamentos maiores para um menor número de horas na escola. Os responsáveis financeiros, ficando cientes da situação via grupos de WhatsApp, solicitaram reuniões com o novo gestor, que acabou por conceder mais descontos na tentativa de corrigir a situação. Não houve nehum tipo de registro dos descontos, foram acordados somente em conversa privada.

Na tabela abaixo, vemos o resultado das receitas de mensalidade mês a mês, onde N é o número de alunos. Como não havia controle de inadimplência, os dados de receita foram calculados como se a inadimplência fosse 0.

| MESES | RECEITAS      | N  |
| ----- | ------------- | -- |
| 6     |  R$ 62.409,18 | 43 |
| 7     |  R$ 62.409,18 | 43 |
| 8     |  R$ 57.728,49 | 40 |
| 9     |  R$ 40.786,87 | 33 |
| 10    |  R$ 40.786,87 | 33 |

Vemos uma clara redução de receita em função da redução de alunos. A informação não óbvia contida na tabela é a redução de receita devido aos descontos. Essa análie foi feita comparando os valores pagos de mensalidade de agosto e setembro aluno por aluno. A receita total da escola diminuiu em quase 30% entre agosto e setembro. Desse percentual, 40% foi devido aos descontos dados e 60% devido à redução no número de alunos.


### Receitas x despesas - Lucro ou prejuízo?

Comparando os dados de receitas e despesas apresentadas, vemos que o mês de junho apresentou um fechamento positivo. Os demais meses acumularam um prejuízo de mais de 66 mil reais. Tentamos identificar mês a mês o motivo do prejuízo. 

% incluir gráfico

Em junho houve um saldo positivo que foi considerado abaixo da expectativa pelo dono da escola. Para reverter a situação foi feita uma festa julina sem planejamento financeiro. A festa custou mais de 10 mil reais e teve um faturamento da ordem de 3 mil reais, gerando um prejuízo de mais de 7 mil reais. Além disso, a retirada de pró-labore ocorreu sem a devida verificação das contas, gerando dívidas para a escola.

Contando apenas com os dados de saldos bancários e sem a devida separação entre gastos pessoais e empresariais, o dono viu como alternativa óbvia o corte imediato de gastos. Na tentativa de reduzir os custos, foram feitas diversas demissões no mês de agosto, gerando um alto custo com as recisões que foram pagas parte em agosto e parte em setembro. As demissões sem justa causa foram feitas de forma arbitrária e geraram desconforto e insegurança entre os funcionários e responsáveis financeiros. Além disso, a qualidade do serviço foi seriamente afetada, principalmente pelo fato de haver poucos funcionários disponíveis em horários de alta demanda de alunos. Como consequência de todos os fatos citados, vários alunos optaram por encerrar seus contratos prematuramente. Como não havia nenhum controle das finanças, nenhuma multa de recisão contratual foi paga, apesar de prevista em contrato. 

No mês de outubro houve uma redução do prejuízo. Isso se deve em grande parte à redução na folha de pagamento. O pró-labore continuou sendo retirado. Com apenas 33 alunos, os custos da escola já não poderiam ser cobertos pelas mensalidades.

Nesse ponto, a escola solicitou uma avaliação financeira da MP-resuldados para tomar uma decisão baseada em dados (finalmente!).

## Diagnóstico

Depois de uma exaustiva coleta de dados financeiros, constatamos que todo o prejuízo da escola se deu por tomadas de decisão precipitadas e sem embasamento em dados. Como exemplo, a festa em julho, as demissões e descontos em agosto, e as altas retiradas de pró-labore.
Antes de qualquer tomada de decisão em negócios, uma avaliação criteriosa deve ser feita. Não havia nenhum controle das finanças, o que impossibilitou o entendimento das finanças mês a mês. O que foi tido como prejuízo em junho, primeiro mês da nova gestão, na verdade, foi lucro! A mistura entre movimentações pessoais e da escola gerou um diagnóstico errado que motivou mais escolhas erradas, gerando um enorme ciclo de más decisões.

Além das más decisões da nova gestão, verificamos que outro entrave à lucratividade do negócio era a falta de rigor em seguir a tabela de mensalidades calculada para o ano letivo. Se a tabela para 2023 tivesse sido praticada, ao invés de um prejuízo acumulado de mais de 66 mil reais, a escola poderia ter tido um lucro acumulado de mais de 52 mil reais somente nesses 5 meses analisados, mesmo considerando as altas despesas.

Com quantidade de alunos insuficiente para cobrir os custos, o prejuízo nos meses seguintes seria inevitável. Calculamos, então o valor necessário de aporte financeiro a se fazer para segurar a empresa até o fim do ano letivo. O valor foi conseguido através de um empréstimo.

O papel da MP-resuldados foi entender todo o ocorrido ao longo dos meses e apresentar os dados, fatos e como eles se relacionam ao gestor. Os dados contam a história e os números não mentem! Como resultado dessa primeira análise, aconselhamos o dono a fazer um rigoroso acompanhamento das finanças do seu negócio e tomar sempre decisões baseadas em dados.

## Possíveis soluções

Em uma escola onde a única receita são mensalidades, há de se ter o cuidado de preservar um número mínimo de alunos para que, pelo menos, os custos sejam cobertos. Sendo a única fonte de receita, o cálculo das mensalidades deve ser feito com extremo rigor. A lei não permite ajuste de mensalidade após a assinatura do contrato, válido para todo o ano letivo. Como esses contratos são fechados com meses de antecedência, os cálculos devem ser feitos com base em extrapolação de custos e receitas.

Para recuperar o prejuízo financeiro, a MP-resuldados aconselhou o gestor a:
- investir na melhoria dos serviços para evitar a evasão no fim do ano letivo e aumentar a retenção de alunos para o ano seguinte;
- investir em propaganda nas redes sociais para atrair mais alunos para o ano seguinte;
- organizar as finanças de modo a permitir um cálculo mais preciso de mensalidades para o ano seguinte.

## Conclusão

