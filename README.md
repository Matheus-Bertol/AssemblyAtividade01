## AssemblyAtividade01
## Atividades da aula de sistemas embarcados do dia 30/04/2024

# 1- Como funciona a alocação de memória dinâmica para armazenar seu nome? 

```
ORG 000 / inicia programa no endereço 000

/ carrega e armazena os valores das letras nas variaveis name_letra

Load M
Store NAME_M
Load a
Store NAME_A
Load t
Store NAME_T
Load h
Store NAME_H
Load e
Store NAME_E
Load u
Store NAME_U
Load s
Store NAME_S

Halt / Termina execução

/ Definir o que signiifica cada letra na tabela hex

M, HEX 4D
a, HEX 61
t, HEX 74
h, HEX 68
e, HEX 65
u, HEX 75
s, HEX 73

/atribuir as variáveis para definir o espaço 
/Reservar o espaço para o Nome Matheus

NAME_M, HEX 0
NAME_A, HEX 0
NAME_T, HEX 0
NAME_H, HEX 0
NAME_E, HEX 0
NAME_U, HEX 0
NAME_S, HEX 0
```

****![image](https://github.com/Matheus-Bertol/AssemblyAtividade01/assets/141282448/a3bc96a5-06b8-41c8-8496-75de97b1c4af)
