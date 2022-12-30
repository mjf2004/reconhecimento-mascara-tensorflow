# reconhecimento-mascara-tensorflow
Projeto de dissertação iniciado em 2020


# Resultados

As inferências foram realizadas em cinco imagens. Três fora do dataset de teste e duas do dataset de test. Cada imagem teve um critério analisado. Em cada modelo foi retirado os VP (verdadeiro positivo), FP (falso positivo) e FN (falso negativo). As imagens de exemplo pode ser visto abaixo e em seguida os resultados.
![image](https://user-images.githubusercontent.com/71648038/210080688-db595d0b-37ac-4934-9cfe-a362463c6735.png)

resultado base 70-30

![image](https://user-images.githubusercontent.com/71648038/210081407-c9b8b408-fc6a-4893-bcab-2181852a2a04.png)

resultado base 80-20

![image](https://user-images.githubusercontent.com/71648038/210081475-49111616-558b-4ce6-a67c-0d34c77f6087.png)

resultado base 90-10

![image](https://user-images.githubusercontent.com/71648038/210081545-629d1fac-85be-486a-b3d7-f16af42b1ed4.png)

Exemplo de inferência com o SSD Mobilenet V2 FPNLite. Caixa de cor verde "com_mascara" e amarelo "sem_mascara".

![image](https://user-images.githubusercontent.com/71648038/210081764-ca00cd7b-88fc-4486-8cf2-8d2e193f4357.png)

# Tempo de treinamento de cada modelo.
Faster R-CNN inception-resnet-v2 na base 70-30 perdeu acesso a GPU durante o treinamento.
![image](https://user-images.githubusercontent.com/71648038/210082455-92d73c81-1afa-4be2-b93c-0ebd0c22e644.png)

# Outros resultados. FPS e tamanho do arquivo da rede neural com os pesos.

![image](https://user-images.githubusercontent.com/71648038/210082222-7de6ee58-c2a6-4f67-93d9-eb55e3e05efb.png)

