# 📘 GIT & GITHUB DO ZERO
### Cartilha prática para iniciantes

**Curso:** Análise e Desenvolvimento de Sistemas (ADS)  
**Projeto:** Cartilha Digital Educativa  
**Plataforma:** GitHub  
**Público-alvo:** Pessoas sem conhecimento prévio em Git e GitHub

---

# 👋 Boas-vindas!

Você já imaginou trabalhar em um projeto com várias pessoas, sem perder arquivos ou precisar criar documentos chamados `projeto_final`, `projeto_final2` e `projeto_final_agora_vai`?

É justamente nesse cenário que ferramentas como Git e GitHub se tornam importantes.

Nesta cartilha, você aprenderá os principais conceitos de controle de versões e colaboração, desde a criação de um repositório até a integração de alterações realizadas por diferentes pessoas.

**O melhor:** todas as atividades práticas serão realizadas pelo navegador, sem necessidade de instalar programas.

## 📑 Sumário

1. O que é Git?
2. O que é GitHub?
3. O que é um repositório?
4. O que é README?
5. O que é Markdown?
6. O que é commit?
7. O que é branch?
8. O que é pull request?
9. O que é merge?
10. Atividade prática
11. Glossário
12. Referências

---

# 1. O que é Git?

O **Git** é um sistema de controle de versões distribuído, criado por Linus Torvalds em 2005.

Sua principal função é acompanhar as modificações realizadas nos arquivos de um projeto ao longo do tempo.

Imagine que você está desenvolvendo um site e decide modificar seu código. Depois de algumas alterações, percebe que a versão anterior funcionava melhor.

Com o Git, é possível consultar o histórico de alterações e recuperar versões anteriores dos arquivos.

### Para que serve o Git?

- Registrar alterações realizadas em arquivos.
- Consultar versões anteriores de um projeto.
- Identificar modificações feitas ao longo do tempo.
- Desenvolver funcionalidades em linhas de trabalho separadas.
- Facilitar a colaboração entre desenvolvedores.

### 💡 Exemplo prático

Imagine que três estudantes estão desenvolvendo um site.

Ana modifica o HTML, Pedro trabalha no CSS e Maria corrige informações do conteúdo.

Com o Git, é possível registrar essas alterações e acompanhar a evolução do projeto.

**Importante:** o Git é a ferramenta de controle de versões. Ele pode funcionar localmente, sem depender do GitHub.

---

# 2. O que é GitHub?

O **GitHub** é uma plataforma on-line que permite hospedar repositórios Git e colaborar em projetos.

Por meio dele, desenvolvedores e estudantes podem armazenar arquivos, compartilhar códigos, acompanhar modificações e trabalhar em equipe.

O GitHub também oferece ferramentas para organizar tarefas, revisar alterações e documentar projetos.

### Diferença entre Git e GitHub

| Git | GitHub |
|---|---|
| Sistema de controle de versões | Plataforma de hospedagem e colaboração |
| Registra o histórico de alterações | Permite compartilhar repositórios |
| Pode funcionar sem internet | Seus recursos on-line dependem de conexão |
| Pode ser utilizado sem GitHub | Utiliza Git como base para o versionamento |

### Como criar uma conta no GitHub?

1. Acesse https://github.com.
2. Clique em **Sign up**.
3. Informe seu endereço de e-mail.
4. Siga as instruções para configurar sua conta.
5. Confirme seu e-mail, caso solicitado.
6. Faça login na plataforma.

Após o cadastro, você poderá criar seus primeiros repositórios.

**📸 Imagem sugerida:** tela inicial do GitHub e página de cadastro.

---

# 3. O que é um repositório?

Um **repositório**, também chamado de *repository* ou *repo*, é o local onde ficam armazenados os arquivos de um projeto e seu histórico de versões.

Ele pode conter códigos, documentos, imagens, arquivos de configuração e outros materiais.

### Tipos de repositório

**Público (Public):** qualquer pessoa pode visualizar o conteúdo, mas isso não significa que qualquer pessoa possa modificá-lo diretamente.

**Privado (Private):** o acesso é restrito às pessoas autorizadas.

### Como criar um repositório?

1. Faça login no GitHub.
2. Clique no símbolo **+**, na parte superior da página.
3. Selecione **New repository**.
4. Escolha um nome para o projeto.
5. Adicione uma descrição.
6. Selecione **Public** ou **Private**.
7. Marque **Add a README file**, se desejar criar o arquivo inicial.
8. Clique em **Create repository**.

