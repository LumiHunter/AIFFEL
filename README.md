# [E-10] GAN(Generative Adversarial Network) 관련

결과물 3개의 파일을 함께 업로드합니다.

case 1: generator (SGD / learning rate e-5) | discriminator (Adam / learning rate 4e-4) | epoch 300
* loss가 빠르게 0으로 수렴, accuracy 진폭이 큼

case 2: generator (Adam / learning rate e-5) | discriminator (SGD / learning rate 4e-4) | epoch 300
* loss가 0~1 사이에서 비슷하다가 generator loss가 더 높아짐
 
case 3: generator (Adam / learning rate e-5) | discriminator (SGD / learning rate 3e-4) | epoch 400
* 
