# Instance-method-with-String-return-type
class Test6
{
  String a()
{
  String s="SOMYA RAJ SINHA";
   return s;
}
String b(String c)
{
 String z=c;
return z;
}
public static void main(String args[])
{
 Test6 obj=new Test6();
  System.out.println(obj.a());
  System.out.println(obj.b("GOOD BOY"));
}
}
