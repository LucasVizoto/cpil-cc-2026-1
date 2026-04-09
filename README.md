# Configurando um Codespace para este repositório

1. Abra o Visual Studio Code e selecione `Help > About` (ou `Arquivo > Sobre`) no menu da aplicação. Caso a **versão seja MENOR que 1.110**:
    * Acesse o [_site_ de _downloads_ do Visual Studio Code](https://code.visualstudio.com/download) e baixe a versão **User Installer x64**. Essa versão **NÃO** requer permissão de administrador para instalação.
    * Instale a versão baixada. **IMPORTANTE: FIXE a nova versão do Visual Studio Code na barra de tarefas**, assim você poderá acessar facilmente a versão atualizada do editor.
1. No Visual Studio Code, instale as seguintes extensões:
    * GitHub Codespaces
    * Remote Explorer
1. No navegador, faça _login_ no [GitHub](https://github.com).
1. Acesse [https://github.com/faustocintra/cpil-cc-2026-1](https://github.com/faustocintra/cpil-cc-2026-1).
1. Clique sobre o botão `[Fork]` no canto superior direito.
1. Na página seguinte ("Create new fork"), não altere nada, simplesmente clique sobre o botão `[Create fork]`. Aguarde.
1. Retorne ao Visual Studio Code e clique no ícone do Remote Explorer (barra vertical esquerda); será aberto um painel.
    * Na parte superior, caso haja uma caixa de seleção, escolha GitHub Codespaces. 
    * Em seguida, caso ainda não esteja autenticado(a) no GitHub, clique sobre `[Sign In to GitHub]` e siga as instruções na tela.
1. Voltando ao Visual Studio Code após ter feito _login_ no GitHub, haverá um novo botão, `[Create Codespace]` ou `+` quando se paira o cursor do _mouse_ sobre o título GITHUB CODESPACES. Clique sobre ele e vá respondendo às perguntas.
    * ao ser perguntado sobre o repositório para o qual deseja criar um novo Codespace, selecione o seu repositório _forkado_ da disciplina (`<SEU_USUARIO>/cpil-cc-2026-1`).
    * Branch: **main**
    * 2 cores, 8GB RAM, 32 GB storage
1. Aguarde o Codespace ser criado. Ao final, o Codespace relativo ao seu repositório _forkado_ será aberto no editor.
