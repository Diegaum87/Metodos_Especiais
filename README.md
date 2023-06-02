# Metodos_Especiais

Exercitando métodos mágicos
Crie uma classe Filme em que seus objetos sejam instanciados conforme os parâmetros titulo, uma string, e duracao, um inteiro que representa o tempo em minutos. Os atributos devem ter o mesmo nome dos parâmetros;
Faça com que o print dos objetos dessa classe tenham o seguinte formato:
john_wick = Filme('John Wick', 113)
print(john_wick)
# <Filme: John Wick>

Faça com que, ao aplicar len em um filme, seja retornado sua duração em minutos. Seguindo o exemplo do filme acima: len(john_wick) deve retornar 113;
Adicione um atributo de instância numero_de_exibicoes, que sempre será iniciado com o valor 0 (zero). Ele vai indicar quantas vezes o filme foi exibido nos cinemas.
Verifique, utilizando vars(), se um filme possui os atributos titulo, duracao e numero_de_exibicoes com os valores corretos. Ou seja, o primeiro deve ser o título do filme, o segundo deve ser a duração do filme em minutos e, o terceiro, o número de exibições (que deve ser 0).
Faça com que uma instância de filme, ao ser invocada, incremente o atributo numero_de_exibicoes em uma unidade e retorne o valor atualizado de seu número de exibições nos cinemas.
Utilize o vars() novamente para ver se realmente o número de exibições daquele filme foi aumentado em 1 unidade.