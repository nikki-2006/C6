#include<stdio.h>
int main()
{
int i,n,max;
printf("enter the no. of elements:");
scanf("%d",&n);
   int arr[100];
   printf("enter %d elements \n",n);
   for(i=0;i<n;i++){
   scanf("%d",& arr[i]);
   }
   max=arr[0];
   for(i=1;i<=n;i++){
   if(arr[i]>max){
   max=arr[i];
   }
   }
   printf("\n %d",max);
return 0;
}
    
