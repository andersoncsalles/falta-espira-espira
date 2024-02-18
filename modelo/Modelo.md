# Modelagem falta-espira-espira
---

## Modelo
Visualmente o modelo generalizado, falta em qualquer fase, pode ser visto como a imagem abaixo:

<div align="center">
<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/modelo/imagens_modelo/modelo-generalizada.png" width="304" height="269">
</div>

O conjunto de espiras total onde o curto é estabelecido é modelado como uma resistência em série com uma indutância. Então, quando o curto acontece é necessário calcular a componente associada a resistência e a componente relacionada a indutância. 

A resistência é simples, pode ser calculada como:

$R_a = \dfrac{na}{n} \cdot R_{s}$ 

$R_b = \dfrac{nb}{n} \cdot R_{s}$

$R_c = \dfrac{nc}{n} \cdot R_{s}$

E da mesma forma podemos generalizar para as  resistências das outras fases. 

O efeito das componentes de indutância é melhor visualizado pelas matrizes do modelo da máquina. 

Matriz de indutância:

<div align="center">
<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/modelo/imagens_modelo/matriz_indutancia_estator.PNG" width="417" height="216">
</div>

Matriz de indutância mútua entre o estator e o rotor:

<div align="center">
<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/modelo/imagens_modelo/matriz_indutancia_mutua_estator_rotor.PNG" width="649" height="307">
</div>

Derivada da matriz de indutância mútua  entre o estator e o rotor:

<div align="center">
<img src="https://raw.githubusercontent.com/andersoncsalles/falta-espira-espira/main/modelo/imagens_modelo/derivada_da_matriz_de_indutancia_mutua_estator_rotor.PNG" width="717" height="291">
</div>
