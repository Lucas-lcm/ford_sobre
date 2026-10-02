# Projeto Ford Enter

Página institucional do programa Ford Enter, feita com HTML e CSS puros.
Este repositório é o ponto de partida do projeto da turma: você vai cloná-lo,
trabalhar nele durante as aulas e receber atualizações do instrutor.

## Estrutura dos arquivos

```
projeto-ford-enter/
├── index.html        → conteúdo e estrutura da página
├── css/
│   └── style.css     → estilos, comentados por tema
└── README.md         → este arquivo
```

## 1. Copiar o projeto para a sua máquina

Abra o terminal na pasta onde você guarda seus projetos e execute:

```bash
git clone https://github.com/lucas-lcm/projeto-ford-enter.git
cd projeto-ford-enter
```

O `git clone` baixa os arquivos **e todo o histórico de versões**. Confira:

```bash
git status
git log --oneline
```

## 2. Abrir a página

Abra a pasta no VS Code e clique com o botão direito em `index.html` →
**Open with Live Server**. Sem a extensão, basta dar dois cliques no arquivo
para abri-lo no navegador.

## 3. Receber as atualizações da aula

Durante a aula o instrutor vai publicar uma alteração no repositório. Para
trazê-la para a sua cópia local:

```bash
git pull origin main
```

Depois do `pull`, recarregue a página no navegador e veja o que mudou:

```bash
git log --oneline
```

O commit mais recente aparece no topo da lista.

## 4. Salvar o seu próprio trabalho

Antes de dar `git pull`, registre o que você já fez. Assim o Git sabe o que é
seu e o que veio de fora:

```bash
git add .
git commit -m "Descreve o que voce mudou"
```

## Perguntas frequentes

**`fatal: not a git repository`** — você não está dentro da pasta do projeto.
Use `cd projeto-ford-enter` e tente de novo.

**O `git pull` reclamou de alterações locais** — faça `git add .` e
`git commit` antes de puxar as novidades.

**Apareceu um conflito** — você e o instrutor mexeram nas mesmas linhas. Abra o
arquivo indicado: o Git marca as duas versões com `<<<<<<<`, `=======` e
`>>>>>>>`. Escolha o que fica, apague as marcações, salve e faça um novo
commit.

---

Material didático da turma de desenvolvimento web do programa Ford Enter.
