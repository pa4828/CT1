# CT1
# Selvin was playing with the objiect of random size for stress relief. Selvan knows that the Length, Width, and Height of the object. But he would like to know the surface area of the object he is playing with. Can you help him finding it?  Functional Description: Surface area of the object=2 x [width x length + length x height + height x weight] Constraints: 1=&lt;length=&lt;20 1=&lt;width=&lt;20 1=&lt;height=&lt;20 Input Format: First Line:Length of the object in Integer. Second Line:Width of the object in Integer. Third Line:Height of the object in Integer. Output format: Print a Single integer value representing the surface area of the object selvam is playing with.


#include<stdio.h>
int main()
{
    int length,width,height,surfacearea;
    scanf("%d%d%d%d",&length,&width,&height,&surfacearea);
    surfacearea=2*(width*length+length*height+height*width);
    printf("%d\n",surfacearea);

	return 0;
}
