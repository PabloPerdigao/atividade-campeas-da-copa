# Campeãs da Copa

## 1. Proposta

Desenvolva do zero um site chamado **Campeãs da Copa**, dedicado às
seleções que mais vezes conquistaram a Copa do Mundo masculina.

O projeto será construído em etapas. A cada missão, você deverá
acrescentar conteúdo, criar novas páginas, melhorar o site ou resolver
uma situação que possa ocorrer durante o desenvolvimento de um projeto
em equipe.

Utilize HTML e CSS de acordo com o conhecimento adquirido. O site não precisa ter recursos avançados:
priorize uma estrutura organizada, informações corretas, links
funcionando e uma apresentação simples e consistente.

## 2. O que o site deverá conter?

### Página inicial

Uma página inicial chamada `index.html` que apresente as seleções
listadas abaixo. Cada seleção deverá aparecer em um container com:

-   Nome da seleção;
-   Imagem ou bandeira representativa;
-   Quantidade de títulos;
-   Anos em que foi campeã;
-   Breve descrição da trajetória;
-   Link para acessar a página de detalhes.
  
![selecoes](/tabela-selecoes.png)
### Páginas de detalhes

Uma página individual para cada uma das sete seleções. Cada página
deverá apresentar:

-   Nome e imagem representativa da seleção;
-   Breve histórico;
-   Quantidade de títulos mundiais;
-   Informações sobre cada edição em que foi campeã;
-   Ano e país-sede de cada conquista;
-   Breve descrição da campanha vencedora;
-   Link para retornar à página inicial.

As páginas podem seguir uma estrutura semelhante, mas cada uma deverá
conter as informações específicas da seleção correspondente.

## 3. Organização inicial do projeto

O projeto deverá ser criado do zero. 

Organize os arquivos de maneira que
seja fácil localizar as páginas, os estilos, as imagens e a
documentação.

A estrutura final deverá contemplar:

-   `index.html` --- página inicial;
-   `pages/` --- páginas de detalhes das seleções;
-   `css/` --- arquivos de estilos;
-   `assets/img/` --- imagens utilizadas;
-   `README.md` --- apresentação e informações gerais do projeto;
-   `REGISTRO_APRENDIZAGEM.md` --- registro resumido das missões
    concluídas;

## 4. Desenvolvimento por missões

Cada missão representa uma etapa do projeto. Conclua os requisitos da
etapa, verifique o resultado e atualize o registro de aprendizagem antes
de avançar. Além disso, conecte projeto com Vercel para hospedar o site e disponibilizá-lo publicamente.

### Missão 1 | Preparar o projeto

**Objetivo:** criar a estrutura inicial e começar o histórico do
projeto.

Tarefas:

-   Crie uma pasta chamada `campeas-da-copa` e organize o ambiente de
    trabalho.
-   Inicialize um repositório Git local.
-   Crie o `README.md` com o nome do projeto e uma breve descrição.
-   Registre a primeira versão do projeto e confira o histórico criado.

---------------------------------------------
### Missão 2 | Publicar o projeto no GitHub

**Objetivo:** disponibilizar o projeto em um repositório remoto.

Tarefas:

-   Crie no GitHub um repositório vazio chamado `campeas-da-copa`.
-   Conecte o repositório local ao remoto.
-   Confira a configuração da conexão.
-   Publique o histórico inicial e confirme que os arquivos estão
    disponíveis no GitHub.
- Dê acesso aos instrutores adicionando os como colaborados do repositório criado.

Crie o repositório remoto sem gerar um README ou outros arquivos
automaticamente, para evitar divergências entre os históricos iniciais.

---------------------------------------------
### Missão 3 | Construir a página inicial

**Objetivo:** apresentar o projeto e as sete seleções campeãs.

Tarefas:

-   Crie uma branch chamada `feature/pagina-inicial`.
-   Desenvolva a página `index.html` com os cards de todas as seleções
    listadas nesta atividade.
-   Inclua as informações exigidas para cada cartão e um link para a
    respectiva página de detalhes.
-   Organize a apresentação com HTML e CSS simples.
-   Revise as alterações e registre o trabalho em commits com mensagens
    claras.
-   Publique a branch no GitHub e solicite a revisão de um instrutor por
    meio de um Pull Request.
-   Após a aprovação, integre as alterações à `main` e atualize sua
    cópia local.

---------------------------------------------
### Missão 4 | Criar as páginas de detalhes

**Objetivo:** desenvolver as páginas individuais e integrá-las ao site.

Crie **uma branch específica para cada seleção**, partindo da `main`
atualizada. Desenvolva e revise uma página por vez.

Utilize os seguintes nomes para as branches:

-   `feature/perfil-brasil`
-   `feature/perfil-alemanha`
-   `feature/perfil-italia`
-   `feature/perfil-argentina`
-   `feature/perfil-espanha`
-   `feature/perfil-franca`
-   `feature/perfil-uruguai`

Para cada seleção:

-   Crie e acesse a branch correspondente.
-   Desenvolva a página com o histórico e todas as campanhas vencedoras
    da seleção.
-   Inclua um link de retorno à página inicial.
-   Verifique o conteúdo, os links e a apresentação da página.
-   Registre as alterações em commits, publique a branch e solicite
    revisão por Pull Request.
-   Após a aprovação e integração, atualize a `main` local antes de
    começar a próxima seleção.