### Exemplo

**Nome:** `Cartilha-GITHUB`

**Descrição:** Material educativo para ensinar os conceitos e funcionalidades do GitHub a iniciantes.

**Visibilidade:** Public

### Como adicionar arquivos?

1. Abra o repositório.
2. Clique em **Add file**.
3. Selecione **Upload files** para enviar um arquivo do computador.
4. Escolha o arquivo desejado.
5. Escreva uma mensagem descrevendo a alteração.
6. Clique em **Commit changes**.

Para criar um arquivo diretamente na plataforma, utilize **Add file → Create new file**.

Em um repositório vazio, o GitHub pode apresentar o link **creating a new file** no lugar do botão Add file.

**📸 Imagem sugerida:** tela de criação de repositório e botão Add file.

---

# 4. O que é README?

O **README** é um arquivo utilizado para apresentar e documentar um projeto.

Normalmente, seu nome é `README.md`.

Ele costuma aparecer automaticamente na página principal do repositório quando está localizado em um local reconhecido pelo GitHub, como a raiz do projeto.

### O que colocar em um README?

- Nome do projeto.
- Descrição e objetivos.
- Instruções de utilização.
- Tecnologias utilizadas.
- Informações sobre os integrantes.
- Orientações para contribuir.

### Como criar um README?

1. Abra seu repositório.
2. Clique em **Add file → Create new file**.
3. Digite `README.md` como nome.
4. Escreva uma apresentação do projeto.
5. Clique em **Commit changes**.

### Exemplo de README

```md
# Meu Primeiro Projeto

Este projeto foi criado para aprender GitHub.

## Objetivo

Praticar a criação de arquivos e commits.

## Autores

Grupo de estudantes de ADS.
```

O GitHub exibirá os títulos e demais elementos com a formatação correspondente.

**📸 Imagem sugerida:** exemplo de README exibido na página de um repositório.

---

# 5. O que é Markdown?

O **Markdown** é uma linguagem de marcação leve, utilizada para formatar textos de maneira simples.

É muito utilizada no GitHub para escrever arquivos README, documentações e cartilhas.

Arquivos Markdown normalmente possuem a extensão `.md`.

### Principais comandos

| Sintaxe | Resultado |
|---|---|
| `# Título` | Título principal |
| `## Subtítulo` | Título secundário |
| `**texto**` | Texto em negrito |
| `*texto*` | Texto em itálico |
| `- Item` | Item de lista |
| `[Site](https://github.com)` | Link |
| `![Imagem](imagem.png)` | Imagem |

### Como criar um arquivo Markdown?

1. Entre no repositório.
2. Clique em **Add file → Create new file**.
3. Digite `exemplo.md`.
4. Insira o conteúdo:

```md
# Aprendendo Markdown

## Minha primeira lista

- Git
- GitHub
- Markdown

**Este texto está em negrito.**

*Este texto está em itálico.*
```

5. Clique em **Preview**, quando disponível, para visualizar a formatação.
6. Clique em **Commit changes** para salvar.

### 💡 Você sabia?

Esta própria cartilha pode ser publicada como um arquivo Markdown chamado `cartilha.md`.

Isso permite que o GitHub exiba títulos, listas, tabelas e links diretamente no navegador.

---

# 6. O que é commit?

Um **commit** é um registro de alterações realizado no histórico de um projeto.

Ele permite identificar o que foi modificado, quem realizou o registro e quando ele aconteceu.

Cada commit possui um identificador próprio, conhecido como *hash*.

### Exemplo

Imagine que você criou um arquivo chamado `index.html`.

Depois, adicionou um título à página.

Você pode registrar essa alteração com a mensagem:

`Adiciona título à página inicial`

Essa mensagem ajuda outros integrantes a compreenderem o que mudou.

### Como fazer um commit pelo GitHub?

1. Abra um arquivo do repositório.
2. Clique no ícone de lápis para editar.
3. Faça uma alteração.
4. Clique em **Commit changes**.
5. Escreva uma mensagem explicando a mudança.
6. Escolha se deseja registrar a alteração na branch atual ou criar outra branch, quando essa opção estiver disponível.
7. Confirme em **Commit changes**.

### Boas práticas

Prefira mensagens claras e objetivas.

