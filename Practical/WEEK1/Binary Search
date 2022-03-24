#include <stdio.h>

int main()
{
    int a[100],n;
    scanf("%d",&n);
    
    for(int i=0;i<n;i++)
        scanf("%d",&a[i]);
        
    int key,comp=0,flag=0;
    scanf("%d",&key);
    
    int start=0,end=n-1,mid;
    mid=(start+end)/2;
    
    while(start<=end){
        comp++;
        if(a[mid]==key){
            printf("key found\n");
            printf("index is : %d\n",mid);
            flag=1;
            break;
        }
        else if(a[mid]>key)
            end=mid-1;
        else
            start=mid+1;
            
        mid=(start+end)/2;
    }
    
    if(flag==0){
        printf("key not found\n");
    }
    printf("Total comparisons : %d\n",comp);
    
}
