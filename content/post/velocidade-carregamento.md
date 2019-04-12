+++
title = "Velocidade de carregamento com Hugo, Netlify e Otimização de Imagens"
date = "2019-04-11T18:47:08+02:00"
author = "ComprovandoSEOnaVIP"
tags = ["Velocidade"]
categories = ["tecnologia"]
menu = ""
banner = "img/velocidade.jpg"
bannersmall = "img/velocidade-small.jpg"
+++

Todos nós sabemos que a velocidade de carregamento é um fator indireto de posicionamento no Google. Principalmente depois do ranking priorizar a experiência do usuário em dispositivos móveis, do famoso termo: [Mobile First](https://blog.apiki.com/mobile-first-o-conceito-e-sua-aplicabilidade/).

Digo que é um fator indireto porque o Google não confirmou que este é um fator e os sites especializados na área não afirmam isso categoricamente. 

Mas considerando a experiência do usuário ao acessar um site, quando um site demora muito a carregar muitas vezes perdemos a paciência pressionamos o botão voltar e vamos para a outra opção de busca. Mesmo nós que criamos sites passamos por isso quando estamos buscando por assuntos de nosso interesse.

Isso passa uma mensagem para o buscador que, por algum motivo, o usuário não ficou contente com aquela página que estava bem posicionada. Já que ele saiu dela rapidamente e vou buscar a resposta em outro site da SERP.

Muitos especialistas defendem que esse é um fator relevante na classificação dos sites, ainda que não haja confirmação oficial a respeito. Mas se pararmos para pensar, faz todo o sentido.

## Velocidade em Site Estático x Site Dinâmico

Então, já que a velocidade do site é fator importante, gostaria de falar de uma característica importante dos sites estáticos.

Na grande maioria das vezes, com igualdades de condições, um site estático será mais rápido que um site dinâmico. As condições que me refiro são, por exemplo, as configurações de servidores. 

Se você pagar uma grana a mais para colocar seu site dinâmico em um ótimo servidor VPS, ele pode ter o mesmo desempenho que um site estático em um servidor mais simples. Mas o contrário é muito difícil de acontecer.

Simplesmente pelo fato de o site estático não usar banco de dados. Ele simplesmente entrega o HTML + CSS + JS para o usuário no tempo em que o site dinâmico está buscando os dados no servidor, só depois ele monta o HTML + CSS + JS pra entregar.

Mas você pode questionar que fazer um site dinâmico na unha é totalmente inviável nos dias de hoje e eu serei obrigado a concordar com você.

Por isso surgiram os geradores de site estático como o [Hugo]( https://comprovandoseonavip.live/post/hugo-is-for-lovers/), que está sendo usado aqui [neste site]( https://comprovandoseonavip.live/).

## Hugo + Netlify

Agora aqui entra a grande sacada que vai elevar ao extremo a qualidade de carregamento dos sites estáticos simples ou que usam algum gerador. 

Se o site estático será mais rápido para carregar, imagine se ele estivesse hospedado num servidor Premium de ótima qualidade?

Seria um pouco mais caro, mas seria o melhor dos mundos não é?

Mas é melhor que isso: a [Netlify](https://netlify.com/) é uma dessas empresas que trabalham com modelo fremium na internet, similar ao que faz a [Cloudflare](https://cloudflare.com/).

<img src="/img/netlify.jpg" alt="Netlify - Hospedagem Fremium para Hugo e Sites Estáticos" class="center">

Isso significa que você pode fazer um site estático em Hugo e hospedar gratuitamente no ótimo servidor deles e alcançar resultados excelentes.

Para demonstrar, vou postar aqui alguns prints dos resultados desse site nas ferramentas que fazem análise de velocidade de carregamento.

<img src="/img/pagespeed.jpg" alt="resultados do comprovandoseonavip no pagespeed" class="center">



<img src="/img/gtmetrix.jpg" alt="desempenho do comprovandoseonavip no gtmetrix" class="center">

Invejosos vão dizer: “Claro, com 298kb até minha vó!”. Mas esses são os exatos 298kb que precisam ser mostrados nessa página, incluindo imagens, thumbnails dos posts e um vídeo do Youtube. Isso é otimização!


## Otimização de Imagens

Obviamente não foi magicamente alcançado esses resultados, mesmo que seja uma forma que naturalmente é mais rápida, alguns ajustes na otimização foram necessários.

Principalmente em imagens. Essa mídia tão necessária é o maior vilão na velocidade de carregamento em nossos sites.

Mas aqui vou dar uma dica que poucos fazem, mas que faz total diferença no tamanho do arquivo da imagem que você vai subir no seu site. 

Você provavelmente busca suas mídias em bancos de imagens gratuitos como o [Pixabay](https://pixabay.com/) ou num pago como o [Shutterstock](https://www.shutterstock.com/). 

Neles você pode baixar imagens em alta resolução, mas como você pode ver abaixo em um exemplo no Pixabay, quanto maior o tamanho da resolução maior o tamanho em KBs da imagens. 

<img src="/img/download-pixabay.jpg" alt="Mudando a Resolução de imagens no Pixabay" class="center">

Uma imagem em alta resolução chega a 2 MB, porém quase nunca será necessário ou possível mostrar a imagem em sua resolução total no seu site. Em geral a imagem com resolução 640 será muito adequada e em alguns casos muito específicos 1280 talvez seja necessário.

O importante é adequar a imagem para o que de fato ela será utilizada no site.

Por isso, a partir de hoje, passe a trabalhar e olhar com mais cuidado  para resolução das imagens que você usa seu site, mesmo antes de usar ferramentas de otimização como o [TinyPNG](https://tinypng.com).

Um exemplo aqui neste site são as imagens thumbnails dos posts. 

<img src="/img/blog-comprovandoseonavip.jpg" alt="Imagens no blog comprovandoSEOnaVIP" class="center">

Na guia blog, onde aparece a lista de posts, uso uma imagem com resolução maior, que eu poderia chamar, por exemplo: capa.jpg. 

Enquanto que na sidebar é a mesma imagem com resolução menor e com nome capa-small.jpg.

Essa pequena alteração garante uma economia gigante de KBs e melhora consideravelmente a velocidade de carregamento da página.

Até a próxima!
