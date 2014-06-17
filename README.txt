Padroniza��o C�digo

1. idioma
O codigo fonte deve ser escrito em ingl�s.
exemplo:
struct str_dataClient
{
	char name[];
	int number;
};

Nomes e termos regionais sem correspondentes em ingl�s, ou de pessoas ou localidades, 
devem ser escritos no idioma de contexto do termo.
Atualmente ingl�s � a linguagem padr�o para comunica��o internacional.

2. Nomenclatura
A escolha adequada e consistente de nomes � o aspecto mais importante na padroniza��o, 
uma vez que deve permitir a compreens�o f�cil e sem (ou reduzida) ambiguidade aos humanos dos elementos 
representados no c�digo.

3. Tipos de dados
Variaveis globais................... g_nome_variavel
Estruturas.......................... str_nome_estrutura
ponteiros........................... *pNome_ponteiro

3.1. Abrevia��es
N�o use abrevia��es a menos que elas sejam bem conhecidas fora do seu projeto.

4. Documenta��o
no in�cio de todo c�digo fonte utilize o padr�o abaixo
Informa��es: autor, data in�cio, data da �ltima altera��o, nome do programa, fun��o do c�digo.
N�o acentue os coment�rios!

/* ***************************************************************
* Autor: nome(s) do(s) autor(es) do codigo
* Inicio: data de inicio da codificacao
* Ultima alteracao: data da ultima alteracao realizada no codigo
* Nome: Nome do programa
* Funcao: descricao do que eh o programa
*************************************************************** */

4.1 sub-rotina/m�todo
Utilize o padr�o abaixo, contendo: nome do m�todo, fun��o, par�metros recebidos, valor retornado.

/* ***************************************************************
* Metodo: nome do metodo
* Funcao: testa os valores para transmissao
* Parametros: descricao dos parametros recebidos
* Retorno: descricao do valor retornado
*************************************************************** */
void testaValor (void)
 {
	 if (valor==10)
		 { //valor eh o tamanho da mensagem recebida
 			//fa�a algo aqui
 		}//fim do if
 	else
		 {
 			//fa�a outra coisa aqui
 		}//fim do else
}//fim do metodo testaValor

