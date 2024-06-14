# python-chaos-simulator

Nesta análise, simulamos como seria o dia a dia em uma academia, com 100 pessoas treinando. Dessas, 99 são usuários normais e 1 é um pouco bagunceiro. Cada pessoa precisa de um haltere para treinar.

O código simula o comportamento desses usuários. Eles escolhem aleatoriamente um haltere disponível para usar durante o treino e, em seguida, devolvem o haltere escolhido após o término do treino. O usuário bagunceiro, no entanto, tem a liberdade de devolver o haltere em qualquer lugar, não necessariamente onde o pegou.

A cada iteração do loop principal, que representa um dia de treino, as posições dos halteres são reiniciadas e os usuários treinam 10 vezes. Após 50 dias de treino, registramos o nível de caos na academia.

O histograma mostra a distribuição do nível de caos na academia ao longo dos 50 dias de treino. Cada barra no histograma representa um intervalo de valores de caos, e a altura da barra indica a frequência com que esse intervalo de caos ocorreu durante os dias de treino.

A partir do histograma, podemos observar a distribuição dos níveis de caos na academia. Isso nos permite entender melhor como o comportamento dos usuários, especialmente do usuário bagunceiro, afeta o ambiente da academia. Quanto mais alta uma barra no histograma, mais frequente é o nível de caos correspondente. Isso pode nos ajudar a tomar decisões e implementar políticas para melhorar o funcionamento da academia e reduzir o nível de caos. Por exemplo, podemos aumentar a quantidade de halteres disponíveis ou implementar regras mais rígidas para o usuário bagunceiro devolver os halteres nos lugares corretos.

# resultado

![image](https://github.com/crlsmees/python-chaos-simulator/assets/143832741/70a120cc-d4c4-4ea7-b147-557cd8a432a4)

A partir do histograma, podemos concluir que o nível de caos na academia tende a se concentrar em torno de 0.20, indicando que a maioria dos dias de treino apresenta um grau moderado de desordem. No entanto, a presença do usuário bagunceiro contribui para uma maior variabilidade e ocasionais picos de caos.

Para mitigar esses níveis mais altos de desordem, recomenda-se aumentar a quantidade de halteres disponíveis para cada peso, o que aumentaria, consequentemente, o número de espaços vazios para devolução. Isso poderia diminuir a competição por halteres e reduzir a probabilidade de caos causado pela falta de equipamentos.

Implementar regras mais rígidas para a devolução dos halteres também ajudaria a estabilizar o ambiente da academia, promovendo um funcionamento mais organizado e eficiente.
