# FAC-UNB-2024.1

* Matéria: Fundamentos de Arquitetura de Computadores.
* Professor: TIAGO ALVES DA FONSECA.
* 4° semestre de Engenharia de Software.

# Observações
* Qual linguagem?
 * A linguagem a ser usada nas implementações é a linguagem de montagem
   para a plataforma RISCV 32 bits (RV32IMFDN).
 * A extensão do arquivo com a listagem em linguagem de montagem deve
   ser .riscv
 * ATENÇÃO: a primeira instrução a ser lida pelo juiz eletrônico deverá
   ser posta imediatamente após do label "main:" da sua listagem.
 
* Meu programa acusa "RunTime Error" no Judge
  * Uma das possíveis causas é o esquecimento do 'return 0' ao terminar o
    programa, os juízes verificam se o programa terminou com sucesso e
    qualquer retorno diferente de 0 indica que pode ter ocorrido algum
    problema. Lembre-se: em RiscV, há uma ecall utilizada para sinalizar
    o 'return 0'.
  * Se você tem o return 0, verifique se as suas estruturas estão dentro dos
    limites das entradas.

# Trabalhos

## Trabalho 1
* A - [Ola Mundo](https://moj.naquadah.com.br/contests/ta_fac_t1_2024_1/olamundo.pdf)
* B - [Soma de dois numeros](https://moj.naquadah.com.br/contests/ta_fac_t1_2024_1/soma2.pdf)
