# ProductOfArray
import java.util.Scanner;
public class ProductOfArray {
    
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    int[]arr=new int[]{1,2,3,4,5};
    int product=1;
    for( int i=1; i<arr.length;i++ )
    {
        product=product*arr[i];
    }
    System.out.println("Product of all the elements of an arrray:" +product);
    }
    
}
