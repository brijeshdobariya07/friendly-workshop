# Resume

## Brijesh Dobariya

### About me:

Hello !!

I am Brijesh Dobariya. I am studying B.tech (IT) from Institute of Advanced Research, Gandhinagar.

[Github Profile](https://github.com/brijeshdobariya07)

[LinkdIn Profile](https://www.linkedin.com/in/brijesh-dobariya-04b7861aa/)

![img](C:\Users\Brijesh Dobariya\Pictures\software-web-development-programming-concept-260nw-1122339353.webp)



> "The way to get started is to quit talking and begin doing."

```java
import java.util.Scanner;

class area
{
	int result;

	area(int l,int b)
	{
		result=l*b;
	}
	void display()
	{
		System.out.println("Area of rec is :- "+result);
	}
	public static void main(String args[])
	{
		Scanner value=new Scanner(System.in);
		System.out.println("enter length : ");
		int length=value.nextInt();
		System.out.println("enter breadth : ");
		int breadth=value.nextInt();

		area a1=new area(length,breadth);
		a1.display();
	}
}
```

```OutPut
enter length :
7
enter breadth :
6
Area of rec is :- 42
```