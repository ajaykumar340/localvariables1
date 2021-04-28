### local vriables##########

public class Ajaykumar
{
public void aaa()
{
int a=20;   @@@................. local variable............. ######33
System.out.println(a);
}
System.out.println(a);   ///## get the error here because the out of the method ### 
public static void main(String [] args)
{
Ajaykumar ak=new Ajaykumar();
ak.aaa();
}
}



#### instance variables............#########
import java.io.*;
public class Ayk
{
    int a;
    int b;    ////// instance variables......###33
    int c;
    static int ajay; ///////// static variables........$$$
    public void goodnight()
    {
       // int a=50;// local variables
        System.out.println(a);
        System.out.println(ajay);
        
    }
    //System.out.println(a);// outside the method//;;
    public static void main(String [] args)
    {
        Ayk aa=new Ayk();
        Ayk ab=new Ayk();
        aa.a=20;
        aa.b=30;  /// first object values  
        aa.c=40;
    }
}
