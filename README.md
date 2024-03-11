# Diagnóstico financeiro de uma escola

## Introdução

Uma escola de período integral recém comprada e prestes a fechar as portas solicitou uma avaliação das finanças para guiar uma tomada de decisão: fechar, vender ou investir.

Neste trabalho podemos ver como uma decisão baseada em dados pode afetar a saúde financeira de uma pequena empresa.


## Objetivos

- investigar as possíveis causas do prejuízo financeiro dos últimos 5 meses (junho a outubro de 2023);
- criar um plano de recuperação financeira através do cálculo das mensalidades para o ano seguinte (2024) de forma a cobrir os custos e manter valores atrativos para ganhar da concorrência;
- preparar a escola para uma possível venda;
- criar um plano para atrair possíveis sócios.

## Dados

Os dados reais de nome foram anonimizados e os dados de turma foram agrupados por faixa etária seguindo deliberação do Conselho Regional de Ensino. Os valores monetários foram anonimizados usando um fator de conversão. Todo o trabalho mostrado aqui foi realizado com autorização da escola.
Os dados disponíveis para a avaliação foram:
- tabela de mensalidades do ano 2023 em função das horas de permanência na escola;
- tabela com nome dos alunos, turma a qual pertence, horários de entrada e saída e valores de mensalidade pagos para o mês de agosto e setembro;
- extratos bancário das duas contas PJ dos 5 meses anteriores (junho a outubro de 2023).

Não havia dados financeiros disponíveis dos meses anteriores a junho. Dois programas de contabilidade estavam sendo usados pela nova gestão, porém os registros não estavam sendo feitos de forma adequada. As movimentações pessoais e empresariais do novo dono não estavam devidamente identificadas e separadas.

Para conhecer as despesas da escola, classificamos os dados de movimentação bancária como gastos pessoais ou gastos da escola. Os dados que não conseguimos classificar foram computados como gastos da escola com a finalidade de obter um limite superior de gastos.

Os valores da tabela de mensalidades não foram praticados desde o início do ano letivo. A gestão anterior à compra forneceu descontos de mensalidades indiscriminadamente e sem alteração formal  no contrato. Os dados de mensalidades efetivamente pagas pelos alunos foram retirados dos extratos bancários, comprovantes de pix e registros informais no computador da escola. Não havia nenhum controle da taxa de inadimplência.


## Análise de dados


### Despesas

A partir dos extratos bancários obtivemos o limite superior de gastos mensais referentes às despesas da escola. Seguem os dados de gastos (fixos, variáveis e pró-labore) e número N de alunos por mês. As retiradas de pró-labore foram contabilizadas como despesas.

| MESES | DESPESAS      | N  |
| ----- | ------------- | -- |
| 6     |  R$ 58.136,22 | 43 |
| 7     |  R$ 73.274,51 | 43 |
| 8     |  R$ 74.271,44 | 40 |
| 9     |  R$ 64.923,11 | 33 |
| 10    |  R$ 55.771,65 | 33 |

Analisando a tabela acima, notamos uma perda de 3 alunos entre julho e agosto. Verificamos que pertenciam a uma mesma família. Supomos que a troca de gestão tenha gerado alguma insegurança ou insatisfação, culminando no encerramento dos 3 contratos. Notamos uma segunda fuga de alunos entre os meses de agosto e setembro. Verificamos que ocorreu a demissão de um professor, que prontamente se empregou em outra escola, incorrendo na migração de alguns alunos. A demissão ocorreu com base em uma necessidade de corte de gastos, sem considerar as consequências do ato. 

Notamos uma elevação significativa dos gastos de junho para julho. Verificamos que, na tentativa de melhorar a arrecadação da escola, foi feita uma festa julina. Dada a falta de planejamento prévio, a festa gerou um prejuízo de mais de 7 mil reais.

De julho para agosto o gasto se manteve alto devido às demissões de diversos funcionários, dentre eles, o professor citado acima. Parte das recisões foi paga no mês de agosto e parte foi paga no mês de setembro.

Em outubro houve uma redução de custos devido a menor quantidade de funcionários e de alunos (redução dos gastos variáveis).


### Receitas

A única fonte de receitas da escola eram as mensalidades. Os valores tabelados variam de acordo com o número de horas que o aluno passa na escola. No gráfico abaixo comparamos a tabela de mensalidades proposta para o ano de 2023 (em verde) com os valores efetivamente praticados no mês de agosto (em azul).

