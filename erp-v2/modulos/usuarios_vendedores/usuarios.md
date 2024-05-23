# 👤 Usuários

Aqui você tem a visão de todos os usuários cadastrados na plataforma Gestão.Online, podendo fazer cadastro, enviar notificações e até excluir um usuário cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/modulo_usuario.gif)

<br>

Nesta guia está um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_notificacao.png" alt="" data-size="line"> Enviar notificações para usuários;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar usuário.

![](/erp-v2/assets/modulos/menu_guia_usuarios.png)

<br>

### Criar notificação

Ao clicar no primeiro item do menu vamos para o envio de notificação aos usuários, o preenchimento é bem simples e intuitivo.

![](/erp-v2/assets/modulos/menu_guia_usuarios_notificacao.png)

<br>

Você precisa definir primeiro nível de criticidade da notificação, das opções disponíveis têm:

- Mínimo;
- Baixo;
- Normal;
- Alto;
- Urgente.

![](/erp-v2/assets/modulos/menu_guia_usuarios_notificacao_criticidade.png)

<br>

Após a definição do nível, seguimos para o perfil de usuário que irá receber esta notificação que você está gerando, são os tipos:

- Todos;
- Usuário;
- Coordenador;
- Gerente;
- Administrador;
- Super administrador.


![](/erp-v2/assets/modulos/menu_guia_usuarios_notificacao_perfil.png)

<br>

Depois de definido o tipo de usuário, agora vamos para a mensagem, deixamos um editor de texto com algumas funções para você poder escrever a sua notificação:

- <img src="/erp-v2/assets/modulos/icon_tamanho_texto.png" alt="" data-size="line"> Escolha de tamanho do texto;
- <img src="/erp-v2/assets/modulos/icon_negrito.png" alt="" data-size="line"> Negrito;
- <img src="/erp-v2/assets/modulos/icon_italico.png" alt="" data-size="line"> Itálico;
- <img src="/erp-v2/assets/modulos/icon_sublinhado.png" alt="" data-size="line"> Sublinhado
- <img src="/erp-v2/assets/modulos/icon_hiperlink.png" alt="" data-size="line"> Hiperlink;
- <img src="/erp-v2/assets/modulos/icon_lista_ordenada.png" alt="" data-size="line"> Listas ordenada;
- <img src="/erp-v2/assets/modulos/icon_lista_nao_ordenada.png" alt="" data-size="line"> Lista não ordenada;
- <img src="/erp-v2/assets/modulos/icon_limpar_formatacao.png" alt="" data-size="line"> Limpar formatação. 

<!-- Nesta parte perguntar ao Paulo as restrições de envio de notificação para deixar o aviso na página para os demais usuários -->

![](/erp-v2/assets/modulos/menu_guia_usuarios_notificacao_enviada.gif)

<br>

### Filtros usuários

No menu de filtro você pode definir uma busca específica por usuários, seja por nome, e-mail, documento, status ou unidade. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos usuários, no primeiro filtro você pode filtrar pelo ID do usuário:

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro_id.png)

Nesta janela que se abriu, tem algumas funções importantes para abordarmos, o primeiro é o tipo de busca, com algumas opções:

- **Igual a:** Este filtro é usado para buscar registros que possuam um valor exatamente igual ao especificado. Por exemplo, se você busca por “idade igual a 30”, retornará apenas os registros com a idade exata de 30 anos;
- **Diferente de:** Com este filtro, você pode buscar registros que tenham valores diferentes do especificado. Por exemplo, se você busca por “status diferente de ‘concluído’”, retornará todos os registros com status diferentes de “concluído”.
- **Menor que:** É utilizado para buscar registros cujo valor seja menor do que o especificado. Por exemplo, se você busca por “preço menor que 100”, retornará todos os registros com preço inferior a 100.
- **Menor ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “quantidade menor ou igual a 10”, retornará registros com quantidade igual ou menor que 10.
- **Maior que:** Busca registros cujo valor seja maior do que o especificado. Por exemplo, se você busca por “receita maior que 5000”, retornará registros com receita superior a 5000.
- **Maior ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “nota maior ou igual a 7”, retornará registros com nota igual ou maior que 7.
- **Dentro de:** Este filtro é usado para buscar registros cujo valor esteja dentro de um intervalo específico. Por exemplo, se você busca por “id dentro de 15 a 19”, retornará registros com id entre 15 e 19 anos.
- **Fora de:** Similar ao filtro anterior, mas busca registros cujo valor esteja fora do intervalo especificado. Por exemplo, se você busca por “preço fora de 5 a 10”, retornará registros com preço abaixo de 5 ou acima de 10.

{% hint style="info" %}
**Informativo:** No uso do filtro **`Dentro de`** ou **`Fora de`** você precisa inserir todos os valores que ficarão dentro ou fora da busca, igual exemplo abaixo:
{% endhint %}

