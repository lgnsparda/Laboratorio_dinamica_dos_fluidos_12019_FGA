Grupo 6:
- Vitor Rossi - 14/0066632
- Blenda Rodrigues - 15/0119551
- Giulliano Cezar - 13/0027260

### 1.	Início:

##### Integrantes
  - Vitor Rossi - 14/0066632
  - Blenda Rodrigues - 15/0119551
  - Giulliano Cezar - 13/0027260

##### Tema escolhido
  Coeficiente de descarga

##### Objetivo do experimento
   Determinar experimentalmente o coeficiente de descarga (Cd) para ambos os medidores de vazão: um tubo de Venturi e uma placa de orifício.

##### Escopo do experimento
   Serão coletados experimentalmente dados das vazões dos sistemas de medição tubo de Venturi e placa de orifício para 10 medições diferentes com o auxílio de um rotâmetro. Em paralelo a isso, serão calculadas as vazões teóricas para cada medição através da equação de bernoulli e equação da continuidade. Os coeficientes de descarga, tanto o do tubo de venturi como o da placa de orifício, serão determinados relacionando as vazões experimentais e teóricas, visualmente representados pelo levantamento da curva da vazão experimental pela vazão teórica.
   

### 2.	Planejamento e Preparação:

#### Identificação do grupo

  - Vitor Rossi - 14/0066632
  - Blenda Rodrigues - 15/0119551
  - Giulliano Cezar - 13/0027260

#### Teoria do experimento

Coeficiente de descarga é um importante conceito na engenharia em aplicações de bocais ou tubos com alguma constrição e tem como principal objetivo estabelecer uma correção para uma medida. O coeficiente de descarga é definido como a razão entre a taxa de vazão mássica experimental pela taxa de vazão mássica teórica. Nesse experimento, serão determinados os coeficientes de descarga para um tubo de venturi e para uma placa de orifício, dois meios vastamente utilizados na indústria para medição de fluxo de massa.

Em ambos o tubo de venturi e a placa de orifício, a medição do fluxo é determinada a partir de uma diferença de pressão. O tubo de venturi possui uma garganta cilíndrica entre uma seção convergente e outra divergente e a placa de orifício é um disco com um orifício, geralmente concêntrico, e é instalada em uma tubulação. Ambos têm como objetivo acelerar o fluido e temporariamente baixar sua pressão.

A precisão da medição são dependentes principalmente de variações na pressão, temperatura, composição do fluido, densidade, centragem da placa, interferência da precisão na execução do furo da placa e precisão instrumental. As placas de orifício são de fácil construção e de custo relativamente baixo, quando comparadas com o tubo de venturi, que é de construção mais complexa e custo relativo maior, mas os dois sistemas são simples, robustos e confiáveis.

A vazão teórica pode ser obtida através de uma combinação da equação de Bernoulli com a equação da continuidade, da seguinte forma:

Equação de Bernoulli:

<img src="https://latex.codecogs.com/gif.latex?\frac{P_{1}}{\rho}&space;&plus;&space;\frac{1}{2}V_{1}^{2}&space;&plus;&space;gZ_{1}&space;=&space;\frac{P_{2}}{\rho}&space;&plus;&space;\frac{1}{2}V_{2}^{2}&space;&plus;&space;gZ_{2}" title="\frac{P_{1}}{\rho} + \frac{1}{2}V_{1}^{2} + gZ_{1} = \frac{P_{2}}{\rho} + \frac{1}{2}V_{2}^{2} + gZ_{2}" />

Como as tubulações utilizadas são horizontais,  <img src="https://latex.codecogs.com/gif.latex?Z_{1}&space;=&space;Z_{2}" title="Z_{1} = Z_{2}" /> , então os termos dependentes de Z se cancelam

Equação da continuidade:

<img src="https://latex.codecogs.com/gif.latex?\sum&space;\rho_{in}A_{in}V_{in}&space;=&space;\sum&space;\rho_{out}&space;A_{out}V_{out}" title="\sum \rho_{in}A_{in}V_{in} = \sum \rho_{out} A_{out}V_{out}" />

