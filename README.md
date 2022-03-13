# area-of-room
class Over
{
    int v,v1,v2;
    void method()
    {
        System.out.println("method with no parameters");
        v1=10;
        v2=20;
        v=v1*v2;
         System.out.println("area of the room"+v);
        
    }
    void method(int a)
{
     System.out.println("method with one parameters");
     v1=a;
     v2=30;
     v=v1*v2;
      System.out.println("area of the room "+v);
}
void method(int a,int b)
{
     System.out.println("method with two parameters");
     v1=a;
     v2=b;
     v=v1*v2;
      System.out.println("area of the room"+v);
}
}
class Main
{
    public static void main(String[]args)
    {
        Over m=new Over();
        m.method();
        m.method(89);
        m.method(98,99);
    }
}
    
