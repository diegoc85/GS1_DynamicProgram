INTEGRANTES:
- Débora Ivanowski – RM 555694
- Diego Cabral – RM 557817

SOLUÇÃO DO PROBLEMA:

Desenvolvimento de um sistema chamdo NimbusTech D2 integrado e autônomo voltado à prevenção e ao combate de queimadas. Ao utilizar dados históricos e de previsões climáticas, o sistema é capaz de identificar padrões e antecipar ações em regiões com alto risco de incêndios florestais como na Amazônia. 
Drones equipados com sensores térmicos são acionados para realizar o monitoramento em tempo real dessas áreas, aplicar retardantes de chamas quando necessário e executar técnicas de cloud seeding (semeadura de nuvens) para estimular chuvas em regiões críticas prevenindo possíveis queimadas. 
A plataforma também realiza a coordenação automatizada de equipes de emergência em terra como os agentes da Defesa Civil e bombeiros; organiza o envio de recursos ao local da ocorrência, registra o histórico das ações e prioriza as intervenções conforme o grau de risco identificado. Dessa forma, a solução atua de maneira preventiva e reativa, otimizando o tempo de resposta e minimizando os danos causados pelos incêndios.

•	Estímulo de Nuvens (Cloud Seeding)
O cloud seeding é uma técnica que busca estimular a precipitação em nuvens que já possuem umidade, por meio da dispersão de substâncias como iodeto de prata, sal (cloreto de sódio) e dióxido de carbono congelado (gelo seco). Esses agentes agem como núcleos de condensação, acelerando a formação de gotas de chuva ajudando no combate direto a focos de incêndio em áreas remotas. 
•	Uso de Drones no Cloud Seeding e no Monitoramento

a)	Estímulo de nuvens
Drones equipados com dispersores de iodeto de prata poderão voar até as nuvens identificadas como aptas para o estímulo. 

b)	Monitoramento e prevenção 
Drones com sensores térmicos e câmeras multiespectrais poderão detectar pontos de calor em tempo real, monitorar áreas de risco antes que o fogo se inicie e apoiar equipes de terra com imagens aéreas em incêndios ativos. 

FUNCIONAMENTO
Ao iniciar o programa, o usuário escolhe, em um menu, as seguintes opções: 1) verificar os dados climáticos em tempo real dos locais mais críticos; 2) detectar possíveis focos ativos de queimadas, 3) buscar ocorrência ou 4) sair do programa. Os dados são coletados de sensores fixos, estações meteorológicas, câmeras com IA, satélites e drones, os quais são recebidos pela plataforma, via APIs meteorológicas e geoespaciais confiáveis. O sistema avalia riscos com base em temperatura, umidade, vento, fumaça, NDVI (Índice de seca ou vegetação) e precipitação. Havendo risco, envia notificações como “Alerta! Possível risco de incêndio” e pergunta ao usuário se deseja ativar o Cloud Seeding, podendo fazer isso automaticamente. Se houver focos ativos, o sistema criará uma operação em que drones com retardantes serão enviados e equipes de terra serão coordenadas para o local. Relatórios completos são gerados com números de protocolo, imagens geolocalizadas, status da operação e dados da equipe. O sistema também salva esses relatórios, que podem ser buscados por número de protocolo, nome da operação ou região, para futuras análises e auditorias. Todas as ações e notificações são registradas para garantir rastreabilidade e transparência.

INSTRUÇÕES DE USO DO PROGRAMA:

. Pré-requisitos
- Python 3 instalado
- Ambiente Jupyter (VS Code + extensão Jupyter)
- Importar random, time, bisect e datetime, que são módulos da biblioteca padrão do Python.
- Foi utilizado todos os itens do conjunto 3:Analise de algoritmos/notação O grande, Busca binária, dicionários

1: Gera dados climáticos aleatórios para locais de alto risco e alerta, se houver condição de incêndio (cloud seeding)

2: Simula detecção de focos ativos, lista prioridades e permite registrar operação reativa (quando já há a queimada)

3: Pesquisa ocorrências/relatórios já gerados. (Disponível somente após a criação de pelo menos um relatório.)
- Protocolos seguem o formato: P0001, P0002,
- Para pesquisar por tipo, digite preventiva ou reativa (após a geração de um relatório)
- As buscas por texto não diferenciam maiúsculas de minúsculas.
- Sempre verifique se já houve geração de relatório antes de usar a opção 3.

4: Encerra o programa.



