
Task
1) What kind of statements require a;?
- Control statements ( if, while, switch and for ) and 
the stetement’s header such as (# include 
<stdio.h> and libraries )
2)What is the difference between int and short int?
- The size of int is 2 bytes and of short int is also 2 
bytes.
- Int and short are 2bytes on 16 compilers one 32 
bits compilers , int is 4 pyte while short remains 16 
bits .
3)What are the constrain on decaring variables in c ?
- All variables names must begin with a letter of 
alphabet or an unders car (-). After the first initial 
letter , variable names can also contain letter , and 
numbers variable names are cases sensitive . no 
spaces or speclal characters.



#include <stdio.h>
Int main()
{
Int a,b,c,sum;
Printf(“enter a value of a \n”);
Scanf(“%d”,&a);
Printf(“enter a value of b \n”);
Scanf(“%d”,&b);
Printf(“enter a value of c \n”);
Scanf(“%d”,&c);
Sum=a+b+c;
Printf(“sum =%d”,sum);
Return 0;
}
#include <stdio.h>
#define pi=3.14
Int main()
{
Fioat r,area
printf(“enter a value of r \n”);
scanf(“%f”,&r);
area=3.14*r*r;
printf(“%f”,area);
return 0;
}


#inciude <stdio.h>
int main()
{
Int a,b,c,d,e,f,g,x;
Printf(“enter the value of a \n”);
Scanf(“%d”,&a);
Printf(“enter the value of b \n”);
Scanf(“%d”,&b);
Printf(“enter the value of c \n”);
Scanf(“%d”,&c);
Printf(“enter the value of d \n”);
Scanf(“%d”,&d);
Printf(“enter the value of e \n”);
Scanf(“%d”,&e);
Printf(“enter the value of f \n”);
Scanf(“%d”,&f);
Printf(“enter the value of g\n”);
Scanf(“%d”,&g);
X=((a+b/c*d-e)*(f-g));
Printf(“%d”,x);
Return 0;
}

#include <stdio.h>
Int main()
{
Int n,x,y,z;
Scanf(“%d %d %d “ ,&n &x &y );
Z=(y-x)*n;
Printf(“%d”,z);
Return 0;
}
#include <stdio.h>
Int main()
{
Int a,x,y,z,b,sum;
Scanf(“%d”,a);
x=a%10;
y=a%100;
z=y/10;
b=a/100;
sum=x+z+b;
printf(“sum of digits =%d” ,sum);
return 0;
}

#include <stdio.h>
Int main()
{
Int n,x,y,z;
Scanf(“%d %d %d “ ,&n &x &y );
Z=(y-x)*n;
Printf(“%d”,z);
Return 0;
}

#include <stdio.h>
Int main()
{
Int a,x,y,z,b,sum;
Scanf(“%d”,a);
x=a%10;
y=a%100;
z=y/10;
b=a/100;
sum=x+z+b;
printf(“sum of digits =%d” ,sum);
return 0;
}

#include <stdio.h>
Int main()
{
Int x;
Scanf(“%d” ,&x);
If(x%2==0)
Printf(“Even”);
Else
Printf(“odd”);
Return 0;
}

#include <stdio.h>
Int main()
{
Int x,y;
Scanf(“%d %d”,&x,&y);
If(x>0&&y>0)
Printf(“Q1”);
Else if(x>0&&y<0)
Printf(“Q2”);
Else if(x<0&&y<0)
Printf(“Q3”);
Else if(x<0&&y>0)
Printf(“Q4”);
Else if(y==0)
Printf(“x-axis”);
Else if(x==0)
Printf(“y-axis”);
Return 0;
}

#include <stdio.h>
Int main()
{
Int x,steps;
Scanf(“%d”,&x);
Steps=(x=4)/5;
Printf(“%d”,steps);
}
#include <stdio.h>
#include <stdlib.h>
int main()
{
float weight,height,Bmi;
scanf("%f%f",&weight,&height);
Bmi=weight/height*height;
printf("%f",Bmi);
 return 0;
}
/* final velocity*/
#include <stdio.h>
#include <stdlib.h>
int main()
{
 long long t,v,u,s,a;
 scanf("%d%d%d",&t,&u,&a);
 v=u+a*t;
 printf("%d\n",v);
 s=u*t+0.5*a*t*t;
 printf("%d\n",s);
 return 0;
}
