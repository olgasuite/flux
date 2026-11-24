# OLGA Flux

<!-- aviso-ia -->
> **Feito com IA.** O código deste repositório foi escrito pelo **Claude Code** (inteligência artificial da Anthropic), a partir das especificações, dos testes e da revisão do autor. Leia antes de usar, como faria com qualquer código.

Site publicado do **OLGA Flux**, sistema de gestão de festivais e mostras de cinema: curadoria e seleção de filmes, programação, cópias e HDs de envio, KDMs, vinhetas, legendagem, bilheteria e recepção de convidados.

O acesso é por login, e cada usuário vê só os eventos e módulos liberados para ele.

## O que há aqui

- `index.html`: o sistema inteiro (HTML + CSS + JavaScript, sem build), com os dados no Firebase (Firestore).
- `bandeiras/`: bandeiras dos países, mostradas ao lado dos títulos.
- `OLGA2.png`, `favicon.ico`: imagens do site.

Este repositório recebe só os arquivos publicados. As regras de acesso aos dados e as funções do servidor (leitura de CPL, conferência de KDM contra o certificado da sala) ficam no Firebase, fora daqui.
