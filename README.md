## Tarefa : Agrupamento e Redução de Dimensionalidade

Descrição do problema:

Nesse laboratório iremos aplicar os conceitos de agrupamento e redução de dimensionalidade em dados textuais, mais especificamente, em dados de letras de música. A ideia é encontrar grupos em letras de músicas de três gêneros musicais.

Link para os dados:

Os dados para este laboratório foram coletados pelo professor Nazareno Andrade, estando disponíveis no GitHub Links to an external site.. São eles:

Rock: link Links to an external site.
Samba: linkLinks to an external site.
Sertanejo: linkLinks to an external site.
Descrição dos dados:

SName: Coluna que contém o título da música
Lyric: Coluna que contém a letra da música
Artist: Nome do artista ou banda
Songs: Número de músicas do artista. Caso o mesmo artista tenha mais de uma música no conjunto, o valor dessa coluna estará repetido em todas as músicas.
Popularity: Popularidade do artista. Caso o mesmo artista tenha mais de uma música no conjunto, o valor dessa coluna estará repetido em todas as músicas.
Genre: Gênero da música.
Genres: Gêneros possíveis.
As atividades esperadas para essa etapa são descritas a seguir:

Escolha um ou mais conjuntos de letras de músicas e realize as etapas descritas a seguir:

Utilize o k-means para procurar grupos de músicas, identificando o melhor número de grupos através das técnicas explicadas nas aulas. Em seguida, descreva os grupos encontrados, listando as palavras e os artistas mais frequentes em cada grupo. Tente nomear os grupos e explique em detalhes o racional para sua nomeação para cada grupo. Repita este processo utilizando como entrada para o k-means:
O título da música;
A letra da música;
A concatenação do título e letra;
Mesmo que 1 acima, mas aplique uma redução de dimensionalidade utilizando o PCA, e utilize os dados transformados como entrada para o k-means. 
Compare a qualidade dos grupos com e sem PCA usando o coeficiente de silhueta.
Utilize o PCA e t-SME e gere visualizações dos grupos encontrados nas questões anteriores. As visualizações indicam que os grupos são bem separados? Por que você acha que sim ou que não?