**Bom exemplo:** `Corrige erros de português no capítulo 2`

**Exemplo pouco informativo:** `Mudanças`

### Como consultar o histórico?

Na página de arquivos do repositório, clique no link de histórico de commits, geralmente identificado por um número de commits ou pela opção **Commits**.

Você poderá visualizar os registros realizados e acessar os detalhes de cada alteração.

**📸 Imagem sugerida:** janela Commit changes e página de histórico de commits.

---

# 7. O que é branch?

Uma **branch** é uma linha de desenvolvimento de um projeto.

Ela permite realizar alterações de maneira separada, sem modificar imediatamente a versão principal.

A branch principal normalmente recebe o nome `main`.

### Exemplo

Imagine que seu grupo está criando uma cartilha.

A versão principal está na branch `main`.

Um integrante deseja adicionar um capítulo sobre Markdown.

Em vez de modificar diretamente a versão principal, ele pode criar uma branch chamada:

`capitulo-markdown`

Assim, poderá trabalhar nesse conteúdo separadamente.

### Como criar uma branch?

1. Abra seu repositório.
2. Na aba **Code**, localize o seletor de branches, normalmente exibindo `main`.
3. Clique nesse seletor.
4. Digite o nome da nova branch.
5. Selecione a opção para criar a branch a partir de `main`.
6. Confirme a criação.

### Como trabalhar na branch?

1. Selecione a branch criada.
2. Abra o arquivo que deseja modificar.
3. Clique no lápis para editar.
4. Realize suas alterações.
5. Registre as mudanças com um commit.

As alterações ficarão nessa branch até serem integradas à principal.

**📸 Imagem sugerida:** menu de seleção e criação de branches.

---

# 8. O que é pull request?

Um **pull request**, frequentemente abreviado como **PR**, é uma solicitação para integrar alterações de uma branch a outra.

Ele permite que os integrantes visualizem, discutam e revisem as mudanças antes da integração.

### Exemplo

Pedro criou uma branch chamada `capitulo-markdown` e concluiu o conteúdo.

Agora, ele deseja adicionar esse capítulo à versão principal da cartilha.

Para isso, pode abrir um pull request.

Os outros integrantes poderão verificar o conteúdo e sugerir correções antes da integração.

### Como criar um pull request?

1. Envie ou registre suas alterações na branch criada.
2. Acesse a aba **Pull requests**.
3. Clique em **New pull request**.
4. Em **base**, selecione a branch que receberá as alterações, como `main`.
5. Em **compare**, selecione a branch com suas modificações.
6. Verifique as diferenças apresentadas.
7. Clique em **Create pull request**.
8. Adicione um título e uma descrição.
9. Confirme em **Create pull request**.

### Exemplo de título

`Adiciona capítulo sobre Markdown`

### Exemplo de descrição

`Este pull request adiciona explicações sobre Markdown, exemplos de formatação e instruções práticas para iniciantes.`

### Por que utilizar pull requests?

- Facilitar a revisão de alterações.
- Permitir comentários e sugestões.
- Melhorar a colaboração.
- Organizar a integração de novas funcionalidades.
- Reduzir a possibilidade de alterações incorretas na versão principal.

**📸 Imagem sugerida:** tela de criação de pull request.

---

# 9. O que é merge?

O **merge** é o processo de integrar alterações de uma branch em outra.

Geralmente, ele é realizado depois que um pull request foi revisado e aprovado, quando a aprovação é exigida ou adotada pela equipe.

### Exemplo

A branch `capitulo-markdown` contém um capítulo finalizado.

Depois da revisão, o grupo decide integrar esse conteúdo à branch `main`.

Ao realizar o merge, as alterações passam a fazer parte da versão principal do projeto.

### Como fazer merge pelo GitHub?

1. Abra a aba **Pull requests**.
2. Selecione o pull request desejado.
3. Confira as alterações.
4. Verifique se existem conflitos ou restrições.
5. Clique em **Merge pull request**, caso essa opção esteja disponível.
6. Confirme em **Confirm merge**.

Após a integração, o GitHub poderá oferecer a opção **Delete branch** para excluir a branch de trabalho, caso ela não seja mais necessária.

### O que são conflitos de merge?

Um conflito pode acontecer quando duas branches apresentam alterações incompatíveis em um mesmo trecho de arquivo e o Git não consegue decidir automaticamente qual conteúdo manter.

