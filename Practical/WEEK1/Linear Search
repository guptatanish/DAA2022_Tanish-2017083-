#include <stdio.h>

int main()
{
    int a[100],n;
    scanf("%d",&n);
    
    for(int i=0;i<n;i++)
        scanf("%d",&a[i]);
        
    int key,comp=0,flag=0;
    scanf("%d",&key);
    
    for(int i=0;i<n;i++){
        comp++;
        if(a[i]==key){
            printf("key found\n");
            printf("index is : %d\n",i);
            flag=1;
            break;
        }
    }
    
    if(flag==0){
        printf("key not found\n");
    }
    printf("Total comparisons : %d\n",comp);
    return 0;
    
}
