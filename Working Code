#include <bits/stdc++.h>
using namespace std;

int findMinDiff(int arr[], int n, int m){
    
    if(m==0 || n==0)
      return 0;
      
    sort(arr,arr+n);
    
    if(n<m)
      return -1;
    
    int min_diff=INT_MAX;
    
    for(int i=0;i+m-1<n;i++){
        
        if(arr[i+m-1]-arr[i]<min_diff)
          min_diff=arr[i+m-1]-arr[i];
    }
    return min_diff;
}
int main()
{
    int arr[]={7,3,2,4,9,12,56};
    int n=sizeof(arr)/sizeof(arr[0]);
    int m = 3;
    cout<<"Minimum Difference:"<<findMinDiff(arr,n,m);

    return 0;
}

