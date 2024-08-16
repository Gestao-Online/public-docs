# Como corrigir uma nota fiscal de serviço rejeitada (NFSe)?

A nota fiscal pode ser rejeitada por algumas situações específicas. A maioria delas é causada por erros contidos nas informações enviadas ao fisco.

Assim, ao preencher determinados campos, é possível perceber inconsistências que geram diferentes tipos de rejeições. Felizmente, cada uma delas tem uma solução.

{% hint style="warning" %}
**Atenção:** O acompanhamento de Nota Fiscal é realizado somente por usuários de nível alto. Vendedores não têm acesso a essas opções mostradas neste guia.
{% endhint %}

O primeiro passo para a correção é identificar qual erro é mostrado, em nosso sistema, você pode ver esta mensagem primeiro clicando no botão  acompanhar nf. E uma nova janela será aberta, ela basicamente é um espelho da tela de . Observe que podemos ver o status, tipo, número RPS, etc.

O primeiro passo para a correção é identificar qual erro é mostrado. Em nosso sistema, você pode ver esta mensagem primeiro clicando no botão <img src="/erp-v2/assets/icon_acompanhar_nf.png" alt="" data-size="line"> acompanhar NF. E uma nova janela será aberta, ela basicamente é um espelho da tela de [**Nota Fiscal NFSe**](/erp-v2/funcionalidades/fiscal/nota_nfse.md). Observe que podemos ver o status, tipo, número RPS, etc.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf.gif)

Clicando no botão <img src="/erp-v2/assets/funcionalidades/icon_editar_item.png" alt="" data-size="line"> editar, você verá as informações dessa NFSe e, ao final da página, encontrará a mensagem retornada do emissor.

Através dessa mensagem de erro, que podemos identificar o que houve e então verificar como poderemos corrigir o problema. 😁👍

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf_editar_mensagem_erro.gif)

## Problemas com certificado digital

Por exemplo, neste caso ocorreu o erro **E328**, mas analisando melhor a mensagem, a prefeitura local (neste caso em específico) trouxe um retorno e uma possível correção, informando que o certificado digital da empresa era inválido, e como possível correção ou solução, a prefeitura recomenda que seja utilizado um certificado digital ICP Brasil que não esteja revogado ou expirado para que a criação da NF ocorra normalmente.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf_editar_mensagem_erro.png)

Para este caso, a substituição do certificado digital pode ser feita acessando a tela [**Empresas**](/erp-v2/funcionalidades/parametrizacoes/empresas.md) e indo nas configurações fiscais, alterando o certificado digital cadastrado.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_fiscais.png)

Nos dados fiscais, você pode adicionar o certificado digital da empresa. Os certificados digitais são aceitos em formato **`.pfx`** ou **`.p12`**. 

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_certificado.png)

## Problemas com XML

Em alguns casos, você pode se deparar com erro de XML, mas, em geral, a rejeição do XML em uma nota fiscal acontece devido a erros na inserção dos dados.

Na prática, isso significa: CNPJ ou IM (Inscrição Municipal) incorretos, códigos de serviços e/ou cálculos de tributos informados incorretamente, duplicidade, problemas com o certificado digital e outras questões semelhantes.

Abaixo estão listados os erros mais comuns de rejeição de XML em notas fiscais:

- CNPJ inválido.
- Quantidade de caracteres no campo excedente ao padrão.
- Certificado digital inconsistente e/ou vencido, que foi o exemplo que explicamos acima.
- Prazo de cancelamento de uma nota fiscal excedido (24 horas).
- Problemas com a inscrição estadual.
- Erro de duplicidade.
- PIS e Cofins calculados e/ou informados incorretamente.

Em nosso exemplo abaixo, tivemos um caso de problema com XML. Lendo a mensagem de erro, já podemos ver que a prefeitura nos enviou um código do possível erro.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_mensagem_erro_xml.png)

Aqui ele já nos informa que temos o código do serviço inválido, ou seja, precisamos corrigir antes de emitir a nota fiscal novamente. Mas se olharmos mais, temos outro erro sendo exibido.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_mensagem_erro_xml_2.png)

O segundo erro se refere ao número de inscrição do prestador. No entanto, é importante considerar que um erro pode estar afetando o outro. Ao corrigirmos o primeiro erro, é possível que o segundo seja resolvido automaticamente. 😁

Após corrigir os erros da nota fiscal, não esqueça de abrir novamente a movimentação e clicar no botão gerar NF, assim ela será emitida corretamente para você.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_mensagem_erro_xml_3.png)