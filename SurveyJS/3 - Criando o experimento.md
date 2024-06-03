# Criando o experimento

<details>
<summary><strong>Sumário</strong></summary>
  
* [A primeira pergunta](#a-primeira-pergunta)
* [Tipos de pergunta](#tipos-de-pergunta)
  * [Múltipla escolha](#múltipla-escolha)
  * [Escala de classificação](#escala-de-classificação)
  * [Caixas de seleção](#caixas-de-seleção)
  * [Lista suspensa](#lista-suspensa)
  * [Lista suspensa de múltipla seleção](#lista-suspensa-de-múltipla-seleção)
  * [Ranking](#ranking)
  * [Subjetivas](#subjetivas)

</details>

A criação de um bom experimento envolve diversas etapas, como um bom desenho do estudo, um objetivo bem delineado, dentre outros processos e informações. Assim, nesse guia serão apresentados os componentes disponibilizados pela plataforma e como utilizá-los de forma geral.

## A primeira pergunta
Ao clicar no botão _Add question_, uma nova pergunta surge na tela e alguns novos campos aparecem:

**1. Nova página e nova pergunta**  
Adicionando uma nova pergunta, automaticamente é criada uma nova página, e você pode ou não definir um título e uma descrição para a página. Além disso, é possível escrever a sua pergunta no lugar de _question 1_.

**2. Tipo de pergunta**  
O SurveyJS conta com diferentes tipos de questões, como rankings, classificações, perguntas objetivas, subjetivas, entre outras. Nesse caso, o tipo da pergunta é preparado para respostas de até 1 linha. Caso queira trocar o tipo da pergunta, basta selecionar esse campo e trocar (ou selecionar um novo tipo de elemento no menu esquerdo).

**3. Tipo da resposta**  
As perguntas que possuem como resposta algum tipo de texto também podem ser configuradas para receber algum formato específico, como um link, número de telefone, senha, etc. E a seleção de tipo da resposta server justamente para permitir que apenas os tipos solicitados sejam levados em consideração na hora da resposta.

**4. Configurações gerais da pergunta**  
Por ser uma aba de configuração geral, a _General_ sempre irá abrir ao adicionarmos um novo elemento no experimento, e através dela podemos alterar o nome da pergunta (nesse caso para o controle de quem está criando o experimento), o título da pergunta (aquele que será exibido), o tipo de dado da resposta (3), o texto de exibição (texto que fica sendo mostrado no campo mas não é contabilizado como resposta), entre outras configurações.

Os demais campos dentro da questão (1) servem para duplicar a pergunta, tornar a pergunta obrigatória e deletar a pergunta.

![A primeira pergunta](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/639aa164-1800-4495-a6f9-58dc4ae0d667)

## Tipos de pergunta

### Múltipla escolha 
A questão de múltipla escolha (_Radio Button Group_) cria uma nova pergunta que exibe diversas opções de resposta ao participante, contudo, apenas uma pode ser escolhida.

![Múltipla escolha](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/2f21cceb-8dcf-4a39-b475-29e48856aa9a)

### Escala de classificação
A escala de classificação (_Rating Scale_) permite a classificação de algum elemento que for exibido na pergunta. Existem 3 diferentes formas de classificação no SurveyJS: a numérica, a que usa estrelas para representar a classificação e a que utiliza emoticons (alterável no campo _Labels_).

![Escala de classificação](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/22458842-94de-4d90-bd74-53e79d734bcf)

### Caixas de seleção
As caixas de seleção (_Checkboxes_) seguem o mesmo layout da questão de múltipla escolha, porém, a diferença aqui é que mais de uma opção pode ser marcada como resposta.

![Caixas de seleção](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/6ebbdc2a-7795-49b8-aabf-aff53aa2ff18)

### Lista suspensa
A lista suspensa (_Dropdown_) tem o mesmo objetivo da questão de múltipla escolha, a seleção de apenas um item. A principal diferença aqui está na exibição, onde ao invés das opções aparecerem em diferentes linhas e possuírem um campo para marcação ao seu lado, elas estarão contidas em uma lista que mostra as opções e permite a seleção de uma delas.

![Lista Suspensa](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/ed4592ce-7443-4090-82e5-a7111181f8ef)

### Lista suspensa de múltipla seleção
É exibida exatamente igual à anterior, porém, permite a seleção de uma ou mais opções.

![Lista Suspensa múltipla](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/6a42b821-e3fe-486f-8c0a-0403d5520a97)

### Ranking
A pergunta com ranking envolve a ordenação de acordo com algum critério (estabelecido na pergunta) de 2 ou mais opções.

![Ranking](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/8ab74591-6464-482e-a3f6-bef8c0ab383e)

### Subjetivas
As perguntas subjetivas podem ser divididas em 3 tipos dentro do SurveyJS: resposta curta, resposta longa e múltiplas respostas. Os nomes são bem sugestivos, então a escolha depende sempre do objetivo. Das três, a mais "incomum" é a de múltiplas respostas, que permite a inserção de diferentes frases como uma mesma resposta:

![Subjetivas](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/fc490c76-2866-4e8b-84c4-ec91b6ab1c3b)

---
