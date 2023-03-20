# crud-20230320

## Comandos GitHub

- `git init`
  - Cria a pasta `.git` e inicializa o repositório
- `git add` (Stage Changes)
  - Adiciona alterações dos arquivos em uma caixinha (Staged Changes)
  - Usando o `git add .`, adicionamos TODOs os arquivos alterados na caixinha
- `git commit -m "MENSAGEM DO COMMIT"`
  - Sela a caixinha de alterações e da um NOME pra esse conjunto de alterações
    - A mensagem do commit é esse nome
- `git status`
  - Nos mostra quais códigos/arquivos estamos guardando para mandar pro GitHub
- `git remote add origin git@github.com:omariosouto/crud-20230320.git`
  - Sincroniza nosso projeto LOCAL com o REMOTO no GitHub
- `git push -u origin main`
  - origin: Pra onde vai (no caso ORIGIN é o GitHub adicionado no REMOTE)
  - main: Ramificação/Branch que queremos atualizar
- `git pull`
  - O git pull, pega as alterações que estão no GITHUB e traz para o seu projeto localmente
- `git checkout -b nome-da-branch`
  - Cria uma nova branch e já muda para ela
- `git checkout nome-da-branch`
  - Muda para uma branch existente
- `git merge nome-da-branch`
  - Mescla a branch atual com a branch que você passou como parâmetro

### E se eu comecei tudo pelo GitHub?
- `git clone https://github.com/omariosouto/dicas-github-20230320.git`
  - Devemos usar o comando GitClone apontando para o repositório novo

## Qualidade
- Linter
  - [ESLINT](https://eslint.org/docs/latest/use/getting-started)
    - [Padrão Airbnb](https://github.com/airbnb/javascript)
 

## Referências

- [Melhorando o README do Projeto](https://www.youtube.com/watch?v=yMRSDdifGW8)
- [Link do DISCORD](https://mariosouto.com/discord/)
- [Como ver a árvore de commits?](https://github.com/omariosouto/crud-20230320/network)
  - Dica do **@BdSCunha**!
- [Dicas para ver o Git no mundo real](https://www.youtube.com/playlist?list=PLh2Y_pKOa4Uf-cUQOVNGlz_GVHx8QYoE6)

### Programas
- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en)
- [VSCode](https://code.visualstudio.com/)
