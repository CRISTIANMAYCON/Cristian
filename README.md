
# nome_da_variavel = dado/valor/atributo

numero = 20
# Nome da variável: numero
# Dado/valor atribuído: 20

nome = 'Veronica'

variavel = [21, 'Maria', 19.90]

print(numero)
# Exibe em tela o conteúdo da variável numero

print(nome)
print(variavel)

     
20
Veronica
[21, 'Maria', 19.9]
Sintaxe básica, leitura léxica e indentação


dicionario = {'Nome':'Fernando',
              'Idade':33,
              'Formação':'Eng. da Computação'}

print(dicionario)

# Por leitura léxica entenda que o interpretador lê o código sequencialmente,
# de cima para baixo, da esquerda para direita, levando em conta os espaços e
# tabulações aplicadas ao código (indentação).

     
{'Nome': 'Fernando', 'Idade': 33, 'Formação': 'Eng. da Computação'}
Estrutura básica de um programa

Olá Mundo!!! em Java


class MeuPrograma {
    public static void main(String args[]) {
        System.out.println("Olá Mundo!!!");
    }
}

     
Olá Mundo!!! em C#


using System; 
namespace MeuPrograma { 
    class OlaMundo { 
	    static void Main(string[] args) {
           Console.WriteLine("Olá Mundo!!!"); 
	       Console.ReadKey(); 
	    } 
    } 
} 

     
Olá Mundo!!! em Python


print('Olá Mundo!!!')

     
Olá Mundo!!!
Linguagens de Alto Nível vs Linguagens de Baixo Nível

Olá Mundo!!! em Assembly


section     .text
global      _start

_start:

    mov     edx,len
    mov     ecx,msg
    mov     ebx,1
    mov     eax,4
    int     0x80

    mov     eax,1
    int     0x80

section     .data

msg     db  'Olá Mundo!!!',0xa 
len     equ $ - msg

     
Olá Mundo!!! em Python


print('Olá Mundo!!!')

     
Olá Mundo!!!
