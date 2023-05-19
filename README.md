## APIComEntityFramework

## Desafio de projeto
Para este desafio, utilizei conhecimentos adquiridos no curso de Introdução a APIs e Entity Framework com C# da DIO.

## Contexto
Você foi contratado para construir uma API, que terá as funções de cadastro, alteração, busca por nome/Id e remoção de contatos. Será preciso que use
um banco de dados da sua prefência.

## Proposta
Para esse projeto foi construida uma classe chamada "Contato".

A classe contém quatro variáveis, sendo:

**Id**: Tipo int.É o identificador do contato.

**Nome**: Tipo string. É o nome do contato.

**Telefone**: Tipo string. É o telefone do contato.

**Ativo**: Tipo bool. Informa se o contato está ativado.

Feito isso foi criado o context para para gerenciar a interação com o banco de dados assim como a string de conexão necessária assim como os pacotes
via nuget abaixo:
**Microsoft.EntityFrameworkCore.Design**
**Microsoft.EntityFrameworkCore.SqlServer**(banco de dados de sua preferência)

Antes de inicar crie um database para guardar esses dados e lembre-se de colocá-lo na string de conexão e execute os comandos para configurar o Entity
Framework.

Depois de configurado foi feito um crud para a API dentro do controller de Contatos com os conhecimentos adquiridos até o momento.

## ✒️ Autores

* **Um desenvolvedor** - [Gabriel Batista]([https://github.com/batiistta])