![gráfico de mensalidades em função das horas de permanência na escola](./imagens/plano_de_mensalidades_antigo.png 'Gráfico de mensalidades em função das horas de permanência na escola')

Devido aos descontos dados pela gestão anterior, os valores de mensalidade praticados ficaram bem abaixo do esperado. Não houve coerência na aplicação de descontos, resultando em pagamentos maiores para um menor número de horas na escola. Além disso, alunos de uma mesma turma, frequentando a escola pelo mesmo número de horas, chegaram a ter mais de 40% de diferença na mensalidade paga. Os responsáveis financeiros, ficando cientes da situação via grupos de WhatsApp, solicitaram reuniões com o novo gestor, que acabou por conceder mais descontos na tentativa de corrigir a situação. Não houve nehum tipo de registro dos descontos, foram acordados somente em conversa privada.

Na tabela abaixo, vemos o resultado das receitas de mensalidade mês a mês, onde N é o número de alunos. Como não havia controle de inadimplência, os dados de receita foram calculados como se a inadimplência fosse 0.

| MESES | RECEITAS      | N  |
| ----- | ------------- | -- |
| 6     |  R$ 62.409,18 | 43 |
| 7     |  R$ 62.409,18 | 43 |
| 8     |  R$ 57.728,49 | 40 |
| 9     |  R$ 40.786,87 | 33 |
| 10    |  R$ 40.786,87 | 33 |

Vemos uma clara redução de receita em função da redução de alunos. A informação não óbvia contida na tabela é a redução de receita devido aos descontos. Essa análise foi feita comparando os valores pagos de mensalidade de agosto e setembro aluno por aluno. A receita total da escola diminuiu quase 30% de um mês para o outro. Desse percentual, 40% foi devido aos descontos dados e 60% devido à redução no número de alunos.


### Receitas x despesas - Lucro ou prejuízo?

Comparando os dados de receitas e despesas apresentadas, vemos que o mês de junho apresentou um fechamento positivo. Os demais meses acumularam um prejuízo de mais de 66 mil reais. Tentamos identificar mês a mês o motivo do prejuízo. 

![Gráfico de comparação entre receitas e despesas.](./imagens/comparacao.png 'Gráfico de comparação entre receitas e despesas.')

Em junho houve um saldo positivo que foi entendido como prejuízo pelo dono da escola (total desorganização das contas!). Para reverter a situação (que não existia) foi feita uma festa julina sem planejamento financeiro. A festa custou mais de 10 mil reais e teve um faturamento da ordem de 3 mil reais, gerando um prejuízo de mais de 7 mil reais. Além disso, a retirada de pró-labore ocorreu sem a devida verificação das contas, gerando dívidas para a escola.

Contando apenas com os dados de saldos bancários e sem a devida separação entre gastos pessoais e empresariais, o dono viu como alternativa óbvia o corte imediato de gastos. Na tentativa de reduzir os custos, foram feitas diversas demissões no mês de agosto, gerando um alto custo com as recisões que foram pagas parte em agosto e parte em setembro. As demissões sem justa causa foram feitas de forma arbitrária e geraram desconforto e insegurança entre os funcionários e responsáveis financeiros. Além disso, a qualidade do serviço foi seriamente afetada, principalmente pelo fato de haver poucos funcionários disponíveis em horários de alta demanda de alunos. Como consequência de todos os fatos citados, vários alunos optaram por encerrar seus contratos prematuramente. Como não havia nenhum controle das finanças, nenhuma multa de recisão contratual foi paga, apesar de prevista em contrato. 

No mês de outubro houve uma redução do prejuízo. Isso se deve em grande parte à redução na folha de pagamento. O pró-labore continuou sendo retirado. Com apenas 33 alunos, os custos da escola já não poderiam ser cobertos pelas mensalidades.

Nesse ponto, a escola solicitou uma avaliação financeira da MP-resuldados para tomar uma decisão baseada em dados (finalmente!).

## Diagnóstico

Depois de uma exaustiva coleta de dados financeiros, constatamos que todo o prejuízo da escola se deu por tomadas de decisão precipitadas e sem embasamento em dados. Como exemplo, a festa em julho, as demissões e descontos em agosto e as altas retiradas de pró-labore.

