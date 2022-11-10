# Trabalho-AV2-Estrutura-de-Dados-em-C

## Conhecendo os 4 metodos

  **Bubble Sort**: Consiste em percorrer um vetor diversas vezes comparando uma posição do vetor com a próxima, invertendo a posição caso x+1 seja maior.
  
  ![image](https://user-images.githubusercontent.com/101484912/200907973-f5b14011-5d8a-4e99-807f-f585805b99ab.png)
  
  **Merge Sort**: Consite em dividir um vetor e dividir os vetores subsequentes desse recursivamente até que todos os subvetores tenham um índice só. A partir desse
    momento os subvetores vão se fundindo de forma ordenada até formarem um unico vetor.
    
   ![image](https://user-images.githubusercontent.com/101484912/200910657-59a9f5ec-0ddd-4941-9744-22390c4fb736.png)
   
   **Quick Sort**: Primeiro escolhe-se um pivô (elemento aletório do vetor), a partir desse pivo, são selecionados à esquerda os elementos menores que ele, e a direita
   os maiores. Um novo pivô é escolhido e esse movimento é repetido até que sobrem duplas de números que serão invertidas se não estiverem na ordem desejada ou numeros
   sozinhos.
   
   ![image](https://user-images.githubusercontent.com/101484912/200914917-c3686411-9fb1-41f0-8957-047eda0a18dc.png)

   **Heap Sort**:
   
   

### Comparção entre 4 métodos de ordenação
  
  **Estabilidade**: Se da por estável um algoritmo que preserva a ordem (alfabética/lexicográfica) dos elementos das chaves.

   *exemplo-> 3[a], 2[b], 2[c], 1[d] -> retornará caso estável -> 1[d], 2[b], 2[c], 3[a] -> caso contrário -> 1[d], 2[c], 2[b], 3[a]*

   ![image](https://user-images.githubusercontent.com/101484912/200865446-1f1b934d-07e7-4205-89f2-4dbe5f0d049f.png)
                                              
  **Complexidade**: Se da pela solução da equação de recorrência de um algoritmo.
  
   *exemplo - > T(n)=2T(n/2)+Θ(n) -> após resolver a equação do merge sort - > T(n)=O(n * log n)*
  
   ![image](https://user-images.githubusercontent.com/101484912/200876614-0e9c79f1-0ef0-4c72-8305-34bad13a0258.png)
   
   *apesar de alguns terem a mesma complexidade computacional, isto não quer dizer que todos executem ao mesmo tempo para a mesma instância*
       
   ![image](https://user-images.githubusercontent.com/101484912/200877094-1eba05d8-28e4-4234-b21a-8208ef82c604.png)
   
   
### Considerações finais
 
     Método Bolha é o menos recomendado para grandes quantidades de dados.
     QuickSort é o mais recomendado entre os algoritmos que utilizam comparação
     QuickSort não necessita de alocação extra de memória por ser in-place, ou seja, sua ordenação ocorre no próprio vetor
   
