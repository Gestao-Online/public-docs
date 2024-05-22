# 🔔 Controle de exclusão em notificações

Nesta aba você tem acesso administrativo ao controle de exlusão de notificações na plataforma Gestão.Online:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes.gif)

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

<br>

Nesta aba está um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar controle de exclusão de notificação.

![](/erp-v2/assets/modulos/menu_guia_usuarios.png)

<br>

### Adicionar novo controle de exclusão em notificações

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo controle de exclusão em notificações, confira abaixo o procedimento para fazer o preenchimento corretamente:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_add_exclusao.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados da nova exclusão de notificação:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_add_exclusao_1.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_add_exclusao_menu.png)

<br>

Com a página aberta, por padrão, quando você for criar uma exclusão é exigido o valor, tipo e tipo expiração. Agora os outros campos só serão liberados após o preenchimento desses outros:

- **Valor** (Informação do motivo da exclusão, se será temporária ou permanente);
- **Tipo** (Define o tipo entre e-mail. telefone ou documento);
- **Tipo Expiração** (Se ela será permanente ou temporária);
- **Data Expiração** (Ativo caso marque tipo expiração temporário);
- **Data criação** (Este item não é alterado, é preenchido automaticamente pela plataforma).

<br>

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_add_exclusao_2.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do controle de exclusão em notificações será salvo e ativará naquele momento:

![](/erp-v2/assets/modulos/configuracoes/aba_notificações_add_exclusao_salvar.gif)


### Filtros controle de exclusão em notificações

No menu de filtro você pode definir uma busca específica por controles, seja por valor ou por nome. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_menu_filtro_1.png)

.

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_menu_filtro_2.png)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos controles de exclusão, no primeiro filtro tem o ID da exclusão:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_filtro_id.png)

<br>

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

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_filtro_dentrode.png)

<br>


Agora no filtro por **`Tipo`** existem três opções para você utilizar nas buscas, sendo elas:
- Email;
- Telefone;
- Documento.

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_filtro_tipo.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_filtro_grid.png)

![](/erp-v2/assets/modulos/configuracoes/aba_norificacoes_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Pois você pode ficar despreocupado! Colocamos o botão redefinir, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_grid_restaurar.gif)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_filtros_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada usuário mostrado, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_editar_excluir.png)

<br>

### Botão direito mouse aba controle de exclusão em notificações

Lembrando que em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_btn_mouse.gif)

<br>

### Paginação aba usuários

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de usuários mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/configuracoes/aba_notificacoes_paginacao.png)