Antes de qualquer tomada de decisão em negócios, uma avaliação criteriosa deve ser feita. Não havia nenhum controle das finanças, o que impossibilitou o entendimento das finanças mês a mês. O que foi tido como prejuízo em junho, primeiro mês da nova gestão, na verdade, foi lucro! A mistura entre movimentações pessoais e da escola gerou um diagnóstico errado que motivou escolhas erradas, gerando um enorme ciclo de más decisões.

Além das más decisões da nova gestão, verificamos que outro entrave à lucratividade do negócio era a falta de rigor em seguir a tabela de mensalidades calculada para o ano letivo. Se a tabela para 2023 tivesse sido praticada, ao invés de um saldo negativo de mais de 62 mil reais, a escola poderia ter tido um saldo positivo de mais de 23 mil reais  nesses 5 meses analisados, mesmo considerando as decisões ruins.

No gráfico abaixo podemos ver a comparação entre receitas reais (azul), despesas (vermelho) e possíveis receitas considerando a tabela de mensalidade que não estava sendo praticada (verde). As linhas tracejadas em azul, vermelho e verde são as respectivas médias para os cinco meses estudados das receitas, despesas e receitas tabeladas. A linha tracejada preta se refere aos gastos fixos da escola. Dada toda a desorganização das contas e a falta de dados anteriores, os gastos fixos foram estimados usando uma regressão linear.

![Gráfico de comparação entre receitas e despesas com médias.](./imagens/comparacao-medias.png 'Gráfico de comparação entre receitas e despesas com médias.')

Olhando o gráfico, vemos um prejuízo real em quatro dos cinco meses estudados. A média das despesas foi consideravelmente maior que a média das receitas. Porém olhando as receitas de mensalidade tabeladas, vemos que o prejuízo poderia ter sido evitado somente com a prática da tabela e mensalidades. Também podemos notar que as receitas dos últimos dois meses já não eram capazer de pagar os custos fixos da escola (aluguel, folha de pagamento, manutenção...). Só para os custos fixos, a escola precisaria de 35 alunos pagantes. Considerando  as mensalidades tabeladas, esse número cai para 26. A diferença é muito relevante se considerarmos que o número de alunos caiu de 43 para 33 em poucos meses.

Durante os meses analisados, o custo médio de um aluno para 8 horas de permanência foi perto de R$ 1700 enquanto a mensalidade paga foi em média R$ 1376. A tabela previa, em média, uma receita de R$ 1822. Se a tabela tivesse sendo praticada, ao invés do prejuízo de R$ 324 por mês por aluno, a escola poderia ter lucrado R$ 122 por mês por aluno além do pró-labore.



## Ponto de equilíbrio financeiro

Para entender melhor os problemas financeiras da escola, decidimos entender quantos alunos a escola precisaria para manter receitas e despesas em equilíbrio ao longo dos meses. A capacidade máxima é de 100 alunos. Como tivemos muitas variações de gastos extras e até desnecessários e também uma variação expressiva no número de alunos, fizemos os cálculos para o cenário que passou e outros hipotéticos.

Para o cálculo do ponto de equilíbrio, decidimos separar o pro-labore do sócio. Fizemos uma estimativa média do limite inferior das retiradas de modo que, as despesas da escola podem estar ligeiramente inflacionadas. 

De posse desses dados, calculamos o número mínimo de alunos para a escola estar em equilíbrio financeiro (receitas = despesas, desconsiderando o pró-labore do sócio). Considerando a média dos meses estudados, a escola precisaria de 42 alunos para estar em equilíbrio financeiro, mesmo com as mensalidades defasadas e gastos impensados. Chamamos esse cenário de cenário 0.

![Gráfico do ponto equilíbrio financeiro considerando as despesas e receitas médias do 5 meses estudados.](./imagens/ponto-de-equilibrio-0.png 'Gráfico do ponto equilíbrio financeiro considerando as despesas e receitas médias do 5 meses estudados.')

No cenário hipotético 1, desconsideramos os gastos com a festa e as demissões sem justa causa. Com isso, o número de alunos para a escola estar em equilíbrio financeiro cai de 42 para 36.

Considerando um cenário hipotético 2 onde a tabela de mensalidades estivesse sendo devidamente praticada, o ponto de equilíbrio acontece com um número de alunos 32 mesmo com as altas despesas.

