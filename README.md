# Segurança Wordpress

Passo a Passo de como melhorar a segurança do wordpress

## Mantenha seu WordPress atualizado

https://www.homehost.com.br/blog/wordpress/como-atualizar-o-wordpress-pelo-wp-admin/

    - Automatico
    
    O WordPress possui a função para ser atualizado automáticamente, sem intervenção do administrador. Esta configuração é recomendada, pois sempre que houver atualização de segurança, ela será feita de forma automática, deixando seu site sempre seguro.

    Para habilitar este tipo de atualização, edite o arquivo wp-config.php , que fica na raiz da pasta do seu WordPress, e adicione a ele a seguinte linha:

    define( 'WP_AUTO_UPDATE_CORE', true );
---

## Fuja de Login e Senhas comuns

https://www.hostinger.com.br/tutoriais/como-mudar-a-senha-do-wordpress-admin

    - Manualmente
    
    Faça login no painel administrativo do WordPress com suas credenciais existentes.
    No menu do painel, clique em "Usuários" e, em seguida, selecione o usuário cuja senha você deseja alterar.
    Na página do perfil do usuário, role a página até a seção "Nova senha" e clique no botão "Gerar senha".
    O WordPress irá gerar uma senha aleatória para você, que pode ser alterada posteriormente se desejar.
    Se você preferir criar sua própria senha, basta digitar uma nova senha forte na caixa "Nova senha" e confirmá-la na caixa "Confirmar senha".
    Clique no botão "Atualizar perfil" para salvar suas alterações
---

## Ativando 2 Steps Authentication

https://jamesrmoro.me/como-ativar-a-verificacao-em-duas-etapas-no-wordpress/#:~:text=No%20seu%20site%20WordPress%2C%20navegue,Ent%C3%A3o%2C%20clique%20em%20Ativar.

    - Plugin(Google Authenticator)
    
    Proucure o plugin Google Authenticator e, em seguida, clique em Instalar Agora.
    Então, clique em Ativar.
    Instale o Google Authenticator
    Após ter instalado o aplicativo do Google Authenticator no seu celular, clique no botão de adicionar.
    Irão aparecer 2 opções que você pode escolher para dar sequência ao processo. São elas:
    Ler um código de barras
    Digitar uma chave fornecida
    Escolha qualquer uma das opções acima. As informações você encontrará no seu próprio site WordPress.
    No seu site WordPress que você visualizará as informações de segurança e como deve ativar a verificação em duas etapas.
    No painel de controle do WordPress, navegue até “Usuários” e clique no usuário em que você quer definir a segurança em duas etapas.
    Role a janela para baixo e encontre a opção Configurações do Google Authenticator.
    Na janela de configurações do Google Authenticator, você encontra as opções abaixo.
    Faça o que é descrito para configurar o plugin corretamente.
    Ativar – Marque esta opção para ativar a função do plugin.
    Modo relaxado – Dá mais tempo para os usuários digitem os códigos de acesso ao blog. Marque esta opção apenas se achar que não conseguirá digitar o código de acesso em até 1 minuto.
    Descrição – É uma descrição que identifica como o seu site vai aparecer escrito no Google Authenticator. Simplesmente coloque o nome do seu site aqui.
    Secreto – É a chave que o aplicativo no seu celular vai precisar para gerar códigos de acesso ao seu site. Clique em Create New Secret para gerar os códigos e inseri-los no aplicativo. Ou, se preferir, escaneie o do código QR com a câmera do seu aparelho.
    Ativar senha do aplicativo – Ignore esta opção.
    Após definir as opções clique no botão azul Atualizar Perfil, ao final da página
---

## Faça backups com frequência

https://www.melhoreshospedagem.com/backup-wordpress/

    - Plugin(UpdraftPlus)
    
    Proucure o plugin UpdraftPlus e, em seguida, clique em Instalar Agora.
    Na menu lateral do WordPress > Backups do UpdraftPlus. Na nova tela que surgir, vá em configurações e agende os backups da maneira que achar ideal. Optamos por definir que novos backups sejam feitos semanalmente.
    Agora, é necessário escolher para onde vai o backup gerado pelo UpdraftPlus. Escolheremos o Google Drive, pelo fato de ser uma plataforma em nuvem utilizada por várias pessoas. Com isso, será solicitado meu login com a conta do Google.
    O Google confirmará se permitimos a vinculação da nossa conta com o UpdraftPlus e nos enviará de volta para tela do plugin. Dessa forma, basta salvar as configurações, ir para a aba "Backup / Restauração" e clicar no botão "Backup Agora".
---

## Use a Última Versão do PHP

    - Manualmente
    
    Somente feito pelo site da kinghost
---

## Use Sempre a Versão mais Recente Plugins

https://pt.blogpascher.com/encaixes-wordpress/Como-ativ%C3%A1-los-put-a-dia-autom%C3%A1ticas-plugins-para-wordpress

    - Automatica
    
   Selecione todos os plugins
   Va em ações em massa
   Selecione Ativar atualizações automáticas
   Clique em aplicar
---

## Use Sempre a Versão mais Recente Temas

    - Automatica(habilitando no menu)
    
   Faça login no painel de administração do WordPress.
    Clique em "Configurações" no menu à esquerda e selecione "Escrita".
    Role a página para baixo até a seção "Atualização automática".
    Marque a caixa ao lado de "Atualizar automaticamente apenas temas".
    Clique no botão "Salvar alterações" no final da página.
---
