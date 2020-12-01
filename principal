package Principal;

import Logica.PilaDinamica;
import java.util.ArrayList;
import java.util.List;

import java.util.Scanner;


public class Main {
     public static void main(String args[]){
        Scanner leer = new Scanner(System.in);
        List <Integer> lista=new ArrayList();
        PilaDinamica Pila= new PilaDinamica();
        
       boolean continuar = true;
             
       int  menu=0;
    
        while(continuar){
    
        System.out.println("BIENVENIDOS A  LA PILA DINAMICA \n"
                   + "1: INSERTAR PALABRA A LA PILA\n"
                   + "2: MOSTRAR PILA DINAMICA \n"
                   + "3: ELIMINAR UN ELEMENTO \n"
                   + "4: SALIR");
        menu=leer.nextInt();
        
          switch(menu){
              case 1:
                  int i=0,li=1,ls=10,num;
                  
                for( i=0;i<10;i++){
            num=(int)(Math.random()*(ls-li)+1);
            
                lista.add(num);
                }
                Pila.Empujar(lista);
                  lista.clear();
                  
                break;
            case 2:
                 
               Pila.mostrarPila();
              
               break;
            case 3:
                Pila.SacrPila();
                break;
            case 4:
                System.out.println(" ELEGISTE SALIR...");
                continuar=false;
                break;
                 default:
                 System.out.println("opcion incorrecta");
                 break;
           
          }
     }
  }
}
