# 👤 Usuários

Aqui você tem a visão de todos os usuários cadastrados na plataforma Gestão.Online, podendo fazer cadastro, nviar notificações e até excluir um usuário cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/modulo_usuario.gif)

<br>

Nesta guia temos um nu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_notificacao.png" alt="" data-size="line"> Enviar notificações para usuários;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar usuário.

![](/erp-v2/assets/modulos/menu_guia_usuarios.png)

<br>

Ao clicar no primeiro item do menu vamos para o envio de notificação aos usuários, o prenchimento é bem simples e entuitivo. 

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

Depois de definido o tipo de usuário, agora vamos para a mensagem, deixamos um editor de texto com algumas funções para você poder excrever a sua notificação:

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

No menu de filtro você pode definir uma busca específica por usuários, seja por nome, e-mail, documento, status ou unidade. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos usuários, no primeiro filtro você pode filtrar pelo ID do usuário:

![](/erp-v2/assets/modulos/menu_guia_usuarios_filtro_id.png)

Nesta janela que se abriu, temos algumas funções importantes para abordarmos, o primeiro é o tipo de busca, com algumas opções:

- **Igual a:** Este filtro é usado para buscar registros que possuam um valor exatamente igual ao especificado. Por exemplo, se você busca por “idade igual a 30”, retornará apenas os registros com a idade exata de 30 anos;
- **Diferente de:** Com este filtro, você pode buscar registros que tenham valores diferentes do especificado. Por exemplo, se você busca por “status diferente de ‘concluído’”, retornará todos os registros com status diferentes de “concluído”.
- **Menor que:** É utilizado para buscar registros cujo valor seja menor do que o especificado. Por exemplo, se você busca por “preço menor que 100”, retornará todos os registros com preço inferior a 100.
- **Menor ou igual a:** Similar ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “quantidade menor ou igual a 10”, retornará registros com quantidade igual ou menor que 10.
- **Maior que:** Busca registros cujo valor seja maior do que o especificado. Por exemplo, se você busca por “receita maior que 5000”, retornará registros com receita superior a 5000.
- **Maior ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “nota maior ou igual a 7”, retornará registros com nota igual ou maior que 7.
- **Dentro de:** Este filtro é usado para buscar registros cujo valor esteja dentro de um intervalo específico. Por exemplo, se você busca por “id dentro de 15 a 19”, retornará registros com id entre 15 e 19 anos.
- **Fora de:** Similar ao filtro anterior, mas busca registros cujo valor esteja fora do intervalo especificado. Por exemplo, se você busca por “preço fora de 5 a 10”, retornará registros com preço abaixo de 5 ou acima de 10.

{% hint style="info" %}
**Atenção:** No uso do filtro `Dentro de` ou `Fora de` você precisa inserir todos os valores que ficarão dentrou ou fora da busca, igual exemplo abaixo:
{% endhint %}

![](/erp-v2/assets/modulos/menu_guia_usuario_filtro_dentrode.gif)

