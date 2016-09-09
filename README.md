# ZJBS
public class stars4{
// method repeat is not enabled

   public static void main(String[] args){
      line(10);
      line(5);
      line(3);
      System.out.println();
      box(5,5);
      box(9,9);
   }
   public static void line (int count){
     repeat("*", count); 
     System.out.println();
      
   }
   
   public static void box (int width, int height){
      
      System.out.print("\n");
      line (width);
      
      for (int line =1; line<=height; line++){
         System.out.print("*");
         repeat(" ",(width-2));
         System.out.println("*");
      }
      line(width);
   }
   public static void repeat(String s, int times) {
     for (int i = 1; i <= times; i++) {
         System.out.print(s);
     }
   }
}
