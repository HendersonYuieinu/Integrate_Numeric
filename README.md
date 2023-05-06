# Integrate_Numeric
Projeto feito com o professor de fisica Jaime e Wilson do Instituto Federal, feito para resolução de problemas matematicos usando Integral.
Sendo usado 3 metodos de resolução: metodo de retangulos; metodo dos trapezios; regra de simpson 1/3.

Foi usado o IDE de python do Jupyter, do pacote Anaconda. Usei da biblioteca matemática NumPy e do MatPlotLib para a geração dos gráficos no Script
O codigo calcula a área de funções geradas no codigo usando de Três metodos citados.

Metodo dos Retangulos:
  Primeiro tipo de calculo usado no script.
  ele divide função em diversos retangulos, cada retangulo tem a sua altura no tamanho do Y correspondente ao retangulo da função, e a baseé super fina com a expessura
  bem proxima do zero, o codigo faz uma somatoria da area de todos os retangulos para chegar no valor mais aproximado do valor da area da função.
  Aproximado pois caso a função tenha curvas, o retangulo por ser uma forma reta, por consequencia terá perdas de alguns espaços
 

Metodo dos Trapezios:
  Segundo tipo de calculo usado no script.
  Ele cria varios trapezios para cobrir a area da função, tendo as duas alturas, a altura correspondente a função e a altura do segundo valor em X, com uma base tambem
  o mais proximo de zero, para ter a menor perda de area, e assim fazendo um somatorio da area de todos os trapezios.
  Esse metodo se mostra mais eficiente que o dos retangulos, pois como é um trapezio, ele acaba se dando com com curvas por ter uma estrutura mais 'curvada' e em curvas   retas, acaba se tornando mais eficiente e praticamente nao tendo perdas na area e assim chegando no valor ainda mais aproximado do valor exato da função.
  
 Metodo de Simpson 1/3:
  O terceiro metodo do script.
  Ele é um tipo de calculo que usa de estruturas polinomiais para fazer o calculo da função, cria uma variavel que recebe o ponto medio do ponto inicial e final e
  então ele realiza um calculo para criar o polinomio, soma o ponto Y no ponto inicial com o ponto Y do ponto medio, multiplicado por 4 e somando pelo ponto Y
  do ponto final e então multiplica essa soma pelo valor do ponto medio dividido por três.
  Ele acaba se tornando bem mais eficiente que os outros dois metodos por trazer resultados exatos em funções tanto afim, de segundo grau e algumas trigonometricas. 
  
