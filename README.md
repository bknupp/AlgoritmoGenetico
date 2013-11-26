AlgoritmoGenetico
=================

Exemplo de um AG básico. Código comentado para facilitar no estudo. Disciplina: Inteligência Artificial

Os cromossomas são selecionados de uma população para serem pais de um cruzamento. O problema é como selecionar esses cromossomas. De acordo com a teoria da evolução de Darwin, o melhor sobrevive para criar a descendência. Há muitos métodos para selecionar o melhor cromossoma.

Elitismo = Quando criamos uma nova população por cruzamento e mutação, nós temos uma grande chance de perder os melhores cromossomas.
Elitismo é o nome do método que primeiro copia os melhores cromossomas (or os poucos melhores cromossomas) para a nova população. O resto da população é construída das formas descritas acima. Elitismo pode aumentar rapidamente o desempenho do AG, porque previne a perda da melhor solução já encontrada.

* Taxa de Cruzamento
A taxa de cruzamento deve em geral ser alta, cerca de 80%-95%. Entretanto, alguns resultados mostram que para alguns tipos de problemas, uma taxa de cruzamento de cerca de 60% é o melhor.

* Taxa de Mutação
Por outro lado, a taxa de mutação deve ser muito baixa. As melhores taxas parecem estar na faixa de 0.5%-1%.

* Tamanho da População
Pode ser um pouco surpreendente que populações de tamanho muito grande, normalmente não aumentam o desempenho do AG (no sentido de aumentar a velocidade com que são encontradas as soluções). Um bom tamanho para a população é cerca de 20-30, entretanto às vezes tamanhos de 50-100 são relatados como os melhores. Alguns autores também mostram que o melhor tamanho da população depende do tamanho da série codificada (cromossomas). Isto significa que se você tem cromossomas com 32 bits, a população deve ser maior do que se você tivesse cromossomos com 16 bits.

* Seleção
A Seleção através da Roleta pode ser usada, mas mas às vezes a Seleção por Classificação pode ser melhor. Existem também alguns métodos mais sofisticados que mudam os parâmetros de seleção durante a execução do AG. Basicamente, eles tem comportamento similar a tempero falsificado. Elitismo deve ser usado se você não tem outro método para preservar a melhor solução. 

* Codificação
A codificação depende do problema e também do tamanho das instâncias do problema. 

* Tipos de Cruzamento e Mutação
Os operadores dependem da codificação e do problema
