---
title: Módulo 3 - Epistemologia da Ciência da Informação
# subtitle: 
tags:
  - science information
  - chronography
  - information retrieval
author: >-
    Gabriel Santiago Macedo^[Universidade Federal do Rio de
    Janeiro (UFRJ), Instituto Brasileiro de Informação em Ciência e
    Tecnologia (IBICT), Programa de Pós-Gradução em Ciência da 
    Informação (PPGCI), gabrielmacedo@discente.ibict.br, 
    [orcid:0000-0001-8845-7985](https://orcid.org/0000-0001-8845-7985);
    Disciplina - Cronografia da Ciência da Informação, Docente - 
    Lillian Maria Araujo de Rezende Alvares.]
# author:
#  - name: Gabriel Santiago Macedo
#    email: gabrielmacedo@discente.ibict.br
#    orcid_id: 0000-0001-8845-7985
#    affiliation: 1
# affiliation:
#  - name: 
#      Universidade Federal do Rio de Janeiro (UFRJ), Instituto 
#      Brasileiro de Informação em Ciência e Tecnologia (IBICT), 
#      Programa de Pós-Gradução em Ciência da Informação (PPGCI)
#    index: 1
date: 02/07/2023
abstract: >-
    Resumo do Módulo 3 da disciplina "Cronografia da Ciência da 
    Informação",  "Epistemologia da Ciência da Informação", 
    Docente - Lillian Maria Araujo de Rezende Alvares.
copyright:
  statement: >-
    © 2023 The author. Published under a CC BY-SA 4.0 license.
  year: 2023
  holder: Gabriel Santiago Macedo
license:
  - text: >-
      This work is licensed under a Creative Commons
      Attribution-ShareAlike 4.0 International License.
    type: open-access
    link: 'https://creativecommons.org/licenses/by-sa/4.0/'
  - >-
      The copyright holder grants the IBICT permission to 
      archive and post a copy of this paper in the journal 
      article databases.
bibliography: "https://raw.githubusercontent.com/gabrielmacedo/ci/main/biblioteca.bib"
csl: "https://github.com/gabrielmacedo/ci/raw/main/abnt.csl"
lang: pt-BR
draft: true
---

# Módulo 3: Epistemologia da Ciência da Informação

Este resumo apresenta um recorte sobre o percurso histórico da epistemologia da Ciência da Informação (CI). A natureza cronográfica a ser empregada neste texto tem por objetivo identificar os eventos relacionados ao estudo da informação em face das novas tecnologias, especialmente quanto ao campo da _Recuperação da Informação_ (RI).

Considerando que a epistemologia busca compreender a natureza do conhecimento científico, suas bases, limitações e métodos, uma análise das tecnologias contemporâneas de Processamento de Linguagem Natural (PLN), em inglês _Natural Language Processing_ (NLP), para a recuperação de informações requer, inicialmente, a identificação dos marcos do seu desenvolvimento e a compreensão da relação temporal estabelecida entre estes.

Atualmente, com a ampla adoção de sistemas de PLN, como o ChatGPT (_Generative Pre-trained Transformer_), a análise da evolução desses modelos torna-se ainda mais relevante para os pesquisadores da ciência da informação que estão interessados em aprofundar o entendimento das interrelações entre informação e tecnologia. 

Ao abordar as formas de recuperação da informação produzidas por esses sistemas, os pesquisadores podem realizar uma avaliação crítica das limitações e contribuições apresentadas, além de expandir a capacidade de identificar áreas não exploradas, desafios em aberto ou questões não resolvidas que demandam atenção e investigação adicional.

Podemos nos perguntar se, seriam os atuais modelos de interação homem-máquina como o ChatGPT, ou seja, interfaces com sistemas pré-treinados para realizar conversas em linguagem natural uma resposta consistente aos problemas de _complexidade e difusão de conhecimento_ ou mesmo de _explosão informacional_, sob os quais se debruçaram respectivamente Paul Otlet e Vannevar Bush?

A relação entre a tecnologia e a informação foi abordada por esses e outros autores ao longo do tempo, sendo uma questão central à ciência da informação desde a sua proposição enquanto ciência, no início dos anos 1960. A recuperação da informação, em específico, foi até considerada como "o  _núcleo_  da  área  por diferentes autores, entre os quais Saracevic, em seu livro _Introduction to Information Science de 1970_" [@araujo2014].

Visando dar continuidade ao trabalho empenhado no resumo anterior, do módulo 02, adotaremos aqui o recorte temporal entre o final dos anos 1950 e o início dos anos 1970. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.

Os problemas de recuperação da informação que motivaram Cyril Cleverdon, um ex-bibliotecário da _Engine Division of the Bristol Aeroplane Co. Ltd._, a implementar o _The ASLIB Cranfield Research Project_, no _College of Aeronautics at Cranfield_, e os testes que o sucederam, entre 1958 e 1963 que foram realizados também em outros centros de estudos são exemplos seminais abordados por autores da ciência da informação [@araujo2014].

Os projetos consistiram numa pesquisa, inicialmente sem a utiliação de computadores, com o objetivo de melhorar a eficiência dos sistemas de recuperação de informação, avaliando melhores linguagens e métodos de indexação [@cleverdon1960; @cleverdon1967].

O primeiro projeto, iniciado em abril de 1958, foi caracterizado pela comparação de 4 modelos de indexação sob uma coleção de documentos de aviaçao: Classificação Decimal Universal (CDU), catálogo de assuntos em ordem alfabéfica, esquema de classificação facetada, sistema de termo único. Os testes envolveram a comparação da eficiência relativa de cada um dos quatro índices em comparação a um conjunto de questões. As questões usadas foram produzidas por representantes de cerca de cinquenta organizações no Reino Unido, Estados Unidos, Canadá e Holanda [@cleverdon1960]. 

Ao tratar detalhadamente das razões de fracasso ou de sucesso na busca de informação relevante, o projeto objetivou levantar os requisitos que um sistema de recuperação de informação deveria atender. Cleverdon [-@cleverdon1960, p.9] indica que a ausência de experimentos práticos atrelados às teorias de indexação a superestimavam, "todos aqueles que tentam resolver os problemas de recuperação de informações estão trabalhando muito no escuro, incertos quanto aos problemas reais e totalmente incapazes de aplicar quaisquer medições às soluções propostas". 

Assim, conclui que o requisito principal para avaliar a recuperação da informação é um padrão de medição reconhecido e um método de medição satisfatório. E, com o projeto, esperavam ter dados suficientes para formar um padrão de medição para sistemas de recuperação [@cleverdon1960]. Em termos de desempenho, foi constatado que todos os sistemas operavam em níveis próximos de eficiência [@cleverdon1967].

Em 1963, cinco anos após o início dos experimentos, os testes realizados com a documentação de metalurgia da _Western Reserve University_, seviram para estabelecer duas medidas utilizadas para avaliar os sistemas, a taxa de recuperação ou revocação (_recall ratio_) e a taxa de precisão (_precision ratio_) [aitchison1963; @cleverdon1967]. 

![Figura 1: Recuperação/Precisão, @cleverdon1967](https://github.com/gabrielmacedo/ci/assets/20596966/7afc38a1-ca30-4a0b-88ff-be5259f718da)

Os resultados dos testes indicaram a relação inversa entre recuperação e precisão. Considerando que a taxa de recuperação máxima possível de 100 por cento pode ser obtida ao recuperar todos os documentos disponíveis, a melhoria na taxa de precisão implicaria portanto numa queda na taxa de recuperação. De forma inversa, para aumentar a taxa de recuperação, um maior número de documentos não relevantes também seriam recuperados. "Este é sempre o caso ao operar dentro de um determinado sistema" [@cleverdon1967, p. 179].

Outra abordagem de indexação foi porposta por Salton com o sistema SMART (_System for the Mechanical Analysis and Retrieval of Text_), desenvolvido nos anos 1960. Embora tratasse de problemas semalhantes aos que estavam sendo trabalhados em Cranfield, ao comparar os efeitos de diferentes formas de indexação de textos, havia diferenças significativas entre as duas abordagens. A mais significativa delas consistia na utilizava de computadores por Salton, permitindo processamento avançado de dados e algoritmos complexos, enquanto os experimentos de Cranfield dependiam de técnicas manuais e estatísticas [@cleverdon1967].

Uma das principais contribuições do sistema SMART foi o desenvolvimento do modelo de espaço vetorial (_vector space model_) para recuperação de informações. Esse modelo utilizava representações matemáticas dos documentos e das consultas para calcular a similaridade entre eles. Em vez de se basear apenas na presença ou ausência de palavras-chave, o modelo vetorial considerava a relevância e importância relativa dos termos, permitindo uma recuperação mais precisa. Além disso o SMART implementou a indexação automática de documentos, utilizando técnicas como a extração de palavras-chave e a atribuição de pesos aos termos com base em sua frequência nos documentos. O SMART também introduziu a ideia de consultas interativas, permitindo aos usuários refinar suas consultas com base nos resultados apresentados. Isso possibilitava uma interação mais dinâmica entre o usuário e o sistema de recuperação de informações [@salton1965].

> "O sistema pode ser controlado pelo usuário de modo que uma solicitação de pesquisa possa ser processada primeiro em um modo padrão; o usuário fica então livre para analisar a saída obtida e, dependendo de seus requisitos adicionais, uma reavaliação da solicitação pode ser solicitada sob novas condições. A nova saída pode ser novamente examinada e o processo iterado até o momento em que o tipo e a quantidade correta de informações sejam recuperados" [@salton1965]. (tradução automatizada com correções manuais)

Apesar das metodologias divergentes, tanto o desenvolvimento do SMART quanto dos projetos de Cranfield fizeram contribuições significativas para o campo da recuperação de informações. No entanto, enquanto o PNL avançava nos modelos de indexação, as tarefas de tradução automatizada (_machine translation_) passaram a ser questionadas.

Após a não concretização das altas expectativas geradas com o experimento de tradução automatizada do russo para o inglês, iniciado no experimento da Georgetown-IBM de 1954, o governo dos Estados Unidos cria 10 anos depois, em 1964, o ALPAC (_Automatic Language Processing Advisory Committee_). O ALPAC foi um comitê composto por sete cientistas, liderado por John R. Pierce, com o objetivo de avaliar o progresso da linguística computacional e da tradução automatizada. 

O relatório intitulado _Language and Machines_, publicado 02 anos depois pelo ALPAC, em 1966, é cético sobre o custo e a eficácia da tradução automatizada, indicando que para o estado atual da tecnologia não houve a tradução de texto científico geral e que a utilidade das traduções dependeria de pós-edição humana. O documento ainda enfatiza que seria necessário ampliar a pesquisa básica em lingüística computacional e na construção de auxílios de máquina para tradutores humanos [@alpac1966]. 

Em suma, o comitê avaliador considerou que a tradução mecanizada era mais cara, mais lenta e menos precisa do que um tradutor humano [@alpac1966; @josselson1971]. Como consequência, o relatório acabou fazendo com que o governo dos Estados Unidos reduzisse o financiamento do tema.

Josselson [-@josselson1971] ao abordar a reação soviética ao relatório, com base no documento _Nauchno-Tekhnicheskaja Informatsija_ (Informação Técnico-Científica) publicado em 1968, destaca que a avaliação do comitê foi encarada como muito estreita e pragmática, pois não refletia as potencialidades da tradução automatizada. Para os soviéticos, esta tecnologia carregava ideias para resolver "um dos problemas mais importantes do século XX, os problemas envolvendo a simbiose entre homens e máquinas" [Nauchno-Tekhnicheskaja _apud_ @josselson1971, p. 47].




Entre 1968 e 1970, Terry Winograd desenvolveu o SHRDLU, um programa de demonstração voltado à compreensão de linguagem natural em inglês, usando as linguagens LISP e Planner. Em sua tese no Massachusetts Institute of Technology (MIT), publicada em 1971, sob o título _PROCEDURES AS A REPRESENTATION FOR DATA IN A COMPUTER PROGRAM FOR UNDERSTANDING NATURAL LANGUAGE_ o autor descreve o sistema como um modelo capaz de receber comandos e de interagir em linguagem natural, respondendo a frases e realizando ações, além de pedir esclarecimentos quando não consegue deduzir, ou seja, fazer inferência sobre o sentido de uma interação com base no contexto disponível. 

Seu objetivo era superar os problemas de manipulação apenas sintática e gramatical presentes nos primeiros sistemas de tradução automatizada, como os aplicados na tradução entre inglês e russo. O autor reconhecia a necessidade de lidar com os aspectos semânticos e de conferir aos computadores a capacidade de usar um conhecimento prévio sobre os assuntos para os quais deveria oferecer resposta. O entendimento da linguagem por máquinas deveria combinar "gramática, semântica e racioncínio de uma maneira muito íntima, chamando cada parte para ajudar as outras" [@winograd1971, p. 12].

![Grafo indicando o funcionamento do programa SHRDLU. As setas indicam qual parte do programa aciona a outra - @winograd1971](https://github.com/gabrielmacedo/ci/assets/20596966/1c8d43f6-6644-432d-b9cb-b7e6b67d199a)



Os primeiros sistemas de recuperação da informação 


...
em razão de terem sido referenciadas por @gao2023 para a compreensão dos modelos de Recuperação de Informações Conversacionais (RIC), em inglês _Conversational Information Retrieval_ (CIR), dos quais fazem parte ferramentas como o ChatGPT.
...






LANCASTER, 1968


com base principalmente na sistematização apresentada por @ingwersen2005




Os estudos de Cranfield lançaram conceitos sobre a ciência da computação e a consulta de informações, como _revocação_ e _precisão_, que foram relevantes para o desenvolvimento de sistemas de busca.






Recuperação de Informações Conversacionais (RIC), em inglês Conversational Information Retrieval (CIR), com foco nas abordagens neurais que foram desenvolvidas nos últimos anos. O progresso no aprendizado profundo trouxe grandes melhorias no processamento de linguagem natural (NLP) e na IA de conversação, levando a uma infinidade de serviços de conversação comercial que permitem interação naturalmente falada e digitada, aumentando a necessidade de mais interações centradas no ser humano (no usuário) na recuperação de informações [@gao2023].


Fuzzy para recuperação de informação



por @pinheiro1995, o avanço da computação e da inteligência artificial promovem mudanças significativas na compreensão dos fenômenos informacionais. 


Para Robinson e  [-@robinson2010], ao tratar dos modelos quantitativos de informação,


Mudar o canal na teoria da situação equivale a mudar os tipos de inferências feitas sobre entidades ou objetos. O canal, portanto, determina o que pode ser conhecido sobre uma situação.

a construção da ontologia em um canal marca os limites da utilidade da teoria para a ciência da informação. Em outras palavras, a teoria da situação permite deduções uma vez que um modelo do mundo é dado em termos de objetos e canais que representam as relações entre eles. O problema principal é justamente a construção do modelo qualitativo do mundo que fornece a base para fazer inferências. 



A CENTRALIDADE DOS PROBLEMAS DE LINGUISTICA




Sinalizamos que tomamos aqui o conceito de informação como visto por xxxx em xxxxx, no qual há uma relação funcional para a caracterização do conceito, ou seja, ele deve responder à uma intenção teleológica e de utilidade para os usuários, mais do que a uma busca por uma definição terminológica precisa.
estabelecer uma base sólida de conhecimento científico para orientar a pesquisa e a prática nessa área.




Assim, será dada especial atenção ao diálogo da Ciência da Informação com a Computação, e




ênfase à recuperação de informações, considerando sua vertente pragmática e tecnológica, 

. É importante destacar que essa relação já foi observada por diversos autores no passado, sendo portanto uma vertente comum aos estudos informacionais [@borko1964; @harmon1971]. No entanto, renovar esse empenho é fundamental para a contínua evolução da ciência, o que demanda dos cientistas da informação a realização periódica de revisões em seus pressupostos ou mesmo a redefinição dos elementos estruturais fundamentais, quando se faz necessário [@zins2007].

De modo mais específico, serão buscados os principais marcos e os pioneiros que exerceram influência no desenvolvimento da interação homem-máquina quanto ao processamento de linguagem natural, no período compreendido entre o nascimento da computação moderna, em 1936, e as primeiras experiências de tradução automatizada (_machine translation_), em 1954. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.







Quanto ao primeiro experimento de machine translation, em 1954, os dois principais pesquisadores envolvidos foram Paul L. Garvin, que fez o trabalho linguístico, e Peter Sheridan, responsável pela programação. Foi desenvolvido um sistema de pequena escala para traduzir frases do russo para o inglês. Em 7 de janeiro de 1954 a demonstração ocorreu na sede da IBM em Nova York, com testes na tradução entre o idioma russo e inglês. Foram inseridas várias mensagens curtas, compreendidas no intervalo de 250 palavras do dispositivo, que incluíam breves declarações em russo sobre: política, direito, matemática, química, metalurgia, comunicações e assuntos militares. As frases foram então transformadas para inglês sem intervenção humana [@hutchins1997].

Com base nos avanços atuais das tecnologias de processamento de linguagem natural e aprendizado de máquina, é possível considerar a abordagem de Shannon para um preditor de texto como uma das precursoras dos modelos de previsão de próxima palavra. Esses modelos têm ganhado destaque devido à sua aplicação em larga escala, impulsionada pelo progresso dos algoritmos de aprendizado de máquina e pelo aumento do poder de processamento computacional. A contribuição de Shannon nessa área representa um marco importante na evolução desses modelos, que visam melhorar a capacidade de antecipação e sugestão de palavras com base no contexto textual.

Além disso, o modelo de previsão de próxima palavra tem sido utilizado em diversas outras aplicações, como tradução automática, correção automática de texto, completamento de frases, geração automática de texto e até mesmo em assistentes virtuais. A previsão de próxima palavra é uma técnica fundamental para melhorar a eficiência e a precisão dessas aplicações.

A retomada do percurso histórico empreendido nesse resumo preliminar é importante devido à herança que as tecnologias de interação atuais possuem desse desenvolvimento. Isso se deve ao fato de que essas tecnologias computacionais colocam a interação em linguagem natural - e sua consequente tradução - como elemento central na operação de máquinas. Portanto, compreender as origens desse desenvolvimento histórico proporciona uma base sólida para o entendimento das interações homem-máquina contemporâneas.

Em que pese as raízes históricas da CI remontarem a interrelação de diversos campos ciêntificos quanto ao problema da disponibilidade de acesso à informação, serão as modificações impulsionadas pelos esforços de guerra e a estrutura de reprodução do capitalismo do século XX, os fatores responsáveis pela ampliação exponencial da produção e difusão de informações. E é nesse contexto de explosão informacional, principalmente após a segunda guerra, que ocorrerá a consolidação da CI enquanto um campo disciplinar, com as raízes estabelecidas na necessidade de especialização do trato informacional, culminando no início dos anos de 1960 na formulação dos primeiros conceitos da CI e na promoção de debates voltados à delimitação do seu campo [@pinheiro1995; @alvares2010].


Os recentes avanços no processamento de linguagem natural destacam a importância de uma compreensão qualitativa aprofundada, por parte do campo da Ciência da Informação, sobre a renovação das práticas de recuperação de informações. A revisão cronológica apresentada neste trabalho, que aborda as origens do desenvolvimento de sistemas computacionais de tradução automática, contribui para alcançar esse objetivo. Nesse sentido, a adoção de uma perspectiva centrada na tecnologia como meio de observação da Ciência da Informação desempenha um papel fundamental na compreensão desse campo. Essa abordagem não apenas faz parte da essência dessa disciplina, mas também traz consigo novas perspectivas aos profissionais envolvidos, enriquecendo a capacidade de compreensão dos desafios enfrentados.

## Referências