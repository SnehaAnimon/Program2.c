# Program2.c
//Write a program to calculate volume using a function.

#include<stdio.h>

#include<conio.h>

float pi=3.14;

int cube(int a);

int cuboid(int l,int w,int h);

int sphere(int r);

void main()

{

    int i,j,k,l,d,V;

    printf("Find volume of some shapes\n");

    printf("\n CUBE\n");

    cube(i);

    printf("\n CUBOID\n");

    cuboid(j,k,l);

    printf("\n SPHERE\n");

    sphere(d);

}

   int cube(int a)

   {

       printf("Enter side of the cube\n");

       scanf("%d",&a);

       printf("Volume of cube is: %d\n",a*a*a);

   return 0;

   }

   int cuboid(int l,int w,int h)

  {

      printf("Enter length of cuboid\n");

      scanf("%d%d%d",&l,&w,&h);

      printf("Volume is cuboid: %d\n",l*w*h);

      return 0;

     }   

     int sphere(int r)

     {

         printf("Enter radius of sphere\n");

         scanf("%d",&r);

         printf("Volum of sphere is:%f",4/3*pi*r*r*r);

         return 0;

    

         

     }

   



















    
   

   

 

  





   

   

       

       

     

   

   



  

      
   

   

  

  



     

   

       



       

    

         

     


