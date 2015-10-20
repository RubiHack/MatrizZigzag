# MatrizZigzag
Primer Repocitorio
Ruben Rodriguez Rojas

package matrizsigsag;

public class MatrizSigsag {

              public static void main(String[] args) {
        
        int [][]Mat = new int[3][3];
        
        for(int i=0; i<3; i++){
            for(int j=0; j<3; j++){
                Mat[i][j]= (int)(1+Math.random()*9);
                System.out.print(Mat[i][j]);
            }
            System.out.println("");
        }
        
       for(int i=0; i<3; i++){
           for(int j=0, c=i; j<3; j++,c++){
               System.out.print("["+Mat[i][j]+"]");
               
               if(j == 1)
               j++;
               i++;
               if(i == 1)
                   j++;
            }
           System.out.println("");
       }
        
        
        
        //--------------------------------------
        
    }
    
}
