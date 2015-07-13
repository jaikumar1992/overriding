# overriding
sample
interface Ainterface
{
int a=5;
static final int b=4;
void display();

void add();

}
class BB implements Ainterface
{
public void display()
{
System.out.println("It is a interface");
}
public void add()
{
int c=a+b;
System.out.println("sum of a and b is :" +c);
}
public static void main(String []args)
{
BB obj=new BB();
obj.display();
obj.add();
}
}
