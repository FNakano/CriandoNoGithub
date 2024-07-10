# CriandoNoGithub

## Objetivo

- Verificar o que pode ser feito para documentação de projetos através da interface web do Github (ié, sem instalar/usar o Git no desktop/notebook);
- Instruir um colaborador com menos familiaridade/afinidade com Tecnologia da Informação para que ele consiga atualizar a documentação de um projeto;
  
## Introdução

No Github (este site), projetos são conjuntos de arquivos. Estes podem ser arquivos texto, como este README, código-fonte de programas, imagens, ... Os arquivos podem ser visualizados através do navegador, sem instalar nenhum programa no computador ou add-on no navegador.

Github é um site que armazena projetos e programas de seus usuários. Dentro de um projeto pode haver vários repositórios (que também são conjuntos de arquivos). Frequentemente um projeto corresponde a um repositório.

Github tem funcionalidades como:

1. Permitir colaboração (várias pessoas atualizando vários arquivos ao mesmo tempo)
2. Manter versões (sim, mantém um histórico das atualizações e é possível *baixar* uma versão antiga)

Usar toda a funcionalidade do Github requer conhecimento sobre o site. Às vezes adquirir esse conhecimento requer conhecer outras ferramentas e outros elementos (como conceitos) da área de Tecnologia da Informação.

O objetivo da construção deste repositório é explorar e documentar o que pode ser feito no Github para permitir que um colaborador menos *informático* consiga atualizar a documentação de um projeto (ié textos e figuras ).

## Resultados

### Como inscrever-se no Github

A inscrição é gratuita, mediante preenchimento de cadastro. A partir do site github.com, clicar no botão *Sign up* e preencher o cadastro. Depois disso você tem acesso à página de controle da sua conta.

### Como criar um novo repositório e chamar colaboradores no Github

Na página de controle há abas: "Visão Geral", "Repositórios", "Projetos", "Pacotes" e "Estrelas". Selecionando a aba "Repositórios" aparece a lista de seus repositórios. No canto superior direito há o botão "Criar Novo". Clique nesse botão.

Caso esteja em dúvida sobre o botão a clicar, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-44-31.png ) pode ajudar.

Na nova página, preencha o nome do repositório e clique no botão "Criar Repositório", no final da página. 

Caso esteja em dúvida sobre como preencher a nova página, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-45-25.png) pode ajudar.

Caso queira ajuda para localizar o botão "Criar Repositório", a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-45-47.png) pode ajudar.

Após criar o repositório, o github cria uma página para configurar o repositório. Nela você pode, por exemplo, incluir colaboradores.

Caso queira ajuda para localizar onde convidar colaboradores, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-45-47.png) pode ajudar.

Clicando em convidar colaboradores abre-se um popup para você buscar ou incluir colaboradores. Os colaboradores receberão mensagens que podem aceitar (ou recusar) o convite.

Caso queira ver um exemplo do popup, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-52-49.png) pode ajudar.

### Como atualizar um arquivo da documentação (.md) com a interface web do Github

É habitual criar um README.md que contenha alguma informação sobre o repositório. O arquivo é criado clicando no link `README.md`. Isto abre, dentro do navegador, um editor de texto. Digite algum texto. Salve o texto (e mais algo) clicando no botão "Commit changes...". Commit é um pouco diferente de simplesmente salvar o arquivo. O site verifica se as mudanças que você fez no arquivo podem ser fundidas com as mudanças que seus colaboradores podem ter feito, cria uma nova versão do arquivo e permite colocar algum comentário sobre essa nova versão. Para tal, após clicar no botão, aparece um pop-up para preencher os dados.

Caso queira ver a janela do editor, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-54-32.png) pode ajudar.

Caso queira ver um exemplo do popup de commit, a [figura](./Captura%20de%20tela%20de%202024-07-03%2013-59-19.png) pode ajudar.

Caso queira modificar um arquivo já existente, selecione o arquivo que deseja editar, clique no ícone de lápis (no canto superior direito do texto), o texto passa a aparece na janela do editor. Modifique o que quiser e clique em "commit changes".

Caso queira criar um novo arquivo, na página que mostra o repositório, clique no botão "+" entre a caixa de pesquisa e o botão "Código" e selecione "criar novo arquivo". 

Caso queira ver onde está o botão "+", a [figura](./Captura%20de%20tela%20de%202024-07-03%2014-00-22.png) pode ajudar

#### Como enviar outros arquivos (por exemplo figuras e programas)

Para enviar arquivos de seu computador para o repositório, na página que mostra o repositório, clique no botão "+" entre a caixa de pesquisa e o botão "Código" e selecione "enviar arquivo". 

Caso queira ver onde está o botão "+", a [figura](./Captura%20de%20tela%20de%202024-07-03%2014-00-22.png) pode ajudar

A página para envio de arquivos é aberta. Você pode arrastar ou selecionar arquivos. Depois de adicionar todos os arquivos que quiser, clique no botão "Commit changes".

Caso queira ver a página para envio de arquivos, a [figura](./Captura%20de%20tela%20de%202024-07-10%2015-12-02.png) pode ajudar.

#### Como criar hyperlink para uma figura/arquivo

Supondo que a figura esteja na mesma pasta (diretório) em que o arquivo que você está editando está, digite no editor de texto \[texto \]\(caminho para figura\), por exemplo: \[figura\]\(./Captura%20de%20tela%20de%202024-07-10%2015-12-02.png\). Para saber o caminho para figura, em uma outra aba do navegador, entre no repositório e clique sobre a figura/arquivo que quer linkar, então copie o texto que está na barra de endereços dessa aba e cole na parte destinada ao caminho para a figura. Isto ajusta o caminho, substitui espaços em branco e caracteres acentuados para o link ser usado no texto.

#### Como mostrar uma figura

Crie um link para a figura e coloque um ponto de exclamação antes do "abre colchete". Por exemplo: \!\[\]\(./Captura%20de%20tela%20de%202024-07-03%2014-00-22.png\)

### Onde posso aprender mais sobre formatação de texto no github

Github formata texto baseado em uma linguagem chamada markdown. A variação de markdown que Github usa é documentada neste site: https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
