# **GO DocBuilder**


**Descrição:**  
A GO DocBuilder é uma extensão do sistema Gestão Online que permite gerar documentos em PDF (como contratos e propostas comerciais) baseados em templates do Google Docs.

Esta extensão busca um documento modelo no Google Docs, substitui tags por dados do sistema (como nome do parceiro, endereço, CNPJ, etc.) e perguntas/respostas personalizadas inseridas pelo usuário, gerando um PDF final automaticamente.

**Como criar o Template no Google Docs**

<p align="center">
  <img src="assets/extensao-GO-DocBuilder2.png" alt="GO DocBuilder GIF">
</p>

Crie um documento no Google Docs com as variáveis a serem substituídas. As variáveis devem ser colocadas no formato:

* `$P{parceiro.nome}`  
* `$P{parceiro.cpf_cnpj}`  
* `$P{questao_nome}`  
* `$P`{resposta\_\[nome\_da\_pergunta\]}

Essas variáveis serão substituídas automaticamente com os dados da entidade e respostas do formulário.

## **Configuração da Extensão**

### **1\. Acesso à Configuração**

Para configurar a extensão GO DocBuilder:
<p align="center">
  <img src="assets/extensao-GO-DocBuilder3.gif" alt="GO DocBuilder GIF">
</p>


<br>


1. Acesse o menu de Extensões no sistema  
2. Localize a extensão GO DocBuilder  
3. Clique em Configurar

*2\. Campos de Configuração**

### Na tela que abrir, você verá uma tabela com os documentos já configurados:

* Cada linha representa um botão que aparecerá nas telas do sistema  
* Se for a primeira vez, a tabela estará vazia  

<p align="center">
  <img src="assets/extensao-GO-DocBuilder4.png" alt="GO DocBuilder GIF">
</p>


<br>

**Adicionar Novo Documento**

1. Clique no botão "+" no canto superior direito da tabela  
2. Um formulário será aberto com os campos de configuração!
<p align="center">
  <img src="assets/extensao-GO-DocBuilder5.gif" alt="GO DocBuilder GIF">
</p>



#### 

#### 

#### **Campos obrigatórios**

*  Nome do botão: Nome que aparecerá no botão na tela

* Tela: Onde o botão deve aparecer (Movimentação, Parceiro, etc.)  
* Link: URL do documento do Google Docs
  
<p align="center">
  <img src="assets/extensao-GO-DocBuilder6.png" alt="GO DocBuilder GIF">
</p>



<br>


**Tipo Movimentação**

Quando a tela for "Movimentação", permite especificar em qual tipo de movimentação o botão deve aparecer Quando você associa o botão a um ou mais tipos de movimentação ele só será exibido nas telas de movimentação que correspondam ao tipo selecionado.

Caso nenhum tipo seja selecionado, o botão não será exibido em nenhuma movimentação.

<p align="center">
  <img src="assets/extensao-GO-DocBuilder15.png" alt="GO DocBuilder GIF">
</p>

<br>

Assim que é finalizado todas as etapas, um aviso no estilo pop-up é exibido ao usuário dentro do Gestão Online. Informando que foi feito o certificado foi emitido e um agendamento do vencimento deste certificado que foi criado dentro da tela de Agendamentos.


#### **Campo: Tipo de Perfil**

Este campo define quais perfis de usuário do sistema têm permissão para visualizar e utilizar o botão configurado. Quando você associa o botão a um ou mais perfis, ele só será exibido para os usuários que possuírem um dos perfis selecionados. Se outro usuário logado tiver um perfil diferente (não listado na configuração), ele não verá o botão.

#### É possível associar múltiplos perfis ao botão, permitindo que diferentes papéis o utilizem.

Caso nenhum perfil seja selecionado, o botão não será exibido para ninguém.

<p align="center">
  <img src="assets/extensao-GO-DocBuilder8.png" alt="GO DocBuilder GIF">
</p>

<br>

#### 

#### 

#### **Campos opcionais:**

Possui Perguntas?: Ativa formulário com perguntas personalizadas

Anexar Documento?: Se deve salvar o PDF como anexo da entidade
<br>

### **Configuração de Perguntas**



Quando "Possui Perguntas?" está ativado, você pode configurar:

