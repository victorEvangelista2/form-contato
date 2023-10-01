# Formulário de Contato e seus elementos 📋

# Elementos que compõe um formulário

| Elementos | descrição |
| --- | --- | 
| FORM | _Essa tag indica que estamos iniciando um formulário, recebe como principais atributos **"method"** e **"action".**_ | 
| INPUT | _Um campo para que o usuário possa inserir algum texto, data, número, cor, etc… possui como principal o atributo **"type"**._ | 
| TEXTAREA | _Representa uma caixa de texto, útil quando você quer permitir ao usuário informar um texto._ | 
| BUTTON | _Um botão clicável, que possui como principail atributo type._ | 
| LABEL | _A tag label é importante para os campos de formulários. Ela especifica qual o "rótulo" do input e ajuda na experiência do usuário durante a utilização e preenchimento do formulário._ | 

# Atributos que compõe o elemento "FORM"

 1. ***accept***
 2. ***accept-charset***
 3. ***autocapitalize***
 4. ***autocomplete***
 5. ***name***
 6. ***rel***
 7. ***action***
 8. ***enctype***
 9. ***method***
 10. ***novalidate***
 11. ***target***

# A seguir seram mostrados como são aplicados ⬇️


# accept 📌

 - A propriedade aceitar é um atributo do tipo de arquivo **"input"** . Foi suportado no **"form"** elemento, mas foi removido em favor do arquivo.

 - Como um determinado tipo de arquivo pode ser identificado de mais de uma maneira, é útil fornecer um conjunto completo de especificadores de tipo quando você precisar de arquivos de um tipo específico ou usar o curinga para indicar que um tipo de qualquer formato é aceitável.

 - **Nota**: *Este atributo foi descontinuado e não deve ser usado. Em vez disso, use o acceptatributo nos "input type=file" elementos.*

## exemplos:

 - Quando definido em um tipo de entrada de arquivo, o seletor de arquivo nativo que é aberto deve permitir apenas a seleção de arquivos do tipo correto. A maioria dos sistemas operacionais alivia os arquivos que não atendem aos critérios e não são selecionáveis.<br>
 1. <img  src="Imagens/cap 2.png" width="42%"><br>
 2. <img  src="Imagens/cap 1.png" width="55%">

 # accept-charset 📌


 - O atributo "Accept-Charset" não é exatamente um atributo HTML, mas sim um cabeçalho HTTP que pode ser usado em solicitações HTTP enviadas pelo navegador. Ele especifica a codificação de caracteres aceitável para a resposta da solicitação. 
 - Isso permite que o cliente (geralmente um navegador da web) indique ao servidor quais conjuntos de caracteres ele suporta, para que o servidor possa enviar uma resposta no formato apropriado.

## exemplos:

``` 
Accept-Charset: iso-8859-1
```

```
Utf-8, iso-8859-1;q=0.5
```

```
Accept-Charset: utf-8, iso-8859-1;q=0.5, *;q=0.1
```

# Autocapitalize 📌

 - O atributo "autocapitalize" é usado em elementos HTML para controlar a capitalização automática de texto em campos de entrada e campos de texto.
 - Ele pode ter os seguintes valores:

| Valores | Descrição |
| --- | --- | 
| **ON** | _primeira letra de cada sentença por padrão uma letra maíuscula. Logo as demais letras serão por padrão minúsculas._ |
| **OFF** | _Isso desativa a automática. Por padrão as letras serão minúsculas._ |
| **WORDS** | _Apenas as primeiras letras de cada palavra são capitalizadas automaticamente._ |
| **SENTENCES** | _Apenas a primeira letra de cada frase é capitalizada automaticamente._ |
| **CHARACTERS** | _Cada caractere é capitalizado automaticamente._ | 

 - Isso é útil para personalizar a **entrada de texto em formulários**, **dependendo dos requisitos** do seu site ou aplicativo.
 - **Observação**: _O atributo autocapitalize nunca ativa a autocapitalização para um elemento <input> com um atributo type cujo valor seja url, email, ou password._

# Autocomplete 📌

 - O atributo "autocomplete" em HTML é usado para controlar se um navegador deve ou não fornecer sugestões de preenchimento automático para campos de formulário. Ele aceita os seguintes valores:

```
"ON": Permite que o navegador forneça sugestões de preenchimento automático para o campo de formulário.
```

```
"OFF": Impede o navegador de fornecer sugestões de preenchimento automático para o campo.
```

```
"USERNAME":
Um nome de usuário ou nome de conta.
```

```
"E-MAIL": 📧
Um endereço de e-mail.
```

```
"NAME": O campo espera que o valor seja o nome completo de uma pessoa. Usar " name" em vez de dividir o nome em seus componentes é geralmente preferido porque evita lidar com a grande diversidade de nomes humanos e como eles são estruturados; no entanto, você pode usar os seguintes autocompletevalores se precisar dividir o nome em seus componentes:
```
 - Isso pode ser útil em **formulários** sensíveis, como os que solicitam informações pessoais ou financeiras, onde você deseja dar ao usuário mais **controle sobre as informações que são automaticamente preenchidas pelo navegador.**

# Name 📌

 - O atributo "name" em HTML é usado para dar um nome a um elemento, como um campo de formulário, uma âncora (link), ou um elemento de imagem. Esse nome é principalmente usado para identificar o elemento quando se envia dados de um formulário para um servidor.
# exemplos:
 - Em um formulário, os campos de entrada (input) podem ter um atributo "name" para que os dados sejam identificados quando o formulário for submetido. Em JavaScript, você pode acessar elementos com base em seus nomes para interagir com eles.

 - O atributo "name" pode ser usado nos seguintes elementos:

| elementos | Atributo |
|---|---|
| button | name |
| fieldset | name |
| form | name |
| iframe | name |
| input | name | 
| map | name | 
| object | name |
| output | name | 
| param | name | 
| select | name | 
| textarea | name |

# rel 📌

 - O atributo "rel" em HTML é usado principalmente em elementos de link (como <a> e <link>) para especificar o relacionamento entre o recurso vinculado (como uma página da web, um arquivo de estilo CSS, etc.) e o documento atual. Ele descreve a natureza do link.

 - Alguns valores comuns para o atributo "rel" são:

```
"STYLESHEET": Usado em links para arquivos CSS, indicando que o link se relaciona com uma folha de estilo.
```

```
"NOFOLLOW": Usado em links para informar aos mecanismos de busca que eles não devem seguir o link.
```

```
"CANONICAL": Usado para indicar a URL canônica de uma página, ajudando a evitar conteúdo duplicado.
```

```
"PREV" e "NEXT": Usados para criar uma relação de páginas em uma série de páginas, como em paginação.
```

```
"ICON": Usado para especificar um ícone de favorito ou ícone de aplicativo associado a uma página.
```

 - O atributo "rel" pode ser personalizado para relacionamento entre documentos e recursos da web. 📂

Navegadores suportados:

| Navegadores | rel |
| --- | --- |
| Google chrome | ✅ |
| Microsoft Edge | ✅ |
| Fire Fox | ✅ |
| Safari | ✅ |
| Opera | ✅ |

# Action📌
