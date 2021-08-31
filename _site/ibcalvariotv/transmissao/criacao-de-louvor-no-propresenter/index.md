# Criação de louvor no ProPresenter
<a onclick="window.history.back()">Back</a>

{: .no_toc}

Índice
* TOC
{:toc}

<style>
  .multiColumn {
    column-count: 2;
  }
</style>

Os louvores são transmitidos através de um software chamado [Pro Presenter 6](https://renewedvision.com/propresenter/). 

Ele é gratuito, porém sem algumas funcionalidades, além de conter uma marca d'agua ao transmitir algo.

![Marca D'agua no ProPresenter6](marcadagua.png)

<!-- <video width="100%" controls>
  <source src="https://renewedvision.com/wp-content/uploads/2020/01/promo.mp4" type="video/mp4">
</video> -->

Ele possui diversas funcionalidades, porém o usamos apenas para transmitir a letra dos louvores. Para isso é colocado um fundo verde atrás das letras e um software muda o verde por outra imagem (Pro exemplo das Cameras). Essa técnica é chamada de [chroma key](https://pt.wikipedia.org/wiki/Chroma_key).

<!-- Colocar imagem de exemplo do chroma key -->

## Criando um novo louvor

Para criarmos um novo louvor é necessário criar um arquivo e inseri-lo no Pro Presenter usando o padrão.

### Criando o arquivo

Primeiramente pegue a letra do louvor desejado, seja na internet ou outra fonte. Depois crie um arquivo usando essa letra.

Para criar o arquivo de letras, pode ser usado um editor de texto como o **Bloco de Notas** ![Bloco de Notas](notepad.png), Word ![Word](word.png) ou Notepad++ ![Notepad ++](notepad++.png). É aconselhável que o editor escolhido tenha opção de deixar todas as letras em caixa alta (Maiúsculas), pois esse é o padrão das letras na igreja, e permitir controlar trocar a codificação para Ansi.

* O **Bloco de Notas** permite alterar a codificação, mas não alterar todas as letras para maiúscula.

![Alterando codificação no Bloco de Notas](notepadCod.png)

* O **Word** permite alterar todas as letras para maiúscula, mas não alterar a codificação.

![Alterando letras para maiúsculas no Word](wordUppercase.png)

* O **Notepad++** permite as duas funções.

<div class="multiColumn">
  <div class="column">
    <img src="notepad++Cod.png" alt="Alterando codificação no Notepad++">
    <br>
    <strong>Alterando codificação no Notepad++</strong>
  </div>
  <div class="column">
    <img src="notepad++UpperCase.png" alt="Alterando letras para maiúsculas no Notepad++">
    <strong>Alterando letras para maiúsculas no Notepad++</strong>
  </div>
</div>

Portanto é possível usar o Word em conjunto com o Bloco de Notas ou o Notepad++.

Copie e cole a letra desejada no editor e separe em conjuntos de linhas o louvor desejado segundo o padrão desejado:

<div class="multiColumn">
  <div class="column">
    <img src="linhasBanda.png" alt="Padrão de Linhas Banda">
    <strong>Banda: No máximo duas linhas</strong>
  </div>
  <div class="column">
    <img src="linhasJovens.png" alt="Padrão de Linhas Jovens">
    <strong>Jovens: No máximo cinco linhas</strong>
  </div>
</div>

Sempre tenha o cuidado de separar as linhas de forma a facilitar a operação. Isso pode ser feito: 

* Observando como música é cantada;
* colocar partes que são cantadas juntas próximas;
* repetir as estrofes conforme são cantadas.

> &#9888; Muitas vezes o louvor é cantado de forma diferente na igreja em relação ao original. Por isso busque ouvir o louvor, seja de cultos anteriores, no ensaio ou através de nossa [audioteca](https://www.dropbox.com/sh/0qsq9cuuwt9zjec/AAAA8-EbGFNkeiE3NZj5GXZea?dl=0&lst=) <!-- Adicionar link -->.

### Modelo

Vamos ver como criar um novo modelo segundo o padrão da igreja. Tanto para usa-lo caso não tenha no PC, quanto para entender suas características.

* Abra o Pro Presenter

* Na parte inferior esquerda clique na seta ao lado do simbolo **"+"** e clique em **Criar novo Modelo**.

![Botão para edição de Modelo](modelButton.png)

* Uma tela irá se abrir para salvar o novo modelo. Coloque um nome (exemplo "PADRÃO LEGENDA IBCAL") e clique em salvar.

![Salvar Modelo](modelSave.png)

* Será aberto uma janela de edição de slide, onde iniciaremos a edição do nosso modelo.

* Primeiramente altere o Tamanho para 1920 X 1080

![Tamanho Padrão](modelSize.png)

* Altere o fundo para a cor verde.

![Fundo Padrão](modelBackground.png)

* Por ultimo altere o estilo de texto conforme a imagem a baixo.

![Fundo Padrão](modelText.png)

E com isso está finalizado o nosso modelo. Agora podemos usá-lo como base para os louvores seguintes.

### Importando o Arquivo

Tendo o modelo pronto, vamos importar o arquivo que foi criado anteriormente dentro do pro presenter. Para isso abra o pro presenter e na parte superior clique em Arquivo -> Importar -> Importar Arquivo...

![Importar arquivo no Pro Presenter](importPro.png)

Indique o local do arquivo e uma janela irá aparecer. Preencha conforme abaixo:

![Configurações de Importação](importSettings.png)

Clicando em editar veremos como o arquivo foi importado e também permite alterar o nome. Sempre coloque o nome em letras maiúsculas:

![Configurações de Importação](importName.png)

Se tudo estiver correto clique em Importar e pronto um novo louvor será inserido no pro presenter

![Configurações de Importação](importEnd.png)

<!-- ## Edição um louvor já existente -->

> TODO: Incluir edição de um louvor já existente

> TODO: Incluir o funcionamento do Git no lado de quem edita e as características de funcionamento na igreja (quando reinicião o computador faz o reset).