* Título da Pergunta: Texto da pergunta  
* Tipo do Campo: Texto, Data ou Área de Texto  
* Obrigatório?: Se o campo é obrigatório  
* Colunas: Layout da pergunta (1-12 colunas)
 
<p align="center">
  <img src="assets/extensao-GO-DocBuilder10.gif" alt="GO DocBuilder GIF">
</p>
<br>

### **Anexos Automáticos**

Quando ativado, o PDF gerado é:

* Salvo como anexo da entidade  
* Registrado no histórico  
* Associado automaticamente ao registro
<p align="center">
  <img src="assets/extensao-GO-DocBuilder11.png" alt="GO DocBuilder GIF">
</p>

**Variáveis Disponíveis por Tela**

IMPORTANTE: As variáveis listadas abaixo são POSSÍVEIS para cada tela, mas só existem se o campo correspondente existir na entidade. 

<p align="center">
  <img src="assets/extensao-GO-DocBuilder12.png" alt="GO DocBuilder GIF">
</p>


# Tags de Variáveis

## **MOVIMENTAÇÃO (movVenda, movPedido, movRecorrencia)**

### **Dados Básicos da Movimentação:**

* $P{movimentacao.id} - ID da movimentação
* $P{movimentacao.tipo} - Tipo (V, PV, R)
* $P{movimentacao.codigo} - Código interno
* $P{movimentacao.codigo_externo} - Código externo
* $P{movimentacao.status} - Status da movimentação
* $P{movimentacao.observacao} - Observações

### **Valores e Financeiro:**

* $P{movimentacao.valor_total} - Valor total (formatado: 1.234,56)
* $P{movimentacao.valor_desconto} - Valor do desconto (formatado)
* $P{movimentacao.valor_frete} - Valor do frete (formatado)
* $P{movimentacao.valor_retido} - Valor retido (formatado)
* $P{movimentacao.percentual_desconto} - Percentual de desconto

### **Datas:**

* $P{movimentacao.data_negociacao} - Data da negociação (dd/mm/aaaa)
* $P{movimentacao.data_faturamento} - Data do faturamento (dd/mm/aaaa)

### **Itens da Movimentação:**

* $P{movimentacao.movimentacao_itens_descricao} - Descrição dos itens
* $P{movimentacao.movimentacao_itens_quantidade} - Quantidade dos itens

### **Dados de Recorrência:**

* $P{movimentacao.recorrencia_numero_contrato} - Número do contrato
* $P{movimentacao.recorrencia_inicio_contrato} - Data início (dd/mm/aaaa)
* $P{movimentacao.recorrencia_validade_contrato} - Data validade (dd/mm/aaaa)
* $P{movimentacao.recorrencia_periodicidade} - Periodicidade
* $P{movimentacao.recorrencia_dias_para_faturar} - Dias para faturar
* $P{movimentacao.recorrencia_status} - Status da recorrência
* $P{movimentacao.recorrencia_tentativa} - Número de tentativas
* $P{movimentacao.recorrencia_dia_proxima_tentativa} - Próxima tentativa (dd/mm/aaaa)
* $P{movimentacao.recorrencia_dia_proxima_fatura} - Próxima fatura (dd/mm/aaaa)

### **Campos Especiais para Propostas:**

* $P{num.proposta} - Número da proposta
* $P{validade.proposta} - Data de validade da proposta (dd/mm/aaaa)
* $P{observacao.proposta} - Observações da proposta

### **Tipo de Movimentação:**

* $P{tipo_movimentacao.id} - ID do tipo
* $P{tipo_movimentacao.descricao} - Descrição do tipo
* $P{tipo_movimentacao.status} - Status do tipo
* $P{tipo_movimentacao.tipo} - Tipo

### **Tipo de Movimentação Destino:**

* $P{movimentacao.tipo_movimentacao_destino} - Tipo de movimentação destino

### **Tipo de Negociação:**

* $P{tipo_de_negociacao.id} - ID do tipo de negociação
* $P{tipo_de_negociacao.descricao} - Descrição
* $P{tipo_de_negociacao.status} - Status
* $P{tipo_de_negociacao.codigo} - Código

### **Dados do Parceiro (Cliente):**

