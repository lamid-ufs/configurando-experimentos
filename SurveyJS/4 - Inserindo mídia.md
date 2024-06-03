# Inserindo mídia

<details>
  
  <summary><strong>Sumário</strong></summary>

* [Inserindo imagem](#inserindo-imagem)
* [Inserindo vídeo](#inserindo-vídeo)
* [Inserindo áudio](#inserindo-áudio)

</details>

A inserção de mídia em experimentos no SurveyJS pode ser muito simples ou muito complicadas (não existe meio termo), tudo depende do que você precisa.

## Inserindo imagem
A inserção de imagem é uma tarefa bem simples. Basta clicar no elemento _Image_ no menu esquerdo e a questão já será adicionada no experimento. A seleção da imagem ocorre através do botão _Choose image_, onde você selecionará uma imagem que esteja no seu computador e a enviará para o SurveyJS.  Também é possível inserir uma imagem através de um link, basta ir na aba _General_ e inserir o link da imagem no campo _Image or video file URL_.  
Editar as propriedades da imagem também é bem tranquilo, basta percorrer o menu direito iniciando pela aba _General_ que você encontrará configurações como tamanho, tamanho das bordas, identificador da imagem, entre outras.

![Inserindo imagem](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/12f70d76-35e2-4662-8fe0-52b4b858f03e)

## Inserindo vídeo
O processo de inserção de vídeo é igual ao de imagem, inclusive, ocorre no mesmo campo. A principal diferença aqui é que ao abrir o explorador de arquivos do seu computador, você deve trocar a opção de "Arquivos de imagem" para "Todos os arquivos", o que permitirá encontrar vídeos. 

![image](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/59526c9f-eeae-4576-8004-0f31f817fd03)

Também podem ser inseridos vídeos do YouTube, indo na aba _General_ e inserindo o link do vídeo no campo _Image or video file URL_.

## Inserindo áudio
A inserção de áudio no SurveyJS é uma tarefa que demanda um pouco de paciência pois não é uma função nativa da plataforma, ou seja, não tem nenhum recurso pronto (como o das imagens e vídeos) que permita a inserção de áudios. Porém, nada que a sabedoria (gambiarra) não dê jeito. Assim, para inserir áudios no seu experimento, siga os passos:
**1. Faça o upload dos seus áudios no Google Drive**

**2. Torne os links dos áudios compartilháveis com qualquer pessoa**    
     Abra o áudio, vá em "Compartilhar", na parte de "Acesso Geral" troque para "Qualquer pessoa com o link" e habilite a função "Leitor". (Lembre de salvar e repetir o procedimento em todos os áudios)  
     
**3. Abra o áudio em uma nova janela**  
     Selecione o símbolo dos 3 pontinhos do lado esquerdo do botão de "Compartilhar" e clique em "Abrir em uma nova janela".

**4. Copie o código do áudio**  
     Ao abrir o áudio em uma nova janela, vá novamente nos 3 pontinhos e clique em "Incorporar item..."    
     Com a janela aberta (semelhante a que está sendo exibida aqui), copie esse código da parte branca.
     
![image](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/54acacfa-2236-4174-a8a8-cf5aa65ed2a0)

Ao copiar o código, você deverá ter algo mais ou menos nesse formato  
```<iframe src="https://drive.google.com/file/d/1l-V2ZsDCc9TOEmFcc5bcWFUax0Epx4pq/preview" width="640" height="480" allow="autoplay"></iframe>```

**5. Abra o elemento HTML no SurveyJS**  
    Volte no seu experimento no SurveyJS e abra o elemento _HTML_ no menu esquerdo. Ao selecionar o elemento HTML, irá aparecer o campo (1) na aba _General_, é lá que você irá colar o código que copiou no drive. Se der tudo certo, você verá algo muito semelhante ao que está sendo exibido na parte (2).

![HTML](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/baf78f8b-25a0-47fa-a3e3-2f2b40f9b726)

**6. Edite o tamanho do player**  
    É bem perceptível que o tamanho do player do áudio não está nada compatível com o tamanho do experimento. Para ajustar o tamanho do elemento vamos mexer no código HTML, mais especificamente nos campos `width="640" height="480"`, que representam a largura e altura do elemento, respectivamente.  
A minha sugestão é deixar da seguinte forma: `width="400" height="70"`. Caso você tenha feito tudo corretamente, o player deve estar sendo exibido da mesma forma que o que está sendo mostrado aqui:

![Player editado](https://github.com/lamid-ufs/configurando-experimentos/assets/88946365/3c8ee838-761b-4ab4-a5df-1d4eccff95c1)

> [!TIP]
> Você pode trocar apenas os números dentro do código, substituindo o 640 por 400 e o 480 por 70, só lembre de deixá-los entre aspas.

---


