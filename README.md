include <stdio.h>
voud swap(int*x,int*y){
  int temp=*x;
  *x=*y;
  *y=temp;
  }
int main (){
  int a=5,b=10;
  swap(&a,&b);
  printf("a=%d,b=%d",a,b);
  return 0;
 }
