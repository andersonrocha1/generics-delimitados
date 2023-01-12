* Exemplos no repositório para possíveis consultas

    . princípio get/put);
    - **Covariância**;
    - **Contravariância**;

* Problema 2 (princípio get/put)
Vamos fazer um método que copia os elementos de uma lista para uma
outra lista que pode ser mais genérica que a primeira.
public class Program {

	public static void main(String[] args) {
List<Integer> myInts = Arrays.asList(1, 2, 3, 4);
List<Double> myDoubles = Arrays.asList(3.14, 6.28);
List<Object> myObjs = new ArrayList<Object>();
copy(myInts, myObjs);
copy(myDoubles, myObjs);

    }
 
}

https://stackoverflow.com/questions/1368166/what-is-a-difference-between-super-e-and-extends-e


- Java wrapper types (próximos exemplos)

image.png