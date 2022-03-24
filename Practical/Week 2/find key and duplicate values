#include <iostream>
using namespace std;

int main()
{
    int n;
    cin >> n;
    int a[n];
    for(int i=0;i<n;i++)
        cin >> a[i];
        
    int key,count=0,flag=0;
    cin >> key;
    
    for(int i=0;i<n;i++){
        if(flag==1 && a[i]!=key)
            break;
        
        if(a[i]==key){
            flag=1;
            count++;
        }
    }
    
    if(flag==1){
        cout << "key found & total occurrence : " << count << endl;
    }
    else
        cout << "key not found" << endl;
    return 0;
}
