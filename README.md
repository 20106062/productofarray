public class  productofarray
{
   public static void main(String[]args)
    {
       int[]arr=new int[]{10,2,34,56};
        int product=0;
            for(int i=0;i<arr.length;i++){
        product= product+arr[i];
        }
        System.out.println(" product of all the elements of an array:"+ product);
         }
    }
