#  Deep Learning HSE осень 2021


### Полезные ресурсы
* Если вы хотите скачать из репозитория конкретную папку или файл, просто вставьте ссылку на неё в [сервис для скачки](https://minhaskamal.github.io/DownGit/#/home?url=). 

### Домашние задания
| №      | Название        | Задание                                  | Где задание лежит  | Срок     |
| :---:  |:-------------:  | :--------------------------------------  | :----------------: | :------: |
| 1      | Дообучить сеть  | Обучить первую NN на PyTorch             | 01_Week            | 17.11.21 |
| 2      | Град спуск (ШАД)| Реализовать град спуск                   | 02_week            | 17.11.21 |
| 3      | Our first CNN   | Обучить первую CNN                       | 06_week            | 17.11.21 |
| 4      | Autoencoders    | Обучить Conv Autoencoder + interpolation | 09_week            | 24.11.21 |
| 5      | Conditional GAN | Обучить  CGAN + interpolation            | 10_week            | 01.12.21 |

[Таблица](https://docs.google.com/spreadsheets/d/1jjvWV7kHw88akCuMFbbAcNsnrUdGH530hUTAhhm182w/edit#gid=0) с результатами сдачи

### Программа курса + ссылки на хорошие материалы по теме
01. Введение в нейросети
02. Адаптивные варианты градиентного спуска
   - [Почему momentum работает](https://distill.pub/2017/momentum/)
   - [Bias correction in Adam](https://www.youtube.com/watch?v=-0ZMU-gnm2g)
03. Алгоритм обратного распространения ошибки
04. Инструменты в Python для обучения нейронных сетей
   - [Dataloader/Dateset в PyTorch](https://discuss.pytorch.org/t/making-iterable-objects-using-torch-utils-data-dataloader/16681/2)
   - [weight initialization](https://www.deeplearningwizard.com/deep_learning/boosting_models_pytorch/weight_initialization_activation_functions/)
05. Батч-нормализация. Инициализация. Эвристики для обучения сетей
   - [BatchNorm explained](https://towardsdatascience.com/batch-normalization-in-3-levels-of-understanding-14c2da90a338)
   - [custom weight decay](https://raberrytv.wordpress.com/2017/10/29/pytorch-weight-decay-made-easy/)
   - [inverted dropout](https://www.coursera.org/lecture/deep-neural-network/dropout-regularization-eM33A)
06. Свёрточные нейронные сети
   - [Convolution in CNN explained](https://www.youtube.com/watch?v=KTB_OFoAQcc)
07. Inception. Resnet. Transfer learning. Metric Learning
   - [ResNet](https://towardsdatascience.com/understanding-and-visualizing-resnets-442284831be8)
   - [1x1 convolution](https://stats.stackexchange.com/questions/194142/what-does-1x1-convolution-mean-in-a-neural-network)
08. Интерпретация свёрточных нейронных сетей. Перенос стиля
   - [что выучивает сеть](https://towardsdatascience.com/understanding-your-convolution-network-with-visualizations-a4883441533b)
   - [перенос стиля](https://towardsdatascience.com/neural-style-transfer-applications-data-augmentation-43d1dc1aeecc) 
   - [Unsampling: Unpooling and Transpose Convolution](https://medium.com/jun-devpblog/dl-12-unsampling-unpooling-and-transpose-convolution-831dc53687ce)
09. Autoencoders. Manifold learning
   - [Что такое manifold. Интуиция, стоящая за этим понятием](https://bjlkeng.github.io/posts/manifolds/)
   - [Manifold learning и скрытые переменные](https://habr.com/ru/post/331500/)
   - [Manifold learning on MNIST -> 2D-representation learned by an autoencoder](https://www.kaggle.com/apapiu/manifold-learning-and-autoencoders/notebook)
10. Генеративные нейронные сети
   - [GAN explained](https://www.coursera.org/learn/build-basic-generative-adversarial-networks-gans/lecture/gIAJ0/putting-it-all-together)
   - [Deconvolution issue. Checkerboard](https://distill.pub/2016/deconv-checkerboard/)
   - [VAE ultimate guide & intuition](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)