* $P{parceiro.id} - ID do parceiro
* $P{parceiro.nome} - Nome/Razão social
* $P{parceiro.razao_social} - Razão social
* $P{parceiro.cpf_cnpj} - CPF/CNPJ (formatado)
* $P{parceiro.tipo_pessoa} - PF (Pessoa Física) ou PJ (Pessoa Jurídica)
* $P{parceiro.data_de_nascimento} - Data nascimento (dd/mm/aaaa)
* $P{parceiro.codigo} - Código do parceiro
* $P{parceiro.email} - E-mail
* $P{parceiro.telefone} - Telefone
* $P{parceiro.celular} - Celular
* $P{parceiro.telefone_comercial} - Telefone comercial
* $P{parceiro.cep} - CEP
* $P{parceiro.endereco} - Endereço
* $P{parceiro.numero} - Número
* $P{parceiro.complemento} - Complemento
* $P{parceiro.bairro} - Bairro
* $P{parceiro.cidade} - Cidade
* $P{parceiro.estado} - Estado

### **Dados do Parceiro Indicador:**

* $P{parceiro_indicador.id} - ID do indicador
* $P{parceiro_indicador.nome} - Nome do indicador
* $P{parceiro_indicador.cpf_cnpj} - CPF/CNPJ do indicador
* $P{parceiro_indicador.tipo_pessoa} - Tipo de pessoa
* $P{parceiro_indicador.data_de_nascimento} - Data nascimento
* $P{parceiro_indicador.codigo} - Código
* $P{parceiro_indicador.razao_social} - Razão social
* $P{parceiro_indicador.email} - E-mail do indicador
* $P{parceiro_indicador.telefone} - Telefone do indicador
* $P{parceiro_indicador.celular} - Celular do indicador
* $P{parceiro_indicador.telefone_comercial} - Telefone comercial
* $P{parceiro_indicador.cep} - CEP
* $P{parceiro_indicador.endereco} - Endereço do indicador
* $P{parceiro_indicador.numero} - Número
* $P{parceiro_indicador.complemento} - Complemento
* $P{parceiro_indicador.bairro} - Bairro
* $P{parceiro_indicador.cidade} - Cidade do indicador
* $P{parceiro_indicador.estado} - Estado do indicador

### **Dados da Unidade:**

* $P{unidade.id} - ID da unidade
* $P{unidade.descricao} - Descrição da unidade
* $P{unidade.identificador} - Identificador
* $P{unidade.descricao_completa} - Descrição completa
* $P{unidade.status} - Status da unidade
* $P{unidade.codigo} - Código da unidade
* $P{unidade.telefone} - Telefone da unidade
* $P{unidade.celular} - Celular da unidade
* $P{unidade.email} - E-mail da unidade
* $P{unidade.endereco} - Endereço da unidade
* $P{unidade.numero} - Número da unidade
* $P{unidade.complemento} - Complemento da unidade
* $P{unidade.bairro} - Bairro da unidade
* $P{unidade.cidade} - Cidade da unidade
* $P{unidade.estado} - Estado da unidade
* $P{unidade.parceiro} - Parceiro da unidade

### **Dados da Empresa:**

* $P{empresa.id} - ID da empresa
* $P{empresa.cnpj} - CNPJ (formatado)
* $P{empresa.inscricao_estadual} - Inscrição estadual
* $P{empresa.nome_fantasia} - Nome fantasia
* $P{empresa.telefone} - Telefone da empresa
* $P{empresa.celular} - Celular da empresa
* $P{empresa.email} - E-mail da empresa
* $P{empresa.cep} - CEP da empresa
* $P{empresa.endereco} - Endereço da empresa
* $P{empresa.numero} - Número da empresa
* $P{empresa.complemento} - Complemento da empresa
* $P{empresa.bairro} - Bairro da empresa
* $P{empresa.cidade} - Cidade da empresa
* $P{empresa.estado} - Estado da empresa

### **Dados do Vendedor:**

* $P{vendedor.id} - ID do vendedor
* $P{vendedor.nome} - Nome do vendedor
* $P{vendedor.email} - E-mail do vendedor

### **Tags Especiais:**

