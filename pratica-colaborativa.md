# GUIA DE PRÁTICA COLABORATIVA

[Insira o conteúdo aqui]

# COMMIT: COMO SALVAR E REGISTRAR ALTERAÇÕES?[cite: 3]
O Commit no GitHub é uma funcionalidade utilizada para registar e guardar alterações feitas num projeto, permitindo acompanhar a evolução do código ao longo do tempo.

## 1. Qual é a funcionalidade do Commit?
O Commit funciona como um registo de uma alteração realizada num projeto. Sempre que um programador modifica, adiciona ou remove ficheiros, pode criar um commit para guardar essas alterações no histórico do projeto.

- Cada commit contém:

- Alterações: apresenta o que foi modificado no projeto.

- Mensagem: descreve resumidamente o que foi feito.

- Autor: identifica quem realizou a alteração.

- Data e hora: indica quando a alteração foi registada.

- Histórico: permite consultar as alterações anteriores.

## 2. Quais são os objetivos do Commit para a página?
Numa página web, os principais objetivos são:

- I. Guardar alterações: registar modificações feitas no HTML, CSS, JavaScript e outros ficheiros.

- II. Acompanhar a evolução: visualizar como a página foi desenvolvida ao longo do tempo.

- III. Organizar o desenvolvimento: separar as alterações por funcionalidades ou melhorias.

- IV. Facilitar a colaboração: permitir que vários programadores trabalhem no mesmo projeto.

- V. Recuperar versões anteriores: possibilitar o retorno a uma versão anterior caso ocorra algum erro.

- VI. Documentar o projeto: manter um histórico das melhorias e correções realizadas.

## 3. Exemplo prático
Imagine que está a desenvolver uma página de uma loja online:

| Commit: 1                      | Objetivo: 2                    |
| :---                           | :---                           |
| Criar estrutura da página      | Adicionar a estrutura HTML.    |
| Adicionar estilos CSS          | Melhorar o aspeto visual.      |
| Criar menu de navegação        | Adicionar menus e links.       |
| Adicionar imagens dos produtos | Apresentar os produtos.        |
| Corrigir erros da página       | Resolver problemas encontrados.|

## 2. Como é estrutura de codigo sobre o Commit?

### Como funciona o commit?
O processo normalmente tem 3 etapas:

#### 1. Fazer alterações

Você modifica arquivos do seu projeto, por exemplo:

- Altera um código.

- Cria um arquivo.

- Corrige um erro.

Remove alguma funcionalidade.

#### 2. Adicionar as alterações


bash
git add .
Esse comando prepara todas as alterações para serem registradas.

#### 3. Fazer o commit


[ bash: git commit -m "Descrição das alterações" ]
Exemplo:


{ bash: git commit -m "Corrige tela de login"]
Isso registra as alterações no histórico do Git.

### O que o commit faz?

- **Salva:** registra um ponto específico do projeto.

- **Registra:** guarda um histórico das alterações.

- **Identifica:** permite saber o que foi modificado e quando.

- **Organiza:** facilita acompanhar a evolução do projeto.

- **Permite recuperar:** ajuda a voltar a versões anteriores.

### Exemplo completo

[ bash ]
[ git status ]
[ git add . ]
[ git commit -m "Adiciona funcionalidade de cadastro"]
[ git log ]
**Importante:** o commit não envia as alterações para o GitHub. Para isso, você utiliza:

[ bash: git push ]
Resumindo:

| Comando: 1    | Função: 2              |
| :---          | :---                   |
| [ git add .]  | Prepara as alterações  |
| [ git commit ]| Registra as alterações |
| [ git push ]  | Envia para o GitHub    |
| [ git pull ]  | Baixa atualizações     |
| [ git status ]| Verifica alterações    |


# HISTÓRICO: COMO VISUALIZAR MUDANÇAS REALIZADAS?

Histórico de alterações – Como visualizar mudanças realizadas?
O histórico de alterações é um recurso do GitHub que permite acompanhar todas as modificações feitas em um projeto ao longo do tempo. Cada vez que um integrante registra uma alteração por meio de um commit, essa ação fica armazenada no histórico.

Com essa ferramenta, é possível identificar quem realizou cada modificação, quando ela aconteceu e quais arquivos foram alterados. Isso facilita a organização do projeto e permite acompanhar a participação de cada integrante.

Como visualizar o histórico no GitHub:
1. Acesse o repositório do projeto.
2. Entre na página principal, onde aparecem os arquivos.
3. Clique na opção Commits ou no histórico de commits.
4. Escolha uma alteração para visualizar seus detalhes.
5. Confira o autor, a data e as modificações realizadas.
Exemplo: se um integrante alterar uma informação da cartilha, o histórico permitirá consultar essa mudança e identificar quem foi o responsável.

