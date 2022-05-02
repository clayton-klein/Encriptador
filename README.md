# Encriptador de palavras.

**Primeiro Challange do Programa ONE/Alura 2022.**

**Objetivo:**
Desenvolver uma aplicação que criptografa textos, assim você poderá trocar mensagens secretas com outras pessoas que saibam o segredo da criptografia utilizada.

**As "chaves" de criptografia que utilizaremos são:**
- `A letra "a" é convertida para "ai"`  
- `A letra "e" é convertida para "enter"`  
- `A letra "i" é convertida para "imes"`  
- `A letra "o" é convertida para "ober"`  
- `A letra "u" é convertida para "ufat"`  

**Requisitos:**
- Deve funcionar apenas com letras minúsculas.
- Não devem ser utilizados letras com acentos nem caracteres especiais.
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original. 

    Por exemplo:
    `"gato" => "gaitober"`
    `gaitober" => "gato"`

- A página deve ter campos para inserção do texto a ser criptografado ou descriptografado, e a pessoa usuária deve poder escolher entre as duas opções.
- O resultado deve ser exibido na tela.

**Extra:**
- Um botão que copie o texto criptografado/descriptografado para a área de transferência - ou seja, que tenha a mesma funcionalidade do `ctrl+C` ou da opção "copiar" do menu dos aplicativos.

**Minhas observações:**  
- Apesar de já vir estudando programação front-end há uns 5 meses mais ou menos, este foi meu primeiro projetinho prático (tirando os que fiz seguindo exemplos de livros). Me levou muito mais horas do que eu imaginava para desenvolvê-lo (dezenas hehe) e eu tentei colocar em prática um pouco de tudo o que já aprendi até hoje, inclusive um pouco de responsividade que foi algo que o desafio em si não exigiu (pediram para desenvolver apenas uma versão Desktop a princípio).  
  
- As tecnologias utilizadas foram HTML, CSS e JavaScript no geral e uma pequena expressão regular para conseguir filtrar os caracteres especiais. Apesar da expressão regular ser pequena, deu um certo trabalho entender como elaborar uma que atendesse os requisitos do projeto, claro que eu poderia ter resolvido de outras formas, mas eu acredito que a solução com Regex foi a mais elegante.
