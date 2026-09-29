Dois erros que eu encontrei:

1.Erro: Erro no construtor (nome = nome;)
    Explicação: faltou "this.", pois sem ele dentor do código vai aparecer "null".
    Solução: Adicionei o "this." dentro do código, ficando assim: "this.nome = nome;" e "this.salario = salario;". Agora aparecendo o nome da funcionária no Terminal.

2.Erro: Aumento salarial "(salario = salario + percentual;)"
    Explicação: Está somando, ao invés de calcular o percentual da diferença (ex. R$ 3000 + 10 = R$ 3010). Forma certa de calcular o aumento (ex. 10% de 3000 = R$3000).
    Solução: Calculei o percentual ao invés de soma, multiplicando e depois dividindo para aparecer o real aumento salarial.
