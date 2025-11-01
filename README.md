# Entrega-do-Projeto---Loja-de-Doces---Lambda-Function-e-S3

## Descrição:
- Primeira Stack com AWS para simular um pedido numa livraria.

### CandyBloowDataBucket (à direita)
- É o local onde os dados ficam armazenados.

### CandyBloowBaseAccessPoint
- É uma porta de entrada para acessar o bucket de forma controlada.

### CandyBloowAnalyticsAccessPoint
- É outra porta de acesso, mas voltada para análises de dados.

### CandyBloowAnonymizerFunction
- É uma função Lambda, ou seja, um pequeno programa automático (Ela processa os dados antes de guardá-los ou antes de alguém acessá-los).

### CandyBloowAnonymizerFunction
- É uma permissão que autoriza a execução da função Lambda.
