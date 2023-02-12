# QUAD.C
FINDING THE ROOTS OF A QAUDRATIC EQUATION.
#include<stdio.h>
#include<math.h>
int main()
{
	int a,b,c;
	float x,y;
	int d;
	
	printf("ENTER THE VALUES TO FORM THE QUADRATIC EQUATION ");
	
	printf("\n\nENTRER THE COEFICIENT OF THE x^2: ");
	
	scanf("%d",&a);
	
	printf("\n\nENTRER THE COEFICIENT OF THE x: ");
	
	scanf("%d",&b);
	
	printf("\n\nENTRER THE CONSTANT VALUE: ");
	
	scanf("%d",&c);
	
	printf("\n\nQUADRATIC EQUATION WITH THE GIVEN VALUES IS %dx^2+%dx+%d=0",a,b,c);
	
	printf("\n\nFINDING THE ROOTS OF THE GIVEN QUADRATIC EQUATION");
	
	d=(b*b)-(4*a*c);
	
	if (d>=0)
	{
		printf("\n\nROOTS ARE REAL");
		
		x=(-b+sqrt(d))/2*a;
		
		y=(-b-sqrt(d))/2*a;
		
		printf("\n\nONE ROOTS OF THE GIVEN QUADRATIC EQUATION  AS X: %.1f",x);
		
		printf("\n\nONE ROOTS OF THE GIVEN QUADRATIC EQUATION  AS Y: %.1f",y);
		
			if (x==y)
			{
				printf("\n\nROOTS ARE REAL AND EQUAL");
			}
	}
	else
	{
		printf("\n\nROOTS ARE IMAGINARY");	
	}

	return 0;
	
	
}
