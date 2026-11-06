---
title       : "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date        : {{ .Date }}
slug        : "{{ .File.ContentBaseName | urlize }}"

description : "Descrição curta do episódio (aparece em buscas)"
summary     : "Resumo curto do episódio (aparece na listagem)"
keywords    : ["SEO keyword 1", "SEO keyword 2", "SEO keyword 3"]
tags        : ["podcast"]
params:
  neso:
    cover:
      image: "capa.jpg"
      alt_text: "Descrição da imagem"
      caption: "Legenda opcional"
---

Texto de apresentação do episódio.



---
#### NOSSAS REDES:

[Instagram](https://www.instagram.com/_altplustab/) | [Youtube](https://www.youtube.com/channel/UC4gWdl0yO_qL0uCN1qx9qUw) | 
[Apple Podcasts](https://itunes.apple.com/us/podcast/alt-tab/id1342047659?mt=2) | [Spotify](https://open.spotify.com/show/6LfQuNtzCAzpmwowj2tPZV?si=hkmSDMfRRRCegxUTrcp6pg)

---
#### FICHA TÉCNICA
- **Criação e Pauta:** Felipe Souza,  Frederico Almeida, Guilherme Encarnação e Yuri Amorim.
- **Edição de som e Design:** Guilherme Encarnação
- **Edição de Vídeo:** Yuri Amorim