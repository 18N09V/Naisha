#include<stdio.h>
int main()
{
	int m,n,p,q,i,j;
	printf("enter the no.of elements of first\n");
	scanf("%d%d",&m,&n);
	printf("enter the no.of elements of second\n");
	scanf("%d%d",&p,&q);
	if(n!=p)
	{
		printf("multiplication not possible and end the program\n");
		return 1;
	}
	int x[m][n];
	int y[p][q];
	int z[n][p];
	printf("enter elements into matrix A\n");
	for (i=0;i<m;i++)
	{
		for (j=0;j<n;j++)
		{
			scanf("%d",&x[i][j]);
		}
	}
	
	printf("matrix A\n");
	for (i=0;i<m;i++)
	{
		for (j=0;j<n;j++)
		{
			printf("%d ",x[i][j]);
		}
		printf("\n");
	}
	
	
  
 
#include<stdio.h>
#include<math.h>
int main()
{
	float a,b,c,desc,r1,r2,realpart,imgpart;
	printf("enter the coefficients of a,b and c:");
	scanf("%f%f%f",&a,&b,&c);
	if(a==0)
	{
		printf("coefficient of a cant be zero...\n");
		printf("try again...\n");
		return1;
	}
	desc=(b*b)-(4.0*a*c);
	if(desc==0)
	{
		printf("the roots are real and equal\n");
		r1=r2=(-b)/(2.0*a);
		printf("the two roots are r1=r2=%f\n",r1);
	}
	else if(desc>0)
	{
		printf("the roots are real and equal\n");
		r1=(-b+sqrt(desc))/(2.0*a);
		r2=(-b-sqrt(desc))/(2.0*a);
		printf("the roots are r1=%f and r2=%f\n",r1,r2);
	}
	else
	{
		printf("the roots are imaginary\n");
		realpart=(-b)/(2.0*a);
		imgpart=sqrt(-desc)/(2.0*a);
		printf("the roots are r1=%f+i%f\n",realpart,imgpart);
		printf("r2=%f-i%f\n",realpart,imgpart);
	}
		return 0;
}
		

	
