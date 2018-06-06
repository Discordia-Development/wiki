<!-- TITLE: Menções -->
<!-- SUBTITLE: Notifique usuários diretamente -->

Menções são um modo de notificar diretamente um usuário, múltiplos usuários ou cargos em mensagens. O seu propósito principal é chamar a atenção de alguém para um canal ou mostrar para alguém que você está falando especificamente com ele. Você pode mencionar usuários ou cargos usando `@nome`.

# Mencionando usuários
Ao mencionar um usuário diretamente, ele irá receber uma notificação e a mensagem estará destacada para ele. Não existe permissões para mencionar um usuário individualmente. Para mencionar um usuário no aplicativo ou no navegador você pode começar a escrever seu nome (depois do `@`) e selecioná-lo da lista de sugestões, ou clicar com o botão direito no usuário e selecionar "Mencionar". No aplicativo móvel você pode simplesmente tocar no nome ou na foto de um usuário e ele será mencionado na caixa de texto.

# Mencionando cargos
Ao mencionar um cargo, todo usuário que possuir acesso ao canal irá receber uma notificação e o canal estará destacado como se tivesse recebido uma menção direta. Para permitir que um cargo seja mencionado por qualquer pessoa, ative as menções para aquele cargo em Configurações do Servidor > Cargos > Permitir que qualquer um @mencione esse cargo. Muitos donos de servidores gostam de ativar isso por um breve período de tempo ao querer mencionar todos os usuários de um cargo e então desabilitar, para fazer um anúncio para um cargo específico, por exemplo.

# @everyone e @here
Usar `@everyone` e `@here` permite mencionar usuários com e sem cargos. A diferença entre os dois é que `@everyone` menciona usuários desconectados (offline) e `@here` menciona somente usuários disponíveis (online) e que não estejam ausentes no momento.

# Menções usando IDs
Você pode também mencionar diretamente um usuário ou um cargo através do seu ID. O aplicativo automaticamente substitui `@cargo` ou `@usuario#discrim` por `<@&ID>` e `<@ID>`, respectivamente. O motivo disso é que nomes de usuário mudam enquanto IDs não. O aplicativo não mostrar menções como o nome do usuário ou cargop ode ser obtido ao escapar a menção. Isto pode ser feito digitando `\@nome#discrim` ou `\@cargo` e irá mostrar o ID, mas ainda notificará o usuário. Mencionar usuários pelo ID é comumente usado por bots.