* $P{total_produtos_geral} - Total geral de todos os grupos
* $P{total_desconto_geral} - Desconto geral de todos os grupos
* $P{total_produtos_com_desconto_geral} - Total geral com desconto

## **PARCEIRO (parceiroCliente, parceiroIndicador, parceiroFornecedor)**

### **Dados Completos do Parceiro:**

* $P{parceiro.id} - ID do parceiro
* $P{parceiro.nome} - Nome
* $P{parceiro.razao_social} - Razão social
* $P{parceiro.cpf_cnpj} - CPF/CNPJ (formatado)
* $P{parceiro.tipo_pessoa} - PF (Pessoa Física) ou PJ (Pessoa Jurídica)
* $P{parceiro.data_de_nascimento} - Data nascimento (dd/mm/aaaa)
* $P{parceiro.codigo} - Código do parceiro
* $P{parceiro.email} - E-mail
* $P{parceiro.telefone} - Telefone
* $P{parceiro.celular} - Celular
* $P{parceiro.telefone_comercial} - Telefone comercial
* $P{parceiro.cep} - CEP
* $P{parceiro.endereco} - Endereço
* $P{parceiro.numero} - Número
* $P{parceiro.complemento} - Complemento
* $P{parceiro.bairro} - Bairro
* $P{parceiro.cidade} - Cidade
* $P{parceiro.estado} - Estado


## **USUÁRIO (usuario)**

### **Dados do Usuário:**

* $P{usuario.id} - ID do usuário
* $P{usuario.name} - Nome do usuário
* $P{usuario.email} - E-mail
* $P{usuario.username} - Nome de usuário
* $P{usuario.cellphone} - Celular
* $P{usuario.document} - CPF/CNPJ (formatado)
* $P{usuario.country} - País
* $P{usuario.state} - Estado
* $P{usuario.city} - Cidade
* $P{usuario.address} - Endereço
* $P{usuario.zip_code} - CEP

## **UNIDADE (unidade)**

### **Dados da Unidade:**

* $P{unidade.id} - ID da unidade
* $P{unidade.descricao} - Descrição
* $P{unidade.identificador} - Identificador
* $P{unidade.descricao_completa} - Descrição completa
* $P{unidade.status} - Status da unidade
* $P{unidade.telefone} - Telefone
* $P{unidade.celular} - Celular
* $P{unidade.email} - E-mail
* $P{unidade.codigo} - Código
* $P{unidade.endereco} - Endereço
* $P{unidade.numero} - Número
* $P{unidade.complemento} - Complemento
* $P{unidade.bairro} - Bairro
* $P{unidade.cidade} - Cidade
* $P{unidade.estado} - Estado
* $P{unidade.parceiro} - Parceiro associado

## **CONTRATO DE CONTROLE DE UNIDADE (contrato_controle_unidade)**

### **Dados Básicos do Contrato:**

* $P{contratocontroleunidade.id} - ID do contrato
* $P{contratocontroleunidade.data_validade} - Data de validade (dd/mm/aaaa)
* $P{contratocontroleunidade.valor_limite} - Valor limite (formatado)
* $P{contratocontroleunidade.observacao} - Observações
* $P{contratocontroleunidade.status} - Status do contrato
* $P{contratocontroleunidade.data_de_alteracao} - Data da última alteração (dd/mm/aaaa)
* $P{contratocontroleunidade.tipo_contrato} - Tipo do contrato
* $P{contratocontroleunidade.fechamento_automatico} - Fechamento automático
* $P{contratocontroleunidade.fa_dia_semana} - Dia da semana para faturamento
* $P{contratocontroleunidade.fa_dia_mes} - Dia do mês para faturamento
* $P{contratocontroleunidade.fa_status} - Status do faturamento automático
* $P{contratocontroleunidade.fa_ultima_data_liberacao_confianca} - Última liberação de confiança
* $P{contratocontroleunidade.fa_ultima_data_verificacao} - Última verificação
* $P{contratocontroleunidade.fa_ultima_data_de_tentativa} - Última data de tentativa

### **Dados do Usuário Associado:**

* $P{usuario.id} - ID do usuário
* $P{usuario.email} - E-mail do usuário

### **Dados da Unidade Associada:**

