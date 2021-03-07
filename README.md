# AULAS

TUTORIAIS DE C  [Início](https://tutoriais-de-c.ndicedodo.repl.co/)   [Discord](https://tutoriais-de-c.ndicedodo.repl.co/discord.html)   [Aulas](https://indicedoconhecimento.github.io/)

## AULA 1 - Hello World

pra começar bem em uma linguagem tem que fazer **Hello World** <br>
caso contrário você cai na maldição e não vai aprender direito a linguagem
```c
hello world em C:
#include<stdio.h>
int main(){
  printf("Hello World");
  return 0;
}
```

agora traduzindo pra brasileiro:
```
bota o stdio.h no meio
começa tudo aqui
  manda um Hello World com o printf do stdio
  programinha foi relax, agora pode sair
acaba tudo aqui
```
dica: nunca esqueça o ponto e vírgula no fim da linha<br><br>

dica2: // pra deixar comentário, não executa, mas serve pra explicar o código pra alguém ou você mesmo daqui a 1 mês<br><br><br>

## AULA 2 - variáveis
imagina você, fazendo uma prova, e você tem que lembrar quem criou a linguagem C, como você lembra? memória!<br><br>

pra poder guardar dados na memória com C, é bem simples, você cria uma variável, que como o nome diz, varia o que você coloca.<br><br>

partes: **tipo, modificador, nome e valor**<br><br>

- tipo diz que tipo de coisa você, número, letra, texto, etc<br>
os tipos mais usados e exemplo de valor:
```c
int     - 32// inteiro
float   - 3.14 // decimal (ou ponto flutuante)
double  - 3.1415 // decimal bolado (mais casas)
char    - 'F' // letra
char*   - "press F" // texto, ponteiro
```

uma coisa importante: **todos os tipos são a mesma coisa em sua essência**, são bits de dados, o que muda é a forma que se interpreta, o tamanho também muda para caber o dado desse tipo<br>
Ex.: colocar número em char, ele sempre foi número, só que o compilador interpreta seu caractere com a tabela ASCII

- modificador(opcional) modifica alguma característica, tamanho, constante, negativo, etc.

- nome ou identificador identifica qual variável vc tá chamando obv

- valor o que você vai colocar pra lembrar? opcional, pode colocar depois<br><br>

na prática:
```c
int main(){
  int idade_c, outra_var;//cria 2 variáveis, nome idade_c e outra_var
  outra_var = 49; //coloca 49 como valor
  idade_c = outra_var; //coloca o valor igual da outra_var
  printf("%i",idade_c);//mostra no console
}
```

agora tente modificar os nomes, os tipos e os valores pra brincar<br><br>

como printar variáveis com printf<br>
você já leu um artigo na wikipédia e tem aqueles [1] e [2]?<br>
são referências, que ficam no final pra não atrapalhar ali.<br><br>

com printf é a mesma coisa, mas você tem que dizer o tipo: printf("idade do C eh %i,var_int);<br>
tem vários tipos de referência, além do tipo da variável, muda como imprime, se é binário, decimal ou hexa.<br>
[Lista Deles](https://docs.microsoft.com/pt-br/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-160#type-field-characters)<br><br><br><br><br><br><img src="https://cdn.discordapp.com/attachments/811046575555346502/817514642766823484/c-programming-569564.png">
