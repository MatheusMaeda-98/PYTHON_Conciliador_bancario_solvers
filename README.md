# Conciliador_banc-rio_solvers
Este script em python ofere diversos tipos de solver para auxiliar a realização de conciliações bancárias.

**Usos dos scripts**
Este script foi desenvolvido para auxiliar casos em que o banco oferece um valor agrupado de recebimento apenas e que a equipe financeiro precisa realizar as conciliações de único pagamento para diferentes nfs pagos ou não. Também se aplica para o caso em que o cliente paga várias notas fiscais em um único pagamento.
Para otimizar seu uso recomenda-se que os inputs sejam formatado em excell pelo power query para que os valores analisados estejam separados por virgula.

O arquivo oferece 3 tipos de scripts, detalhado abaixo:

 - O primeiro script oferece uma solução de solver em força bruta, recomenda seu uso apenas para baixo quantidade de inputs a serem verificados.
 - O segundo script oferece uma solução mais robusta e dinâmica, caso ele não encontre uma solução exata, ela vai te retornar a mais próxima, seu processamento é mais rápida em relação ao primeiro script.
 - O terceiro script ofereçe uma solução de combinação de pagamento atrelado a nomes, encontra um combinação exata ou mais próximo ao objetivo. Esse script serve para efetuar pagamentos em budget curto no dia.
