# Crowd-Counting

Crowd counting is a technique used to estimate the number of people in an image at a particular instance.
Accurate and quick estimation of crowd counts is a challenging yet meaningful task which has a wide
range of applications in diverse fields. A CNN-based crowd counting approach which utilizes the first 13
layers of pre-trained VGG-16 model and dilated convolutional layers to generate quality density maps is
proposed. The dilated layers allow for larger receptive fields without increasing the amount of
computation. In addition, a federated learning-based approach involving the federated averaging algorithm
is adopted to decentralize the training process, reduce the time taken and preserve privacy. The problem of
domain-adaptation in crowd counting is also addressed by training a model using the abundant labelled
data available in the source domain and transferring the parameters learnt to a target domain with relatively
fewer labelled data using neuron linear transformation, thereby minimizing the domain gap and improving
performance.


Research Paper Citation:
Senthilkumar, R., Ritika, S., Manikandan, M., Shyam, B. (2022). Crowd Counting Using Federated Learning and Domain Adaptation. In: Badica, C., Paprzycki, M., Kharb, L., Chahal, D. (eds) Information, Communication and Computing Technology. ICICCT 2022. Communications in Computer and Information Science, vol 1670. Springer, Cham. 
https://doi.org/10.1007/978-3-031-20977-2_8