Nesse caso, será necessário analisar as diferenças, escolher ou combinar o conteúdo correto e registrar a resolução.

**Importante:** o merge não é a mesma coisa que o pull request. O pull request propõe e permite revisar as alterações; o merge realiza a integração.

**📸 Imagem sugerida:** botão Merge pull request e confirmação da integração.

---

# 10. 🧪 Atividade prática — Nosso primeiro projeto colaborativo

Agora que você conhece os principais conceitos, chegou a hora de praticar!

### Objetivo

Criar um repositório, adicionar arquivos, registrar alterações e colaborar com outros integrantes utilizando o GitHub.

### Etapa 1 — Criar o repositório

1. Acesse o GitHub.
2. Crie um repositório público chamado `meu-primeiro-projeto`.
3. Adicione um README.
4. Descreva o objetivo do projeto.

### Etapa 2 — Criar um arquivo Markdown

1. Clique em **Add file → Create new file**.
2. Crie um arquivo chamado `apresentacao.md`.
3. Escreva seu nome e uma breve apresentação.
4. Registre a alteração com um commit.

### Etapa 3 — Criar uma branch

1. Abra o seletor de branches.
2. Crie uma branch chamada `minha-contribuicao`.
3. Selecione essa branch.
4. Edite o arquivo `apresentacao.md`.
5. Acrescente uma seção chamada **O que aprendi sobre GitHub**.
6. Faça um novo commit.

### Etapa 4 — Criar um pull request

1. Acesse **Pull requests**.
2. Clique em **New pull request**.
3. Compare `minha-contribuicao` com `main`.
4. Crie o pull request.
5. Revise as alterações apresentadas.

### Etapa 5 — Realizar o merge

1. Abra o pull request.
2. Confira as alterações.
3. Clique em **Merge pull request**, se estiver disponível.
4. Confirme a integração.
5. Volte à branch `main` e confira o conteúdo atualizado.

### Etapa 6 — Colaborar com um colega

1. No repositório, abra **Settings**.
2. Acesse **Collaborators**.
3. Clique em **Add people**.
4. Convide um colega pelo nome de usuário.
5. Aguarde a aceitação do convite.
6. Peça que ele crie uma branch e faça uma alteração.
7. Revisem juntos o pull request antes de realizar o merge.

### Resultado esperado

Ao finalizar a atividade, você terá praticado os principais recursos apresentados nesta cartilha.

---

# 11. 📖 Glossário

| Termo | Significado |
|---|---|
| Git | Sistema de controle de versões |
| GitHub | Plataforma de hospedagem e colaboração |
| Repository | Repositório que armazena arquivos e histórico |
| README | Arquivo de apresentação e documentação |
| Markdown | Linguagem simples de formatação de textos |
| Commit | Registro de alterações no histórico |
| Branch | Linha de desenvolvimento |
| Pull Request | Solicitação de integração de alterações |
| Merge | Integração de alterações entre branches |
| Main | Nome frequentemente utilizado para a branch principal |
| Collaborator | Pessoa autorizada a colaborar no repositório |

---

# 12. 🔗 Referências e materiais complementares

Para aprofundar os conhecimentos, recomendamos as seguintes fontes oficiais:

**Git — Site oficial**  
https://git-scm.com/

**GitHub — Documentação oficial**  
https://docs.github.com/pt

**GitHub — Introdução aos repositórios**  
https://docs.github.com/pt/repositories/creating-and-managing-repositories/quickstart-for-repositories

**GitHub — Introdução a pull requests**  
https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

**GitHub — Introdução ao Markdown**  
https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

---

# 🎓 Conclusão

O Git e o GitHub são ferramentas importantes para o desenvolvimento de software e para o trabalho colaborativo.

Ao longo desta cartilha, aprendemos como organizar arquivos, registrar versões, criar branches, propor alterações e integrá-las a um projeto.

Mais do que armazenar códigos, o GitHub permite que pessoas trabalhem juntas de maneira organizada, acompanhando a evolução de cada projeto.

**Agora é sua vez de praticar!**

Crie seu primeiro repositório, experimente os recursos apresentados e continue desenvolvendo seus conhecimentos.

---

**📘 GitHub do Zero — Aprender, praticar e colaborar.**

*Material educativo desenvolvido por estudantes do curso de Análise e Desenvolvimento de Sistemas.*
