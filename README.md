# ejercicio
package calculadora;


public class Calculadora {
    int n1=2;
    int n2=3;
    
    int sumar(){
        return n1+n2;
    }
    int restar(){
    return n1+n2;
    
    }
    int multiplicar(){
    return n1+n2;
    
    }
    int dividir(){
    return n1+n2;
    
    }
    
    
    
    public static void main(String[] args) {
       Calculadora objeto1=new Calculadora();
        System.out.println("la suma es "+ objeto1.sumar());
        System.out.println("la resta es "+ objeto1.restar());
        System.out.println("la multiplicacion es "+ objeto1.multiplicar());
        System.out.println("la division es "+ objeto1.dividir());
    
    }
    
}
