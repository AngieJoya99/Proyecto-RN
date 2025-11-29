# Params 1

* 1 capa RNN de 64
* L2 = 0.001
* Dropout = 0.3
* Opt Adam LR = 0.00001
* EarlyStopping
* epocas = 200
* lote = 32
* sizeEmbedding = 164

## 1 | Submuestreo 80% = 7342

## 2 | Submuestreo 50% = 4589

## 3 | Submuestreo todas igual

## 4 | Neg igual a Neutro sin pesos

## 5 | Neg igual a Neutro con pesos

## 6 | Sin submuestreo con pesos

# Params 2

* Sin submuestreo con pesos
* 1 capa RNN de 64
* L2 = 0.001
* Dropout = 0.3
* Opt Adam LR = 0.00001
* EarlyStopping
* epocas = 200
* lote = 32
* sizeEmbedding = 164

## 7 | L2 = 0.0001

## 8 | L2 = 0.01

## 9 | 2 capa RNN de 32 -> 16

## 10 | 2 capa RNN de 32 -> 16 sin dropout

## 11 | 2 capa RNN de 32 -> 16 con dropout y recurrent dropout 0.3

## 12 | 2 capa RNN de 32 -> 16 con recurrent dropout 0.3

## 13 | 2 capa RNN de 32 -> 16 con dropout=0.3 y recurrent dropout=0

# Params 3

* Sin submuestreo con pesos
* 2 capa RNN de 32 -> 16
* L2 = 0.001
* Dropout = 0.3 dentro de las capas secuenciales
* Opt Adam LR = 0.00001
* EarlyStopping
* epocas = 200
* lote = 32
* sizeEmbedding = 164