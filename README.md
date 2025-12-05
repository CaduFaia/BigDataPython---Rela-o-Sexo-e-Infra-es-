# BigDataPython---Rela-o-Sexo-e-Infra-es-

NOME DA IES: UNESA Rio de Janeiro
CAMPUS Niteroi
Analise de dados em Big Data sobre Infrações de transito e a correlação entre os sexos
Nome do(s) discente(s) integrantes do grupo:
Carlos Eduardo Faia Esteves
Pedro De Souza
Nome do(a) professor(a) orientador
Simone Gama
Ano: 2025
Cidade/estado
Niterói/ Rio De Janeiro
Sumário
1. DIAGNÓSTICO E TEORIZAÇÃO.......................................................................................................... 3
1.1. Problemática e/ou problemas identificados ............................................................................... 4
1.2. Justificativa .................................................................................................................................. 4
1.3. Objetivos/resultados/efeitos a serem alcançados (em relação ao problema identificado e sob a perspectiva dos públicos envolvidos) ............................................................................................... 4
2. PLANEJAMENTO E DESENVOLVIMENTO DO PROJETO .................................................................... 4
2.1. Detalhamento técnico do projeto ............................................................................................... 5
3. ENCERRAMENTO DO PROJETO ........................................................................................................ 5
3.1.1. RESULTADOS E DISCUSSÃO: ............................................................................................ 5
3.1.2. CONSIDERAÇÕES FINAIS .................................................................................................. 5
1. DIAGNÓSTICO E TEORIZAÇÃO
1.1. Problemática e/ou problemas identificados
A problemática do estudo gira em torno de entender as possíveis correlações entre o sexo do condutor e as infrações de trânsito, com o objetivo de identificar padrões específicos no comportamento dos
motoristas. A partir dessa análise, pode-se avaliar se existem diferenças significativas nas infrações
cometidas por homens e mulheres, bem como por diferentes faixas etárias. Isso é particularmente
relevante para a formulação de políticas públicas que busquem promover um trânsito mais seguro e
consciente.
1.2. Justificativa
A justificativa para a realização deste estudo é a crescente necessidade de análises mais
precisas e fundamentadas sobre o comportamento dos motoristas e a relação entre
características demográficas (como o sexo e a faixa etária) e as infrações de trânsito. A
compreensão desses fatores é essencial para o desenvolvimento de políticas públicas mais eficazes e direcionadas, tanto em termos de fiscalização quanto de educação no trânsito.
1.3. Objetivos/resultados/efeitos a serem alcançados (em relação ao problema identificado e sob a perspectiva dos públicos envolvidos)
O principal objetivo do projeto foi analisar como as infrações de trânsito se distribuem entre homens e mulheres e como essa distribuição varia de acordo com a faixa etária. A intenção não foi provar que um grupo dirige melhor ou pior, mas observar tendências estatísticas com base em dados oficiais e entender se existe algum padrão relevante nas infrações registradas. Durante o desenvolvimento, buscamos identificar pontos como: qual sexo aparece com mais infrações, se existem diferenças em tipos de infração (como leves, médias, graves e gravíssimas), e se a idade influencia o comportamento no trânsito. Além disso, construímos visualizações comparativas e começamos a aplicar regressões lineares para enxergar possíveis tendências. Outro objetivo importante foi aprender a lidar com dados reais na prática — desde a limpeza da base, padronização de categorias e tratamento de inconsistências até a criação de gráficos, agrupamentos e análises automatizadas usando bibliotecas como Pandas, NumPy e Scikit-Learn.Como resultado, conseguimos produzir gráficos e tabelas que mostram diferenças claras entre perfis demográficos e também aprimoramos nossas habilidades técnicas em análise de dados.
2. PLANEJAMENTO E DESENVOLVIMENTO DO PROJETO
2.1. Detalhamento técnico do projeto
A equipe deste trabalho escolheu a base de dados: 2.1-infracoes-por-sexo_idade-24.csv (https://dadosabertos.rj.gov.br/km/dataset/infracoes-de-transito-por-sexo-e-idade/resource/92cf5ec2-0ea0-41b1-92ec-0dba50c11b24)
Limpeza da base de dados: Foram utilizados os Pandas para realizar a limpeza da base de dados. A limpeza incluiu a remoção de registros com valores ausentes nas colunas SEXO_ARQ e FAIXA, além de normalizar os valores das variáveis SEXO_ARQ (transformando em "M" e "F") e DESCR_MUNIC_INF (convertendo para maiúsculas e removendo espaços extras).
Distribuição de Frequência: A distribuição de frequência foi feita para calcular a quantidade de infrações por nível de gravidade (representado pela coluna LIT_PTO), como "Leve", "Média", "Grave" e "Gravíssima". Também foi gerada uma tabela de contagem de infrações, mas esta foi segmentada por faixa etária e sexo dos infratores.
3. ENCERRAMENTO DO PROJETO
3.1.1. RESULTADOS E DISCUSSÃO:
Ao começarmos o trabalho, desde o principio foi se notado uma certa tensão da equipe em lidar com um tema tão controverso e polemico, "relacionar acidentes com gêneros e idades", porém ao passar do projeto, notou-se padrões interessantes e contrários a crenças populares. Durante o desenvolvimento, houve auxilio da inteligência artificial "Open Ai" (ChatGpt) em trechos mais específicos e complexos do mesmo. Muitas ferramentas e bibliotecas foram descobertas pela equipe, como "Sklearn, Pandas, Numpy" dentre outras. A conclusão final foi de que apesar de polemico, as estatísticas e dados provam ao contrario de conceitos infundados em nossa sociedade, além de preparar melhor a equipe para projetos maiores no futuro, já que, por mais simples que este trabalho tenha sido (teoricamente) o mesmo foi mais difícil e complexo do que esperado, porem o objetivo final foi alcançado, portanto, a missão também foi cumprida
3.1.2. CONSIDERAÇÕES FINAIS
A conclusão final foi de que apesar de polemico, as estatísticas e dados provam ao contrario de conceitos infundados em nossa sociedade, além de preparar melhor a equipe para projetos maiores no futuro, já que, por mais simples que este trabalho tenha sido (teoricamente) o mesmo foi mais difícil e complexo do que esperado, porem o objetivo final foi alcançado, portanto, a missão também foi cumprida.
