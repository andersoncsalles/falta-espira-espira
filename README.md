# falta-espira-espira
Apresentação do modelo para simulação de falta espira-espira para máquina de indução com rotor em gaiola.
---

## Motivação
Os motores elétricos são amplamente usados na indústria, com destaque para máquina de indução com o rotor em gaiola, por sua simplicidade e preço. Eles possibilitam aplicações como bombas hidráulicas, compressores de ar, movimento de esteiras entre outras. As falhas nas máquinas elétricas ocorrem no estator em 38% dos casos, indicando um problema recorrente. Como essas falhas tendem a evoluir com o tempo, a detecção precoce é crucial para minimizar danos ao núcleo do estator.

Um dos objetivos para indústria é a prestação contínua de todas as operações. Para atingir essa meta, é essencial entender as falhas no estator. Essas faltas podem impactar o funcionamento das máquinas elétricas, causando vibrações e aquecimento. Isso pode iniciar um ciclo potencialmente destrutivo. Nesse contexto detalharemos a falta espira-espira.

A imagem a seguir apresenta as faltas no estator.
<div align="center">

<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/imagens/faltas_estator.png" width="250" height="250">

</div>

---

### Projeto

Um dos pontos principais é que quando em falha as correntes de curto-circuito tendem a aumentar a degradação do isolamento devido ao sobreaquecimento provocado por pontos quentes, isto é, o curto-circuito continua evoluindo até que uma área maior do sistema de isolamento seja danificada e cause avarias mais severas, ao final, causando a degradação total da operação da máquina. Em geral, essas faltas não são perceptíveis sendo negligenciadas pelos dispositivos de proteção.

A capacidade de isolamento pode ser afetada por fatores ambientais e operacionais. Estes incluem temperaturas elevadas, desgaste do material isolante com o tempo, sobrecarga, efeito dos conversores, contaminação por produtos químicos e umidade.

A falta espira-espira, que ocorre quando as espiras de uma mesma bobina estão em curto. É possível observar na figura a seguir dois trechos distintos nas bobinas. O primeiro em que o curto foi de fato estabelecido e um segundo ainda saudável, apesar de sofrer ação da falta. 

<div align="center">
  
![espira=espira](https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/imagens/falta_espira-espira.png)

</div>


Esse projeto reproduz a falta espira-espira na máquina de indução com rotor em gaiola utilizando simulação computacional no Matlab/Simulink para identificar assinaturas do curto-circuito.


## Resultado
O resultado da simulação é apresentado na figura a seguir.A falta ocorre na metade da janela de tempo da simulação. 

<div align="center">

<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/imagens/resultado_simula%C3%A7%C3%A3o.png" width="500" height="350">

</div>

Mais informações sobre o modelo: [Modelo matemático](https://github.com/andersoncsalles/falta-espira-espira/tree/main/modelo)


