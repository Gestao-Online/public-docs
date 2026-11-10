# 🎲 Editando meus dados

Aqui é possível completar o cadastro na plataforma e acessar mais algumas informações, veja cada uma:

![](/erp-v2/assets/editando_meus_dados.gif)

Assim que entramos no menu de edição de usuário, está um pequeno menu na cor cinza ao lado direito da tela. Temos algumas funções neles:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/edit_dados_menu_superior.png)

## Guia Geral

Olhando para a guia **`Geral`**, por padrão, quando sua conta é criada é exigido o nome de usuário, e-mail e unidade. Então, essas informações você não precisa alterar, mas tem outros campos para preenchimento, são eles:

- **Nome** (Aqui é possível colocar o nome completo);
- **Nome usuário** (Este é nome/código/CPF usado para fazer login na plataforma);
- **Alterar senha** (Para mais informações, [clique aqui](/erp-v2/minhas_preferencias/alt_minha_senha.md));
- **Status** (Aqui define o status de usuário da plataforma, é um item alterado somente do administrador);
- **Perfil** (Aqui define que tipo de autorização você tem na plataforma, alterado somente por administrador);
- **Unidade** (Nome do local/setor de trabalho, é bloqueado, alterado somente pelo administrador);
- **E-mail** (Item obrigatório, você não pode modificar este e-mail, sua conta está vinculada exclusivamente a ele);
- **Telefone**;
- **Documento** (Pode colocar um documento seu de identificação, RG/CPF/CNH);
- **CEP** (Após inserir o CEP, os demais dados serão preenchidos automaticamente);

![](/erp-v2/assets/edit_dados_guia_geral.png)

### Campos de Status, perfil e unidade

Na parte de status, perfil e unidade, como usuário comum, você não consegue fazer alterações. Para cada um dos casos, uma mensagem específica de erro irá aparecer:

Estas opções permitem alterações somente pelo administrador 😉👍

![](/erp-v2/assets/edit_dados_bloqueados.gif)

## Guia Notificações

Agora, na guia **`Notificações`** há controle de todas as notificações geradas para o usuário na plataforma. Confira abaixo:

![](/erp-v2/assets/edit_dados_notificacao.png)

### Menu superior guia notificações

Aqui temos um pequeno menu no lado direito da tela com algumas funções, sendo elas:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar item. 

{% hint style="danger" %}
**Atenção:** A função **`Adicionar Item`** só está disponível para administradores, podendo somente ele criar notificações por esta opção. As demais notificações automáticas seguem normalmente.
{% endhint %}

![](/erp-v2/assets/edit_dados_notificacao_menu.png)

E você como usuário pode **`apagar`** as notificações recebidas (Não sendo possível recuperar depois) quanto a editar as notificações já recebidas, é uma função disponível somente para administradores. Veja o exemplo de uso abaixo: 

![](/erp-v2/assets/edit_menu_notificacao_apagar.gif)

## Guia Access Tokens

Agora, na guia **`Access Tokens`** é possível encontrar o relatório de tokens de acesso gerado ao usuário e o período de duração de cada um em cada sessão na plataforma, e estas informações não são permitidas modificações em nenhum dos níveis de acesso. Pois são gravadas no banco de dados para registro:

![](/erp-v2/assets/edit_dados_access_token.png)

## Guia Metadata

Na guia **`Metadata`** ficam os registros de perfil, modificação de foto de perfil, alteração de cor do tema, adição de itens nos favoritos ou até mesmo remoção. Todas as informações organizadas na plataforma ficarão salvas e registradas nessa guia, para quando fizer login tudo ficar do jeitinho que foi deixado! 😁

![](/erp-v2/assets/edit_dados_metadata.png)

## Guia Events

Na última guia ficaram os **`Events`** com tudo que o seu usuário fez, um pouco parecido com o Access Tokens, mas enquanto lá registra somente seu acesso, aqui no `events` ficará tudo o que você fizer, alteração, adição, pesquisa, visualização de algum item ou cliente, todas as informações registradas aqui.

E por se tratar de uma página com informações importantes, os dados não podem ser apagados ou alterados, confira a imagem abaixo:

![](/erp-v2/assets/edit_dados_events.png)