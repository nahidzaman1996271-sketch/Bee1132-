# Bee1132-[main.c](https://github.com/user-attachments/files/23749908/main.c)
#include <stdio.h>
#include <stdlib.h>

int main(){
int a,b,temp,sum=0;
scanf("%d %d",&a,&b);
if(a>b){
    temp=a;
    a=b;
    b=temp;
}
for(int i=a;i<=b;i++){
    if(i%13!=0){
        sum+=i;
    }
}
printf("%d\n",sum);
return 0;
}
