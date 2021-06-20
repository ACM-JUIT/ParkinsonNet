#  RNN (Recurrent Neural Network)

## Defination
A **Recurrent Neural Network (Sequence Models/RNN)** is a type of artificial neural network (that can process a sequence of inputs in Deep Learning) commonly used in speech recognization and natural language processing (NLP) .

## Uses of **RNN (Recurrent Neural Network)**
1. Auto completion of sentances (like in google).
2. The RNN is even used in Translation .
3. Named Entity Recognition : In which we give input as a sentence and in output the word are seperated between person , company , time etc. 
4. Whereas the RNN is also used  Sentimental Analysis . 

![image](https://user-images.githubusercontent.com/85950108/122661348-fd564d80-d1a6-11eb-8106-4f7e5b1dee65.png)

## Why ANN And CNN are not Used ?
Following are the reasons;
1. No fixed size of neurons in the layer.

   ![image](https://user-images.githubusercontent.com/85950108/122661491-87eb7c80-d1a8-11eb-89c4-fadd98577951.png)

2. Too much computation.( as **neural network** works on number and not on string and "One hot end     coding" is used. )

   ![image](https://user-images.githubusercontent.com/85950108/122661503-a3568780-d1a8-11eb-9d1b-b4642da44f5e.png)

3. Parameter are not shared as in **CNN**(convulation).

   ![image](https://user-images.githubusercontent.com/85950108/122661472-5bcffb80-d1a8-11eb-9379-a21c116ba0cb.png)


##  Named Entity Recognition
First we covert the word into vector form and then  input them into the  hidden neural layer (one by one ) . Once the network is trained it will return **Name** as 1 and **other word** as 0.

![image](https://user-images.githubusercontent.com/85950108/122661209-57eeaa00-d1a5-11eb-9011-013a94c3988d.png)

whereas the **Generic Represenation of RNN** is we have only one layer and we are in a loop where we are suppling the output of previous word as an input for second word. 

![image](https://user-images.githubusercontent.com/85950108/122661245-c7fd3000-d1a5-11eb-9350-4715229068be.png)

### Language Translator 
In this we write all the words first and then the translation is done whereas it as two parts where first is encoder where the input is given and decoder where we get the output.

![image](https://user-images.githubusercontent.com/85950108/122661654-304e1080-d1aa-11eb-8d7d-dc7f69832efa.png)
