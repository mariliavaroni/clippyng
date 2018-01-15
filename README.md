# Bem vindo ao Clippyng! :D


## Objetivo

Esta ferramenta foi criada para participar do concurso de encerramento do **[MOOC Introdução à Programação: Python para Jornalistas](https://journalismcourses.org/course/view.php?id=60)**. O objetivo é aplicar as habilidades aprendidas no curso para criar uma solução original para um problema jornalístico utilizando **Python**.

Esse foi meu primeiro curso de programação. Ao longo das aulas, aprendi que esta linguagem me permite automatizar processos de busca e raspagem de dados. Um dos tipos de busca que mais faço em meu trabalho na [**Mensagem Comunicação**](http://www.mensagemcomunicacao.com.br/) e que mais me toma tempo é a realização de clipagens online, o que me motivou a criar a **Clippyng**.

## Funcionamento
*Clipping* é um relatório gerado com notícias sobre determinado personagem ou assunto. Para jornalistas que trabalham com **assessoria de imprensa**, ele é fundamental para demonstrar resultados do trabalho que vem sendo desenvolvido. Para jornalistas que trabalham em **redação**, o *clipping* pode ajudar no monitoramento de um determinado assunto ou fonte relevante de interesse de cobertura.

Além de **otimizar o tempo** buscando em vários sites de uma só vez, a ferramenta **facilita as buscas** que seriam feitas manualmente em buscadores como Google, Bing ou Yahoo. Isso porque os resultados dos buscadores são influenciados pelo SEO (*Search Engine Optimization*), que organiza as informações por relevância de página. Assim, uma notícia que saiu em um veículo da grande mídia é priorizado em relação a portais segmentados, por exemplo, e links interessantes para o monitoramento acabam sendo jogados para as últimas páginas dos resultados. O uso é simples:

>- **Passo 1:** Digite a lista de sites nos quais a busca deverá ser feita, separados por ponto e vírgula.
>- **Passo 2:** Digite a palavra chave a ser buscada.
>- **Resultado:** Clippyng fará a busca e mostrará um resumo de quantos links foram pesquisados e em quais deles a palavra foi encontrada.
>- ***Importante:*** Para que a ferramenta funcione, é necessário ter instaladas as bibliotecas Requests e Beautiful Soup.

## Demonstração
Neste [vídeo](https://youtu.be/Fm04JxZPTpU), você pode acompanhar um teste de como **Clippyng** procurou pela palavra **unicamp** nos sites **[G1](http://g1.globo.com/)**, **[Folha de S. Paulo](https://www.folha.uol.com.br/)** e **[Correio Popular](http://correio.rac.com.br/)** e nos respectivos sub-sites de cada uma dessas páginas. Após realizar a busca, a palavra **unicamp** foi procurada em 1019 sites e encontrada em 8. Além dos links, o resultado mostra também o trecho do texto onde a palavra foi encontrada. 