Como há apenas uma entrada e uma saínda de cada tubulação, a equação da continuidade se torna:

<img src="https://latex.codecogs.com/gif.latex?\rho_{1}A_{1}V_{1}&space;=&space;\rho_{2}&space;A_{2}V_{2}" title="\rho_{1}A_{1}V_{1} = \rho_{2} A_{2}V_{2}" />

O fluido, água, é considerado incompressível, então <img src="https://latex.codecogs.com/gif.latex?\rho_{1}&space;=&space;\rho_{2}&space;=&space;\rho" title="\rho_{1} = \rho_{2} = \rho" />

Isolando a velocidade no ponto 2, temos:

<img src="https://latex.codecogs.com/gif.latex?V_{2}&space;=&space;\frac{A_{1}V_{1}}{A_{2}}" title="V_{2} = \frac{A_{1}V_{1}}{A_{2}}" />

Substituindo V2 na equação de Bernoulli, temos:

<img src="https://latex.codecogs.com/gif.latex?\frac{P_{1}}{\rho}&space;&plus;&space;\frac{1}{2}V_{1}^{2}&space;=&space;\frac{P_{2}}{\rho}&space;&plus;&space;\frac{1}{2}\frac{A_{1}^2V_{1}^2}{A_{2}^2}" title="\frac{P_{1}}{\rho} + \frac{1}{2}V_{1}^{2} = \frac{P_{2}}{\rho} + \frac{1}{2}\frac{A_{1}^2V_{1}^2}{A_{2}^2}" />

Isolando V1:

<img src="https://latex.codecogs.com/gif.latex?V_{1}&space;=&space;\frac{1}{\sqrt{\frac{A_{1}^2}{A_{2}^2}&space;-&space;1}}\sqrt{\frac{2(P_1&space;-&space;P_2)}{\rho}}&space;\newline" title="V_{1} = \frac{1}{\sqrt{\frac{A_{1}^2}{A_{2}^2} - 1}}\sqrt{\frac{2(P_1 - P_2)}{\rho}} \newline" />

Logo, a vazão volumétrica teórica é dada por:

<img src="https://latex.codecogs.com/gif.latex?Q_{teorica}&space;=&space;V_{1}A_{1}&space;=&space;\frac{A_{1}}{\sqrt{\frac{A_{1}^2}{A_{2}^2}&space;-&space;1}}\sqrt{\frac{2(P_1&space;-&space;P_2)}{\rho}}&space;\newline" title="Q_{teorica} = V_{1}A_{1} = \frac{A_{1}}{\sqrt{\frac{A_{1}^2}{A_{2}^2} - 1}}\sqrt{\frac{2(P_1 - P_2)}{\rho}} \newline" />

Comparando a vazão teórica com a vazão experimental, obtida a partir das medições, temos o fator de correção Cd, chamado de coeficiente de descarga:

<img src="https://latex.codecogs.com/gif.latex?Q_{experimental}&space;=&space;C_{d}Q_{teorica}" title="Q_{experimental} = C_{d}Q_{teorica}" />


#### Procedimentos experimentais:

##### Estimativa do tempo necessário para a montagem e execução do procedimento

O experimento será feito em uma bancada hidráulica didática constituída de tubulações do Laboratório de Termociências da FGA. Estima-se que o tempo de preparação e de execução do procedimento leve por volta de uma hora.

##### Membro do grupo responsável pelo procedimento de montagem e execução

Todos os membros estarão presentes na montagem e execução do experimento

##### Cronograma estimado para a montagem e realização do experimento completo

- Conectar um manômetro de tubo em U na tubulação do tubo de venturi e outro manômetro de tubo em U na tubulação com a placa de orifício para fazer as leituras de pressão
- Abrir a válvula da bancada que vai liberar o escoamento para as duas tubulações utilizadas
- Retirar o ar do tubo para evitar bolhas de ar no escoamento 
- Esperar até o fluxo de água se estabilizar para considerar um escoamento de regime permanente
- Ler a medição de vazão no rotâmetro
- Obter as medidas de pressão nos manômetros para 10 vazões diferentes

#### Determinação dos dados a serem medidos e/ou calculados

