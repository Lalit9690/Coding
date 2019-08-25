
#include<stdio.h>
int add(int a, int b);  //function declaration with arguments
int main()
{
	int a,b,c;
	printf("Enter the value of a and b:\n");
	scanf("%d%d",&a,&b);
	c=add(a,b);      // function calling
	printf("Addition of a and b:%d",c);
	return 0;

}
 int add(int x,int y)// function definition
 {
 	int z; 
 	z=x+y;
 	return 0;
 }
