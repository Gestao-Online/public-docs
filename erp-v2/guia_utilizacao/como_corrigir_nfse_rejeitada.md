# Como corrigir uma nota fiscal de serviço rejeitada (NFSe)?

<!-- CONFIRMAR COM PAULO SOBRE ESSA GUIA EM ESPECÍFICO, POIS EXISTEM MUITAS POSSIBILIDADES DE ERRO EM UMA NFSe E PRECISO SABER SE SERÃO CITADOS TODOS OU SOMENTE OS MAIS FREQUENTES. -->

Quando uma nota fiscal é rejeitada pela SEFAZ, ela deixa de ser válida, impedindo que a emissão seja finalizada. E ela pode ser rejeitada por algumas situações específicas. A maioria delas é ca
sada por erros contidos nas informações enviadas ao fisco.

Assim, ao preencher determinados campos, é possível que sejam percebidas inconsistências que geram diferentes tipos de rejeições. Felizmente, cada uma delas tem uma solução.

{% hint style="warning" %}
**Atenção:** O acompanhamento de Nota Fiscal é realizado somente por usuários de nível alto. Vendedores não têm acesso a essas opções mostradas neste guia.
{% endhint %}

O primeiro passo para a correção é identificar qual erro é mostrado, em nosso sistema, você pode ver esta mensagem primeiro clicando no botão <img src="/erp-v2/assets/icon_acompanhar_nf.png" alt="" data-size="line"> acompanhar nf. E uma nova janela será aberta, ela basicamente é um espelho da tela de [**Nota Fiscal NFSe**](/erp-v2/funcionalidades/fiscal/nota_nfse.md). Observe que podemos ver o status, tipo, número RPS, etc.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf.gif)

Clicando no botão <img src="/erp-v2/assets/funcionalidades/icon_editar_item.png" alt="" data-size="line"> editar, você verá as informações dessa NFSe, e ao final da página encontra a mensagem que é retornada do emissor.

Através dessa mensagem de erro que podemos identificar o que houve e então verificar como poderemos corrigir o problema. 😁👍

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf_editar_mensagem_erro.gif)

Por exemplo, neste caso ocorreu o erro E328, mas analisando melhor a mensagem, a prefeitura local (neste caso em específico) trouxe um retorno e uma possível correção, informando que o certificado digital da empresa era inválido, e como possível correção ou solução, a prefeitura recomenda que seja utilizado um certificado digital ICP Brasil que não esteja revogado ou expirado para que a criação da NF ocorra normalmente.

![](/erp-v2/assets/guia_utilizacao/guia_como_corrigir_nfse_rejeitada_btn_acampanha_nf_editar_mensagem_erro.png)

Para este caso, a subtituição do certificado digital pode ser feita acessando a tela [**Empresas**](/erp-v2/funcionalidades/parametrizacoes/empresas.md) e ir nas configurações fiscais alterar o certificado digital cadastrado.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_fiscais.png)

Nos dados fiscais você pode adicionar o certificado digital da empresa. Os certificados digitais são aceitos em formato **`.pfx`** ou **`.p12`**. 

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_certificado.png)

Agora com o 