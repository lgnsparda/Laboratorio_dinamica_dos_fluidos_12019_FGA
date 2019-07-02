Grupo 8:
- Thayná Cortes Pereira - 17/0063577
- Danilo Fernandes Duarte - 17/00085
- Leonardo da Silva Santos - 17/0038882

### 1.	Início:

#### 1.1 Tema: Perda de carga:
  Uma importante área de aplicação de mecânica dos fluidos na engenharia é o dimensionamento de dutos. O problema tende a envolver as seguintes considerações: dada a geometria material do duto, vazão e propriedades do fluido, qual é a queda de pressão associada aos efeitos viscosos?
Em função disso o estudo do fenômeno da perda de carga foi escolhido no intuito de se obter um maior entendimento dos efeitos de forças dissipativas em casos simples de escoamentos em dutos.

#### 1.2 Objetivos:
  Para tanto foi optado por realizar um estudo quantitativo da pressão a montante e jusante de um fluido escoando em um duto de pvc a uma vazão conhecida e a partir destes valores e das dimensões do sistema determinar grandezas relevantes associadas ao efeito de perda de carga. Nominalmente o coeficiente de Reynolds , para se determinar a linearidade do fluxo, o fator de atrito de Darcy e a perda total de carga e potência observada, além de se estudar os modos com que essas grandezas se relacionam.  

#### 1.3 Escopo:
    Para que as grandezas desejadas possam ser corretamente aferidas deverão ser medidas no equipamento de simulação de escoamentos hidráulicos a pressão a montante e a jusante do fluido a diferentes vazões controladas por um rotâmetro e ambas as grandezas registradas.
    Com esses dados será possível obter um valor para a perda de carga a partir da equação de Navier-Stokes com o qual poderá ser determinado o fator de atrito pela equação de Darcy–Weisbach e a potência dissipada na seção do duto observada e a devida propagação de erros.
    
#  Nota: 2,5


### 2.	Planejamento e Preparação:

#### 2.1 Teoria do experimento:
##### 2.1.1Escoamento laminar plenamente desenvolvido em dutos de seção circular:

  O escoamento interno é  todo escoamento que é contido ou con?nado por paredes. O exemplo mais direto deste é o escoamento em tubos e conduto onde ocorre a aparição de efeitos viscosos crescentes devido ao con?namento. Estes efeitos são oriundos das camadas limite existentes nas paredes que aumentam de espessura ao longo do escoamento, causando desaceleração do escoamento axial na região da parede e aceleração do escoamento axial na região central. Esta característica sustentará a incompressibilidade do escoamento.
  Todo escoamento interno apresenta perda de pressão. A uma distância “l” da entrada, as camadas limite se uni?cam, e os per?s de velocidade se ajustam até este ponto. A partir deste ponto, a velocidade não mais varia na direção axial, tornando-se apenas função da coordenada radial (No caso de tubos de seção circular). Esta condição é chamada de escoamento plenamente desenvolvido, onde o per?l de velocidade é constante na direção axial, bem como a tensão cisalhante nas paredes do tubo. Outra característica é o decaimento linear da pressão com a direção axial. Logo, chama-se L de comprimento de desenvolvimento, ou seja, o comprimento necessário para o escoamento atingir a condição de desenvolvimento pleno. A literatura traz correlações para L como função do número de Reynolds baseado no diâmetro do tubo