# BRANCH: COMO CRIAR UMA RAMIFICAÇÃO DO PROJETO?

Branch – Como criar uma ramificação do projeto?
Branch, que significa ramificação, é um recurso do GitHub utilizado para criar uma versão separada do projeto principal. Ela permite que os integrantes desenvolvam melhorias, façam testes ou modifiquem arquivos sem alterar diretamente a versão principal.

Esse recurso é muito útil em trabalhos em equipe, pois cada pessoa pode trabalhar em uma parte do projeto com mais organização e segurança. Depois que as alterações forem revisadas, elas poderão ser incorporadas ao projeto principal por meio de um Merge.

Como criar uma Branch no GitHub:
1. Acesse o repositório do projeto.
2. Clique no botão que mostra o nome da ramificação atual, como main ou principal.
3. Digite um nome para a nova ramificação, por exemplo, melhoria-guia.
4. Selecione a opção para criar uma nova branch a partir da principal.
5. Depois de criada, selecione essa ramificação para começar a trabalhar nela.
Exemplo: imagine que um integrante queira melhorar a explicação sobre GitHub na cartilha. Ele pode criar uma branch chamada melhoria-guia, realizar as alterações nela e depois solicitar uma revisão antes de incorporar o conteúdo ao projeto principal.

# PULL REQUEST: COMO SOLICITAR A REVISÃO DE UMA ALTERAÇÃO?

O **Pull Request (PR)** é uma solicitação formal enviada à equipe para que as alterações feitas na sua cópia de trabalho (uma branch secundária) sejam analisadas e incorporadas ao projeto principal (main ou master).

*Analogia Prática:* Imagine um trabalho acadêmico em grupo. Você escreve o seu capítulo em uma folha separada e a entrega ao grupo dizendo: "Escrevi a minha parte, por favor leiam e vejam se posso anexar ao documento final".

### Passo a passo para criar um Pull Request1
* **1. Envie suas alterações para o GitHub (Push):**
Certifique-se de enviar seu código local antes de abrir o PR.
No seu terminal ou programa Git, envie a branch com as suas alterações para o repositório remoto:

    git push origin nome-da-sua-branch

* **2. Acesse o repositório no GitHub:**
Navegue até a página principal do projeto.
Abra o seu navegador e acesse a página do projeto no GitHub. Na página principal, você verá um aviso destacado em amarelo indicando que a sua branch recebeu alterações recentes.

* **3. Clique em 'Compare & pull request':**
Inicie o formulário da solicitação.
Clique no botão verde **"Compare & pull request".** Caso o banner não apareça, vá até a aba **"Pull requests"** e clique no botão **"New pull request".**

* **4. Selecione as branches corretas:**
Verifique a origem e o destino.
No topo da tela, confirme se a branch de destino (base) é a main e se a branch de origem **(compare)** é a sua branch de trabalho.

* **5. Preencha o título e a descrição:**
Forneça contexto para quem for revisar.
**Título:** Escreva um resumo direto do que foi feito (Ex.: Adiciona página de login).
**Descrição:** Explique o que mudou, os motivos da alteração e como testar.

* **6. Conclua a criação do Pull Request:**
Submeta para a análise da equipe.
Clique no botão verde **"Create pull request"** localizado no canto inferior direito do formulário.

# MERGE: COMO JUNTAR ALTERAÇÕES AO PROJETO PRINCIPAL?

O Merge (Mesclagem) é a ação técnica de unir o histórico de commits e as alterações de uma branch aprovada com a branch principal do projeto.

**Analogia Prática:** Após todos os integrantes do grupo lerem e aprovarem o capítulo que você escreveu na folha separada, vocês colam essa folha definitivamente na pasta do trabalho final.

### Passo a passo para realizar o Merge
* **1. Acesse o Pull Request aberto:**
Localize a solicitação que precisa ser integrada.
Acesse a aba *"Pull requests"* no repositório e clique no título do PR que deseja revisar e integrar.

* **2. Revise as alterações na aba 'Files changed':**
Garanta que o código está correto.
Clique na aba **"Files changed"** no topo da página do PR para visualizar as linhas de código adicionadas (em verde) e removidas (em vermelho). Se tudo estiver correto, retorne à aba **"Conversation".**

* **3. Verifique se não há conflitos:**
O GitHub faz a checagem automática de compatibilidade.
Confira a caixa de status no final da página. Se houver a mensagem verde "This branch has no conflicts with the base branch", o Merge pode ser feito com segurança.

* **4. Execute o Merge:**
Incorpore as alterações definitivamente.
Clique no botão verde **"Merge pull request"** e, em seguida, clique em "Confirm merge".

* **5. Exclua a branch de trabalho (Opcional, mas recomendado):**
Mantenha o repositório limpo.
Após a confirmação do Merge, clique no botão **"Delete branch"** para remover a branch secundária que já foi integrada.

