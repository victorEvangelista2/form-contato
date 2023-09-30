# Formulário de Contato e seus elementos

# FORM 

 - Essa tag indica que estamos iniciando um formulário, recebe como principais atributos method que recebe como valor o método http que esse formulário irá executar (get, post) e action que especifica para onde enviar os dados do formulário quando um formulário é enviado.

# INPUT

 - Um campo para que o usuário possa inserir algum texto, data, número, cor, etc… possui como principais atributos type, que recebe como valor o tipo do input.

# TEXTAREA

 - Representa uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre, como um comentário ou formulário de retorno.

# BUTTON

 - Um botão clicável, possui como principais atributos type, que caso receba submit como valor e esteja dentro de um formulário, irá submeter o formulário.

# LABEL 

 - A tag label é importante para os campos de formulários. Ela especifica qual o "rótulo" do input (a que se refere o input, como por exemplo envolvê-la em um texto “Nome completo”), e ajuda na experiência do usuário durante a utilização e preenchimento do formulário.

# Atributos que compõe o elemento "FORM"

 - "accept"
 - "accept-charset"
 - "autocapitalize"
 - "autocomplete"
 - "name"
 - "rel"
 - "action"
 - "enctype"
 - "method"
 - "novalidate"
 - "target"

# A seguir seram mostrados como são aplicados


# **accept**

 - A propriedade aceitar é um atributo do tipo de arquivo **"input"** . Foi suportado no **"form"** elemento, mas foi removido em favor do arquivo.

 - Como um determinado tipo de arquivo pode ser identificado de mais de uma maneira, é útil fornecer um conjunto completo de especificadores de tipo quando você precisar de arquivos de um tipo específico ou usar o curinga para indicar que um tipo de qualquer formato é aceitável.

 - **Nota**: *Este atributo foi descontinuado e não deve ser usado. Em vez disso, use o acceptatributo nos "input type=file" elementos.*

## exemplos:

 - Quando definido em um tipo de entrada de arquivo, o seletor de arquivo nativo que é aberto deve permitir apenas a seleção de arquivos do tipo correto. A maioria dos sistemas operacionais alivia os arquivos que não atendem aos critérios e não são selecionáveis.<br>
 1. <img  src="Imagens/cap 2.png" width="42%"><br>
 2. <img  src="Imagens/cap 1.png" width="55%">

 # **accept-charset**


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

# Autocapitalize

 - O atributo "autocapitalize" é usado em elementos HTML para controlar a capitalização automática de texto em campos de entrada e campos de texto. Ele pode ter os seguintes valores:

- "on": A primeira letra de cada sentença será por padrão uma letra maíuscula.
```
todas as demais letras serão por padrão minúsculas.
```

- "off": Isso desativa a automática.
- "words": Apenas as primeiras letras de cada palavra são capitalizadas automaticamente.
- "sentences": Apenas a primeira letra de cada frase é capitalizada automaticamente.
- "characters": Cada caractere é capitalizado automaticamente.

Isso é útil para personalizar a entrada de texto em formulários, dependendo dos requisitos do seu site ou aplicativo.