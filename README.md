![image](https://github.com/user-attachments/assets/26fde5c4-f3b7-4922-9036-31d8700d3e00)


usamos o useEffect para “atualizar” os componentes automaticamente, e foi atualizado o sistema para funcionar como foi pedido: 

Estamos no Brasil, então todos os pontos para calcular distância devem partir daqui. <br>
Temos que ter pelo menos 10 destinos pré cadastrados com suas distâncias.<br>
Calcular a distância até o destino escolhido.<br>
Acima de 2000 Km pega 2 voos.<br>
Se o voo for inferior a 2 meses a partir de agora é 1500 reais (considerando ida e volta).<br>
Se o voo for igual ou superior a 2 meses a partir de agora, paga 700 reais (considerando ida e volta).<br>
Acima de 2000 Km cada 1 Km adicional custa 1 real a mais no total.<br>
Cada semana de estadia custará 400 reais na estalagem padrão. Ou 700 reais na estalagem de luxo.<br>
Cada participante adicional adiciona 25% nos custos de estalagem.<br>
Enquanto escolhe o destino, o número de participantes, o tipo de estalagem e as datas de ida e volta, sempre aperece o subtotal imediato da compra a mostra com os critérios detalhados.<br>
Após escolher a viagem, as datas, o número de participantes, será redirecionado para tela de pagamento e fechamento de pedido, discriminando os critérios detalhados e o total. E exibindo métodos de pagamento: pix ou cartão de crédito.<br>

Foi adicionado agora distância e preço também com um subtitulo dos locais, junto com cálculos para caso tenha mais de uma pessoa viajando, dia da viagem e cálculo do preço com base na distância.  

Com o objetivo de mostrar o subtotal do valor, e no terminal mostrar o custo separado por cada parte da viagem.

Também foi feito ajustes no projeto para tornalo mais funcional e menos complicado na coomprienção, e também feito para previnir bugs.


