A versão postaa aqui, é um pequeno corte de todo o trabalho desenvolvido.

O objetivo deste projeto foi criar um modelo de regressão classificatória para prever falhas em ferramentas de usinagem. 
Utilizamos dados extraídos do repositório da UCI, enfrentando desafios significativos, como um dataset extremamente desbalanceado e um 
número limitado de variáveis preditoras.
Tomamos várias decisões ao longo do projeto. A escolha do algoritmo, por exemplo, foi automatizada utilizando o algoritmo LazyPredict,
enquanto a seleção das métricas mais adequadas para o cenário, como F1-Score e accuracy, foi considerada uma decisão minha de qual utilizar.

Tratei os outliers com diferentes abordagens, como Z-score e IQR, e enfrentamos a questão dos valores ausentes, decidindo quais variáveis
preditoras deveriam ser mantidas ou excluídas do treinamento.

Além disso, realizamos uma avaliação detalhada da correlação e importância das variáveis, analisando a distribuição delas em torno da 
média para identificar similaridades, assim como estudamos assimetrias (skewness) e curtoses. Esses foram alguns dos muitos desafios e 
análises que enfrentamos durante a construção deste projeto.
