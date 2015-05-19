Paraiba.js
==================

##[http://paraibajs.github.io](http://paraibajs.github.io)

Site do paraiba.js, nos acompanhe também em outros canais:

* [Grupo no Facebook](https://www.facebook.com/groups/paraibajs/)
* [Página no Facebook](https://www.facebook.com/paraibajs/)

## Como enviar sua talk

Antes de tudo, se você nunca usou o Github, confira [este artigo](http://php-pb.net/2014/04/29/contribuindo-com-artigos/) do PHP-PB que ensina como contribuir em repositórios com o Jekyll.

Para submeter sua palestra, você deve fazer um *fork* do repositório e enviar um Pull Request com a sua talk para a pasta `_posts`. Seu arquivo deve seguir a seguinte nomeclatura:

    2014-04-29-aplicacoes-desktop-com-nodewebkit.md
    
Fora isso, o seu arquivo deve possuir o seguinte cabeçalho    

    ---
    title: "Desenvolvendo Aplicações desktop com node-webkit"
    layout: post
    order: 0
    categories:
    - talk
    robots: none
    horario: 00h00
    author: Sérgio Vilar
    author_email: vilar@me.com
    slides: http://sergiovilar.com.br/talks/paraibajs-abr
    meetup: 3-meetup-pbjs
    ---
    
    A talk é um live-coding mostrando como construir o Photo Booth do Mac OS X usando apenas HTML, CSS e Javascript.
    
Onde o campo **meetup** equivale ao evento que você deseja submeter. O resto do arquivo é auto-explicativo.