* $P{unidade.id} - ID da unidade
* $P{unidade.descricao} - Descrição da unidade
* $P{unidade.identificador} - Identificador
* $P{unidade.descricao_completa} - Descrição completa
* $P{unidade.status} - Status da unidade
* $P{unidade.telefone} - Telefone da unidade
* $P{unidade.celular} - Celular da unidade
* $P{unidade.email} - E-mail da unidade
* $P{unidade.codigo} - Código da unidade
* $P{unidade.endereco} - Endereço da unidade
* $P{unidade.numero} - Número da unidade
* $P{unidade.complemento} - Complemento da unidade
* $P{unidade.bairro} - Bairro da unidade
* $P{unidade.cidade} - Cidade da unidade
* $P{unidade.estado} - Estado da unidade

### **Dados do Parceiro da Unidade:**

* $P{unidade.parceiro.id} - ID do parceiro da unidade
* $P{unidade.parceiro.nome} - Nome do parceiro da unidade
* $P{unidade.parceiro.razao_social} - Razão social
* $P{unidade.parceiro.cpf_cnpj} - CPF/CNPJ (formatado)
* $P{unidade.parceiro.tipo_pessoa} - PF (Pessoa Física) ou PJ (Pessoa Jurídica)
* $P{unidade.parceiro.data_de_nascimento} - Data nascimento (dd/mm/aaaa)
* $P{unidade.parceiro.codigo} - Código do parceiro
* $P{unidade.parceiro.email} - E-mail
* $P{unidade.parceiro.telefone} - Telefone
* $P{unidade.parceiro.celular} - Celular
* $P{unidade.parceiro.telefone_comercial} - Telefone comercial
* $P{unidade.parceiro.cep} - CEP
* $P{unidade.parceiro.endereco} - Endereço
* $P{unidade.parceiro.numero} - Número
* $P{unidade.parceiro.complemento} - Complemento
* $P{unidade.parceiro.bairro} - Bairro
* $P{unidade.parceiro.cidade} - Cidade
* $P{unidade.parceiro.estado} - Estado

### **Dados da Empresa Associada:**

* $P{empresa.id} - ID da empresa
* $P{empresa.cnpj} - CNPJ (formatado)
* $P{empresa.inscricao_estadual} - Inscrição estadual
* $P{empresa.nome_fantasia} - Nome fantasia
* $P{empresa.telefone} - Telefone da empresa
* $P{empresa.celular} - Celular da empresa
* $P{empresa.email} - E-mail da empresa
* $P{empresa.cep} - CEP da empresa
* $P{empresa.endereco} - Endereço da empresa
* $P{empresa.numero} - Número da empresa
* $P{empresa.complemento} - Complemento da empresa
* $P{empresa.bairro} - Bairro da empresa
* $P{empresa.cidade} - Cidade da empresa
* $P{empresa.estado} - Estado da empresa

### **Tipo de Negociação do Faturamento Automático:**

* $P{fa_tipo_de_negociacao.id} - ID do tipo de negociação
* $P{fa_tipo_de_negociacao.descricao} - Descrição
* $P{fa_tipo_de_negociacao.status} - Status
* $P{fa_tipo_de_negociacao.codigo} - Código

### **Tipo de Movimentação do Faturamento Automático:**

* $P{fa_tipo_movimentacao.id} - ID do tipo de movimentação
* $P{fa_tipo_movimentacao.descricao} - Descrição
* $P{fa_tipo_movimentacao.status} - Status
* $P{fa_tipo_movimentacao.tipo} - Tipo

### **Última Movimentação do Faturamento Automático:**

* $P{fa_ultima_movimentacao.id} - ID da movimentação
* $P{fa_ultima_movimentacao.codigo} - Código da movimentação
* $P{fa_ultima_movimentacao.status} - Status da movimentação
* $P{fa_ultima_movimentacao.valor_total} - Valor total da movimentação (formatado)

## **Tabelas Dinâmicas com Itens de Movimentação**

Para movimentações com múltiplos itens, você pode criar tabelas que se repetem automaticamente:

