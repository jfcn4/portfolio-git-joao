# Registro de Resolução de Conflito

**O que causou o conflito:**
O conflito ocorreu no arquivo `projeto/hello-world/app.js`. Ele foi gerado porque a branch `feat/rota-usuarios` e a branch `fix/bug-app` nasceram do mesmo ponto da linha do tempo, mas ambas alteraram exatamente a primeira linha do mesmo arquivo com códigos diferentes. Quando tentei mesclar a segunda branch, o Git pausou o processo pois não sabia qual das duas modificações deveria prevalecer.

**Como decidi qual versão manter:**
Decidi combinar as duas modificações, reescrevendo o código para incluir tanto o log da rota quanto o log da correção do bug.

**Comando usado para concluir:**
Utilizei `git add projeto/hello-world/app.js` para dizer ao Git que o conflito estava resolvido e, em seguida, rodei `git commit` para finalizar a mesclagem.
