# Características do GIT

- Utiliza SHA1 para criptografar algoritmos de forma _única_

#### Objetos internos do GIT

- **Blob:** bolhas que armazenam o conteúdo.
- **Tree:** árvores que armazenam os _blobs_ e guardam o ome do arquivo (apontam para um blob ou para outra árvore)
- **Commit:** Junta tudo
  - Mostra autor, árvore, hora de edição, etc.
  - Permite montar uma linha de tempo na alteração dos códigos.