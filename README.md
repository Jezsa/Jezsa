import java.util.*;

 // Compiler version JDK 11.0.2

 class kdaragon 
{
   public static void main(String args[]) 
   { 
    int operator, n1, n2;
        System.out.println ("1-Add \n2-Subtract \n3-Multiply \n4-Divide: ");
        System.out.print("choose operator:");
        Scanner sc= new scanner (system.In);
        operator=sc.nextInt();
        System.out.print ("Enter first number:");
        ni=sc. nextInt();
        System.out.print ("Enter  Second number :");
        n2=sc. NextInt();
        
                  int result =0;
                  switch(operator){
                     case 1:
                       result= n1+ n2;
                       break;
                       
                       case 2:
                         result=n1-n2;
                         break;
                         
                         case 3:
                           result=n1*n2;
                           break;
                           
                           case 4:
                             result=n1/n2;
                             break;
                             
                            default:
                          System.out.println("Entered operator is not invalid");              
   }
   System.out.println("Result is:"+result );
}
