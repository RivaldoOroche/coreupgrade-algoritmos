# coreupgrade-algoritmos
Soluciones a los retos de algoritmos del CoreUpgrade 2018


## 1. ¿Cual es la complejidad de tiempo de la función example()?
```c++
int example(int n)
{
  int count = 0;
  for (int i = n; i > 0; i /= 2)
     for (int j = 0; j < i; j++)
        count += 1;
  return count;
}
```
Respuesta:
 Este algoritmo se ejecuta en un tiempo:  O(n log n)
 
 
## 2. ¿Cual es la complejidad de tiempo de la función example2()?

```c++
void example2(int n, int arr[])
{
    int i = 0, j = 0;
    for(; i < n; ++i)
        while(j < n && arr[i] < arr[j])
            j++;
}
```
Respuesta:
 Este algoritmo se ejecuta en un tiempo: O(n^2)


## 3. ¿Cuál es la mejor complejidad de tiempo de bubbleSort?
 El mejor tiempo de complejidad es: O(n)