1. Crie uma tabela no Google Docs com os cabeçalhos desejados
2. Na linha de dados, use o formato especial com `[...]`:
   * $P{NomeDoGrupo[...].quantidade}
   * $P{NomeDoGrupo[...].valor_unitario}
   * $P{NomeDoGrupo[...].produto.descricao}
   * $P{NomeDoGrupo[...].produto.descricao_complementar}
   * $P{NomeDoGrupo[...].valor_total}

O sistema automaticamente:
* Agrupa itens por categoria de produto
* Replica a linha para cada item do grupo
* Substitui `[...]` por `[0]`, `[1]`, `[2]`, etc.

### Exemplo de tabela:

| Produto | Quantidade | Valor Unit. | Total |
|---------|------------|-------------|-------|
| $P{Licencas[...].produto.descricao} | $P{Licencas[...].quantidade} | $P{Licencas[...].valor_unitario} | $P{Licencas[...].valor_total} |

### Tags de Totalizadores Disponíveis:

* $P{NomeDoGrupo.total_produtos} - Total do grupo sem desconto
* $P{NomeDoGrupo.total_desconto} - Total de desconto do grupo
* $P{NomeDoGrupo.total_produtos_com_desconto} - Total com desconto aplicado
* $P{total_produtos_geral} - Total geral de todos os grupos
* $P{total_desconto_geral} - Desconto geral de todos os grupos
* $P{total_produtos_com_desconto_geral} - Total geral com desconto

---
# **`$P{tags}` — Listagem de todas as variáveis disponíveis na tela** 

A extensão GO DocBuilder suporta a utilização da variável especial `$P{tags}` dentro do modelo do Google Docs. Essa variável serve para exibir todas as variáveis (tags) disponíveis no momento da geração do documento, juntamente com seus respectivos valores.

## Finalidade

Essa funcionalidade é útil principalmente para:

* Testar a integração com a entidade  
* Visualizar todas as tags possíveis de serem utilizadas nessa tela  
* Ajudar no desenvolvimento de novos modelos

## Como usar

Basta inserir no conteúdo do seu Google Docs o seguinte marcador:

$P{tags}

Durante a geração do documento, esse marcador será substituído por um bloco de texto com todas as variáveis disponíveis no contexto, no formato:

Array

(

    [parceiro.nome] => João Silva

    [parceiro.cpf_cnpj] => 123.456.789-00

    [unidade.codigo] => 001

    ...

)

## **PERGUNTAS E RESPOSTAS (Todas as telas)**

Como Funciona: O sistema permite criar perguntas personalizadas que serão respondidas pelo usuário no momento da geração do documento. As respostas são automaticamente inseridas no template através de variáveis específicas.

Tipos de Variáveis de Perguntas:

1\. Perguntas por Nome (Recomendado):

* $P{questao\_\[nome\_da\_pergunta\]} \- Mostra o título da pergunta  
* $P{resposta\_\[nome\_da\_pergunta\]} \- Mostra a resposta da pergunta

2\. Respostas por Posição (Alternativa):

* $P{resposta1} \- Primeira resposta  
* $P{resposta2} \- Segunda resposta  
* $P{resposta3} \- Terceira resposta

Regras de Nomenclatura: O sistema converte automaticamente o título da pergunta para o nome da variável:

* Remove espaços e substitui por underscore (\_)  
* Converte para minúsculas  
* Remove acentos e caracteres especiais

Exemplos Práticos:

Exemplo 1 \- Pergunta Simples:

* Título configurado: "Nome do Responsável"  
* Variáveis geradas:  
* $P{questao\_nome\_do\_responsavel}   
* $P{resposta\_nome\_do\_responsavel} 
<p align="center">
  <img src="assets/extensao-GO-DocBuilder13.png" alt="GO DocBuilder GIF">
</p>
<p align="center">
  <img src="assets/extensao-GO-DocBuilder14.png" alt="GO DocBuilder GIF">
</p>



## Solução de Problemas

### Erro: "Documento não encontrado"

* Verifique se o link do Google Docs está correto  
* Confirme que o documento tem permissão pública ou compartilhada

### Erro: "Timeout ao acessar documento"

* Documento muito grande  
* Conexão lenta com o Google Docs  
* Tente novamente em alguns minutos

### Variáveis não são substituídas

* Confirme a sintaxe: `$P{nome_da_variavel}`  
* Verifique se a variável existe para a entidade  
  
