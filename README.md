# Hospedagem_Csharpe

<h3>Contexto</h3>
Este é um sistema de hospedagem, que é usado para realizar uma reserva em um hotel. A classe Pessoa representa o hóspede, as classe Suíte e a classe Reserva fazem um relacionamento entre ambos.

O seu programa calcula os valores dos métodos da classe Reserva, que traz a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

<h3>Regras e validações</h3>
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.

2. O método ObterQuantidadeHospedes da classe Reservaretorna a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria retorna o valor da diária (Dias reservados x valor da diária).

3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.

![UML](https://github.com/MichelinJV/Hospedagem_Csharpe/blob/main/diagrama_classe_hotel.png)

