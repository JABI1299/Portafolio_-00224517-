#include <stdio.h>
#include <iostream>
using namespace std;
int a[10];

int calculo(){
    int i=0, j=0,k;
    for(i=0;i<10;i++){
printf("%d,",a[i]);
if(a[i] > j){
j = a[i];
}
}
return j;
   
}


int main(){

int i=0, j=0, k;
printf("datos ingresados\n" );
for(i=0;i<10;i++){

scanf("%d/n",&a[i]);
}

   j=calculo();
printf("\nel numero mayor:%d ",j);

return 0;
}
