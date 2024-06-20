# Unity-no-cena

Contexto: A cena mostra um astronauta que após desembarcar em um novo planeta é atacado por um fantasma que atira tiros de plasmas

O primeiro ato para a criação da cena foi um game object "plane" para ser o chão
nesse chão foi colocado uma textura de chão lunar,importada do asset:
"Lunar Landscape 3D"
![Captura de tela 2024-06-20 181220](https://github.com/LucasSoaresdeAraujo/Unity--cena/assets/161390682/3f8a2750-52d1-40c5-9d5e-221d0bc12909)



Ainda aproveitando do Asset, adicionei um game object "Cube" e coloquei nele textura de rochas
Além de adicionar mais um Game Object "Plane", posicionei um pouco acima do chão e adicionei uma textura de névoa
adicionei mais um game object Cube na região central e adicionei uma textura de rocha diferente


Depois o passo seguinte foi a adição do Asset "Stylized Astronaut",um modelo de um pequeno astronauta
alterei sua largura e escala para que ficasse em um bom tamanho

Após isso foi adicionado o asset "Ghost character Free"
Adicionei uma textura rosa do asset e uma animação em que o personagem tem uma pequena movimentação,não chegando a se mexer muito
e coloquei o fantasminha fornecido frente ao astronauta


Depois disso configurei a altura e escala de uma linha volumétrica do asset "Volumetric Lines"
posicionei ele dentro do fantasma para dar a impressão que o fantasma o disparou
Adicionei o elemento "Colisão" no astronauta e no laser,o que fez com que ao executar a cena,o astronauta fosse empurrado para trás após o laser a linha volumétrica o atingir

Por fim adicionei o Asset 
para ser um elemento do cenário sendo a nave do astronauta

