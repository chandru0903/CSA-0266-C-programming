#include<stdio.h>
#include<math.h>
main(){
   int choice;
   printf("Enter
1 to find area of Triangle
2 for finding area of Square
3 for finding area of Circle
4 for finding area of Rectangle
5 for Parallelogram
");
   scanf("%d",&choice);
   switch(choice) {
      case 1: {
         int a,b,c;
         float s,area;
         printf("Enter sides of triangle
");
         scanf("%d%d %d",&a,&b,&c);
         s=(float)(a+b+c)/2;
         area=(float)(sqrt(s*(s-a)*(s-b)*(s-c)));
         printf("Area of Triangle is %f
",area);
         break;
      }
      case 2: {
         float side,area;
         printf("Enter Sides of Square
");
         scanf("%f",&side);
         area=(float)side*side;
         printf("Area of Square is %f
",area);
         break;
      }
      case 3: {
         float radius,area;
         printf("Enter Radius of Circle
");
         scanf("%f",&radius);
         area=(float)3.14159*radius*radius;
         printf("Area of Circle %f
",area);
         break;
      }
      case 4: {
         float len,breadth,area;
         printf("Enter Length and Breadth of Rectangle
");
         scanf("%f %f",&len,&breadth);
         area=(float)len*breadth;
         printf("Area of Rectangle is %f
",area);
         break;
      }
      case 5: {
         float base,height,area;
         printf("Enter base and height of Parallelogram
");
         scanf("%f %f",&base,&height);
         area=(float)base*height;
         printf("Enter area of Parallelogram is %f
",area);
         break;
      }
      default: {
         printf("Invalid Choice
");
         break;
      }
   }
}