![](/erp-v2/assets/modulos/menu_guia_usuario_filtro_dentrode.gif)

<br>

Depois do filtro de ID, está o filtro de **`nome`**, para colocar o texto que será buscado, por isso é sempre importante o preenchimento completo dos dados de cada usuário 😉👍

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro_nome.png)

<br>

Você pode pesquisar por **`Unidade`** (Unidade já vem pré-definida pelo administrador que fez o cadastro do usuário), confira exemplo abaixo, pois é necessário digitar o nome da unidade para aparecer na busca:

![](/erp-v2/assets/modulos/menu_guia_usuario_filtro_unidade.gif)

<br>

Você tem também o filtro por **`E-mail`**, nele é preciso inserir parte do email ou o nome presente no e-mail para realizar a busca.

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro_email.png)

<br>

Agora no filtro por **`Status`** existem três opções para você utilizar nas buscas, sendo elas:

- <img src="/erp-v2/assets/modulos/icon_status_ativado.png" alt="" data-size="line"> Ativado;
- <img src="/erp-v2/assets/modulos/icon_status_desativado.png" alt="" data-size="line"> Desativado;
- <img src="/erp-v2/assets/modulos/icon_status_aguardando.png" alt="" data-size="line"> Aguardando confirmação.

![](/erp-v2/assets/modulos/menu_guia_usuario_filtro_status.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/menu_guia_usuario_filtro_grid.png)

![](/erp-v2/assets/modulos/menu_guia_usuario_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Pois você pode ficar despreocupado! Colocamos o botão redefinir, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/menu_guia_usuario_grid_restaurar.gif)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtros_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada usuário mostrado, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/menu_guia_usuarios_editar_excluir.png)

<br>

### Botão direito mouse aba usuários

Lembrando que em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_reenviar_mouse.png" alt="" data-size="line"> Reenviar confirmação de e-mail (Este item é somente para casos de usuários que não confirmaram a conta);
- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/menu_usuarios_btn_mouse.gif)

<br>

### Paginação aba usuários

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de usuários mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/menu_guia_usuarios_paginacao.png)

<br>

### Adicionar novo usuário

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo usuário, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/modulos/menu_guia_ususarios_menu_add_user.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados do novo usuário:

![](/erp-v2/assets/modulos/menu_guia_usuario_add_user.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/menu_guia_usuario_add_user_menu.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar uma conta é exigido o perfil e e-mail. Agora os outros campos para preenchimento pode deixar para o usuário quando ele confirmar a conta, listamos os campos abaixo:

- **Nome** (Nome completo do usuário, podendo ele preencher depois);
- **Nome usuário** (É usado para login na plataforma, podendo ser um nome/código/cpf);
- **Alterar senha** (Para mais informações [clique aqui](/erp-v2/minhas_preferencias/alt_minha_senha.md));
- **Status** (Aqui você define o status do usuário, sendo ativado, desativado ou aguardando registro);
- **Perfil** (Item obrigatório, Aqui define que tipo de autorização que ele terá na plataforma);
- **Unidade** (Nome do local/setor de trabalho);
- **E-mail** (Item obrigatório, a conta está vinculada exclusivamente a ele não podendo ser modificado depois);
- **Telefone**;
- **Documento** (Pode ser um RG/CPF/CNH, o usuário pode preencher depois);
- **CEP** (Após inserir o CEP os demais dados serão preenchidos automaticamente);

<br>

![](/erp-v2/assets/modulos/menu_guia_usuario_add_user_itens.png)

<br>

Uma informação importante sobre os tipos de Perfis:

- **Usuário :** Terá acesso básico a plataforma, é responsável pelo cadastro de clientes, realizar vendas e gerar relatórios.

- **Coordenador :** Além das permissões de usuário, ele possui acesso ao financeiro e aos dashboards de sua unidade.

- **Gerente :** Também pode visualizar os relatórios financeiros de outras unidades, cadastrar vendedores (porém não pode apagá-los) além de cadastrar novos usuários de perfil tipo `usuário`.

- **Administrador :** Possui acesso à maioria das funcionalidades, pode cadastrar novos usuários como administrador ou usuário, visualizar o histórico de todas as unidades, alterar ou remover vendedores/usuários ou clientes, alterar entradas no financeiro, cadastrar tabelas de preço e alterar detalhes em formas de pagamento, tipos de negociação e contas bancárias.

- **Super administrador :** Este perfil tem acesso total a plataforma e também pode realizar alterações em eventos e geração de relatórios em páginas como `Notification Template` e `Reports and Widgets`.

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do usuário será salvo e enviado para o email dele uma mensagem para finalizar o registro:

![](/erp-v2/assets/modulos/menu_guia_usuarios_salvar.gif)

