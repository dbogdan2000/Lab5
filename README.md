# Lab5

В пятой лабораторной работе используется нейросеть VGG16, с обученным классификатором в третьей работе, обучаемая на данных, к которым применяются параметры аугментации, полученные из четвёртой работы.

BATCH_SIZE = 8

STEP DECAY:
epochs_drop = 10.0
drop = 0.5

lr = 8e-11:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr1.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr1:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr1:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr1:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr1:Val_Loss.png)


lr = 8e-10:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr2.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr2:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr2:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr2:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SD/lr2:Val_Loss.png)


EXPONENTIAL DECAY:
k = 0.1

lr = 8e-11:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr1.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr1:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr1:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr1:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr1:Val_Loss.png)

lr = 8e-10:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr2.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr2:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr2:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr2:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/ED/lr2:Val_Loss.png)

STEP DECAY WITH WARMUP:
drop = 0.5
epochs_drop = 10.0

lr = 8e-11:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr1.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr1:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr1:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr1:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr1:Val_Loss.png)

lr = 8e-10:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr2.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr2:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr2:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr2:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/SDWW/lr2:Val_Loss.png)

EXPONENTIAL DECAY WITH WARMUP:
k = 0.1

lr = 8e-11:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr1.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr1:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr1:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr1:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr1:Val_Loss.png)

lr = 8e-10:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr2.png)

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr2:Acc.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr2:Val_Acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr2:Loss.png)

![Image alt](https://github.com/dbogdan2000/Lab5/blob/master/EDWW/lr2:Val_Loss.png)
