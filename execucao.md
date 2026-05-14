# Modelo de execução

- O Octave é um interpretador para a linguagem MATLAB.
- O gerenciamento de memória é feito automaticamente por um coletor de lixo.
- O processamento nativo se com linha de execução única (single-thread), mas existe, na biblioteca-padrão, o pacote parallel para processamento pararelo e o comando system para a execução de subprocessos assíncronos.
- A alocação de memória é feita com o operador de igualdade.  Quando se quer guardar o número 7 no endereço de memória apelidado de x, escreve-se x = 7.


