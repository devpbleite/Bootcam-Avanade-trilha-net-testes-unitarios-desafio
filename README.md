# DIO - Trilha .NET - Testes Unitários com C#
www.dio.me

## Descrição do Projeto
Este projeto foi desenvolvido como parte do Desafio de Testes Unitários com C# na trilha .NET da Digital Innovation One (DIO). O objetivo é implementar testes unitários para validar as classes ValidacoesLista e ValidacoesString de um sistema que realiza diversas validações envolvendo listas e strings.

## Funcionalidades Implementadas
**Classes de Validação**
Classe ValidacoesLista
RemoverNumerosNegativos:

Ao passar uma lista com diversos números, incluindo positivos e negativos, deve retornar uma nova lista apenas com números positivos.
ListaContemDeterminadoNumero:

Ao passar uma lista com diversos números, incluindo um número específico, deve retornar verdadeiro, pois encontrou o número na lista.
MultiplicarNumerosLista:

Ao passar uma lista de inteiros, deve retornar uma nova lista, com todos os elementos multiplicados por um determinado número.
RetornarMaiorNumeroLista:

Ao passar uma lista de números inteiros, deve retornar o maior número presente na lista.
RetornarMenorNumeroLista:

Ao passar uma lista de números inteiros, deve retornar o menor número presente na lista.
Classe ValidacoesString
RetornarQuantidadeCaracteres:

Ao passar um texto qualquer, deve retornar a quantidade de caracteres presentes no texto.
ContemCaractere:

Ao passar um texto e um trecho a ser procurado, deve retornar verdadeiro se o trecho procurado está presente no texto.
TextoTerminaCom:

Ao passar um texto e um trecho a ser procurado, deve retornar verdadeiro se o trecho procurado está presente no final do texto.
Testes Unitários Implementados
Classe ValidacoesListaTests
DeveRemoverNumerosNegativosDeUmaLista:

Ao passar uma lista com diversos números, incluindo positivos e negativos, deve ser retornado uma nova lista apenas com números positivos.
DeveConterONumero9NaLista:

Ao passar uma lista com diversos números, incluindo o número 9, deve retornar verdadeiro, pois encontrou o 9 na lista.
NaoDeveConterONumero10NaLista:

Ao passar uma lista com diversos números, mas sem o número 10, deve retornar falso, pois não encontrou o 10 na lista.
DeveMultiplicarOsElementosDaListaPor2:

Ao passar uma lista de inteiros, deve retornar uma nova lista, com todos os elementos da lista multiplicados por 2.
DeveRetornar9ComoMaiorNumeroDaLista:

Ao passar uma lista de números inteiros, sendo o maior deles 9, deve retornar o 9 como maior elemento dentro dessa lista.
DeveRetornarOitoNegativoComoMenorNumeroDaList:

Ao passar uma lista de números inteiros, sendo o menor deles -8, deve retornar o -8 como menor elemento dentro dessa lista.
Classe ValidacoesStringTests
DeveRetornar6QuantidadeCaracteresDaPalavraMatrix:

Ao passar um texto escrito a palavra "Matrix", deve retornar o número 6, representando 6 caracteres presentes na palavra.
DeveContemAPalavraQualquerNoTexto:

Ao passar um texto escrito "Esse é um texto qualquer" e procurar pela palavra "qualquer", deve retornar verdadeiro, pois a palavra existe no texto.
NaoDeveConterAPalavraTesteNoTexto:

Ao passar um texto escrito "Esse é um texto qualquer" e procurar pela palavra "teste", deve retornar falso, pois a palavra não existe no texto.
TextoDeveTerminarComAPalavraProcurado:

Ao passar um texto escrito "Começo, meio e fim do texto procurado" e procurar pela palavra "procurado", deve retornar verdadeiro, pois a palavra existe no texto e está inclusa no final do texto.

## Como Executar os Testes
Clone o repositório:

<code>git clone https://github.com/seu-usuario/nome-do-repositorio.git</code>
Abra o projeto no ambiente de desenvolvimento .NET.

Execute os testes para verificar se as classes de validação estão funcionando corretamente.

<code>dotnet test</code>
Analise os resultados dos testes e ajuste o código conforme necessário para garantir a qualidade do sistema.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias nos testes, corrigir bugs ou adicionar novos cenários de teste. Basta abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT.
