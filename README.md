# FEUP-AEDA

## Theme: Stock Market

### Implemented solution
Num mercado de ações, existem:
- Os clientes, que podem colocar ordens de compra ou de venda;   
- As ordens, que podem ser de dois tipos: de compra e de venda;
- As transações, que são as ordens de venda e de compra concretizadas;
- Os clientes inativos, que são clientes que não colocam ordens de compra ou
de venda há pelo menos 15 dias;
- As notícias, que surgem na comunicação social envolvendo as empresas
cotadas no mercado, e que muitas vezes influenciam o valor das ações dessa
empresa;
- Gestores de conta, que auxiliam na gestão das transações dos clientes e
aconselham sobre os seus investimentos.

Os clientes são identificados pelo NIF, nome, morada, telemóvel, data da última
atividade e gestor de conta.

As ordens de compra são compostas pelo título, data de colocação no mercado e
NIF do cliente que as inseriu, preço máximo disposto a pagar por ação e o valor
máximo a disponibilizar.

As ordens de venda são compostas pelo título, data de colocação no mercado e
NIF do cliente que as inseriu, quantidade de ações a vender e o preço mínimo de
venda de cada ação.

As transações são compostas pelo título da ação, preço da ação, quantidade de
ações, data, NIF do cliente que vende e do que compra.

Os clientes inativos são como os clientes, mas sem gestores de conta.

As notícias são compostas pela data, nome do jornal que a publica, identificação
da empresa sobre a qual é publicada a notícia e a classificação da mesma (0 a 10).

Os gestores são identificados pelo nome, número de identificação do gestor,
telemóvel deste e os clientes do mesmo.

### Funcionalidades do programa
  -Menu Clientes;   
  -Menu Ordens;   
  -Menu Transações;   
  -Menu Notícias;   
  -Menu Gestores.    
