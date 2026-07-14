---
title: O Retrato Invisível
description: A Equipe 14 apresenta uma rede neural que aprende a dirigir sozinha e um episódio de podcast sobre os dois lados dos dados — usá-los para cuidar das pessoas sem expor ninguém.
slug: equipe14-dados-e-privacidade
date: 2026-07-08 00:00:00+0000
image: cover.jpg
categories:
    - Post
tags:
    - Redes Neurais
    - Privacidade de Dados
weight: 1
---

## 👥 Equipe 14

**Autores:** [Edileudo Maciel](https://www.instagram.com/edileudo_maciel) (locução), [Gabriel Matias](https://www.instagram.com/gabrielm_almeida) (pesquisa e roteiro), [Juliano Alencar](https://www.instagram.com/julianomel0) (pesquisa e roteiro) e [Maria Elaine](https://www.instagram.com/elaineeen) (áudio e edição).

Principais temas e interesses abordados pela equipe:
 - Inteligência artificial e redes neurais
 - Ciência de dados e privacidade
 - Desenvolvimento de jogos e software
 - Divulgação da pesquisa em computação feita na UFC

## 🎮 Vídeo — Uma rede neural que aprende a dirigir

E se, em vez de programar cada regra, a gente deixasse o computador **aprender sozinho** a dirigir? É isso que este vídeo mostra na prática: a construção de uma rede neural que, por tentativa e erro, aprende a guiar um carrinho por uma pista em um jogo simples.

O projeto junta três peças que normalmente vivem em mundos separados. O jogo foi feito na engine **Godot**; a rede neural foi implementada **em C++**, sem depender de bibliotecas prontas de machine learning; e as duas partes conversam por meio da **godot-cpp** e do sistema **GDExtension** — o mecanismo oficial da Godot para carregar código C++ compilado como se fosse uma parte nativa da engine. O resultado é uma demonstração visual e intuitiva de como uma inteligência artificial "aprende" um comportamento do zero.

O projeto é da nossa colega **Maria Elaine**, e o código-fonte está aberto no GitHub: [elaineehc/Carrinho-Rede-Neural](https://github.com/elaineehc/Carrinho-Rede-Neural).

{{< youtube "d7A_xL53rSM" >}}

## 🎙️ Podcast — O Retrato Invisível

Todo dia, sem perceber, a gente deixa um rastro de dados: o cartão no ônibus, a mensagem no celular, a busca no mapa. Neste episódio do **CCCast** — nosso podcast de divulgação científica sobre as pesquisas da Universidade Federal do Ceará — o narrador **Edileudo Maciel** investiga uma pergunta incômoda: *dá para usar os dados das pessoas para cuidar delas sem expor ninguém?*

Em formato de monólogo (≈ 14 minutos), o episódio costura **dois lados da mesma moeda**, cada um baseado em uma pesquisa real feita aqui no Ceará:

- **O lado que age.** O sistema **CZRM**, desenvolvido no **Insight Data Science Lab (UFC)**, transforma respostas de questionários sobre renda, nutrição e moradia em um mapa de vulnerabilidade social, ajudando o poder público a decidir quem ajudar primeiro e com qual política. Artigo-base: FURTADO, Lara Sucupira; MOURA, Gustavo; VASCONCELOS, Daniel J. R.; FERNANDES, Guilherme Sales; CRUZ, Lívia Almada; MAGALHÃES, Regis Pires; COELHO DA SILVA, Ticiana L. *An analytical citizen relation management system (CZRM) for social vulnerability mapping and policy recommendation in Brazil.* Decision Support Systems, v. 172, 113995, 2023. [DOI: 10.1016/j.dss.2023.113995](https://doi.org/10.1016/j.dss.2023.113995)

- **O lado que protege.** Pesquisadores do **LSBD (UFC)** usam **privacidade diferencial** para publicar redes de relações (grafos) sem revelar quem está nelas — protegendo tanto o peso quanto a própria existência das conexões. Artigo-base: BRITO, Felipe T.; FARIAS, Victor A. E.; FLYNN, Cheryl; MAJUMDAR, Subhabrata; MACHADO, Javam C.; SRIVASTAVA, Divesh. *Global and Local Differentially Private Release of Count-Weighted Graphs.* Proceedings of the ACM on Management of Data, v. 1, n. 2, art. 154, 2023. [DOI: 10.1145/3589299](https://doi.org/10.1145/3589299)

A conclusão do episódio é simples e fica: **dado não é herói nem vilão — é ferramenta.** O que decide é o uso e o cuidado. E tem muita gente boa, aqui no Ceará, pensando exatamente nisso.

**Ficha técnica:** narração de Edileudo Maciel; pesquisa e roteiro de Gabriel Matias e Juliano Alencar; áudio e edição de Maria Elaine.

{{< audio "o-retrato-invisivel.mp3" >}}