Serão coletados experimentalmente dados das vazões dos sistemas de medição tubo de Venturi e placa de orifício para 10 medições diferentes com o auxílio de um rotâmetro. Em paralelo a isso, serão calculadas as vazões teóricas para cada medição através da equação de bernoulli e equação da continuidade. Os coeficientes de descarga, tanto o do tubo de venturi como o da placa de orifício, serão determinados relacionando as vazões experimentais e teóricas, visualmente representados pelo levantamento da curva da vazão experimental pela vazão teórica.

#### Resultados esperados

Para a placa de orifício é esperado um coeficiente de descarga entre 0,3 e 0,6.

Para o tubo de venturi é esperado um coeficiente de descarga entre 0.980 e 0,995.

##### Referência bibliográfica

WHITE, F, Mecanica dos Fluidos, McGrawHill, RJ, 1991.



### 3.	Execução:

#### Integrantes do grupo
  - Vitor Rossi - 14/0066632
  - Blenda Rodrigues - 15/0119551
  - Giulliano Cezar - 13/0027260
  
#### Divisão de tarefas

 Como previsto na etapa 02, não houve a necessidade de uma divisão de tarefas porque todos os membros do grupo acompanharam todos os procedimentos do experimento. Por se tratar de um teste de bancada, onde a bancada já estava montada, todos os integrantes puderam verificar as medições e entrar em um consenso sobre as medições.
 
#### Descrição dos procedimentos realizados

  - Por causa de um vazamento na tubulação com a placa de orifício, não foi possível fazer as medições nessa tubulação. Apesar disso, nos foram fornecidos dados de duas medições nessa tubulação, que estão organizados na tabela 2.
  - Como o experimento foi feito em uma bancada hidráulica didática do Laboratório de Termociências da FGA, foi preciso apenas: 
    1) Verificar a conexão do manômetro de tubo em U na tubulação do tubo de venturi para fazer as leituras de pressão; 
    2) Abrir a válvula da bancada para liberar o escoamento para a tubulação utilizada; 
    3) Esperar até o fluxo de água se estabilizar para considerar um escoamento de regime permanente; 
    4) Ler a medição de vazão no rotâmetro; 
    5) Ler as medidas de pressão no manômetro 
    6) Repetir os passos v e vi para uma vazão diferente
  - No planejamento, foi dito que faríamos as medições de pressão para 10 vazões diferentes. Por restrições do laboratório, foram feitas apenas duas. Como o objetivo desse experimento é determinar o coeficiente de descarga (Cd) para ambos os medidores de vazão: um tubo de Venturi e uma placa de orifício, essas medições obtidas são suficientes.


  - Dados medidos:

    Tabela 1. Dados das medições para o tubo de venturi

    |Medição|Vazão Rotâmetro (LPH)|P1 (mmHg)|P2 (mmHg)|P1 - P2 (mmHg)|
    |-|-|-|-|-|
    |1|6900|200|130|70|
    |2|3300|173|157|16|

    Tabela 2. Dados das medições para a placa de orifício

    |Medição|Vazão Rotâmetro (LPH)|P1 (mmHg)|P2 (mmHg)|P1 - P2 (mmHg)|
    |-|-|-|-|-|
    |1|6500|216|132|84|
    |2|2900|177|153|24|


  - Fotos do experimento montado e medições para o tubo de venturi:

    Figura 1. Bancada hidráulica didática do Laboratório de Termociências da FGA

    ![bancada](https://github.com/Gezards/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_6/bancada.jpg)

    Figura 2. Manômetro em tubo U - Medição 1

    ![](https://github.com/Gezards/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_6/pressao1.jpg) 

    Figura 3. Rotâmetro - Medição 1

    ![](https://github.com/Gezards/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_6/rotametro1.jpg.jpg)

    Figura 4. Manômetro em tubo U - Medição 2

    ![](https://github.com/Gezards/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_6/press%C3%A3o2.jpg)


    Figura 5. Rotâmetro - Medição 2

    ![](https://github.com/Gezards/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_6/rotametro2.jpg) 

### 4.	Análise e conclusão:
