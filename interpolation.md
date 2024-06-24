# Interpolação

Regras
> Passar **EXATAMENTE** em todos os pontos
> SOMENTE FUNCIONA NO INTERIOR DOS DADOS
> o  grau do Polinomio varia dependendo do numero de pontos, sendo o Max = n - 1

# Métodos de Interpolação
## Lagrange
Abordagem Matricial
- fazer matriz com os X
- o grau máximo é de N - 1, sendo N o numero de pontos
- o máximo de alterações de comportamento do gráfico é N - 1, pois é o máximo que poderia ter de mudanças pegando todos os dados
- a lógica de lagrange é cair num sistema, a complexidade do sistema é a mesma quantidade de pontos
- a solução desse vem por uma multiplicação do inverso da matriz do sistema, com a matriz do resultado


- Lagrange é muito bom para nem tantos dados
- quanto mais próximos as bordas mais volátil fica o resultado dos dados
## Diferenças Divididas

## Diferenças Finitas