# shutdown
public class ShutDown

{
public static void main(Strings[])

{
Runtime run=Runtime.getRuntime();

try
{
Process pro=run.exec("shutdown -s -t"+5);
}

catch(Exception e)
{
System.out.print(e);
}
}
}
