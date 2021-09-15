# Sobre a documentação
{: .no_toc}

Índice
* TOC
{:toc}
---

## Missão
Evitar que o sistema fique na cabeça apenas de algumas pessoas e facilitar a compreensão do fluxo todo para novos participantes do ministério.

## Instruções gerais
Essa documentação tem duplo papel dentro do ministério, é tanto uma ferramenta de treinamento de novos integrantes quanto um guia para os que já atuam no ministério.

Devemos procurar deixá-lo mais enxuto possível para não ficar monótono, mas sem deixar de abordar todos os detalhes que possam produzir conflitos, isso é uma tarefa muito difícil.

Também é importante manter um padrão de linguagem para que alguns trechos não fiquem com a cara de uma pessoa específica.

## Tecnologias utilizadas
- Hospedagem [GitHub pages](https://pages.github.com/)
- Linguagem de notação [kramdown](https://kramdown.gettalong.org/syntax.html)
- Gerador de sites [Jekyll](https://jekyllrb.com/)

## Motivação
Manter uma documentação ativa dá trabalho, isso porque seu foco é determinar como devemos fazer.

E cada coisa pode ser feitas de diversas formas então, por mais que devemos nos esforçar em manter ela enxuta, por outro lado esse é o canal mais útil para explicar porque resolvemos fazer uma coisa de determinada forma.

Ela também é uma grande ferramenta para evitar que as pessoas façam uma coisa fora do que foi pensado pelo grupo gerando situações inusitadas.

Mas o maior problema que a documentação busca resolver é o que está escrito na [missão](#missão).

## Fluxo das alterações
Todas as alterações desse procedimento devem ser feitas via [Fork](https://docs.github.com/pt/github/getting-started-with-github/quickstart/fork-a-repo) e [Pull Requests](https://docs.github.com/pt/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) afim de que, o aprovador (líder do ministério) repasse para o grupo quais alterações mudançcas estão acontecendo. 

## Rodando localmente

Para rodar são necessários:
- Linguagem [Ruby](ruby-lang.org/pt/) (Precisa ser a versão 2.7.0)
- [Gems](https://rubygems.org/) (Já vem instalado com o ruby)
- [Bundler](https://bundler.io/)

Com isso instalado execute `bundle install` no terminal ou cmd, para instalar as dependências. 

Depois execute `bundle exec jekyll serve --livereload` para iniciar o servidor (A opção **--livereload** serve para atualizar a página quando uma mudança for feita). 

Depois abra o seu navegador e digite o endereço **http://127.0.0.1:4000/**.

Com isso a documentação irá se abrir e assim será possivel verificar as alterações antes de manda-las para o Github.