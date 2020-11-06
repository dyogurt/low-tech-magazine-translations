Title: Como construir um *site* *low-tech*?
Date: 2018-9-24
Category: Low-tech Solutions
Tags: ICT, Solar Powered Website
Slug: how-to-build-a-lowtech-website
Lang: pt-PT
Translator: 
Summary: O nosso novo blogue foi concebido para reduzir radicalmente o uso de energia associado à consulta do nosso conteúdo.
Status: draft



![um detalhe do servidor a energia solar](/images/sps_close.jpg)
O primeiro protótipo do servidor a energia solar que corre o novo *site*.  O controlador de carga solar (à direita) está a alimentar o servidor (à esquerda) através de um cabo USB.

[Low-tech Magazine: Versão Kindle](https://solar.lowtechmagazine.com/offline-reading.html).

A revista Low-tech Magazine nasceu em 2007 e, desde então, tem sofrido muito poucas mudanças. Como uma reformulação do *website* já devia ter sido feita há muito tempo — e porque tentamos praticar o que dizemos — decidimos construir uma versão de baixa tecnologia, auto-hospedada, e a energia solar da Low-tech Magazine. O nosso novo blogue foi concebido para reduzir radicalmente o uso de energia associado à consulta do nosso conteúdo.

## Porquê um *site* *low-tech*?

Foi-nos dito que a Internet iria ["desmaterializar" a sociedade e diminuir o uso de energia](https://www.bcg.com/publications/2012/energy-environment-technology-industries-smarter-2020-role-ict-driving-sustainable-future.aspx). Contrariamente a esta previsão, acabou por tornou-se um [grande consumidor de energia em rápido crescimento]({filename}/posts/can-the-internet-run-on-renewable-energy.md).

De forma a contrabalançar as consequências negativas associadas ao elevado consumo de energia, foi proposto o uso de energia renovável como meio de reduzir as emissões dos centros de processamento de dados. Por exemplo, o [relatório anual ClickClean](http://www.greenpeace.org/usa/global-warming/click-clean/) da Greenpeace classifica as principais empresas da *internet* com base na sua utilização de fontes de energia renováveis.

No entanto, alimentar centros de processamento de dados com fontes de energia renovável não é suficiente para fazer face ao crescente uso de energia da Internet. Para começar, a Internet já utiliza três vezes mais energia do que todas as fontes de energia eólica e solar do mundo são capazes de fornecer.

> Alimentar centros de processamento de dados com fontes de energia renovável não é suficiente para fazer face ao crescente uso de energia da Internet.

Por último, a energia solar e eólica nem sempre estão disponíveis, o que significa que se a Internet funcionar com fontes de energia renováveis será necessária uma infraestrutura de armazenamento e/ou transmissão de energia que também é [dependente de combustíveis fósseis para o seu fabrico e substituição]({filename}/posts/how-not-to-run-a-society-on-solar-and-wind-power-alone.md). Alimentar *sites* com energia renovável não é uma má ideia, no entanto, a tendência para o aumento da utilização de energia também deve ser abordada.

Para começar, o conteúdo está a tornar-se cada vez mais exigente em termos de recursos. Isto tem muito a ver com a crescente importância de vídeos, mas uma tendência semelhante pode ser observada entre *sites*. O [tamanho médio de uma página web](https://httparchive.org/reports/page-weight) (definido como o tamanho médio de página dos 500.000 domínios mais populares) aumentou de 0,45 megabytes (MB) em 2010 para 1,7 MB em junho de 2018. Para *sites* móveis, o "peso médio das páginas" aumentou dez vezes de 0,15 MB em 2011 para 1,6 MB em 2018. Utilizando diferentes métodos de medição, outras fontes informam tamanhos médios de página de até 2,9 MB em 2018.

O crescimento do tráfego de dados [tem superado os avanços na eficiência energética](https://www.researchgate.net/publication/224224694/download) (a energia necessária para transferir 1 MB de dados pela *internet*), resultando numa utilização cada vez maior de energia. Os *sites* "mais pesados" ou "maiores" não só aumentam a utilização de energia na infraestrutura da rede, como também encurtam a vida útil dos computadores — para aceder a *websites* maiores os computadores têm que ser mais potentes. Isto significa que é necessário fabricar mais computadores, o que é um [processo que requer muita energia]({nome do ficheiro}/pós/embodied-energy-of-digital-technology.md).

> Estar sempre *online* não é compatível com fontes de energia renovável tais como a energia eólica e solar, que nem sempre estão disponíveis.

Uma segunda razão para o aumento do consumo de energia da Internet é que passamos cada vez mais tempo em *on-line*. Antes da chegada dos dispositivos portáteis e do acesso à rede sem fios, só estávamos ligados quando tínhamos acesso a um computador de secretária no escritório, em casa, ou na biblioteca. Agora vivemos num mundo em que não importa onde estejamos, estamos sempre *on-line*, incluindo, por vezes, através de mais do que um dispositivo em simultâneo.

O acesso "sempre ligado" à Internet é acompanhado por um modelo de computação em nuvem — permitindo dispositivos mais eficientes em termos energéticos, à custa de uma maior utilização de energia nos centros de dados. Cada vez mais, atividades que poderiam perfeitamente acontecer *off-line* — tais como escrever um documento, preencher uma folha de cálculo, ou armazenar dados — requerem agora acesso contínuo à rede. Isto não é compatível com fontes de energia renováveis, tais como a energia eólica e solar, que nem sempre estão disponíveis.

## *Low-tech web design*

O nosso novo *web design* aborda estas duas questões. Graças a um *web design low-tech*, conseguimos diminuir o tamanho médio de uma página do blogue por um factor de cinco em comparação com o *design* antigo — tudo isto tornando o *website* visualmente mais atraente e adequado para dispositivos móveis.  Em segundo lugar, o nosso novo *website* funciona 100% a energia solar, não apenas no papel, mas na realidade: tem o seu próprio armazenamento de energia e ficará desligado durante longos períodos de tempo nublado.

A Internet não é um ser autónomo. O seu crescente uso de energia é a [consequência de decisões reais](http://tonsky.me/blog/disenchantment/) feitas por criadores de *software*, *web designers*, departamentos de *marketing*, editores e utilizadores. Com um *website* a energia solar, leve e fora da rede, nós queremos mostrar que outras decisões podem ser tomadas.

> Com 36 dos cerca de 100 artigos agora *online*, o peso médio das páginas no *website* a energia solar é cerca de 5 vezes inferior ao do *design* anterior.

Para começar, o novo *design* do *website* inverte a tendência para páginas cada vez maiores. Com 36 dos cerca de 100 artigos agora *online*, o peso médio das páginas no *website* a energia solar é de 0,77 MB — cerca de cinco vezes inferior ao do *design* anterior, e menos de metade do tamanho médio das 500 mil páginas dos blogues mais populares em junho de 2018. 

![image](/images/9801a71c-bdae-4732-9ad7-b45d26897a32.jpg)

![image](/images/0103010d-26e1-48e6-a7c1-21d0dd355b1a.jpg)
Um teste de velocidade da antiga e da nova Low-tech Magazine. O tamanho da página diminuiu mais de seis vezes, o número de pedidos cinco vezes, e a velocidade de *download* aumentou dez vezes. Note-se que não concebemos a página *web* para velocidade, mas para baixo consumo de energia. Seria ainda mais rápido se o servidor fosse colocado num centro de dados e/ou numa localização mais central na infraestrutura da Internet. Fonte: Pingdom.

Abaixo estão algumas das decisões de *design* que tomámos para reduzir o consumo de energia. Publicámos um [documento separado que se foca nos esforços de *front-end*](https://github.com/lowtechmag/solar/wiki/Solar-Web-Design), e um [que se foca nos esforços de *back-end*](https://homebrewserver.club/low-tech-website-howto.html#software). Também [divulgámos o código para o *design* do nosso *website*](https://github.com/lowtechmag/solar).

## *Site* estático

Uma das escolhas fundamentais que fizemos foi construir um *website* estático. A maioria dos *websites* atuais utiliza linguagens de programação do lado do servidor que geram o *website* em tempo real, consultando uma base de dados. Ou seja, uma página *web* tem que ser gerada cada vez que alguém visita o *site.*

Por outro lado, um *website* estático é [gerado uma vez e existe como um simples conjunto de documentos no disco rígido do servidor](https://varia.zone/en/what-a-website-can-be.html). Está sempre lá — e não apenas quando alguém visita a página. Os *websites* estáticos baseiam-se assim no armazenamento de ficheiros, enquanto os *websites* dinâmicos dependem de cálculos recorrentes. Os *websites* estáticos requerem consequentemente menos poder de processamento e, portanto, menos energia.

A escolha de um *site* estático permite geri-lo de uma forma económica a partir do servidor no nosso escritório em Barcelona. Fazer o mesmo com um *website* derivado de uma base de dados seria quase impossível, porque exigiria demasiada energia. Seria também um grande risco de segurança. Embora um servidor *web* com um *site* estático possa ser pirateado, existem significativamente menos rotas de ataque e os danos são mais facilmente reparados.

## Imagens com *dither*

O principal desafio foi reduzir o tamanho das páginas sem tornar o *site* menos atraente. Como as imagens ocupam a maior parte da largura de banda, seria fácil ter páginas pequenas e menor utilização de energia, eliminando imagens, reduzindo o seu número, ou tornando-as muito mais pequenas. Contudo, as imagens são uma parte importante do apelo da revista Low-tech Magazine, e o *website* não seria o mesmo sem elas.

> Ao aplicarmos *dithering*, podemos fazer imagens que requerem dez vezes menos recursos, mesmo que sejam apresentadas muito maiores do que no antigo *website*.

Em vez disso, escolhemos aplicar uma técnica de compressão de imagem obsoleta chamada *dithering*. O número de cores numa imagem, combinado com o seu formato de ficheiro e resolução, contribui para o tamanho de uma imagem. Assim, em vez de utilizarmos imagens a cores de alta resolução, escolhemos converter todas as imagens para preto e branco, com quatro níveis intermédios de cinzento.

![image](/images/600px-A20-OLinuXino-LIME2.jpg)
Uma imagem com *dither* do nosso servidor.

Estas imagens a preto e branco são depois coloridas de acordo com a respetiva categoria de conteúdo através das capacidades de manipulação nativa de imagens do *browser*. Comprimidas através deste *plugin* de *dithering*, as imagens apresentadas nos artigos adicionam muito menos peso ao conteúdo: em comparação com o antigo *website*, as imagens consomem aproximadamente dez vezes menos recursos.

## Fonte tipográfica padrão / Sem logo

Todos os recursos carregados, incluindo fontes tipográficas e logótipos, são um pedido adicional ao servidor, exigindo espaço de armazenamento e utilização de energia. Portanto, o nosso novo *website* não carrega nenhum tipo de letra personalizado e remove a declaração de fonte-família, o que significa que os visitantes verão o tipo de letra padrão do seu *browser*. 

Utilizamos uma abordagem semelhante para o logótipo. De facto, a revista Low-tech Magazine nunca teve um, apenas uma imagem de uma lança segurada como uma arma de baixa tecnologia contra as reivindicações de alta tecnologia prevalecentes.

Em vez de um logótipo, que exigiria a produção e distribuição de tipografias e imagens personalizadas, a nova identidade da Low-tech Magazine consiste num único gesto tipográfico: utilizar a seta virada para a esquerda no lugar do hífen no nome do blogue: LOW←TECH MAGAZINE.

## Sem rastreios de terceiros, sem serviços de publicidade, sem *cookies*

*Software* de análise como o Google Analytics regista o que acontece num *website* — que páginas são mais vistas, de onde vêm os visitantes, e assim por diante. Estes serviços são populares porque poucas pessoas hospedam o seu próprio *website*. Contudo, o intercâmbio destes dados entre o servidor e o computador do *webmaster* gera tráfego de dados extra e, portanto, utilização de energia.

Com um servidor auto-hospedado, podemos fazer e visualizar estas medições no mesmo aparelho: cada servidor gera registos do que acontece no computador. Estes registos (anónimos) são apenas vistos por nós e não são usados para criar perfis de visitantes.

> Com um servidor auto-hospedado, não há necessidade de rastreio e *cookies* de terceiros.

A Low-tech Magazine tem usado anúncios da Google Adsense desde o início de 2007. Embora estes sejam um recurso financeiro importante para a manutenção do blogue, têm dois aspetos negativos importantes. O primeiro é o uso de energia: serviços de publicidade aumentam o tráfego de dados e, consequentemente, o uso de energia.

Em segundo lugar, a Google recolhe informações dos visitantes do blogue, o que nos obriga a elaborar extensas declarações de privacidade e avisos de *cookies* — que também consomem dados, e incomodam os visitantes. Sendo assim, substituímos o Adsense por outras opções de financiamento (leia mais abaixo). Não utilizamos *cookies* de todo.

## Com que frequência estará o *site* *off-line*?

Muitas empresas de alojamento *web* afirmam que os seus servidores funcionam com energia renovável. No entanto, mesmo quando estas geram a energia solar localmente e não se limitam a "compensar" a utilização de energia fóssil através da plantação de árvores ou afins, os seus *websites* estão sempre *on-line*.

Isto significa que ou têm um enorme sistema de armazenamento de energia local (o que torna o seu sistema energético insustentável), ou que dependem da rede elétrica quando há falta de energia solar (o que significa que não funcionam realmente a 100% de energia solar).

![O painel de 50W, por cima dele está um painel de 10W de um antigo sistema de iluminação fora da rede.](/images/sps_panel.jpg)
O painel solar fotovoltaico de 50W. Em cima dele está um painel de 10W que alimenta um sistema de iluminação.

Pelo contrário, este *website* funciona com um sistema de energia solar fora da rede com o seu próprio sistema de armazenamento de energia, e ficará *off-line* durante longos períodos mais longos de tempo nublado. Uma fiabilidade inferior a 100% é essencial para a sustentabilidade de um sistema solar fora de rede, porque acima de um certo nível a energia de combustíveis fosseis usada para produzir e substituir as baterias é superior à poupada pelos painéis solares.

Ainda está para se ver com que frequência o *website* vai ficar *off-line*. O servidor *web* é alimentado por um painel solar novo de 50W e uma bateria chumbo-ácido de 12V 7Ah com dois anos. Como o painel solar fica à sombra durante a manhã, só recebe luz solar direta durante 4 a 6 horas por dia. Em condições ótimas, o painel solar gera assim 6 horas x 50 W = 300 Wh de eletricidade.

O servidor *web* usa entre 1 a 2.5 W (dependendo do número de visitantes), o que significa que requer entre 24 Wh e 60 Wh de eletricidade por dia. Em condições ótimas, devemos assim ter energia suficiente para manter o servidor *web* a funcionar durante 24 horas por dia. O excesso de produção de energia pode ser utilizado para aplicações domésticas.

> Esperamos manter o *website* *online* durante um ou dois dias de mau tempo, mais do que isso e ficará *off-line*.

No entanto, durante dias nublados, especialmente no inverno, a produção diária de energia poderá ser tão baixa como 4 horas x 10 W = 40 Wh por dia, enquanto o servidor necessita de 24 e 60 Wh por dia. O armazenamento da bateria é de cerca de 40 Wh, tendo em conta 30% de carga e 33% de profundidade ou descarga (o controlador de carga solar desliga o sistema quando a tensão da bateria cai para 12V).

Consequentemente, o servidor a energia solar permanecerá *on-line* durante um ou dois dias de mau tempo, mas não por mais tempo. Contudo, estas são estimativas, e podemos acrescentar uma segunda bateria de 7 Ah no outono, se for necessário. O nosso objetivo é um "tempo de funcionamento" de 90%, o que significa que o *website* ficará fora de funcionamento durante uma média de 35 dias por ano.

![A bateria de chumbo-ácido de 35Wh e as baterias de Li-Po de 30Wh que alimentam o servidor.](/images/sps_bats.jpg)
Primeiro protótipo com bateria chumbo-ácido (12V 7Ah) à esquerda, e bateria UPS Li-Po (3,7V 6600mA) à direita. A bateria chumbo-ácido fornece a maior parte do armazenamento de energia, enquanto a bateria Li-Po permite que o servidor se desligue sem danificar o *hardware* (será substituída por uma bateria Li-Po muito mais pequena).

## Quando é a melhor altura para visitar?

A acessibilidade deste *website* depende do estado do tempo em Barcelona, Espanha, onde se encontra o servidor a energia solar. Para ajudar os visitantes a "planear" as suas visitas à Low-tech Magazine, fornecemos-lhes várias pistas.

> Para ajudar os visitantes a "planear" as suas visitas à Low-tech Magazine, fornecemos-lhes várias pistas.

Um nível de bateria fornece informação crucial porque pode dizer ao visitante que o blogue está prestes a ficar inacessível — ou que é “seguro” lê-lo. O *design* consiste numa cor fundo que indica a capacidade da bateria carregada a energia solar que alimenta o servidor do *website*. Um decréscimo na altura do fundo colorido indica que é de noite ou está mau tempo.

Para além do nível da bateria, outras informações sobre o servidor são visíveis num painel do *website*. Isto inclui informação contextual da localização do servidor, hora, condições meteorológicas atuais e previsões, e a duração desde a última vez que o servidor foi desligado devido a falta de energia.

Atualização de abril de 2019: Para aceder à Low-tech, independentemente do estado do tempo, temos [várias opções de leitura *offline* disponíveis](https://solar.lowtechmagazine.com/offline-reading.html). Por exemplo, oferecemos uma [brochura encadernada de 710 páginas que contém 37 dos artigos mais recentes do *website*](http://www.lulu.com/shop/kris-de-decker/low-tech-magazine-20122018/paperback/product-24028679.html) (2012 a 2018). Um segundo volume, que recolhe artigos publicados entre 2007 e 2011, será publicado ainda este ano. Os livros são baseados nos mesmos documentos eletrónicos que compõem o *website* a energia solar.

## *Hardware* e *Software*

Escrevemos dois artigos extra com informação técnica mais aprofundada: [Como construir um *website* *low-tech*: *software* e *hardware*](https://homebrewserver.club/low-tech-website-howto.html), que se concentra no *back-end*, e [Como construir um *website* *low-tech*: Técnicas e Processo de *Design*](https://github.com/lowtechmag/solar/wiki/Solar-Web-Design), que se concentra no *front-end*.

SERVIDOR: Este *website* funciona num [computador Olimex A20](https://homebrewserver.club/low-tech-website-howto.html#server). Tem 2 Ghz de poder de processamento, 1 GB de RAM, e 16 GB de armazenamento. O servidor consome 1–2,5 watts de potência.

*SOFTWARE* DO SERVIDOR : O servidor corre Armbian Stretch, um sistema operativo baseado em Debian construído em torno do *kernel* SUNXI. Nós escrevemos [documentação técnica sobre como configurar o servidor](https://homebrewserver.club/low-tech-website-howto.html#configuring-the-webserver). 

*SOFTWARE* DE *DESIGN*: O *website* foi construído com [Pelican](https://blog.getpelican.com/), um gerador de *sites* estáticos. [Partilhámos o código para 'solar', o tema Pelican que desenvolvemos aqui](https://github.com/lowtechmag/solar).

LIGAÇÃO À INTERNET. O servidor está ligado a uma ligação de 100 MBps à Internet por fibra. [Eis como configurámos o *router*](https://homebrewserver.club/low-tech-website-howto.html#network). Por agora, o *router* é alimentado por eletricidade da rede e requer 10 watts de potência. Estamos a investigar como substituí-lo por um mais eficiente que também possa ser alimentado por energia solar.

SISTEMA SOLAR FOTOVOLTAICO. O servidor funciona com um painel solar de 50 Wp e uma bateria de chumbo-ácido de 12V 7Ah. No entanto, ainda estamos a reduzir o sistema e a experimentar configurações diferentes. A instalação fotovoltaica é gerida por um controlador de carga solar de 20A.

## O que acontece ao antigo *website*?

A Low-tech Magazine alimentada a energia solar é um projeto ainda a decorrer. Por enquanto, a Low-tech Magazine, alimentada pela rede elétrica, permanece *on-line*. Os leitores serão encorajados a visitar o *website* a energia solar, se este estiver disponível. O que acontecerá no futuro, ainda não é claro. Existem várias possibilidades, mas muito dependerá da experiência com o servidor alimentado a energia solar.

Até decidirmos como integrar o antigo e o novo *website*, só será possível fazer e ler comentários na revista Low-tech Magazine, que ainda se encontra alojada no TypePad. Se quiser enviar um comentário relacionado com o servidor alimentado por energia solar, pode fazê-lo enviando um *email* para solar (arroba) lowtechmagazine (ponto) com. O seu comentário será publicado no final desta página.

## Posso ajudar?

Sim, podes.

Por um lado, estamos à procura de ideias e feedback para melhorar ainda mais o *website* e reduzir o seu consumo de energia. Vamos documentar extensivamente o projecto para que outros também possam construir *websites* de baixa tecnologia. Para fazer um comentário, por favor envia um *email* para solar (arroba) lowtechmagazine (ponto) com.

Por outro lado, esperamos que as pessoas apoiem este projecto com uma contribuição financeira. Os serviços de publicidade, que têm mantido a Low-tech Magazine desde o seu início em 2007, não são compatíveis com o nosso *web design* mais simples. Por isso, estamos à procura de outras formas de financiar o *website*:

Temos disponíveis [cópias impressas a pedido do blogue](https://solar.lowtechmagazine.com/2019/03/printed-website.html). Estas publicações permitem-lhe ler a Low-tech Magazine em papel, na praia, ao sol, ou quando e onde quiseres.

Podes apoiar-nos através de [PayPal](https://www.paypal.me/lowtechmagazine), [Patreon](https://www.patreon.com/lowtechmagazine) e [LiberaPay](https://liberapay.com/lowtechmagazine/).

O servidor alimentado a energia solar foi construído pelo [Kris De Decker](http://www.krisdedecker.org), [Roel Roscam Abbing](https://roelof.info), e [Marie Otsuka](http://motsuka.com). O *website* impresso é feito pela [Lauren Campbell](http://squishysystems.com). 

* [Recebe a nossa *newsletter*](https://d69baa34.sibforms.com/serve/MUIEAJWIw9w82Dl4ua6FQArPaI-3Qb-zVTwPNabHQgFH51MiGF69Smy9LOC_HPoUmBj0emaXsXT87gcQXDPvtu-AZsJCHWhkkv21CdrcQu4GdnYAhZ-MrIPhwGDecagLzYxqfvkaqXg2ODcbJU4ByoDmzJK3ZTczDo2jcWtfn-En0MGKLVkgxx9TgdHqYoPabMJCMF-agLEclEwv)
* Apoia a Low-tech Magazine via [Paypal](https://www.paypal.me/lowtechmagazine) ou [Patreon](https://www.patreon.com/lowtechmagazine).

## <span id="comments">Comentários</span>

Para comentar, por favor envie um email para solar (arroba) lowtechmagazine (ponto) com.

<div id="comment-list" markdown="1">

##### Seppe

Very interesting project! It'll be interesting to see how well it holds up during the winter.

What software are you running on the server to keep the energy usage so low? (I'm mainly interested in the OS and HTTP server.)

I have a few ideas/suggestions:

I think it should be possible to reach much higher uptime by creating a network of nodes that all host the same set of websites. It wouldn't be a very simple project, and you might argue that it's not as lowtech anymore. But hear me out:

Say you have 5 "lowtech websites" each running on its own server (node), and each located in a different place on earth. You could then duplicate the content of each server to the 4 other servers. This only costs you extra storage. The servers only need to communicate with each other when the content changes. The energy/bandwidth cost of this communication should be negligible for static websites that are updated for example once a day.

The main challenge is the DNS. There needs to be some kind of load balancing between these 5 clients. A rudimentary solution would be to use round-robin DNS. Say you have and A record for solar.lowtechmagazine.com that contains all 5 of the nodes' IP addresses and a lifetime of 5 minutes. Every time a node detects it is going to go down in less than 5 minutes, it updates this DNS record: it removes it's own IP address. Every time a node boots back up, it re-adds it's own IP address to the DNS record.
I'm not an expert on DNS, so I'm not 100% sure that this would work. But I think it's worth investigating if you're thinking about improving uptime.
Obviously more complex schemes would be necessary to handle unexpected node downtime. Depending on the type of website this may be overkill.

About the images. I think you may have gone a bit too far in the image compressing. I see that most (all?) of the images on the grid-powered website or stored in the lossless PNG format. In general this is not a good choice for photos (as opposed to icons or other graphics with few colors): the file size will be much larger than when you're using the lossy JPEG format.

For example: [the main picture for this article is 739 KB in PNG](http://krisdedecker.typepad.com/.a/6a00e0099229e88833022ad3b23825200b-750wi)

The dithered version in PNG is 43 KB, which is indeed a huge improvement, but comes [at a big cost in image quality](https://solar.lowtechmagazine.com/dithers/sps_close.png)

The B&W JPEG version of the main picture [(70% compression) is only 35 KB](https://i.imgur.com/9Z5HkTk.jpg), and I'd say the image quality is much higher than that of the dithered image. (The image resolutions don't match entirely. For the same resolution the image size of the JPEG would probably be more or less the same as the dithered image, but with increased image quality.) You could even lower the JPEG quality further than 70%, but this quickly becomes rather unpleasant to look at, so you may not want to do this.

##### Jiehong

Very interesting experiment!

But what about CDN caching and all other kind of caching between your server and each of the browsers?

It might very be the case that CDN will cache the content of this website for some time according to default cache policies, and also that the client's browsers might also cache part of the website directly.

I'd say that having big caching time for the browser is a big plus, as it would still allow users to access previously accessed pages when they are down at no energy cost.

On the other hand, estimating network caching energy usage might be complicated.

##### Sofie

"The design features a background colour that indicates the capacity of the solar-charged battery that powers the website server. A decreasing height indicates that night has fallen or that the weather is bad."

So that's what it is! It looks more like a glitch. I think it would be better to just add it to the header:
This is a solar-powered website, which means it sometimes goes offline. Battery: xx%

Some other minor issues (in Firefox):
The area you can click on links is some places longer than the text.
When the window is wide the images become too big and lines denoting cut-out text go much further out than the text, which looks odd.

##### QWxleA

Quite enjoyed the article, and am interested how you did the image dithering and coloring. Do you have a link that explains more?

Thanks, Alex

PS you could add a logo if you convert /create it in svg and embed it in the page.

##### Case D

I think it's a really cool project. I'm a hobbyist website tinkerer with a blog, and I've been experimenting with CMSes (I just installed WordPress, but I think it might be too much for what I want to do -- really I'd like a flat-file, static site that I can push to from anywhere (i.e., with a webform), which is what I can't figure out).

I'm writing you because I was curious if you'd share how your publishing workflow works -- do you have a CMS that you use? If so, how do you get from a web form to a published post? Is that how you do it?

##### tx

Some thoughts:

RSS feed is missing!

jquery-3.3.1.min.js is the biggest file on your page, from the limited amount of JS I saw, it could be easily removed. you could cache the your in a separate js file, this would also prevent uselessly sending your script to browser that won't support/accept it.

would you mind sharing the dithering script you apply to images?

I discovered LOW TECH MAGAZINE through this article and I'm really happy with the look and feel of the website! Keeping the default typeface is so rare nowadays and it works very well without JS.

##### kris de decker

RSS feed lives here
<https://solar.lowtechmagazine.com/feeds/all.atom.xml>

##### George Dorn

@ Case D (#5)

Look into various static site generators, like Pelican, Jekyll and dozens of others - <https://www.staticgen.com/>

They require a little bit of effort to set up, design the template, etc, but then whenever you want to publish, you run a command and it (re)generates all of the html. You can run the generator on the server itself, or on any other machine and just send the results to the server (somewhat automatically, via rsync, ftp, scp, etc).

I publish a blog this way via Pelican. I edit a file in reST (other languages also supported) and when I'm ready I run 'make html' and 'make publish' to send it to the server.

##### Perry

very cool. have you considered p2p/distributed web technologies like beaker browser? <https://github.com/beakerbrowser/beaker>

##### Dan

Your site doesn't load in Naked Browser on Android.

##### Ben S

It’s a cute idea, but please don’t dither your images.

One problem which you haven’t addressed is the increasing attitude towards web-pages as being “disposable”.

A good page, living on a sensible URL, could be available for decades if not centuries - but then, surely, there must also be a compromise made to maintain sources at the highest basic quality possible? What is worse that researching an interesting topic, only to run into photocopies of photocopies of a now lost technical drawing, which has become indecipherable over time. Dithering is basically this. You are an important source. Please don’t be a source providing photocopies of photocopies. I often find myself just grabbing screenshots and putting them into presentations or other documents. Ironically, this leads to a continual bit-rot as others do the same and screenshot my content. It’s surprising how many images in searches are clearly screenshots of poorly rescaled original images. Dithering will make this even worse.

I understand you’re trying to make a point - and there is a perverse value in stubbornly pissing into the wind, otherwise I wouldn’t enjoy low-tech so much and try to put it into practice myself - but please don’t let a low-energy perspective compromise on the real core of what you do, which is communicating excellent alternatives.

##### Edwan Summers

Thanks for this excellent post about a very important experiment. The adjustment around a website always being on seems like an important part of this work.

I’ve recently been experimenting with dat [1] which can often involve adjusting expectations about when content is going to be online or not. They have some nice instructions for publishing your static site using dat [2], which would mean that someone could potentially get your website from a peer who is sharing the cost of keeping your content online.

I honestly don’t know of what the energy costs associated with this are, but presumably the peers would only start to contribute traffic when content was requested. I imagine this is something the dat folks would be interesting in helping answer.

[1]: <https://datproject.org/>
[2]: <https://taravancil.com/blog/how-i-publish-taravancil-com/>

PS. I love the idea of doing web comments over email. It also makes me wonder if there could be static site plugins for supporting this process. Like running a Pelican/Jeckle/Hugo/etc conmand every day to examine an mailbox and look for comments on webpages. I guess there would be a necessary step of reviewing them too.

##### Damon Hart-Davis

My off-grid solar server:<http://www.earth.org.uk/note-on-Raspberry-Pi-2-setup.html>

You may also be interested in some of my tools to reduce page and image weight. (No ditherin:; zopfli(png) and similar in my case…)

##### Jeremy Keith

Hi Kris,

That's an absolutely fascinating article! I really like what you're doing.

You mentioned that you were looking for ideas. There's a technology you could use that would allow people to see something from your website, even when the server is down: service workers.

As long as someone has visited your site at least once, you could show them something when they try to visit the site when the server is powered down. That could just be a simple message, or it could be articles that you previously put in the visitor's cache (for example, every time someone visits an article, you could store a copy of that article in a cache to show them later when the server's offline).

Usually service workers come into play when the user's device isn't connecting to the network, but they also apply in your situation, where the server isn't connecting to the network.

I'd be happy to help you write the service worker script if you like.

##### Jacob Hall

Hello there,

I absolutely love this concept, and I hope this is where the world is headed; it simply doesn't make sense to bloat the internet with so much needless data.

My first thought, which commenter Alex also mentioned, is that you may be able to preserve the "modern" look of your site by using .svg graphics for logos and some images (such as graphs). As cool as dithered images look, I suspect a .svg would have an even smaller footprint, and could greatly improve the readability of content such as graphs used in "How Much Energy Do We Need?"

Secondly, I've heard a lot of people say recently that the future of the internet is decentralization, with users "seeding" visited websites to future users to create a more efficient and secure internet experience. I believe that this concept would lend itself well to the ideals of low energy consumption, potentially providing backup should your server ever go down due to weather. I know it isn't practical to implement right now, but I hope that is where the world is headed.

Thank you for the well-written and thought-provoking article.

##### Jeff Jahr

I like the old-timey dithered look of your images, and the way you are using the multiply blend to sepia tone them, that is very cool! However, if you want to have even lower page weight, then you might consider converting the images to grayscale jpg with a reduced quality instead of converting to dithered png.

Here's a quick comparison using your original image, the dithered image that appears in the article, and a conversion to gray jpg using an ImageMagick 'convert' command.

zeppelin:/tmp> convert -grayscale RMS -quality 50 -geometry 800x600 6a00e0099229e88833022ad3b23825200b-750wi.png test.jpg
zeppelin:/tmp> du -bh 6a00e0099229e88833022ad3b23825200b-750wi.png sps_close.png test.jpg
739K 6a00e0099229e88833022ad3b23825200b-750wi.png
43K sps_close.png
28K test.jpg

The image (test.jpg) is 15KB smaller than your dithered one, and still looks good with your color blending method.

If you like the rough look that your dither gives the images, you could ramp the -quality parmeter down to 10 or so, and your jpgs will start to look rough and mottled too- AND the image size will be reduced into the 9KB range for even more weight reduction.

zeppelin:/tmp> convert -grayscale RMS -quality 10 -geometry 800x600 6a00e0099229e88833022ad3b23825200b-750wi.png test10.jpg
zeppelin:/tmp> du -bh test10.jpg
9.1K test10.jpg

Cool stuff, good luck with your web server!

##### Bill Daniel

I'm such a fan. I love your work, I only wish you published more frequently.

The low tech website is brilliant.

I would happily pay to get print versions of your articles.
I'd likely print the whole archive! I'm a paper freak. Film and paper-based photographer, book collector, and collector and archivist of a wide variety of paper-based artifacts.

As a media archivist I'm constantly railing against digital storage, on the cloud or on drives. The future is going to have a dim understanding of what happened in our century, since most of the evidence will be non-existent/un-recoverable.

Keep up the good work! I hope I get the opportunity to purchase some print on demand articles.

##### Drew Gulino

It might go against the spirit of what you're trying to do with your solar web site, but users could go to the [web archive of solar.lowtechmagazine.com](https://web.archive.org/web/20180926204746/https://solar.lowtechmagazine.com/) when it's down (once it is archived; www. is already archived)

On the other hand, you're not using ads, so you're not out any money if users go to the archived site instead.

##### Francesco

Like others have said:

Instead of dithering you can use JPEG. I can achieve 52.4 KB with the image of this post, keeping the colors (compressing with gimp, quality 70, artifacts visible, but if you ask me only to somebody looking for them). Sure it's slightly more, but the image looks almost the same.

Also, since your homepage has a lot of images and might get lots of visits, why not thumbnail the images to a lower resolution? This might cut in half or more the size of the homepage.

Also embedded svg for the logo or other non-photographic graphics it the way to go (if embedded you avoid http requests).

Additionally, like already said, eliminate jQuery (or at least use the slim build, that eliminates some features, see here <https://cdnjs.com/libraries/jquery>).

Putting the computer outside in winter might help a bit with energy efficiency and cooling.

I am convinced this is a low-power website and I like the project, but it remains to be seen wether more energy could be saved in a data center where the computational resources are shared and they have proper cooling solutions.

##### Evan V

Just so you know, if you "snap to web colors" when exporting your dithered PNG you can get a similar aesthetic at an additional 50% size savings.

##### Mengyang Li

Yep, the JPEG format is much better in storing pictures than PNG, You can even use bpg to reduce size while maintain pretty acceptable quality.

[Visual comparison](http://xooyoozoo.github.io/yolo-octo-bugfixes/#mascot&jpg=s&bpg=s)

I think this is over engineered with a huge trade off on the image quality.

##### Leo Tindall

One potential way to reduce energy consumption while still retaining content accessibility might be to publish the site on IPFS, as I've done with my blog [1]. That way, people accessing the site help serve the site.
1:<https://leotindall.com/post/putting_this_blog_on_ipfs/>

##### Job van der Zwan

So I checked the solar powered website images to the regular website images.

To my shock and dismay, TypeKit for some reason uses PNGs for photos. This is extremely inefficient: PNG really is only good at compressing smooth surfaces and gradients. Photos are a terrible choice for PNGs.

I made a test gallery to compare alternative options:
<https://blindedcyclops.neocities.org/low-tech-image-tests/gallery.html>

In my experience, and as shown in the above gallery, cleaning up the image first makes an enormous difference in compression size, and results in better maintained quality at extreme compression values. I suggest Darktable and GIMP:
<http://www.darktable.org/>
<https://www.gimp.org/>

Another conclusion that I would draw is that JPGs aren't that bad.

However, if we insist on using dithered PNGs, here are some suggestions.

PNGquant is a lossy PNG encoder, which can be found here:
<https://pngquant.org/>

The downside is that it only supports Floyt-Steinberg dithering.

PNGs can also be losslessly optimized with optipng:
<http://optipng.sourceforge.net/>

It is often even worth putting the output of GIMP and/or PNGquant through optipng for a few extra percentages.

##### Ivan Vandot

Love the idea, great job. For the even more low-tech site definitely remove jQuery and rewrite in plain JS part for the icon and weather.

##### A Baldo

Wow, this is good news! As one of your readers who lives in a passive solar off-grid home in northeastern North America, your new lower-bandwidth site loads wonderfully fast over my slow cell signal. I tend to browse in “text mode” anyway, for speed and readability on my little phone screen.

Because of my slow connection I have become painfully sensitive to the growing bandwidth requirements you describe, even to read the news. I rely heavily on the text-only NPR page and the text-only National Weather Service forecast page; in cloudy weather they are sometimes the only pages that DO load!

Glad to be able to add the solar version of your site to the list. It is an informative, entertaining, and practical resource (I am now a thermal cooker aficionado, thanks to you!)

anja

PS I agree with Sofie that a simple text battery percentage in the header would probably be sufficient and more readable (when Safari isn’t already in text mode) than having the web page display battery status via background color.

##### Garve Scott-Lodge

Love the idea. Here are a couple of ideas which might improve the site further

There's an easy way to shave a few bytes. The type="text/JavaScript" attribute to the script tag is not needed on html5 pages like yours.

But there may be a more complex way of doing away with jQuery entirely.

All you seem to be using jQuery for is to pull in a JSON file with the current weather and battery stats. Your server is obviously creating the JSON file on the fly. If instead you created a small CSS file with the data you could pull it in instead, setting the attributes of the battery div and using the content declaration of :before and :after pseudo elements to insert words like "snowy" into your content. You'd need to ensure the CSS file wasn't cached, either server side or using a little JavaScript.

Cheers

##### kris de decker

Here is a quick note from Low-tech Magazine. We are a bit overwhelmed by all the feedback, especially because we were still working on the website when word got out.

We managed to fix the most obvious errors, took away the scaffolding, and launched a partly untested website, only to be flooded with traffic. Between 16:00 and 23:30 yesterday, the solar powered server registered 35,000 unique visitors, all while working flawlessly and using only between 1 and 2 watts of power. That's comparable to a very small LED reading light.

In the comments, many people focus on the battery meter and the dithered images, and they come up with very clever ideas to do it differently. For our project, low energy use was not the only goal. We also wanted it to be obvious to visitors that the server is solar powered and that the website is built in a very different way. If it would look and feel just like any other website, almost nobody would realize it is special.

Of course other ideas for image compression are very worthwhile and we look forward to try out some of the ideas and discuss them further.

We are still writing technical information (to be published soon), refining the software, and experimenting with various set-ups of the battery system, so expect more updates in the next days and weeks.

PS: There's a lot of interesting comments on the project over at [Hackernews](https://news.ycombinator.com/item?id=18075143)

PPS: And there is [a nice article on Treehugger](https://www.treehugger.com/solar-technology/low-tech-magazine-switches-low-tech-low-carbon-website.html)

##### Jeff Gnatek

hi there, curious if you have considered doing an inverted color scheme, so dark background with light text.(/blackle.com/ claims to have saved lots of watt hours for not being on a white background.

i love the magazine and look forward to reading more in the future

##### Sava Chankov

Great re-design, completely in line with the site's topic! Reminds me in a way of Fidonet, a lowtech computer network that was popular in early 1990s, before the Internet takeoff. It was ran by volunteers, who ran bulletin board systems that dialed automatically each other in the early morning hours to exchange emails, which took quite long to travel on it compared to the modern email.

##### Jan Steinman

YAY! You guys are my heroes! I've been wanting to do such a thing for some time.

One of the fundamental choices we made was to build a static website. Most of today’s websites use server side programming languages that generate the website on the fly by querying a database. This means that every time someone visits a web page, it is generated on demand.
But wouldn't caching deal with that?

We run a MediaWiki server on a Mac Mini, and are running memcached. About 90% of page requests end up being served by memcached, as far as I can tell. And with an SSD behind that, there isn't too much energy penalty for a cache miss, anyway.

##### Nicolas Huillard

Re. the 10W+ router: since you're on fibre internet, you may probably directly link the server to the fibre ONT, and get a DHCP address from the operator. You would still have the ability to connect from your laptop using a switch and 2 VLANs (the operator DHCP stuff probably already use a VLAN). You would have to check the details for your country/operator.

Re. CDN, IPFS, etc.: since this server is 2W max, adding more infrastructure will kill the energy efficiency (I doubt the typical-low-powered IPFS server around is less than 20W). The page lightness makes all that useless. The RSS feed makes the CDN perfectly redundant too. 500k page views in a few hours for this little thing is impressive!

Re. multi-site web-serving: I use "booth", a software package that distribute tickets to 2 or more locations. The location that have the ticket updates the DNS record to bring the traffic to itself, using a simple home-made script. The DNS stuff relies on setting the TTL very low (~5 minutes). This works great for my pro-hosting needs (semi-solar-powered highly-available hosting at 200W). Using this on very distant locations would make the website highly available at very low cost, and only twice the power (probably 2W active/loaded server + 1W standby server). Since there is no database, dual-active hosting is also very easy, using DNS round-robin. You just need to distribute the content (rsync) and aggregate the logs (mergelog) when there is plenty of sun.

##### STPo

You did a really great job here. Improvements are always possible (and welcome) but hey guys, that's what I call a redesign!

Glad to see some folks showing us the path.

##### Laplace Victor

First, I'm a huge fan of your solar project !

I'm a front-end developer and I see some improvements :

- as mentioned in other comments you can easily remove jquery (or at least use the [CDN version](https://code.jquery.com/jquery-3.3.1.min.js) it will be less ressource intensive for your server) and as I like your project, I rewrite your code in [vanilla javascript](https://jsfiddle.net/59kopbx3/) (let me know if you have any issue)
- images have width 100%, this is ok for mobile but not really on desktop, as your images max size is 800px, so I think you can add this style : .entry-content p.img{ max-width: 800px } it will be less pixel to render, so less energy consumption for visitors.
- also mentioned in other comments, PNG is not the lightest image format, you can have almost the same weight and preserve colors with jpg (or even webp)
- you can "minify" images. All images comes with metadatas, those datas are not necessary for displaying image on the web (ex for [sps_close.png](https://imgur.com/VsSji3A) 40.172 bytes vs 43.415 bytes for original). Have a look at <https://github.com/imagemin/imagemin>
- you can [lazyload images](https://css-tricks.com/the-complete-guide-to-lazy-loading-images/). Don't use the technique using 'scroll' event as it's really ressource intensive for visitors, prefer the Intersection Observer API
- you can also improve browser caching to limit reload of assets <https://varvy.com/pagespeed/leverage-browser-caching.html>
- you can also replace images cloud, sun in footer by unicode characters, <https://unicode-search.net/unicode-namesearch.pl?term=cloud> <https://unicode-search.net/unicode-namesearch.pl?term=sun>

That's it :)

##### Paul Ito

First of all: I love your website and wish I had come across it much earlier.

The article on how to build a lowtech website was super inspirational and sparked (re-sparked?) my interest in building a website with easy and low-impact tools.

My comments on the project:

1) I would love if you would give direct IBAN bank account information if in any way possible. As much as I respect the mission of donation tools like patreon and librepay, they *do* take their cut from the donations. The most direct way to support your product and your mission is monthly payments directly to you. I understand that this is only free of charge if your supporters happen to have an EU bank account with IBAN/BIC, but it would be worth at least giving readers the option to support you in that way.

2) I am not a big fan of the yellow battery indicator that is (as of right now) splitting the screen in half. This feels gimmicky to me and is distracting my attention from your great articles. (Very much personal preference of course)

3) In addition to other people commenting on the use of dithered images, you might consider hosting more hi-res (jgp?) versions on the server and linking the dithered images to them. That way people who *want* the better picture quality can have it, without everyone having to load articles with heavy images in them.

Keep up the great work, I will definitely come back more often!

Cheers,

Paul

##### Frederik Van Der Veken

Excellent project!

I love the idea of a static, non-always on website.
You’re making a fair point, and I agree we need to make a mental shift in what we expect from the on-time of a website.

However, I have some issues with the images.
As some people already mentioned, the dithering really lowers the quality a lot, while a lossy compression could achieve the same file size but with better quality.
Another issue is the black-and-white. This is indeed a smart thing to do as it saves a lot in file size, however, you have to make sure that your article does not depend on the color in the image..

E.g. in your [article on the high-speed trains]({filename}/posts/high-speed-trains-are-killing-the-european-railway-network.md) the original low-speed train route and the newer high-speed train route between Paris and Amsterdam are shown on a map in different colours. Of course both look the same in black and white and the distinction is lost. Maybe you could solve such issues by make one of the lines dashed?

##### Abelardo

Kris, I am cuban reader that become crazy with the cool low tech website

Could Low Tech design and host low tech websites for a fee, that contributes with the magazine?


##### Skye

Just wanted to say absolutely fantastic project - I will be watching this develop and plan to use your example as a template to follow in a website I will be building in the next year or so. The work you are doing is so important - thank you!

##### Geoffrey Tolle

I haven't had a chance to read all the way through your latest article (and won't understand most of it when I do) but I did catch one point that I thought worthy of consideration in the design of your energy storage system.

I see that you chose to use lead / sulfuric acid batteries as your battery back-up. May I suggest that you consider switching to iron-nickel batteries. It may be that I'm preaching to the choir but, in case you haven't heard of them, iron-nickel batteries are a proven if bulky rechargeable technology. They use alternating iron and nickel plates (relatively cheap) in a basic electrolyte to store energy.

They are rechargeable hundreds of times, have less toxic waste products, and are very durable. They have a slow charge and discharge rate but should present few problems for powering low-tech websites. While the units can be quite expensive, they are also amenable to home-production (something that anyone who can assemble a low-tech website should be able to handle).

Well, even if I don't understand the exact nature of this technology, I feel that the possibilities and the look into energy cycling will be helpful to me.

##### Roel RA

Dear low-tech readers,

Quick introduction: I'm Roel one of the collaborators of the project that worked on the web design, back-end and hardware.

As Kris already mentioned, we got caught off guard by the unplanned early launch and all the attention. We are still smoothing out most of the design. Having said that though, solar.lowtechmagazine.com was intended from the start as a public learning moment. The site we've made should thus be understood both a proposition but also as a question and we really appreciate your insights and feedback. These insights and feedback we will use to further improve the website over time and document how and why so they can be points of departure for others.

@Seppe:
We are aware that we could make multiple servers around the world to always have the sun shining and use clever routing to always have the machine on-line. However this was besides the point for us and contra-productive to our message. If weather-based renewable energy is to ever become our main source of energy, that only works if we massively decrease our energy use and adapt our patterns to availability.

In the case of our server it is fairly simple to have a 90% uptime with a cheap and energy efficient computer and a small solar panel. However. to go above that 90% we would need to double or triple the machines used, the solar panels necessary and our storage capacity available. That is not even mentioning the resources necessary to maintain all of this in different parts of the world. If this is to work in a sustainable way, we have to change our attitude and the best way to do that in terms of web is to challenge the holy grail of 'uptime'.

For me the articles 'How (Not) to Run a Modern Society on Solar and Wind Power Alone' and 'How to Run the Economy on the Weather' where very informative in this respect.

As others like @Daniel have pointed out, there is an energy advantage also in economies of scale, running multiple websites on a single machine.

I was very surprised for example during our peak traffic of yesterday. While on the front page of the popular website HackerNews we got 500,000 requests in a few hours, yet the 15 minute average load of the server never reached above 30% of total capacity. So yes multiple popular websites built around the same principles and technologies could have fit comfortably on the same machine.

Something that isn't addressed that much in the comments, but which was very important for the design process and the future archive-ability of low tech magazine is how we converted all of the articles into markdown plain text files, and have made archives of all the original images. This means the 'sources' of the site are in a format which is legible across time and distinct computing environments. Another benefit is that the articles can be written off-line and generated into the website or its RSS feed when necessary. This means the process of dithering the images is part of the generation of the website, so the originals are not lost.

This brings us to the point of the dithered images, which seem to be the most divisive element of the web site :)

@Francesco, @Evan V, @Menyang Li and others

I've looked extensively into image compression and have learned a lot in the process. The choice for the dithering the images was not only one to reduce the size of the file. It was also a design decision to make the web page more calm, legible and outspoken at the same time. I agree that similar space savings can be achieved with colored jpegs with very lossy compression but in my opinion they look a lot worse and need to be displayed small. We also made a decision to stretch the images to full width of the browser to create pauses in the text, whilst creating a sort of visual rithm.

I am also aware that in theory PNG is not the optimum image format, however it is a format that lets me limit the color palette to save space and still create great crisp dithered images. In my post-processing pipelines I've run tools like ‘optipng’ over the resulting output but they could only shave off another 5% of the image size at the cost of having two full extra hours of processing.

However, @Job van Der Zwan, I really appreciate your side-by-side comparison and it reminds me a lot of what I have been doing the past months. I am very impressed with your results and would like to find a way to see how we can create this style of crisp dithered jpegs in an automated pipeline. So please lets continue this conversation!

We plan to publish the pelican theme and all the code in the beginning of next week so those of you interested could have a look at it.

Another issue with the images is that of course not all images lend themselves to the technique, which has been pointed out a few times by some of you. This is something which we will address as well.

The jquery dependency, has also been pointed out a lot and we will remove it sooner rather than later. @Laplace Victor thank you so much for making a pure js implementation. This really helps. We'll be trying it out asap. Again once we've published our sources we are really open to pull requests.

This weekend I will publish an addendum to this article on the technical details for the server configuration.

As Kris already mentioned in this article and on the 'donate' page of the solar site, advertising trackers are incompatible with the new website design and we really want to make Low-Tech Magazine tracker free and sustainable so if you enjoy our work or find our public research useful please donating.

Many thanks for the comments!

##### Tomasz Jadowski

Yes, grid-powered router is the weakest part of this project.

Have you ever heard about mesh networks and [Hyperboria project](https://docs.meshwith.me/)?

When you setup a hyperboria node you could backup your internet connection
with Wi-Fi, GSM or another link and powered them by solar.

The cost is access only via hyperboria network when a grid is off, you could run both versions
(for "normal" IPv4 and for Hyperboria mesh) simultaneously.

I don't know how "expensive" in CPU and power is to run a Hyperboria node.

Good luck! I love this idea!

##### ijk_ijk

Your new solar site is fully accessible from not so powerfull client like old pcs and old tablets with poor hardware and obsolete OS. The regular site makes the browser of my 6 years old tablet to crash but the solar one is perfect ..and faster. Static sites are increasing the life of all clients.

##### J Campbell

Hi,

This is so cool.

I have always thought static websites are the best when your content is just pictures and words. Even the old image rollovers can be fun and generate a little interactivity. But I especially like the dithering idea. I use dithering as an artistic tool for some of my works because I find the dot pattern generated rather pleasing to look at. I also play around with the number of colors and swap colors used in the images. Photoshop's "Save for Web(Legacy)" tool is where I play with images and dithering. I find the diffuse style of dot pattern the most aesthetically pleasing.

Another energy saving concept is that of a black background. When displayed on users devices it required less energy. But it's a significant change to the site appearance.

I just wanted to let you know that this is a fantastic idea you have and it gives your website a palpable quality that does not exist on any dynamic webpage.

##### Joel Mikulyak

I'm a front-end developer, and just wanted to state that I completely love your decision to go low-tech and energy-efficient with your site. If you have any other great resources on the topic, I'd love to read more.


##### Marie Otsuka

Hi all,

I'm Marie, and I'm one of the designers / developers of the website. Thanks so much for your feedback! As Kris and Roel have mentioned, it somehow got out before we were quite ready, but it's been amazing to hear all of the responses so far. We'd planned for this platform to provoke discussion, so we're excited to get this jumpstarted.

A large part of the challenge of this project was balancing functional decisions with the design concept. Often, we opted for the more radical option so that this design questions our current aesthetic expectations. To chime in:

Images

Dithering

Certain images are better suited for other forms of compression. But our goal was to not only compress images, but also to call to attention this act of compression.

We found that dithered images can be stretched beyond their actual image size while providing a distinct aesthetic, and that the artifacts of compression can become an integral part of the design.

(Along those lines... many sites produce multiple images for different sizes appropriate for various display sizes. We opted to use the same image file for both thumbnail and featured images to prioritize the caching, even if it means that the listing pages may be a bit heavier.)

SVG

Inline SVG definitely makes sense as a lightweight graphic form! (They're actually used for the social media icons already.)

I also agree that the legibility of graphs can be improved with SVGs. But we'd need to convert the given raster images we have of these graphs into a vector format — which, if done automatically, would end up producing a super heavy SVG file. What would be ideal is for any informational graphics to be readable and text-based, with svg/css-based shapes, which we unfortunately currently don't have the capacity for within our workflow. But definitely a problem to address!

Using an SVG for the logo is a good practice too, which I've actually seen done well on many sites. But once defined, that logo would have to be preserved on any platform, not just on this website — whether publishing in print or web form. That file would need to be sent around as an asset for any marketing needs. Again, we wanted to question what it means to create a "brand" identity.

We also played with Unicode for the weather icons, but found that the way they displayed (especially more non-default characters such as "windy" or "clear night") were too unreliable. We'll work on better sizing/compressing these though! Also, more improvements are coming to the battery indicator / dashboard / weather page!

JS

jQuery
As Roel mentioned, removing jQuery is in the plans. Thanks to all those with the tips! We thought about doing some more research on potential browser compatibility issues the library helps take care of, but looks like it won't be an issue.

Offline
Service workers for offline reading is something I've also been doing some research on! We're looking forward to further develop how caching might fit into improvements for the site.

Thanks again for all of the comments!
And we appreciate your patience as we work through some kinks.
More soon!

##### QB

I’m a longtime reader and fan; I just wanted to let you know that on Firefox 61.0.2 on Mac OS 10.13, the website has a huge semi-transparent yellow box over the lower half. I think it’s a sun-meter or a battery-meter.

I’m not sure whether it’s deliberate or if it’s a bug that is causing it to cover all the text on the page. If it’s deliberate, I just wanted to let you know that it makes it almost impossible for me to read the page, it’s super distracting. I’d love for it to be just a thin sidebar or something in a top scrolling navbar sort of thing. Having something overlaid on the text like that basically renders the website unusable for me.

Thanks for all the work that you do, and the new server sounds really cool!

##### TC

First off thanks for introducing the world to your website, absolutely love it. I'm new to reading your site, but I assume low-tech is not at the exclusion of clever solutions (which IMHO is where the fun starts). The capability of low cost hardware means that there is a huge amount of potential in even the most basic setups.

It is a very neat idea and I think it could be a very useful concept which could also be applied to many situations where internet access is difficult or limited. In some cases a link to the internet may not be possible, so localised hotspots could also be used. This could be in developing countries, areas of natural disasters or even war zones. Allowing vital information to be broadcast, from medical information/advice to emergency assistance, lost/found persons to providing educational resources. Potential website-in-a-box?

This could also provide an excellent project for schools for teaching.

With regards to the site as a technology news site, I have several observations (none is intended as criticism):

Images:

I agree the dithered styled images are a nice design feature and adds a real charm to the site, particularly the colour categories flowing through to the article. However, you are right to concede that certain images don't lend themselves well to this treatment - ie. your web page speed test image. For diagrams/tables etc SVGs or similar would allow technical details to be read clearly, even if you apply the same grayscale colour mapping (if feasible).

Power bar:

Although I don't think I have any particular sensitivity to colours, I do find the colour hue across the article very distracting when trying to read and absorb the content (people who are particularly sensitive to this - often a characteristic of neurodiversity - will find it even harder). Perhaps consider limiting the overlay to the home page only, or (if feasible) to the article header bar only. A nice feature would be to have a day/night theme so people can select a contrast which is best for them - ensuring the site is accessible to a wider audience (and as someone else commented an added bonus OLED devices will use less power).

Uptime:

I do agree with the principle of 90% uptime, and it underlines the whole concept - adding additional panels and battery/storage, like you say, isn't the point. However it would be interesting if you can determine if the downtime is likely to be off-peak or not. Clearly for yourselves and your readers within +/-2-3 hours GMT their peak times will be very similar and may well be a good fit to the site availability. A study of loading before a downtime could provide an indication of if a certain group of readers are inadvertently being excluded (due to geographical or demographical reasons). Longer term it may be possible to characterise the charging and the loading to allow the site to predict the best times to go offline in order to meet peak times (and provide forecasted downtimes during off-peak periods). I'm sure that would make an interesting project for some students looking at machine learning.

Multisite:

The multiple site location concept does introduce some excellent possibilities, since even one similar site elsewhere in the world could provide complete coverage with additional redundancy, while reducing overall power needs by sharing the serving of multiple sites. This does complicate the setup a little but it does provide the opportunity to grow the idea further. This could perhaps provide the opportunity to scale down the setup with smaller panels and battery. As mentioned before this could have very useful applications for the website-in-box concept where multiple setups could be meshed to cover an area.

Energy storage:

I wonder how feasible alternative energy storage systems would be. It would be interesting if eventually you could replace the need for the batteries completely by using kinetic storage or similar (I claim no knowledge on how practical this is and probably is not suitable for your setup).

##### John

Great site, but what software did you use to generate the site?

You've given hardware details but no software.

##### peter garner

I'm truly inspired!

I've already been running my web site on a Raspberry Pi for a couple of years now and it's proved very economical. This morning I've managed to get my home page size down from 225Kb to 7.5Kb just by getting rid of "decorative" images and reducing the size of others. I found that some page loading speed can be recovered by using sprites, assembled using glue-sprite.

If you didn't want to serve images on-the-fly a potential low(er) energy option is to use a Gopher server. I also run one of these on a low-power Raspberry Pi and it's very effective for serving documents of all types. I know it's an old protocol but according to a recent survey there are 333 active gopherholes (servers).

I plan to start setting up a solar-powered web/gopher server soon, but as I live in Yorkshire, UK, my sunlight hours are not quite as good as Barcelona!

Thanks once again for a brilliant idea - it's the future!

##### Craig Balfour

My name is Craig. I'm a big fan of what you're doing with the Low Tech Magazine, and I love the idea of a solar powered website! The newsletter asked for feedback and suggestions, so I had a look if I could come up with any. This is all pretty rough, so I'm sure I've missed stuff, probably with responsiveness etc.

Anyway, this is my feedback:

Make battery meter a lot less in your face
Love the idea of the battery indicator, but it’s so distracting when reading! When it’s low it also visually breaks the content and makes anything in the battery indicator look like a footer. Here’s how I’d change it:

Align it right, not left.
Make its width something like 64px so it’s just a bar at the side (in the new whitespace)
Move the top border from the content to the battery div so it covers the top nicely.
Lessen the “intensity” of the black on the readout. I found something around #333 to be quite nice, but just play around and see what looks nice.
Also, when at smaller screen sizes, reduce it further and don't bother with the icon, and maybe even the number.

Centre content
Wrap your page in a div with margin: 0 auto; max-width 960px; or something like this to keep it in a nice tidy column on the screen. Otherwise it looks a bit like a newspaper and is hard to follow.

Font family
Really not a fan of the serif font. Nothing wrong with Arial and co, or maybe even a mono font to get that typewriter feel? Idk. I think just the normal sans. This won't increase network traffic, since it's not sending fonts.

Spacing
I have changed the page layout from using lists to using divs with display:flex. It's pretty powerful and a lot more flexible than ul. I think it will make life easier, and it's much easier to get decent spacing around things like the nav.

Logo
I do think you need a logo. A simple SVG is pretty tiny, and it makes the site look heaps more professional. I made a quick one, but use whatever (use that one if you want, or make your own, but I think it needs something!)

Sky background
I stuck a simply CSS gradient as a background to resemble the sky (since it's solar, it seemed nice). Not sure I like the gradient, but whatever. I did wonder about changing the background gradient by time of day. So at night where it's hosted, it would have a black background, then moving into yellow then blue as the day goes on. Only on the body background, not the content background or it would just be annoying. But it shouldn't be too hard. I think a gradient of black through yellow to blue scaled to something like 5000vh then offset based on the time. Shouldn't be much Javascript. Might look super ugly or distracting though, so not sure it's worth it.

Image sizes
There's one image I found called sunnyday.png which is displayed at width 20px, but the image itself is 800px wide! This is not good. It's a simple BW png so it's small, but a simple SVG is still less than 10% of the size. Further, if you're displaying images small on some pages and big on others, save two copies and only send the small one if you can. Storage is cheap, bandwidth (for you server) is not.

Minify agressively!
Ok, so I know how much we hate inlining, but it has its place. Not at the element level, but on the document level. The size of the files being sent is important, smaller files use less energy. However, the number of files is worth thinking about too. Sending a bunch of small files results in a server call per file, which can add up. Having a working copy of the site with all its separate files is a very good idea for building it, it’s SO much easier! But for the published one, I would think about minifying everything and putting your stylesheet contents in a style tag, using inline SVG for icons (this is a tradeoff, since they are duplicated when you use them again. And doing the “use” trick is not a whole lot better because it sticks them in an iframe-which means you’ve got another request anyway. But for small, one-hit images you could base64 encode them. For icons, make a stylesheet for just these and base64 encode the SVG itself, which is very small and doesn’t require hitting the server again.

I minified my version of your homepage to be one file which includes your original css, my overrides, the html itself, and the logo image as a base64 encoded svg. The whole thing is 41kb and loads instantly. It would only be one request to the server (the images on the page would all be their own, but there's not much you can do about this. Base64 encoding them would make them larger, so best to leave as is)

Also, you’re using jQuery. I would avoid that tbh. It’s a pretty big library, and all you’re doing is reading some JSON data, which you could do in a similar amount of code without needing to import jQuery at all. Until you rewrite that function, why not hotlink jQuery from a CDN? It will save your poor little solar server from transferring it each reques.

Don't hold open connections
Your script for showing battery percentage etc holds an open connection the server. I get why you did, but I think until you’ve got your power problems sorted, just query it on page load, then close the connection. Just fire and forget. Otherwise your server is maintaining a heap more connections than it needs, wasting power.

With something like this, you want your server to be doing as little as possible while still working. So anything the browser can do for you is fantastic. The use of image filters etc you’re doing is really great! Keep that up! Same goes for Javascript. So many effects can be done by the browser with some clever CSS. Try to avoid animating etc with Javascript when CSS will do fine. When you do need Javascript, try and avoid jQuery and other large libraries.

Also, when you are querying things like the weather JSON data, where are you getting that from? Can you hit that directly rather than storing it on your server then hitting your own server?

I know this seems like a lot, I hope it doesn't come across as arrogant or like I don't like what you've done. I am so impressed! I wish I could build something like this tbh. Just trying to throw some ideas around, and they hopefully some help. You're more than welcome to use any of my suggestions or code, or simply throw it all away.

I tried attaching my modifications etc but google doesn't allow sending zip files, so here's [a drive link](https://drive.google.com/drive/folders/1G8j1G9JyVuq8d8kz4EWUity2gmXKuuih?usp=sharing).

If that link doesn't work I could try sending loose files.

I've also attached some screenshots just because it's easier to glance at them quickly.
<http://krisdedecker.typepad.com/.a/6a00e0099229e88833022ad3b4657e200b-pi>
<http://krisdedecker.typepad.com/.a/6a00e0099229e88833022ad394c691200d-pi>
<http://krisdedecker.typepad.com/.a/6a00e0099229e88833022ad394c69e200d-pi>
<http://krisdedecker.typepad.com/.a/6a00e0099229e88833022ad36e9bd0200c-pi>

All the best, and hope some of this helps.

[Craig, thanks a lot, I hosted your screenshots on Typepad otherwise the colours won't show, KDD]

Posted by: Craig Balfour | September 28, 2018 at 04:29 PM

##### Premkumar Masilamani

Hi Team - I am impressed with the solar powered website running from the home. Congratulations. I disabled comments on my blog and used a contact form to let the visitors send a message to me. That was one portion of my blog which is hosted elsewhere. Your idea of asking the users to send email to get the comments is really well thought of. I am going to implement that in my blog.

1. How feasible is it to put the email address on the webpage?. Are you net yet spammed?. Are you doing something on this front?.
2. How are the emails converted as blog comments?. Is it a manual conversion or automated? If automated, could you tell us how?. I would like to implement that in my blog as well.

##### Hans Fast

Many congratulations on taking this step: making the statement, showing that it's possible and even extremely attractive to build a website without all the weight we've come to accept. Loading this website is like a breath of fresh air. And your server performance under peak load speaks for itself!

It's clear that you're doing more than publishing a website, it's a demonstrator of the energy usage involved in serving a site. Respect for that.

I would like to mention dat and Beaker browser again (mentioned at least once above). While making a point of letting the website go offline when the battery is empty is a powerful educational move, the various peer-to-peer protocols all overcome this limitation of the http model (I'm only familiar with dat). Publishing over both http and dat simultaneously is fairly straightforward and maintenance-free, so it adds little overhead. Then everyone who views your site rehosts it: if your server is offline, others can still access it via those peers. No need for the solar panels and battery or even the server, you can publish from your laptop. Even more (embodied) energy savings :)

Of course, this is only practically true once all browsers speak peer-to-peer protocols .. and I believe a server is still needed for DNS resolution (so people can find the dat archive that belongs with solar.lowtechmaganize.com). In the meantime, fantastic work of public education going on here.

##### iří Maha

Hey guys,
love your project of low energy consumption website.

I have a two questions:
Any use of versioning system for development? If not, how would xou scale such a project?
How do you deploy? Simply copy files manually?

Thanks and cheers from Czech republic,
Jiří

##### Nikolaus Bartke

Wow, fantastic project, I‘m in love!
I really like the literally spoken „background information“ about energy and weather.
This makes a big difference in perception and creates awarenes in several respects!

Pertaining the comment section, perhaps you can publish a timestamp, like when the mail was sent...

##### Kris De Decker

@Nikolaus Bartke, @Premkumar Masilamani

For now, the comments are added manually to the page. However, this approach doesn't combine well with the amount of comments we are receiving at the moment. We're looking into ways of automating this process. A timestamp could be an idea indeed.

@TC, @Geoffrey Tolle

We chose a lead-acid battery as an energy storage medium because it was available from an earlier solar PV setup. The LiPo battery came with the server.

These batteries will need to be replaced within 1-2 years, but the ultimate goal is to replace them by a compressed air energy storage system. [See: Ditch the Batteries: Off-grid Compressed Air Energy Storage]({filename}/posts/ditch-the-batteries-off-grid-compressed-air-energy-storage.md)

It is one of our goals on [Patreon](https://www.patreon.com/lowtechmagazine)

The solar and battery system are still in an experimental phase. For now, it looks like we have overbuilt the system. This is mainly due to the fact that the router is not yet solar powered, but also because we overestimated the energy use of the server, and because we underestimated the energy production of the solar panel.

We already switched to a battery that is three times smaller: we are now running the sever on the 24Wh UPS LiPo battery and use the lead-acid battery only as a regulator. The next experiment is to run the setup with a smaller solar panel. The aim is to downsize the system as much as we can.

@peter garner

It would be great to see how a similar set-up works in a less sunny country like the UK. Keep us informed!

##### Greg Melton

Many thanks to all the work that has gone into this site. On a personal level, it has inspired me to take up something along the same lines.

I'm not a technical guy, but I did notice that solar.lowtechmagazine.com loaded quite quickly even over a dialup connection. Image dithering may have played a role in the fast load time and perhaps it also requires less cpu power to present the image
in the browser. Power savings at the server and the browser.

Although it is most likely not compatible with the goals of
Lowtechmagazine, the Gopher protocol, I understand is also much less energy intensive. Perhaps a gopher server on the same machine could serve up a Gopher version of Lowtechmagazine.

##### Adam

Hi there,

I love your solar powered project. Fantastic post about it too. One thing I noticed is that your dithered images can be even smaller file sizes if you run them through the tool at tinypng.com - I tried out a couple and it shaved 3-5kb off each image.

I'm a designer/dev and even though there are lots of ways to squish images in gulp, photoshop and many other tools, I've found that the tinypng tool works brilliantly, there's even a CLI you can use.

Just to clarify, I have no links to tinypng, I just really rate their tool.

In my job, I make a lot of static sites with lots of javascript scrolling effects and images so I'm always squishing and minimising to optimise performance but I'm still dealing with quite large page sizes so it's great to see optimisation really pushed to the limit.

I think it's a really interesting project. I work in the news industry so taking pages down to the bare minimum is a really interesting idea, especially when you're disseminating essential news in countries or situations where internet is sporadic at best.

Fascinating stuff and I can't wait to read how the experiment progresses.

Thanks,
Adam

##### Kris De Decker

Reader Qwerty translated [the article to French](https://zestedesavoir.com/billets/2839/comment-fabriquer-un-site-internet-a-basse-technologie/)

Merci beaucoup !

##### Brando

Hi, I saw yesterday your solar website (via Hacker Newsletter), amazing experiment: probably if half the web would save on bandwidth the world could be a better place.

Just a note, the dithered images are a nice hack but on my full HD screen are streched to the border and I think they would look better if you put a maximum width at 1080 px, also because the text doesn’t reach the borders (good) and the images are 800 px wide.

I subscribed the RSS feed, you have some nice articles there but I’m really curious how your experiment will evolve. And also you let me think about the option to migrate my personal site from WordPress to a static generator like HUGO.

All the best, Brando.

##### N Bennett

Hi,

I just read your article on your new web-server approach. Besides your technical implementation, I really liked the way you reduced the web sites data footprint. It is so refreshing to see a website that concentrates on content, and is not overloaded with cookies, banners and whatsoever content I had to ignore otherwise. Websites nowadays are so overloaded with functionality and advertisement, which distracts from the actual content of interest. Thanks! I think, others should follow your approach as well. Clean, nice, and slick.

##### Roel RA

Hello everyone,

For those that have been wondering about the technical details of solar.lowtechmagazine.com I've written a guide on software and hardware over at <https://homebrewserver.club/low-tech-website-howto.html>

It should answer most of your questions but it has a few questions itself!

Please have a look at it and feel free to get in touch.

greetings,

Roel

##### Leon Stafford

I've been a happy subscriber to Low Tech Mag's newsletters for many years now and so glad to see web hosting addressed here, as it's also my nice product at the moment. It allows WordPress sites to be published as static websites, perfect for then serving on a raspberryPi, as some users have reported doing. Depending on the size/load of the site, you can also generate it on the Pi, but I'd keep that stripped down as much as possible and just do static file serving from it. Almost every Pi owner has another computer that can run their WP site for the development part.

##### Tom

Could you add a print-friendly layout of articles for easy printing them and read them offline? I am an English learner and I use your content as a learning personal materials, because when we read something interesting us, we spend more time with them and learning is more fun :-)

##### Nicolas Huillard

@Kris "due to the fact that the router is not yet solar powered"

Yes, make sure that everything needed to connect the server to the Internet (on your side) is solar-powered. Not powering the router, ONT or anything else from the sun is cheating ;-)

You should be able to switch off the grid in the house and still see the lights blink...

Having a nice RRD dataset of the information provided in /api/stats.json, and generating graphs from it would be very educational: we could see how the battery drains in the night, probably faster in the evening when lots of people browse the site, then less so in the middle of the night. We could notice when solar production starts in the morning, offsetting the drain from the server, then starting to charge the battery, and produce a lot of surplus at solar-noon. We should also see seasonal variations and how they're strong.
I use 5 minutes resolution RRD for a few days, then ~1h resolution for a full year, then store nearly daily data for a few years. The problem with RRD is that you must predefine everything at the beginning. The positive side is that it's very light, and suitable for the hardware you have (just take care of Flash wear, probably with tmpfs synchronized with Flash at intervals, or a kind of in-memory RRD server which will store the RRD file at intervals).

(I post on the heavy-website, in the hope that it may reduce your hand-work. You may decide to redirect from the old site to the solar one ASAP, not until you have solved the differences in URIs : old /2018/09/how-to-build-a-lowtech-website.html vs. new /2018/09/how-to-build-a-lowtech-website/ ; we should be able to replace www. with solar. in the addresse bar and get the same article, not a 404 - nothing a tiny rewrite in nginx couldn't solve)

##### Tomas

Hi

I saw your post about the soler powered webserver. I think it's quite neat, but using grayscale PNGs makes a lot of graphics on your site kinda useless, especially any colored graphs like in this [article]({filename}/posts/thermal-efficiency-cooking-stoves.md)

JPEG at a low setting will produce much better images, without loss of color.

For graphics, where PNG is more suited, using a palette makes more sense than grayscale. It's not always better to use a smaller palette either. smol-16.png uses only 16 colors, but takes up more space than smol.png!

Finally, you can use zopflipng to get the most out of the PNGs you've already encoded (if you have the CPU cycles to spare). I generated the attached images with these commands:

convert 6a00e0099229e88833022ad3b23825200b-750wi.png -quality 50% smol.jpg
convert 6a00e0099229e88833022ad3b23825200b-750wi.png -colors 256 -ordered-dither o8x8,4,4,2 smol.png
zopflipng smol.png -y smol.png

Oh, also a lot of links on the solar version of the site are broken :)

##### Kris De Decker

@Tomas, @Nicolas

Thanks for pointing out the problem with broken links. As you have noticed, it's caused by a different URl structure on the old and new websites. We're fixing it ASAP.

##### Rod

I agree the "battery meter" is not clear. The battery is around 90% now and I kept wondering why the "white header bar" didn't scroll off with the top of the page. I read near the top of page and I hate the visual distraction (on all websites). If the battery was 50%-80% I think I'd close the page. :/

Why don't you make it 5-10em wide on the left or right so that it will (most likely) fall outside of the text column?

Or better yet make it a thin horizontal meter at the top or bottom?

##### Nick

Hello!

I applaud your recent effort to reduce the energy usage of your website. However, while reading this [article]({filename}/posts/how-sustainable-is-pv-solar-power.md) I have had trouble reading and interpreting the graphs that are displayed. It seems the dithering effect you implemented may have been too severe for these information rich graphs - in particular various different colored labels are hard to discipher and the text in one chart is illegible.

It is up to you to weigh the trade-off in legibility vs. size for these images, but I thought I would let you know I had trouble reading them.

Thanks for providing this information,
Nick

##### Rick Canfield

Hello Kris,

Really love the design and mentality behind the website, I think it's the start of a new trend for all potential eco-friendly sites in the future. I can picture a coalition of energy saving sites existing with their own badge of honor.

One thing I'd like to suggest or ask about, and maybe it's something you guys have looked into, but whether inverting the site (dark background and light colored text) might not save more energy? I recall Google having an energy saving day many moons ago and they inverted the Google homepage to black for a day, saving a significant amount of power.

I use a plugin Google Chrome plugin called Dark Reader, which helps invert the color of pages in a readable manner, more for the sake of reducing fatigue on my eyesight.

It doesn't make much of a difference with LCD screens, but would with CRT and OLED screens, (which OLED may be the way of the future). It may be good practice to start with. <https://www.quora.com/How-much-energy-would-be-saved-if-Google-used-a-black-screen-instead-of-white>

I'm just wondering if this something you all have considered. I commend the extensive endeavor, creating rare and unique online experiences I believe enhances authenticity.

##### Abraham Palmer

You might have heard this from others but there are many peer-to-peer and synchronization type of technologies that align completely with your goals. It allows people to share the hosting. The technologies haven't crossed over to critical mass, but do appear close. I follow things like Holochain, DAT project and Beaker Browser, IPFS, and Scuttlebutt. You have already done all the hard work and so any mostly available can be replicated now globally with very low total energy usage. I need to get my own website and cloud hosted application converted over to one or more of these. I'm sure the extended community will be happy to help further if you need it.

##### Kris De Decker

@ Nick & others

We know that some images do not work well with the dithering plug-in and we will solve that issue. It's a good opportunity to try out some of the other compression techniques.

@ All

We have released the [source code for the website theme](https://github.com/lowtechmag/solar).

And we have published [a hardware/software guide](https://homebrewserver.club/low-tech-website-howto.html).

##### Ander Gomez

I've seen that you used Armbian, that's a good choice.
Did you consider Alpine with the lbu mode? (r/o image with commits made from the user with "lbu commit -a", will all the new stuff is written back to the sd image, which is the rootfs.

optipng can optimize PNG images without losing too much quality.

Finally, thanks for your low-power site inspiration :D

##### Kris De Decker

Very interesting discussion at Metafilter <https://www.metafilter.com/176879/always-online> where some commenters are arguing that we are "giving solar energy a bad name".

##### Fred

Your website is really excellent, bravo! And it is nice & practical to follow the rss. Just one (small) regret, there are no social links (you know, images where you may click to "bookmark" the page), on twitter (I like), facebook (I hate) or other social media.

##### Alex

Hi!

I was fascinated by the idea and the execution on your solar powered website. Really well done!

I know this is more of a proof-of-concept than an actual production version, but you could squeeze couple more percents of battery life if you'd minimise the pictures. Feel free to disregard this of course :)

I've ran some images from the website through ImageOptim tool and reached savings of 19.5% per file on average.

You can probably find a suitable tool with similar savings results to incorporate into your publishing workflow e.g. pngcrush.

Let me know if i can be of any help.

Regards,
Alex

##### Andy Jacobs

I love the idea that you're pursuing with the server and it clued me in to some great resources for open-source hardware and related projects.

A couple thoughts on the comments section (and community). First, there are ways to accept comments, store them in git, then rebuild the site. Check out <https://staticman.net/> which is designed for Gatsby.

Secondly, there is a burgeoning movement called IndieWeb that allows people to comment, like, or RSVP to your posts from their self-hosted website. Your site can be notified using a "webmention" so that you know they've commented via their own website. Webmentions work a lot like trackbacks, but have some cool new features. <https://indieweb.org/Webmention>

Somewhat related ideas: how does hosting on IPFS or Dat align with your goals? In that way, the static resources are distributed among nodes, and would still be available from the mesh if your node goes down.

Keep up the good work! Someone turned me on to your work from the Scuttleverse.

##### LWATCDR

Like the solar website layout but I agree that your site would use fewer resources if it was run on a cloud server. Modern cloud-based systems are very energy efficient. When no one is visiting your site you are still using power waiting for a request. On a cloud, that system is serving someone else's site. Second, your solar powered site is not low tech. ARM-based SBC running Linux using PV solar is anything but low tech.

I find it kind of funny that some of the same things you are using today I used 20 years ago when I wrote my companies website. I was obsessed with making it work well over dial-up and used a lot of static pages. For example, I had a directory of people looking for work. It was a static page that was generated when someone added an entry.

The dithering is kind of cool and retro looking but just not really worth it for informative sites.

##### Kris De Decker

More articles and discussion about the solar powered server:

[https://www.fastcompany.com/90246767/the-future-of-web-design-is-less-not-more](https://www.fastcompany.com/90246767/the-future-of-web-design-is-less-not-more) (very good article)

[https://tech.slashdot.org/story/18/10/02/1739237/this-solar-powered-low-tech-website-goes-offline-when-its-cloudy](https://tech.slashdot.org/story/18/10/02/1739237/this-solar-powered-low-tech-website-goes-offline-when-its-cloudy)

[https://hackaday.com/2018/10/08/perfecting-the-solar-powered-web-server/](https://hackaday.com/2018/10/08/perfecting-the-solar-powered-web-server/)

##### christian weber

Hi Lowtech<-magazine Team,

Great work with your new solar driven web-server. Even when my SBCs are mostly a bit more power-hungry, I like the concept of max out an A20. 'Featured' in the forum now. :)
<https://forum.armbian.com/topic/8315-daily-tech-related-news-diet/?do=findComment&comment=64064>

I would love to see a short sum-up tutorial here as well (if time allows it):
<https://forum.armbian.com/forum/26-research-guides-tutorials/>
You might get some hints when posting it again there how to improve consumption even more.

##### Benjamin Henrion

There might be a way to consume way less energy would be to use a mix
of an openwrt router as an HTTP proxy caching the connections, and
waking up a more powerful device, such as an Allwinner A20 board.

Some Allwinner boards have a PMU chip that is well supported on
Android kernels. But last time I looked at linux-sunxi.org, the
suspend to ram supporting that chip was sparse.

I have tried a setup with an openwrt router caching the pages, and
that can wakes up an x86 PC with an SSD within 2 seconds with a WOL
packet, and some iptables+tc delay magic.

##### Andreas Kosmehl

Hello,

i read the article about image compression on your page. <https://homebrewserver.club/low-tech-website-howto.html>

If you compress the image with <https://tinypng.com/>, the image quality is better than dithering and the file is also small.
Dithering is not so nice in the browser display when zoomed out. <https://homebrewserver.club/images/international-switchboard.jpg> tiny.png from 163.3 KB (jpg) to 81.9 KB

##### Dominic

Thanks for this excellent post on a very interesting topic.

I share your concerns about the increasing energy demand (not only) of the internet. Therefore using a purely solar power setup (except for the router...) is a pretty radical, yet very consequent (given the "low tech") approach. In addition, to me it seems a bit like art :-)

Coming from a job, which is all about power conversion and power management (funnily enough: for ARM based system) and having an interest into solar power applications for myself I could not stop myself from digging into the described and depicted solar charger and supply setup.

I may well be wrong (having maybe searched for the wrong part, or maybe just found outdated information), but is it possible, that the charge controller is just a linear type with no MPP tracking? (I found this one:
<https://wholesaler.alibaba.com/product-detail/CM2024-PWM-12v-24v-20a-solar_60099884539.html>)

In this case, the power being stored into the battery is not 50Wp, but just, say, 20Wp (depending on the way the solar panel is built/ internally connected).

Opting for the (indeed) more complex technology of an MPP tracker, or at least simple switch mode step down converter (Solar -> Battery) could drastically increase the amount of power you can use for your setup or other
household applications.

Even if the charge controller was an MPP tracker, you might want to consider using one with a lower current rating. Using (massively) oversized supplies,
can ruin (usually it does) the efficiency of such a switcher.

In addition a separate step down converter from the solar panel directly to 5V for powering the server board might (depends on how's it built) increase the efficiency of the system even further. The input of such a setup would
be a (wired) OR (using a dual diode with a common cathode) from solar panel and 12V lead acid battery then.

Having built my own solar powered setup (for a clock and an USB charger/ 5V supply for all kind of stuff) I can highly recommend using some(!) more sophisticated parts. It really pays!

I would also be interested in getting to know, which way the supply voltage (5V?) for the Olimex board is generated?!

Best regards
Dominic

##### Tomas

Hi

I saw your article on the sustainability of solar power [1], and I believe your argment is a bit off.

Yearly insolation for PV purposes doesn't vary as much with lattitude as you think, at least judging by the use of GHI in the article, which is very unfair to any installation outside 30°N-30°S or so.

A more fair estimate is to use global normal irradiance (GNI), weighted by how much power loss is expected due to imperfect pointing [2]. If I do this for the solar installation I'm currently building I come up with the number 2500 kWh/year, for a 2750 W installation, based on data from the Swedish Meteorological and Hydrological Institute for my location.

Whether this pans out remains to be seen, so take these numbers with some reservation :)

There's two other problems near the poles however: fewer sun hours in winter, and the distance between rows must increase. The latter isn't a huge problem since land is much cheaper than PVs. The former is nicely covered by wind power, which is more plentiful in winter (but turbines must be quite large to be worthwhile).

Apart from this I think most of your points are valid.
Using nuclear power to produce PVs is something I've suggested to some environmentalists, and reactionaries pretending to be environmentalists, and neither of those have wanted to hear it.

Tomas

[1] <https://solar.lowtechmagazine.com/2015/04/how-sustainable-is-pv-sol
ar-power.html>
[2] <http://solarpaneltilt.com/>

##### Pete

I have seen your low-tech-website and when I have seen your "Room for improvements" section, I had some ideas, I want to share:

Image Dithering:

I am not sure, if you can use that for your website, but another day I stumbled upon thet project for compressing images: <https://github.com/FLIF-hub/FLIF>

According to the compression experiments we have performed FLIF files are on average:

14% smaller than lossless WebP ,
22% smaller than lossless BPG ,
33% smaller than brute-force crushed PNG files (using ZopfliPNG),
43% smaller than typical PNG files,
46% smaller than optimized Adam7-interlaced PNG files,
53% smaller than lossless JPEG 2000 compression,
74% smaller than lossless JPEG XR compression.

More info: <https://translate.google.com/translate?anno=2&depth=1&hl=de&rurl=translate.google.com&sl=en&sp=nmt4&tl=de&u=https://docs.google.com/spreadsheets/d/1LxY78fbm47VmrYGTXkBXXitGjhGl32NsuHPH2QXufgA/edit%3Fusp%3Dsharing&xid=17259,15700022,15700124,15700149,15700186,15700190,15700201,15700214>

Another more popular image format is "WebP":
<https://developers.google.com/speed/webp/>

From description:
" WebP lossless images are 26% smaller in size compared to PNGs. WebP lossy images are 25-34% smaller than comparable JPEG images at equivalent SSIM quality index. "

Router for the internet connection (lower power consumption):

I would expect, that a sort of ARM computer like RaspberryPi con do the job with less power comsumption. As most of them are only equipped with one NIC only, you hace serveral options to add a second network interface, which is the "clean" way for a router.

a) use a USB to RJ45 network card and connect it to the USB port of the single-board computer.

b) use a "Multiple Ethernet Expansion Board" <https://www.raspberrypi.org/forums/viewtopic.php?t=179904>

Look here for a example for RaspberryPi: <https://www.raspberrypi.org/forums/viewtopic.php?t=179904>

And here: <http://www.industrialberry.com/ethernetberry-v-1-1/>

SSL and Legacy browsers

Should we maintain both HTTP and HTTPS versions of the site?

In my opinion: A clear NO. There are a lot of linux distributions, that offer SSL compatible browsers with a very small footprint. So I will not trade in the security for old browser compatibility.

Just my two cents - hope it helps,

Pete

##### Paul Clarke

I like the idea of the dithering, especially combined with the idea of "print on demand" of articles or issues - let people have the high quality images if they really want them, but offline. Could perhaps do a paywall with high quality versions of the images? Not quite sure how it works with a static site but I will think on this. I like the dithering but think you do need to be sure you have the lowest file size if you're going to have low quality images, I'm sure you're on to this now.

I also moved to a static site for my family tree site (using metalsmith) and don't really have images on there at the moment, but will be taking some inspiration from here, muting my colours and adding in some low res black and white imagery while still trying to give it some style.

Also inspired to reinstate my solar powered ambitions - I had a raspberry pi based webcam powered by motorcycle batter and solar battery charger, but could not keep it online for more than a few hours...

I have a solution for searching articles while using a static site, for example <http://www.clarkeology.com/wiki/#solar/power> - the (very simple, no dependencies) source is below, the minified version is inlined in the page.

'(function (location, innerHTML, path, div, h2, folders, i) {

function get (url, callback, request) {

request = new XMLHttpRequest() // sorry ie6 etc

request.open('GET', url, true)

request.onreadystatechange = function () {

if (request.readyState == 4 && request.status == 200) { // eslint-disable-line eqeqeq

callback(request.responseText)

}

}

request.send()

}

function change (e, hash) {

hash = location.hash

if (!hash) return

path = hash.substr(1)

div = document.getElementsByTagName('div')[0]

h2 = '' + path.replace(/\W/g, ' ') + ''

// div.innerHTML === div['innerHTML'] and we passed in the string innerHTML

div[innerHTML] = h2

folders = ['/names', '/gig', '']

for (i in folders) {

get(folders[i] + '/wiki/' + path + '/', function (content) {

div[innerHTML] = div[innerHTML] + content

})

}

}

window.onhashchange = change

change(location.hash)

})(location, 'innerHTML')'

##### Rob van der Zwan

Dear Kris and team,

First of all, thank you for many years of inspiring articles. Not only were they a joy to read, I have used the insights from them on many occasions in my own life (though admittedly I have trouble going through with all the radical steps required for sustaining this planet, because the mismatch with current societal structures makes it so hard to (ironically) sustain).

Not only than that: I have shared specific topics on response to people asking for advice on buying something new, fixing an issue in the house, and many other cases were your articles can give inspiring alternative ideas¹.

Which leads to my suggestion. The articles are great, but also very dense and often elaborate, giving historical contexts, developments, etc.

My sister just got a new apartment. It is empty. That is a great opportunity to start fresh and do things right from the start! I am looking for one myself, and when the time comes I look forward to having the same opportunity. However, while I enjoy doing the research, the act of "optimisation" my lifestyle, so to speak, my sister represents the more typical case of simply not having the time to read the whole Low Tech Magazine archive digging for gold nuggets.

While I'm already suggestion infrared heating, hooded chairs, Japanese-style insulated tables (forgot the name), putting thermal masses on sunny parts of her room, fireless cookers, pot skirts, but I know I'm missing lots.

Now imagine an illustration of a house, featuring almost all of the ideas you ever wrote into one image. A counter-image to the stereotypical technologist's House of the Future. A House of the Past for the Future, as it were.

Add an image map (look it up, its forgotten but amazon old HTML technology) with links to articles and summaries of articles, and you have a something that lowers the treshold for people to start changing their lifestyles.

Kind regards,
Job van der Zwan

¹ for example, last week I shared the article on heated clothing with the owner of <https://www.sockmama.com/>, who actually makes most of her money selling special socks in person on markets. Both as a suggestion for heated clothing for herself to keep warm in Christmas markets, as wel as promoting warmer and even heated clothing through selling the socks herself - she loved the idea and is looking into it!

(Oh, BTW: I have donated to the project in the past and would like to again, but I'd like to do so directly per bank transfer. Is that a possibility? And I'll try to make some time to contribute to that research into image dithering pipelines, but I can't promise anything)

##### Hunor Karamán

Yo Kris,

First of all good job on the carefully crafted magazine. I really enjoy the content and the whole way you handle this site!

I don't know if you intentionally haven't done it, but sharing the site through Dat would be a good fallback for the times it's down (because of the sun). If you're not familiar with the protocol, I would happily help on that

I'm just overall curious about your opinion on this.

##### Michael

I'm from Germany and read on an advertisement in the bus this afternoon about your website and that it goes out during bad weather. I believe that pointing out the last part that the websites sometimes shuts down delivers the wrong message about solar which is the biggest argument for coal and other dirty forms of energy.

The argument that you can't store solar energy. But it is possible to store energy with batteries. Have you thought about buying one so that your website doesn't shut down? Like a Tesla power wall or something. It would deliver a much better picture about the sustainability and availability of solar power.

Thanks for reading my thoughts on this small topic.

##### Ploc

Hi,

I've been very interested in reading your article named "How to build a Low-Tech website: Software & Hardware" :
<https://homebrewserver.club/low-tech-website-howto.html#compression-of-transmitted-data>

I'm also involved in generating static website and I'm surprised that you confifured your server to gzip resources on-the-fly. As the website is static, and already generated, the result og gzipping is a predictable process and can then be done at the static website generation step.

This would consume less cpu on the server than compressing of the fly, and hence save energy.

What do you think of that?

##### Jan Fabry

Hello,

One small CPU improvement for nginx: if you use the gzip_static module, you can serve precompressed files, instead of letting the server gzip the requests on the fly every time. This should save some CPU cycles.
<https://nginx.org/en/docs/https/ngx_https_gzip_static_module.html>

You would need to change the Pelican workflow to also create .gz versions of the content that can be compressed, but that can't be too hard.

Regards,

Jan Fabry

##### Dave Evans

Hey there!

Just a quick word to say hi and that I really appreciate the project that you're working on. I've been a HBSC mailing list lurker for a while as I too am interested in self hosting a low power solutions to hosting and creating networks.

I'm actually doing a PhD at Goldsmiths, University of London speculating on the relationship between historical
asceticism (hermits, monks, austere protestant living) and networks, looking for clues to how reimagine the network at a more human scale (I'm not religious in the slightest, but the link between how monks etc dealt with the vastness of their God and how we might cope with the vastness of the web seemed like a nice, perverse lens to look at the
internet!).

Anyhow. I've made some solar wireless local area networks (the most recent in a community permaculture garden in a train station). I'm also just trying to get a raspberry pi running as a home server to host my research. What web server do you use for the magazine? I used apache as it was what I've been used to, but would be interested in
alternatives (although I studied printmaking and sculpture so am on a steep technical learning curve these days!).

I have presented at various international conferences and written some stuff about the relationship between asceticism and the internet at the address below - and would love to publish to your magazine if you think it might be appropriate. <https://independent.academia.edu/DaveEvans19>

Keep up the good work - I will follow with interest!

Best wishes from Liverpool,

Dave

##### Raúl

Hi Kris,
your project just boom me!

I am a webdesign freelance from Madrid mountains that works to transform internet into something more simple. I also use portable solar panels to work on the woods.

If you need some collaboration or help with the project please contact me! you can check here some of my portfolio <https://lapatineta.com/en/portfolio>

hasta luego!

Raúl

##### Roel RA

@ Ploc, Jan Fabry,

It seems indeed like a good idea to do the GZIP pre-compression as a step in the generation process. I'll look into this. Thanks for the tips.

@ Dave,

The whole set up, including the webserver, is described here: https://homebrewserver.club/low-tech-website-howto.html

I think both Apache and Nginx are quite suitable for small websites. They are particularly good to use when learning about selfhosting, since there are many articles online about these softwares.

greetings,

Roel

##### Mikoláš Štrajt

Hi,

I just found link to Low tech magazine on Hackers news.

I really enjoy the articles because I am interested in both old technology and solar punk.

I also enjoy the somewhat controversial design element - dithering of images.

But - sometimes dithering the images makes them "unreadable". For example some of those wood carvings in article about ropeways (https://solar.lowtechmagazine.com/2011/01/aerial-ropeways-automatic-cargo-transport.html). Even worse is map at article about high speed trains (https://solar.lowtechmagazine.com/2013/12/high-speed-trains-are-killing-the-european-railway-network.html) - this probably should stay as is, because it's already PNG with limited color set.

Anyway I really like your site. I hope there will be enough light/battery to stay online at weekend. :-)

Also If you need some photos of obsolete tech (steam trains, old tramways etc) I can look for it in my archives. I visit transport themed events quite often.

greetings from Prague by

-- 
Severák
https://tilde.town/~severak/

PS: now after some 30 years we have again trolleybuses (in trial operation) in Prague

They did presentation with old vehicle from musem on new track.

My photos from that event: https://www.zonerama.com/metropolis/303066

##### Paul Laborde

Hello,

I read your article from France and I love your idea.
I tried few time ago to create this kind of machine for an automated solution in gardens.

Maybe I can share some ideas :

Add a proxy page when your server is down a temporary offline page can be displayed

How is user traffic ? Wan you maybe integrate directly a cellular connectivity instead of optical fiber ? (like Soracom)

This new connectivity allow to move server to original hosting zones (trees, mountains, etc)

Maybe you can add an power indicator about battery capacity and solar level with a downtime estimation ?

A super light server with ESP8266 could be original too

I just discovered your website, it's great !

##### N Valova

Hello, Kris.

I've just come across Lowtechmagazine project, thanks to a reshare of a friend on Mastodon.

The idea behind your project is wonderful, and it's valuable that you provide RSS subscription (thank you).

The project is also broadcasting on Twitter. The big Twitter with fat data centres. Have you heard of Mastodon? It's one Fediverse project - a twitter-like federating platform.

To be honest, Mastodon relies on modern web technologies, so it can't be easily hosted at home on a small computer. But there are other interconnected projects (for example, Pleroma) that are more ligthweight and can be hosted "on a potato" some users say.

Self-hosting. Could this topic be of interest to you, in the context of what you're writing about?

I don't know whether self-hosting one's social media can possibly decrease energy consumption worldwide... May be? If people start paying small ammounts of money for energy (self-hosting) or to friends-administrators who will do the server work for them, perhaps people will re-evaluate their social network habits? When there're no big companies providing "free" unlimited server space, and no algorithms showing constant ads with brands telling you to buy this and that "because fashionable", perhaps, users will stop over-consuming and learn once again how to have meaningful online conversations.

Please, consider joining Mastodon (Fediverse generally). There are ways to automatically post from Mastodon to Twitter (https://crossposter.masto.donte.com.br) Many people follow your project on Twitter. I'm sure there are also people among fedizens who will be glad to read you on Fediverse. Perhaps even some of your Twitter followers will eventually join. :)

##### Tom

You guys are awesome! I've been following your blog for quite some time now, I think the first article I read was the one on velomobiles. As an IT student and sustainable, low-tech living-minded individual, let me tell you that your article on a low tech internet rang close to home. And now that I see that you're working on an actual low-tech website, I can't help but offer a helping hand. I've got a few ideas on how you could make comments work in an computationally-efficient manner, and how you could further trim down on page weight too, so anyways, hit me up if you could do with an extra pair of hands on board.

##### Sylvain Couhault 

Hello,

I loved your low tech website and think you've done e real great job.

Since I've read the "Room for Improvements" section I've got some ideas to share with you that, I hope, will help you to go further:

-Images: Did you try the ".GIF" format ? You can use it for static picture limited to 256 colors. It is supported by most of internet browsers. https://en.wikipedia.org/wiki/GIF

-SSL ciphers: if there aren't any sensible or personnal datas on the website, maybe it's not needed to maintain HTTPS. The new General Data Protection Rules requires Ciphered content only if you use personnal datas. For full public datas, it's not mandatory I think.
Nevertheless it would need to be tested on different internet browsers because some of them are blocking sites or displaying security warnings when not in HTTPS (Google Chrome mainly). I think Google Chrome plans to block non HTTPS website in the longterm future but for the moment it works and other browsers will still allow it in the future. Maybe the best way is to test your site with HTTP (no S) with different browsers (Chrome, Opera, Firefox, Microsoft Edge, Brave ... ), see how it displays (warnings and so on ..) and to inform people about the browser they can use to watch your site and the warnings they could encounter.

-Energy sources: maybe you can combine the solar panel with a little wind turbine (thus you can still collect power even with bad weather. It's less efficient than solar panel, but in combination it could be useful to keep along a few hours or days without sun). I think this can be coupled with your battery system (with some other components to avoid interference between solar panel and wind turbine) Here are some examples:

https://www.youtube.com/watch?v=hBx3O55lTDw

https://www.youtube.com/watch?v=o2XEQZsXcIg

I hope these ideas will help you :)

Regards,

Sylvain

##### Adrien CLERC

Hi,

I read https://homebrewserver.club/low-tech-website-howto.html and I was
interested by your image compression techniques.

I would like to give you two ways of optimizing more aggressively.

Optimizing JPEG

==========

If you want to keep the same quality of the input image, here are my
best experience : use Guetzli (first) and MozJPEG (after Guetzli). The
first one (see https://github.com/google/guetzli/) is destructive, and
produce a different image, but with the exact same perceptual result for
our human eyes. The second (see https://github.com/mozilla/mozjpeg) is a
fork of JPEGTurbo with aggressive optimization without any change to the
final results.

So here are the two steps with your original image
(https://homebrewserver.club/images/international-switchboard.jpg):

- guetzli international-switchboard.jpg international-switchboard.g.jpg

- jpegtran -outfile international-switchboard.g.m.jpg
international-switchboard.g.jpg

I have the following resulting images:

156721 nov. 22 10:55 international-switchboard.g.jpg
135206 nov. 22 10:56 international-switchboard.g.m.jpg
163314 nov. 22 10:54 international-switchboard.jpg


Optimizing PNG

=========

If you have PNG (from ditherised images), you can use zopflipng. This
tool (see https://github.com/google/zopfli/) tries to find the best
combinations for a PNG, and achieves better result than optipng.

One step from your 11 color image
(https://homebrewserver.club/images/international-switchboard11.png):

- zopflipng -m international-switchboard11.png
international-switchboard11.z.png

I have the following resulting images:

111255 nov. 22 10:59 international-switchboard11.png
106772 nov. 22 10:58 international-switchboard11.z.png

Conclusion

======

With the original JPEG, I have a 17.3% improvement, using only JPEG.
This image is still 21.5% larger than your 11-color PNG.

With the 11-color PNG, I have a 4.1% improvement. This is not so much,
but still significant.


Note that guetzli needs a lot of memory and CPU. Other tool are more
lightweight.

Have a nice compression day,

Adrien

##### Erick Lavoie

I have read your magazine over the years and I have found tremendous 
value in your writings. I occasionally give workshops for kids in which 
I want to introduce principles of low-tech and alternative energies 
using Lego and custom parts, partly inspired by some of the ideas you 
have articulated so well.

I have just read "How to Build a Low-tech Website" and couldn't help 
wonder whether you have thought of using decentralized technologies to 
distribute your content. The main advantage is that your server does not 
need to be online all the time for content to be accessible, it can be 
distributed by your readers themselves. We could even imagine hosting 
availability following the day cycle around the Earth to reduce the need 
for energy storage, i.e. people could pull their content from places 
that are currently sunny.

Some friend of mine has started to build their own magazine with the 
Beaker Browser [1]. I have personally been using Secure-Scuttlebutt [2], 
which has a mobile application in the works [3], and I am currently 
actively participating in the community. Obviously most of your readers 
are currently not using either one of those so that is not a viable 
replacement to web hosting now. But I think they could still be part of 
a future analysis in an article and a potential progressive transition 
as more people adopt them. I also think you would fit right in with the 
ethos of the current SSB community, so I would be glad to get you 
on-board and introduce you to people if your are interested.

Cheers,

Erick

[1] https://beakerbrowser.com/

[2] https://www.scuttlebutt.nz/

[3] https://www.manyver.se/

##### Terry 

Hello Kris, Roel and Marie,

Very cool project for the WebServer.

I am even more interested how you run the office (light and what i guess is an good old IBM Thinkpad) on solar power. 
Are you charging the Battery of the Laptop or are you running it without battery direkt through solor / or batterythat is loaded through solar panel.

Could you share the experiance please? 
Or give the details on the "electric" hardware you use?
Thank you very much in advance.

I plan on doing similar and wonder what Solarpanel and PowerControler/Battery controler to use.

Best regards

Terry

##### Arne

The gatling webserver is especially resource efficient.

http://www.fefe.de/gatling/

It's author uses it for his own blog (blog.fefe.de), which has a wide 
readership but was hosted on very old hardware until recently.

##### Kris De Decker

**Several people have made dithering plug-ins inspired by the solar powered website:**

- <https://ditherit.com>
- <http://www.microplan.at/bilder-online-dithern-fuer-solar-webserver/?fbclid=IwAR0mKhYBGo-A5WAFos3Lg-JlZLc4F_yy7H_U7oW6N3W_nQRCXLifL_SZBbI>
- <https://merveilles.town/@joshavanier/101243030460823087> 

**Framasoft has translated this article to French:**

- <https://framablog.org/2019/01/24/pour-un-web-frugal/>

**More news articles about the solar powered server:**

- <https://walkerart.org/magazine/low-tech-magazine-kris-de-decker>
- <https://fontsinuse.com/uses/24504/low-tech-magazine-website>
- <https://eyeondesign.aiga.org/low-tech-magazines-solar-powered-website-is-rewriting-the-rules-of-web-design/>
- <https://www.lsnglobal.com/big-ideas/article/22970/kris-de-decker-on-web-design-s-energy-efficient-future>
- <http://catedratelefonica.uoc.edu/2018/10/10/low-tech-magazine-un-sitio-web-sostenible/?platform=hootsuite>
- <https://www.heise.de/make/meldung/Low-Tech-Webseite-geht-offline-wenn-die-Wolken-aufziehen-4183293.html?hg=1&hgi=3&hgf=false>
- <https://www.ticbeat.com/innovacion/esta-pagina-web-funciona-con-energia-solar-y-consume-menos-gracias-a-su-diseno/>
- <http://www.seabro.it/the-future-of-websites-how-one-site-has-gone-100-solar/>
- <https://www.rtl.fr/actu/futur/environnement-un-site-internet-fonctionne-a-l-energie-solaire-7795101025>

**Presentation at Bits und Baume in Berlin:**

- <https://media.ccc.de/v/bub2018-365-how_to_build_a_solar_powered_website>

##### Léo

Hi,

I find your solar website amazing!

Compressing a page is quite demanding for the CPU so your server may use even less power if you cache a compressed version of your pages.

Basically, you just need to tweak your nginx configuration and generate a .gz for each page, which is very easy to script. Then, for each request, nginx will use the .gz file and avoid recompressing the page. If the browser does not support compression, the .html file is served.

This blog post describe the all process https://www.carnaghan.. Here is the official documentation of the module http://nginx.org/en/docs/http/  which seems to be installed in every version of the debian nginx package.

Best regards,
Léo

##### Viga

I just stumbled upon your website, and I really love the idea.

However, I will agree with a lot of the comments about the battery indicator. It fails both on conveying the message (it is far from obvious what it represents) and at making a user-friendly website.
At first it got me to not even attempt reading past the introduiction. It is that annoying. I enentually came back because I al really interrested in the project, but was annoyed constantly during my reading.
It is also marked with a sun icon, wich doesn't map to "battery" in my mind, so the meaning of it may get lost. 

I understand that you want to convey the message that it isn't a standard website, and the dithered images do that pretty well (with the caveat of graphs and tables, as others noted), but the battery meter in its current state isn't the way to go.

Also, did you consider minifying the html/js source? Just stripping whitespace and comments from the javascript saves a bit more than 2kb per page load. You could go further than this by stripping whitespace, comments, and mangling variable names in the whole html/js. I do understand why you wouldn't want to do it, as it closes the code by obfucating it, but the CSS is already minified, so you may not consider this as an issue.

Also, as I read this articles and comments today (jan. 25th, 2019), I have no way when they were published, which is a context I really would like to have when writing this comment. I believe it would be a nice addition to the site.

Viga

##### Sebastian Furnigel

Hi,
Your project got our attention and we’re thinking about what would it take to make a similar project.

Therefore, I’m curious about
the solar cell used – we’re considering a 230w cell;
the raspberry model and what aspects were optimized on it;
and the battery pack used – which direction did you follow for battery metrics?

Your project is a real head-turner and it would be really interesting to have some insight into how yours was done.

Thank you and have a nice day,

Sebastian Furnigel

##### Kyle Norton

I absolutely love the solar-powered website. I love the design, I love the concept.. I want to try and build one of my own here in Austin, Texas.

If I can toss out a suggestion ... I love the battery level indicator, but I would also love to see an indicator of local time and if the site is operating on solar or battery power.

##### Jim Morgan

I've recently had problems with aggressive searchbots on some websites I run. Up to 80% of the bandwidth of the webserver was from bots! I imagine if you reduced or blocked bots on your site, you'd also see some energy savings. 

To combat this, you can create a 'map' in nginx, whereby you ban or rate-limit bots matching a certain regex pattern. 

eg. In the main nginx.conf
```
map $http_user_agent $limit_bots {
    ~*Baiduspider 'baidu';
    default '';
}

limit_req_zone $limit_bots zone=badbots:5m rate=10r/m;
```

Then in the actual website config in the server{} stanza

rate limit for poorly behaved bots
```
limit_req zone=badbots;
```
Monitor the error.log to see crawlers getting banned.

Jim Morgan

##### Aleksandar Milovac (Александар Миловац)

Hi,

Maybe this can help to get more accurate result of battery status, temp, etc...

https://github.com/KoljaWindel

Br,
Aleks

##### RC

I suspect 99% of power consumption for solar.lowtechmagazine.com is from regular kernel book keeping. From what I read, using less ticks per second for the HZ variable in Linux or enabling NO_HZ should reduce power even more. I’m not particularly knowledgeable in this, but I do admire the direction of your website as tech companies build websites only for people who buy the latest products, and for everyone to use the latest unmaintainable codebases.

As I read this, it looks like your five week uptime may finally fail.

##### Chris

Hello,

I've came across your website today and like your minimal attitude to web design pretty much. It is quite a contrast to the bloated webpages we are used to today (the performance improvement is even very noticable when using a quite fast connection - 1000mbps at work / 100mbps at home) and I think the web would be a lot more enjoyable if more pages were built like that.

I've read the article about the webserver configuration [1] and got a suggestion for a configuration change to the nginx configuration. As it wasn't listed there in the improvement list you might not be aware of this already. There is a configuration item called "gzip_static on" [2] which does tell nginx to simply deliver precompressed files from the webroot (so if requesting "index.html" it does send "index.html.gz")

Pre-Compressing the Webpages when updating the site and shipping these compressed versions should decrease cpu load and therefore energy consumption of the Server as the computation for the compression is only necessary one time when updating the page and not for every request. You might even use a higher compression level for this one-time task (though with gzip bumping the level from 6 to 9 doesn't improve the compression ratio a whole lot in my experience - at least with my usual datasets)

I've got no idea how much of a difference this does make - especially as there is quite a bit of processing necessary for the https encryption but it might be worth a try.

Kind regards,

Chris

[1] https://homebrewserver.club/low-tech-website-howto.html#software
[2] http://nginx.org/en/docs/http/ngx_http_gzip_static_module.html

##### kris de decker

French designer and researcher Gauthier Roussilhe was inspired by our solar powered website and built a low-tech website himself, documenting the process in detail (and in English). It’s a great work, and there’s some interesting differences with our solar powered blog.

- <http://gauthierroussilhe.com/en/posts/convert-low-tech>

First, Roussilhe built his site with a user friendly content management system (Kirby), which is then converted into a static website. Compared to our approach, this makes it easier to build a light-weight website for those who are accustomed to working with WordPress.

Second, the designer also tackles his videos, which are hosted on Vimeo and Youtube, and manages to reduce their “weight” by 75%. This is a major contribution, because video takes up the largest share of internet traffic.

Here’s his own conclusion:

If we take stock: I reduced the weight of my site by 10, the average weight of a page by more than 3 and I reduced the weight of my videos on third-party services by 4. I have a site extremely simple to administrate, very light so very fast, which consumes very little electricity and therefore emits little GHG.

The site also follows all the canons of today’s digital design: mobile-first, accessibility, loading speed. In fact it is quite surprising to realize that structural limitations (weight / energy) lead to navigation experiences much more accessible to all audiences regardless of their equipment, their connection or their imperative motricity or vision.

##### David Galeano

Hi,

I think your solar powered server project is very interesting and I may have a couple of suggestions.

I think you could improve performance when serving static files by using the open file cache: https://nginx.org/en/docs/http/ngx_http_core_module.html#open_file_cache

The size of PNG files depends heavily on the compressor used and the contents of the image. I found zopfli to be the best compressor: https://github.com/google/zopfli/blob/master/README.zopflipng
Also the PNG format is very good at compressing images with vertical patterns because each row can be stored as a delta of the previous one, not sure how that could help you but for example in the past I found that just by rotating the image 90 degrees it became a lot smaller.

Anyway, hope any of this helps.

Kind regards,
David

##### Matisse VerDuyn

The goal of this project is great!

A while ago, I put together https://github.com/matisseverduyn/aureum with a similar goal in mind. The concept stemmed from two objectives:
1.) The sole purpose of a website is to provide content, and to be useful, that content must be "comfortably readable" (on any device), and
2.) It's critical, for many reasons, to minimize data transfer (through the elimination of all non-essential HTML tags / attributes, and all CSS classes, especially those that are merely there to indicate visibility toggling).

Aureum helps to display "comfortably readable" information on all screen sizes (including both very large projector screens and very small displays, like smartwatches), and does so with only 3kb of minified CSS. I guess it could be considered a "reset file", but as I've actually used it on a few projects without adding much additional CSS, that classification might not convey its benefits with much justice.

It seems that "certain devices" which may not support features such as CSS media queries are a concern of your current design ("keep the blog accessible for visitors with older computers")? If not, I hope that Aureum is useful to your project. As another commenter Anja mentioned, having sites load quickly (or at all) under really low-bandwidth is both environmentally sensible and a pleasant relief (and quite a surprise to come across).

Thanks for what you've done here,

Matisse

##### sune Petersen

Hello Low Tech Magazine.

What are your thoughts on IPFS and DAT?

Have you thought about putting a mirror of your site up on these protocols?

##### Kris De Decker

We hitted hackernews again: https://news.ycombinator.com/item?id=19407847 

And just wanted to say: thanks so much for all the feedback, and keep it coming. We gave up the idea to try and answer every comment, instead we plan to write an update about the project discussing all the ideas mentioned here. This is especially relevant for the future redesign of the main site, which we plan to do in a different way. It is clear by now that the solar powered website will remain a separate website, as it has become so much more than simply a low-tech version of Low-tech Magazine.

##### Götz Hildebrandt

Dear de Decker,

reading about your low tech magazine, and the solar powered server.
is thier a plan to enable hosting on that server, or clustering with several servers world wide,
that works on the same way - low tech as yours?

For most web site no interpreting language is need, data access is neeed yes but that is all.
C++ as server side language is for common cases enough. (for mine it is)

what are your plans?

Greetings from Germany

##### Ruben

Hi!

Your article on your setup is great, but I was surprised that you don't precompress your pages, images, etc and serve it with nginx, using the option "gzip_static on".

It would be better on your CPU (you'd have to just compress once) and 
you could use the strongest compression possible. Would be good for 
speed as well, as nginx will be able to sent the page right away, 
without waiting for the slow arm CPU to compress it.

Just my two cents!

Cheers,

Ruben

##### Brian Sutherland

Hi, Kris:

Cool website, and one I may be discussing in my PhD thesis on DIY sustainable IT and electronics design.

I suggest that instead of batteries you use a graphene supercapacitor array.  Buy it once, it lasts for 10-20 years, and the system can recharge 1,000,000 times without wearing out.  No heavy or toxic metals, just carbon, plastic and aluminum.   Just be careful about insulating it properly if you stack it into 12 volts rather than 5 volts and use the appropriate cell balancing kit to ensure the capacitors charge evenly.

Also, if your site mirror was in a different time zone with the sun shining, it would never need to go offline, but it would still be 100% solar powered.   Fibre optics being light don't need much power to send information far.

+1 to 117) Ruben's suggestion to use the gzip standard for webpages to reduce the storage and data transfer.

I'm not certain I agree that static HTML pages make for a significant power saving compared to dynamically generated pages since the CPU still needs be running on the storage requests and it writes requests into a log file, that's not much different from a web page call.

Complements to your awesome city:  my spouse and I visited a few years ago.  We enjoyed the art and culture, especially the architecture, and I've been following Francisca Bria's digital citizenship work very closely.

##### Paul Geraghty

Hi,

I followed with interest the Olimex link to your pages (via twitter and @EENewsEurope)

Fine work, this board might be a solution for a problem I have too.

However, being an ex-LAMP dev kinda guy, with experience of caching I noted with interest you do not seem use a memcache.

Heres a link to more info:

https://blog.octo.com/en/http-caching-with-nginx-and-memcached/

I used to do similar on a .gov website for certain common webpages like home page etc.

But this was 10+ years ago using PHPs own memcache on Apache, so I cannot really help you much more.

In effect, this loads, for example, your html in MEMORY so you are not constantly pulling from your sd card. You just need to flush the ram every time you update your page, or it will do it when the SBC reboots, or you can set a time limit, I used to use hourly.

Sorry if my ignorance of SBCs is lacking, and what I am saying is not doable - eg more ram is a no-go, or even if the idea of ram does not translate to the SBC world.  Your the sample nginx config seems to show you are not using this.

Just thought I'd share that with you in case it leads to something positive.

Thanks again for the detailed write-up.

##### Shelby Marvell


I'm thinking of making my raspberry pi a super low-power server... Just wondering if you had done any more to improve it since this article: https://homebrewserver.club/low-tech-website-howto.html

And had a suggestion to maybe reduce image size. GIFs? They take dithering really well... But I know PNGs are compressed at varying strengths. And now I need to find a way to use a solar battery or something for powering it...

##### Kris De Decker

More media links:

https://news.ycombinator.com/item?id=20038619 (Third appearance on Hackernews, again very interesting feedback)

https://calls.ars.electronica.art/prix2019/prixwinner/32502/ [Honorary mention at the Ars Electronica 2019]

https://www.wired.co.uk/article/youtube-digital-waste-interaction-design

https://www.publico.pt/2019/05/05/tecnologia/noticia/revista-duvidas-tecnologia-1871255

https://www.cjr.org/innovations/low-tech-magazine.php

https://www.mcdbooks.com/electric_eel/issue-021

http://fing.org/agenda-futur-transitions2-defi13?lang=fr

https://www.lassembleuse.fr/lowtech/2018/11/15/low-tech-mag.html

##### Kris De Decker

@ Götz Hildebrandt

There are no plans to host other websites on our server.

##### Nicolai

Hello,

I love your site!  It's pushed me to make actual changes in my life.

Here are some small changes you can make to improve your https
configuration to maintain (or increase) security while also using less
electricity.

First, on the server itself, type these commands and compare the output:

openssl speed aes-128-gcm
openssl speed aes-256-gcm
openssl speed chacha20-poly1305

Since your server's CPU (ARM Cortex A7) doesn't support accelerated
AES, chacha20-poly1305 should be SIGNIFICANTLY faster (possibly 10x
faster) which means less electricity usage.  Similarly, aes-128-gcm
should be a bit faster than aes-256-gcm.  In the real world, in actual
TLS usage, aes-256 doesn't solve a problem that aes-128 doesn't.

So, you should configure nginx to support and prefer only these ciphers:

chacha20-poly1305
aes-128-gcm
aes-128-cbc

You don't even need aes-256.  For ECDH curves, you also don't need
secp521r1 or  secp384r1.  Even google.com, which is famous for not
wanting to lose any users, doesn't support these curves.  You should
just support x25519 and P-256 (aka  secp256r1).

Finally, making ECDSA signatures requires less power than making RSA
signatures.  So switching from an RSA cert to an ECDSA cert would
lower your electrical usage.

Hope this helps, and thanks again for your outstanding website!

##### Artūrs Pupausis

Intresting project for sure!

When speaking of server efficiency. Old 40nm SoC isn't the way to go. PNG could be optimized by PNGgauntlet or use webp but I guess it only supports 24bit colors. Brolti compression is more efficient than gzip. CSS, HTML & JS can be minifyed before compression. One commented about Flif but it isn't optimized and not natively supported in browsers.

Combining multiple websites on one server to uses hardware more effectively. SPF+ uses less power for given amount of data compared 100m nic. From a larger server waste heat can be recovered for water heating or room heating in winter. Waste heat can be recovered from waste water drain as well as that water can be reused for toilet. 10nm ARM server uses far less power for the same work compared even to latest Intel offers.

Even better if it is running on hybrid solar PV system with a small battery backup plus optimized PV system with minimal conversion of electricity.

Lastly reusing certain parts of servers like a case and hard drive Remanufacturing instead of shredding could help reduce emissions of the internet.

Speaking of printed version depending on the tech used on paper production, weight, shopping, power source, raw material, disposal & etc. Typical sheet of A4 paper uses ~50 watt hours of energy or more. While reading on modern smartphone for one hour takes Less than a watt hour, but it quickly changes if done on a laptop or older desktop with multiple monitors. But does not include cradle to grave impact of hardware and software used for it Also it would need to be divided by all other stuff used on computer.

##### Amos Blanton

I thought I'd share my solar powered website as it stands, along with
the offer of any help I can give should anyone run into problems I might
be able to help with.

http://solar.amosamos.net/
(https://gitlab.com/Lightnin/amosamos.net)

* It uses an ina219 to measure the state of the battery (Thanks Roel!)
* I'm experimenting with changing the background image depending on the
weather. I'm intrigued by the idea of physically situated servers tied
to their place in space.

I have yet to tackle the data optimization or server customization and
caching, and logging the power usage to look at trends / see if I can
cope with a Danish winter (unlikely at this point). And I am proxying to
my site on nearlyfreespeech.net <http://nearlyfreespeech.net> when the
pi is down. I'm rather attached to uptime at the moment as I am looking
for new opportunities in the realm of playful learning and sustainability.

Thanks for to you all for making this list / club, and for your
contributions to solar.lowtechmagazine.com
<http://solar.lowtechmagazine.com> and associated documentation - which
I found to be really inspiring. 

Best,
Amos

##### Petar Marinov

Hello,

I've been reading articles when you post on lowtechmagazine.com and I like how your photos look (and how little space they take). I've spent some time attempting to replicate the dithering effect of my own photos by I couldn't make it look like in lowtechmagazine.com.

Could you please share what is the command-line (imagemagic) which you use to produce your photos?

--pe
https://github.com/pmarinov

##### Roel Roscam Abbing

Hi Petar,

this is done via the dithering plugin, based on python Pillow I wrote:
https://github.com/lowtechmag/solar-plugins/tree/master/dither

greetings,

Roel

##### Stephen Henderson

You forgot to subtract, car trips to library, record store, theaters, not watching TV, delivering newspapers, producing paper. The internet is an extremely efficient, fast, decentralized way off transferring information compared to other methods. Therefore your premise of the Internet as a carbon problem is just not true, it's a large savings.

If there was simply a fair carbon tax on on everything producing carbon they would all use renewable energy. A server farm produces NO carbon using electricity from an utility. The utility produces carbon because they burn the fossil fuels to supply a server farm. ALWAYS, atack a problem at it's source.

A fair carbon tax is just so simple it makes you sick to think it's not implemented.

##### rockyIII

Hello,

Thanks for your very interesting website.

I´m reading “How to Build a Low-tech Website?“ with lots of attention.

I also have read on several other places (e.g. https://developer-blog.net/raspberry-pi-mit-sonnenenergie-betreiben-teil-4/) that the needed emeryfor a singelborad computerdoes not so much depend on the use of given capacity… so even so astatic web page is faster and needs less energy we could still consider to build also dynamic pages…

That said – I really like the design of https://solar.lowtechmagazine.com/ but it limits us by using some interesting functions if we think of interactin websites, which is a feature that becomes more and more important.

You seem to have no problem to use Facebook and twitter - but this use is a contradiction to your project I want to to address here.

Have you heard of the “Fediverse”?

https://en.wikipedia.org/wiki/Fediverse

and the decentralized networking options? This is a very interesting option which would be interesting to integrated in the Low-tech website project too.

Here I want to recommend the project Hubzilla.

https://hubzilla.org

You can run it in a PHP environment.

Hubzilla has a function called „normadic identity“. With this function you can clone and transfer network accessibility from one to an other server. If one server is down, the other server takes over the job and can do the work. So this concept would allow downtime for a solar driven websites even so functionality of connections would still be working. You jut have to find few partners - self hosted severs, spread all over the world, each powered by solar power, to have a 100% up time. This would be an other innovative concept for a low tech website ;-)

What do you think?

all the best

chris

##### Tom Sparks

For static comments, you could look at https://mademistakes.com/articles/jekyll-static-comments/ it is jekyll centric but you should be to adapt it to use with Pelican.

##### stilbruch

Greetings,

First off, I just want to say how much I absolutely love the lowtechmagazine website. I'm a member of tilde.town, and me and some other members were talking about the site today. We all enjoy the special attention that is paid to design and sustainability. However, the one thing that many of us find slightly annoying about using the site is the presence of the yellow line through the articles indicating the battery of the site. The site would be much easier to read in my opinion, if simply the battery level, or perhaps a bar indicating the level, were presented on the page. Thanks so much for putting out this amazing content!

Hayden

</div>
