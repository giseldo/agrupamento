## 1 
Utilize o k-means para procurar grupos de músicas, identificando o melhor número de grupos através das técnicas explicadas nas aulas. Em seguida, descreva os grupos encontrados, listando as palavras e os artistas mais frequentes em cada grupo. Tente nomear os grupos e explique em detalhes o racional para sua nomeação para cada grupo. Repita este processo utilizando como entrada para o k-means:
O título da música;
A letra da música;
A concatenação do título e letra;
## Respostas 1

P: Utilize o k-means para procurar grupos de músicas, identificando o melhor número de grupos através das técnicas explicadas nas aulas. 

R:  A melhor quantidade de grupos foi 9 com erro (SSD)  de 7,48

P Em seguida, descreva os grupos encontrados, listando as palavras e os artistas mais frequentes em cada grupo. Tente nomear os grupos e explique em detalhes o racional para sua nomeação para cada grupo. 

R: O grupo 0 é chamado de Guloso, por ter palavras como tudo, todo etc

Palavras do Grupo 0: todo mundo, mundo, todo, baby, pra, ninguém, tudo, dia, tchu, bem, quer, fácil, sabe, vida
Artistas do grupo 0: Lulu Santos, Engenheiros do Hawaii, Jota Quest, Blitz, Barão Vermelho, Velhas Virgens, Lobão, Rita Lee, Charlie Brown Jr, Erasmo Carlos,

R: O grupo 1 é chamado de Andarilho, porque tem palavras como vai, gente, vem etc

Palavras do Grupo 1: vai, gente, pra, tudo, bem, vamos, vida, dia, faz, quer, ninguém, sempre, vem, pode
Artistas do Grupo 1: Lulu Santos, Engenheiros do Hawaii, Raimundos, Skank, Charlie Brown Jr, Jota Quest, 
Fresno, Velhas Virgens, Rita Lee, Pato Fu

R: O grupo 2 é chamado de Romantico, porque tem palavras de amor, coração etc
Palavras do Grupo 2: amor, pra, mim, tudo, coração, quero, vida, vou, sol, dor, vem, bem, vai, assim
Artistas do Grupo 2: Jota Quest, Lulu Santos, Erasmo Carlos, Skank, Rita Lee, Los Hermanos, Cássia Eller, Barão Vermelho, Cazuza, Os Paralamas do Sucesso


R: O grupo 3 é chamado de Rotação , porque fala sobre sol, dia, niote etc
Palavras do Grupo 3: nada, pra, dia, faz, vida, quer, tanto, aqui, tudo, sei, deus, noite, quero, luz
Artistas do Grupo 3: Engenheiros do Hawaii, Lulu Santos, Rita Lee, Titãs, Cássia Eller, Raul Seixas, Skank, Erasmo Carlos, Capital Inicial, Os Paralamas do Sucesso    

R: O grupo 4 é chamado de Grudento, porque tem palavas como querto, tudo etc

Palavras do Grupo 4: quero, bem, mim, sei, pra, tão, sempre, tudo, vem, ver, assim, vezes, sinto, pode
Artistas do Grupo 4: Lulu Santos, Engenheiros do Hawaii, Skank, Erasmo Carlos, Cássia Eller, Charlie Brown Jr, Ira!, Rita Lee, Biquini Cavadão, Capital Inicial,

R: O grupo 5 é chamado de Pé no chão, porque tem palavras como hoje, agora etc

Artistas do Grupo 5: Engenheiros do Hawaii, Fresno, CPM 22, Nx Zero, Skank, Jota Quest, Lulu Santos, Rosa de Saron, Dead Fish, Capital Inicial,

R: O grupo 6 é chamado de Americano, porque tem palavras em ingles etc

Artistas do Grupo 6: Jota Quest, Os Paralamas do Sucesso, Rita Lee, Nx Zero, Blitz, Mutantes, Charlie Brown Jr, Dead Fish, Skank, Rosa de Saron

R: O grupo 7 é chamado de Sabe-Tudo, porque tem palavras de sei e vou etc

Artistas do Grupo 7: Jota Quest, Skank, Lulu Santos, Titãs,  Cássia Eller, Charlie Brown Jr, CPM 22, Strike, Fresno, Detonautas

R: O grupo 8 é chamado de Felicidade, porque tem palavras tipo feliz, bela etc

Artistas do Grupo 8: Cássia Eller, Aliados, Jota Quest,  Charlie Brown Jr, Rita Lee, Biquini Cavadão, Los Hermanos, Nx Zero, Barão Vermelho, Leoni

**Falta os artistas**

## 2
Repita este processo utilizando como entrada para o k-means:
O título da música;
A letra da música;
A concatenação do título e letra;


**mudar o nome da coluna**

## 3
Mesmo que 1 acima, mas aplique uma redução de dimensionalidade utilizando o PCA, e utilize os dados transformados como entrada para o k-means. 
Compare a qualidade dos grupos com e sem PCA usando o coeficiente de silhueta.
Utilize o PCA e t-SME e gere visualizações dos grupos encontrados nas questões anteriores. As visualizações indicam que os grupos são bem separados? Por que você acha que sim ou que não?