-   Exclua a branch de trabalho após a integração, quando ela não for
    mais necessária.

---------------------------------------------
### Missão 5 | Revisar arquivos e consultar o histórico

**Objetivo:** corrigir situações comuns sem perder trabalho importante.

Resolva as situações propostas pelo instrutor:

1.  Você preparou um arquivo para commit por engano. Retire-o da área de
    preparação sem descartar as alterações locais.
2.  Uma pasta temporária já rastreada não deve continuar sendo
    versionada. Faça com que o Git deixe de rastreá-la, mantendo os
    arquivos locais, e configure o `.gitignore` para evitar que volte a
    ser adicionada. Lembre-se de que isso não apaga a pasta dos commits
    antigos.
3.  O instrutor solicita que você descubra em qual commit uma página foi
    adicionada e consulte as alterações registradas naquele commit.

---------------------------------------------
### Missão 6 | Interromper e retomar uma tarefa

**Objetivo:** lidar com uma mudança de prioridade sem registrar um
commit incompleto.

Enquanto trabalha na página do Brasil, você recebe do instrutor uma
solicitação urgente de correção em outra parte do projeto.

Tarefas:

-   Faça alterações na página do Brasil, mas ainda não crie um commit
    para elas.
-   Confira o estado do repositório e guarde temporariamente o trabalho.
-   Mude para a `main` atualizada e crie uma branch para a correção
    urgente.
-   Realize a correção, registre-a em um commit e integre-a conforme
    orientação do instrutor.
-   Retorne à branch da página do Brasil e recupere as alterações
    guardadas.
-   Verifique se o trabalho foi recuperado corretamente e continue a
    implementação.

---------------------------------------------
### Missão 7 | Atualizar o trabalho com mudanças da equipe

**Objetivo:** incorporar alterações publicadas por outra pessoa.

Enquanto você trabalha em uma branch, o instrutor fará uma alteração e
publicará novos commits na `main` remota.

Tarefas:

-   Consulte o estado atual do repositório.
-   Busque as atualizações remotas sem integrá-las automaticamente.
-   Examine o que mudou e compare as diferenças.
-   Integre as alterações necessárias pelo procedimento combinado com o
    instrutor.
-   Verifique se o site continua funcionando e publique suas alterações
    quando estiverem prontas.
-   Em um exemplo orientado, pratique também a atualização com
    `git pull`.

---------------------------------------------
### Missão 8 | Resolver um conflito

**Objetivo:** resolver alterações incompatíveis feitas em branches
diferentes.

O instrutor preparará um cenário controlado em que duas branches alteram
a mesma região de um arquivo.

Tarefas:

-   Identifique o arquivo em conflito e examine os marcadores
    apresentados pelo Git.
-   Compare as alterações e defina com o instrutor qual deve ser o
    conteúdo final.
-   Resolva o conflito e remova os marcadores.
-   Marque o arquivo como resolvido e conclua a integração.
-   Verifique o resultado no arquivo, no estado do repositório e no
    histórico.

Se necessário, discuta com o instrutor quando seria apropriado cancelar
uma tentativa de merge.

---------------------------------------------
### Missão 9 | Corrigir ou desfazer alterações

**Objetivo:** escolher uma forma adequada de corrigir erros conforme o
estado do trabalho.

Resolva as duas situações, preparadas com orientação do instrutor:

1.  **Alteração local não commitada:** em um arquivo de teste ou em uma
    mudança descartável, descarte uma alteração do diretório de
    trabalho. Antes de agir, confirme o que será perdido.
2.  **Commit já publicado em uma branch compartilhada:** identifique um
    commit de teste e desfaça seus efeitos sem reescrever o histórico
    compartilhado.

---------------------------------------------
### Missão 10 | Revisar e finalizar o projeto

**Objetivo:** verificar o site completo e preparar a entrega final.

Tarefas:

-   Confirme que todas as páginas foram integradas à `main`.
-   Verifique os links, as imagens e as informações das campanhas
    vencedoras.
-   Revise a organização dos arquivos e o conteúdo do `README.md`.
-   Inclua no README a descrição do projeto, sua estrutura, as
    instruções para visualizar o site e as fontes consultadas.
-   Confira o estado do repositório, o histórico e a sincronização com o
    remoto.


**Conclusão:** o site está funcional, documentado e publicado no GitHub,
e você consegue explicar como organizou e integrou as alterações
realizadas.

## 5. Registro de aprendizagem

Ao concluir cada missão, atualize o arquivo `REGISTRO_APRENDIZAGEM.md`
no próprio repositório. O registro deverá ser breve e conter:

-   **Data e missão:** identifique a etapa concluída.
-   **Entrega:** resuma o que desenvolveu ou corrigiu.
-   **Aprendizado:** descreva o que compreendeu durante a atividade.
-   **Dificuldade ou dúvida pendente:** registre o que ainda precisa
    praticar.
-   **Evidência:** inclua o link do commit, branch ou Pull Request
    relacionado, quando aplicável.

Não é necessário registrar cada comando individualmente nem tirar prints
de todas as execuções. Utilize o histórico do GitHub como evidência do
trabalho; capturas de tela só serão necessárias se forem solicitadas
pelo instrutor para uma situação específica.

O objetivo do registro é acompanhar a evolução ao longo do projeto.

