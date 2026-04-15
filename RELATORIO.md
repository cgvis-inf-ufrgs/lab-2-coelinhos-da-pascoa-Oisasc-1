# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`00303938`</mark>
- **Nome**: <mark>`Isasc Ventura de Oliveira`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<mark>`
    1- VEREFICAR O CÓDIGO

    Parar para olhar o código, alterando ele para descobrir como ele funciona,
    usando funções vistas em aula para ver como elas se comportam.

    2- TAMANHO DOS OBJETOS, FORMATO E POSIÇÃO

    Primeiro defini o tamanho da esfera e seu formato usando Matrix_Scale, logo depois posicionando
    o coelho e o ovo (esfera) para longe da origem usando Matrix_Translate.

    3- ANIMAÇÃO E TIPOS DE MOVIMENTO

    Tentar fazer com que os objetos se movam usando glfwGetTime() (o atribuindo a variavel 'anima' para
    utiliza-lo melhor), utilizando Matrix_Translate e Matrix_Rotate depoios de algumas boas tentativas
    consegui fazer com que girem como deveriam pela orbita da origem, tentei fazer cada coelho e ovos a
    mão, mas no fim decidi por usar um FOR(que parece muito obvio agora...).
    
    4- ROTAÇÃO INDIVIDUAL COELHO E ROTAÇÃO DOS OVOS

    Após conseguir fazer com que os ovos acompanhacem os coelhos utilizei Matrix_Rotate para
    ajustar a rotação pelo os eixos do coelho.

    Utilizando um if (i == 3 || i == 7 || i == 11 || i == 15) separei um coelho a cada 4 da fila para
    receber uma multiplicação de matrizes alterando sua rotação, aqueles que não eram selecionados
    eram multiplicados por uma matriz identidade, assim permanecendo normais.

    5 - REFINAMENTO
    
    Após fazer o "grosso" fui refinando até ficar o mais próximo posível do exemplo dado como resultado
    esperado, todas as partes foram feitas repetidas vezes até um resultado aceitavel.


`</mark>

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

<mark>`
    Demorei a perceber que as rotações estavam em radianos, e concerteza a ordem de multiplicação
    de matrizes, muitas vezes eu acabei por trocar e até eu perceber demorava.
`</mark>

## Você acha que conseguiu resolver o problema de forma adequada?

<mark>`
    Creio que sim, no entanto tenho certeza que tem como otimiza-lo, o deixando bem melhor. Como
    também refina-lo o deixando o mais próximo ainda do resultado esperado.
`</mark>

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>`
    Achei a atividade bem completa, reforçou o que vimos em aula.
`</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
