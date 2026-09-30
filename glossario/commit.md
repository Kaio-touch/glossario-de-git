---
title: commit
---

# commit

Um commit é um objeto que guarda o estado inteiro do projeto num instante,
junto com o autor, a data, uma mensagem e o identificador do commit anterior
— o seu *parent*.

É o parent que transforma os commits numa história: cada um aponta para o
que veio antes, e é por isso que `git log` consegue caminhar para trás.

Um commit nunca muda depois de criado. Corrigir um commit é, na verdade,
criar outro.
