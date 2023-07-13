<h1> EXPRESSÕES REGULARES </h1> 

<h2> regexr.com (site usado teste de ER) </h2>

<h4> Qual a sua função na  pratica </h4>    

    - Realizar uma pesquisa para validar se existe uma determinada informação 
    - não pesquisa uma palavra e sim uma combinação de letras

<h2> Comandos </h2>

    // - ER sempre fica entre barras
    /./g - pesquisar todo os caracteres
    /d./g - todas as letras d e o . ponto serve para que aceite qualquer letra
    /e|é/g - (OU) pesquise todos os e ou é
    /()/g - criando um grupo
    /[]/g - itens individuais, que não precisam estar em sequencia  
    /[a-e]/g - todas as letras que estão entre o "A" e "E" (a, b, c, d, e)
    /[^a]/g - todas as letras menos a letra "A" (ate os espaços e acentos)
    /[A-E]/g - todas as letras MAIUSCULAS que estão entre o "A" e "E" (A, B, C, D, E)
    /(e+)/g - somente uma sequencia de "ss" criando um grupo entre os SS
    /(s)?/g - torna o grupo como opcional
    /s{2}/g - somente vai achar 2 "S" em sequencia (Ex: essência) 
    /s{2,}/g - somente vai achar 2 ou mais "S" em sequencia (Ex: essência)
    /^ a/g - so retorna se iniciar com "a" 
    /a $/g - so retorna se terminar com "a"
    /\./g - procura literalmente "."   
    
    
    
  
  <h4> Flags </h4>

      //g - (Global)   todas as letras
      //i - (Case insensitive)   não diferencia as maiúsculas das minusculas


  <h2> Exemplos </h2>

      para procurar um email:
        - /([a-z0-9]{2,})@(a-z0-9{2,})(\.[a-z]{2,})(\.a-z{2,})?/g

      para procurar telefone:
        - /\([0-9]{2}\)\s([0-9]{4,5})\-([0-9]{4})/g



    
