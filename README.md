# Título
Prevendo a evasão de alunos no Ensino Superior Online

# Resumo
Que sinais antecedem a evasão de um aluno no Ensino Superior Online? Como aumentar o engajamento para evitar essa situação? Estas são as perguntas que este projeto busca responder! O trabalho envolve uma análise exploratória detalhada, engenharia de features e modelagem preditiva (Random Forest e Regressão Logística), com o objetivo de identificar padrões e fornecer insights sobre os principais fatores que influenciam a evasão estudantil.

# Modelos de previsão escolhidos:

Random Forest: foi escolhido por ser robusto ao lidar com dados não lineares, o que permite capturar padrões em problemas com múltiplas interações entre variáveis. Além disso, a capacidade de paralelizar o treinamento do modelo (n_jobs=-1) resulta em maior eficiência computacional em datasets maiores. O Random Forest também fornece métricas de importância das variáveis, permitindo a identificação de fatores relevantes para a previsão.

Regressão Logística: foi escolhida pela sua alta interpretabilidade. Embora o Random Forest permita acessar a importância das variáveis, os coeficientes da Regressão Logística oferecem uma interpretação mais direta: o sinal dos coeficientes indica a direção do efeito (positivo ou negativo), enquanto sua magnitude reflete a intensidade do impacto. Essa característica é essencial para o problema em questão, que demanda insights em relação a fatores que aumentam as chances de evasão.

# Insights:

Fatores como:

- o número de provas realizadas (- provas realizadas = + chance de evasão)
- o número de exercícios realizados (- exercícios realizados = + chance de evasão)
- o acesso à plataforma (- acesso/número de visitas = + chance de evasão)
- tempo na plataforma (- tempo = + chance de evasão)
- intervalo de dias entre o primeiro e o último exercício/prova (- intervalo entre primeiro e último exercício/prova = + chance de evasão)

impactam as probabilidades de evasão. Esses resultados estão em conformidade com as observações feitas durante a análise exploratória (baixa interação com a plataforma = evasão).

Com base nesses insights, podem ser adotadas ações específicas para desincentivar a evasão, como:

- Incentivar a realização de mais provas e exercícios: programas de gamificação ou metas de aprendizado podem motivar os estudantes a se engajarem mais com o conteúdo e a prática. Oferecer algumas provas e exercícios exclusivamente em formato síncrono também pode ser uma estratégia eficaz para evitar que os alunos posterguem as atividades e, consequentemente, deixem de finalizá-las.

- Estímulo ao acesso frequente à plataforma: notificações personalizadas, lembretes de atividades pendentes, conteúdos novos e até uma ofensiva (semelhante ao Duolinguo) podem incentivar visitas diárias ou semanais.

- Aumentar o intervalo entre os prieiros provas/exercícios realizados: o baixo intervalo de dias entre o primeiro e o último prova/exercício pode indicar períodos de inatividade ou desinteresse. Assim, aplicar recompensas para quem realizar provas/exercícios regularmente ou completar as atividades dentro de prazos curtos pode ser um caminho promissor.

Fatores como:

o número de provas realizadas (+ provas realizadas = - chance de evasão)
o número de exercícios realizados (- exercícios realizados = + chance de evasão)
o acesso à plataforma (- acesso/número de visitas = + chance de evasão)
tempo na plataforma (- tempo = + chance de evasão)
intervalo de dias entre o primeiro e o último exercício/prova (- intervalo entre primeiro e último exercício/prova = + chance de evasão)
foram identificados como essenciais para as chances de evasão. Esses resultados estão em conformidade com as observações feitas durante a análise exploratória (baixa interação com a plataforma = evasão).

Tendo isso em vista, ações como:

- Incentivar a realização de mais provas e exercícios: programas de gamificação ou metas de aprendizado podem motivar os estudantes a se engajarem mais com o conteúdo e a prática. Oferecer algumas provas e exercícios exclusivamente em formato síncrono também pode ser uma estratégia eficaz para evitar que os alunos posterguem as atividades e, consequentemente, deixem de finalizá-las;

- Estímular ao acesso frequente à plataforma: notificações personalizadas, lembretes de atividades pendentes, conteúdos novos e até uma ofensiva (semelhante ao Duolinguo) podem incentivar visitas diárias ou semanais;

- Aumentar o intervalo entre os prieiros provas/exercícios realizados: o baixo intervalo de dias entre o primeiro e o último prova/exercício pode indicar períodos de inatividade ou desinteresse. Assim, aplicar recompensas para quem realizar provas/exercícios regularmente ou completar as atividades dentro de prazos curtos pode ser um caminho promissor;

têm o potencial de criar uma experiência mais atrativa aos alunos, desincentivando a evasão.
