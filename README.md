# ejercicio
package calculadora;

import java.util.Scanner;


public class Calculadora {
    int n1;
    int n2;
    int sumar(){
        Scanner leer=new Scanner(System.in);
        System.out.println("ingrese numero 1");
        n1=leer.nextInt();
        System.out.println("ingrese numero 2");
        n2=leer.nextInt();

        return n1+n2;
        
    }
    int restar(){
        
    return n1-n2;
    
    }
    int multiplicar(){
       
    return n1*n2;
    
    }
    int dividir(){
        
    return n1/n2;
    
    }
    
    
    
    public static void main(String[] args) {
       Calculadora objeto1=new Calculadora();
        System.out.println("la suma es "+ objeto1.sumar());
        System.out.println("la resta es "+ objeto1.restar());
        System.out.println("la multiplicacion es "+ objeto1.multiplicar());
        System.out.println("la division es "+ objeto1.dividir());
    
    }
    
}


package carrito;


public class Carrito {

   int[] precios={1000,5000,4000,1000,30000};
   int[]cantidad={};
   
   public int agregarcantidad(){
       for(int n1){
       }
   
   }
   
   public int calculartotal(){
   }
   
   
   
    
    
    
    
    
}

