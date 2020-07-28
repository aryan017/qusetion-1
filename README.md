# qusetion-1
public class copyarray{

     public static void main(String []args){
         int [] a = {2,3,4,5};
         int [] b = new int[a.length];
         for(int i=0; i<a.length; i++){
             b[i]=a[i];
             
         }
         for(int j=0; j<a.length; j++){
         System.out.print(a[j] + " ");
         }
         System.out.println();
         for(int j=0;j<a.length; j++){
         System.out.print(b[j] + " ");
         }System.out.println();
        
     }
}