Em um cenário hipotético 3, consideramos a tabela de mesalidades sendo cumprida e desconsideramos os gastos com a festa e as demissões sem justa causa. Com isso, o número de alunos para o equilibrio financeiro seria de apenas 27 alunos, representando menos de 30% da capacidade máxima da escola.

Em qualquer um dos cenários hipotéticos, o prejuízo poderia ter sido evitado. Abaixo construímos um gráfico comparando receitas e despesas dos cinco meses somados no cenário real e nos três cenários hipotéticos estudados acima:

![Gráfico de receitas e despesa: expectaticva x realidade.](./imagens/cenarios.png 'Gráfico de receitas e despesa: expectaticva x realidade.')

No último mês estudado, a escola já não tinha quantidade de alunos suficiente para cobrir os custos fixos. O prejuízo nos meses seguintes seria inevitável. Calculamos, então o valor necessário de aporte financeiro a se fazer para segurar a empresa até o fim do ano letivo. O valor foi conseguido através de um empréstimo. Estratégias inteligentes de redução de despesas foram sugeridas, como migração de banco para redução das taxas bancárias, adoção de um único sistema contábil gratuito e troca de fornecedores. As medidas simples tinham potencial de reduzir em mais de 10% o empréstimo necessário.

O papel da MP-resuldados foi entender todo o ocorrido ao longo dos meses e apresentar os dados, fatos e como eles se relacionam ao gestor. Os dados contam a história e os números não mentem! Como resultado dessa primeira análise, aconselhamos o dono a criar o hábito de fazer um rigoroso acompanhamento das finanças do seu negócio e tomar sempre decisões baseadas em dados.


## Possíveis soluções

Para recuperar o prejuízo financeiro, a MP-resuldados aconselhou o gestor a tomar algumas atitudes para o ano seguinte:
- investir na melhoria dos serviços para evitar a evasão no fim do ano letivo e aumentar a retenção de alunos (possível simplesmente com uma gestão de pessoal adequada a custo zero);
- investir em propaganda nas redes sociais para atrair novos alunos (baixíssimo custo e ótimo potencial de retorno);
- organizar as finanças de modo a permitir um cálculo mais preciso de mensalidades;
- seguir o plano financeiro (eis o mais importante!)

Mantendo a escola em funcionamento até o fim do ano letivo, ficaria aberta a possibilidade de vender a escola ou conseguir uma sociedade (houve interessados que desistiram ao ver o livro contábil - ou a falta dele). 

## Conclusão

Antes de comprar um negócio, certifique-se da saúde financeira da empresa está em dia, se a possibilidade de lucro está dentro das suas expectativas e se você tem vontade de estar a frente do negócio. Se não sabe como fazer, consulte um especialista, analise os dados apresentados e tire suas próprias conclusões antes de investir seu dinheiro. Tenha em mente que, mesmo um negócio consolidado no mercado pode sofrer revezes em uma troca de gestão. Tenha sempre uma reserva financeira para lidar com os imprevistos!

Decisões de negócios não devem ser tomadas com base na intuição do gestor. Reúna dados, mantenha-os organizados e peça ajuda antes de tomar decisões precipitadas. Muitas vezes, em uma empresa, um bom trabalho de gestão de pessoal e organização das contas pode significar a diferença entre lucro e prejuízo.

No caso específico da escola, os problemas financeiros poderiam ter sido evitados simplesmente seguindo a tabela de mensalidades. Mas mesmo sem poder corrigir esse problema no meio do ano letivo, a escola poderia ter tido um baixo lucro até o fim do ano, mas não teria acumulado dívidas. Se o novo gestor não tivesse feito nada além de tocar o negócio como ele já estava, nenhuma dívida teria sido contraída. Nesse caso, se atentar à qualidade do serviço prestado, trabalhar para reter os alunos e atrair mais alunos para o ano segiuinte teria sido uma estratégia melhor. Empresas são investimentos de longo prazo. É preciso estratégia e paciência para levar uma empresa ao auge da lucratividade.

Funcionando em plena capacidade e com o cálculo correto de mensalidades, a escola tem potencial de gerar um alto lucro. Para saber mais, consulte os repositórios de calculo-de-mensalidades e viabilidade-de-negocio.

-----------------------------------------------------------------------------
MP-resuldados

Dos dados aos resultados. Um pouco de física, matemática, negócios e finanças.
