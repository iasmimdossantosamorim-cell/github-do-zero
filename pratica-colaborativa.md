# GUIA DE PRÁTICA COLABORATIVA



# COMMIT: COMO SALVAR E REGISTRAR ALTERAÇÕES?
Um **commit** funciona como um "ponto de salvamento" (checkpoint) no histórico do projeto. Para salvar e registrar as alterações, primeiro adicionam-se os ficheiros modificados com o comando `git add .` e, em seguida, executa-se o comando `git commit -m "Sua mensagem descritiva aqui"`. A mensagem deve explicar de forma clara o que foi alterado ou adicionado.

# HISTÓRICO: COMO VISUALIZAR MUDANÇAS REALIZADAS?
Para visualizar o histórico de alterações no terminal, utiliza-se o comando `git log`, que mostra a lista de todos os commits realizados, com o autor, a data e a mensagem. Diretamente na interface do GitHub, basta clicar no ícone de relógio (**Commits**) na página principal do repositório para ver todas as revisões e comparar as linhas de código modificadas.

# BRANCH: COMO CRIAR UMA RAMIFICAÇÃO DO PROJETO?
Uma **branch** (ramificação) permite criar uma linha de desenvolvimento independente para testar novas funcionalidades sem alterar o código principal. Para criar e alternar para uma nova branch pelo terminal, utiliza-se o comando `git checkout -b nome-da-branch`. No GitHub, é possível criar clicando no menu suspenso de branches e digitando o nome da nova ramificação.

# PULL REQUEST: COMO SOLICITAR A REVISÃO DE UMA ALTERAÇÃO?
Um **Pull Request (PR)** é uma solicitação feita no GitHub para integrar as alterações de uma branch para a branch principal (`main`). Para abri-lo, aceda ao repositório no GitHub, clique em **Pull requests**, depois em **New pull request**, selecione a branch com as suas alterações e clique em **Create pull request** para que a equipa possa rever o código antes de o aprovar



# MERGE: COMO JUNTAR ALTERAÇÕES AO PROJETO PRINCIPAL?
O **Merge** é o processo de unir as alterações de uma branch secundária à branch principal. Após a revisão e aprovação do Pull Request no GitHub, basta clicar no botão verde **Merge pull request** e confirmar. Pelo terminal, o processo é feito alternando para a branch principal (`git checkout main`) e executando `git merge nome-da-branch`.