#### 2.1.2 Número de Reynolds
  O número de Reynolds consiste em uma grandeza adimensional usada no auxílio de previsões acerca de padrões do escoamento de um dado fluido em diferentes situações. A baixos números de Reynolds fluidos tendem a escoar de modo predominantemente laminar enquanto a números mais elevados turbulência surge como resultado de diferenças entre a direção do escoamento do fluido e a direção do vetor velocidade para um determinado ponto, formando vorticidades e outros fenômenos que utilizam-se de parte da energia do escoamento e são difíceis de prever por meios analíticos.
    Para dutos o número de reynolds pode ser obtido apartir da análise adimensional da equação de Navier Stokes, dada pela equação:
                      
 ![](https://lh4.googleusercontent.com/tSooxVNlbYS89JL_Jp7MpNR4vJZZjQ3Zr3X6LP5x2LKu2Uq3FjcG5xkKuw9Bdg10yS-7WJDi-XveJlFbdpvHR_pjbsx1i2SuS-nvKEA)
 
  Em que, Re é o número de Reynolds, "rho" a massa específica do fluido, u a velocidade do fluido,"my" sua viscosidade cinemática e D o diâmetro do duto
  Por meios experimentais, é possível observar, em dutos para que valores do número de Reynolds começa-se a observar rajadas de turbulência capazes de afetarem quais soluções são aplicáveis para um dado caso, razão pela qual será utilizado seu valor para determinar uma velocida para qual o escoamento será laminar, caso ao qual o experimento será limitado.

#### 2.1.3 Perda de carga - fator de atrito
  A perda de carga é indiferente para tubos que estejam inclinados ou na horizontal sendo ela, então, proporcional à tensão de cisalhamento na parede do tubo. Este fato pode ser concluído com base em cálculos matemáticos de perda de carga para tubos inclinados onde, em determinado momento, não se leva mais em consideração as diferenças de inclinação do tubo.
  
 <p align="center">
  <img width="460" height="300" src="https://lh3.googleusercontent.com/0N9cpZW0ojiYiLWugJFQk4XUWYhlUVtKX5hk4ra6Q_uml59-Lfz7jSA89QprseAkqtIeX1oPgsY9bi8OpxQ8bzyJjKFn4qsgv8NWrE4f">
</p>
  
  Pensando em um tubo inclinado (Figura 1) com uma área transversal constante cujo escoamento considera-se permanente incompressível , tem-se que a equação de escoamento permanente é dada por:

  ![](https://lh3.googleusercontent.com/nlJAGYtZLyQ1qJuS8FO-x1dClx8tcdW1QpCVMKcUIyzieOxTOKyvDE55rBiVSo6d90QycpSJtnRHV-EXYOQJh9qBlC_zQNHnpuVYJvo)
    
  Como o  formato de perfil velocidade nas duas seções são as mesmas , podemos retirar da equação que os termos 1 e 2 são equivalentes. Com isso a perda de carga pode ser escrita apenas em termos de queda de pressão e da variação de elevação:
  
  ![](https://lh3.googleusercontent.com/UaipyN5srX5EV1FZWGAKH5jXEQCcmNJElu-JSk4gjUviN9Kiho54PP7SV2_5XC9nAQllxxQVK50_LNjjvV6wK8qb6v0hP8BfL6D0bng)

#### 2.2 Procedimentos experimentais:

##### PREPARAÇÃO E SELAGEM HIDRÁULICA DO CIRCUITO:
- Encher o Reservatório (RA)com água até o nível máximo (50 mm do topo da caixa),com as seguintes Válvulas abertas:a deBloqueio(VB); a de Regulagem de Vazão(VRV) e a deBloqueio (VBS).

- Fechar, durante esta selagem hidráulica,todas as Válvulas de bloqueio instaladas no topo de cada Manômetro (MU);

-Antes de ligar a Bomba centrífuga (BC):Fechar completamente a Válvula de Regulagem de Vazão (VRV);Verificar se a Válvula gaveta (comporta) (VG)está completamente aberta. ATENÇÃO: Esta válvula (VG) nunca deve ficar completamente fechada. Pode ficar, no máximo, fechada pela metade, sob pena de rompimento na junção da mangueira do respectivo manômetro, ocasionando vazamento de água e fluido manométrico. Abrir as Válvulas de bloqueio VB1 (do Ramo 1) e as VB2 e VB3 (do Ramo 2).

-Com a Válvula VBS ainda aberta; ligar a Bomba centrífuga (BC)e abrir a Válvula VRV lentamente (manter vazão baixa, no máximo, em torno de 10 l/min) até que o circuito esteja “selado” hidraulicamente (sem bolhas de ar nas tubulações). 

- Em seguida fechar a Válvula (VBS) e fechar novamente as Válvulas (VRV), VB2 eVB3e abrir todas as Válvulas de topo dos Manômetros (MU) e verificar se todos os Manômetros estão com os fluidos manométricos equilibrados e que não tenha bolhas de ar nas mangueiras que ligam os mesmo aos seus respectivos acessórios. Se tiver bolhas, realizar procedimento, conforme treinamento, para eliminar estas bolhas.

##### PRÁTICA: OPERAÇÃO NO CIRCUITO:
  O objetivo é determinar o Fator de atrito (Fanning) real num Tubo reto de Dn=32 mm e, também, no de Dn=20, ambos com 100cm de comprimento entre as tomadas de pressão, para utilizar o Fator de atrito nos cálculos dos Comprimentos equivalentes da primeira parte(Ramo 1). Obs.:Considerar o Fator de atrito (Fanning) de um tubo de Dn=25 como sendo a interpolação dos dois mencionados anteriormente. Para tanto:
  
  - Para tanto, fechar a Válvula de bloqueio (VB1) e abrir a Válvula de bloqueio(VB2) do tubo de DN=32 mm.
  
  - Ligar a Bomba (BC) e abrir lentamente esta Válvula (VRV) e realizar medidas de vazão de 5 em 5 litros/min, registrando o h no respectivo manômetro.
  Obs.: realizar estas medidas com o aumento da vazão e, também, no período de diminuição da vazão até zero, a fim de verificar eventuais histereses nas leituras do manômetro.

  - Em seguida, fechar a VB2 e abrir a VB3 e realizar o mesmo procedimento para o tubo de DN=20 mm.

 #### Resultados esperados:
  Espera-se medir uma perda de pressão proporcional ao comprimento da seção medida e ao fator de atrito do duto de pvc.

### 3.	Execução:

