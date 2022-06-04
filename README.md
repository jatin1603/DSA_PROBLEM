# DSA_PROBLEM

![image](https://user-images.githubusercontent.com/79332951/171985096-6b4a5561-afad-40b5-8853-a65b6bfa05a4.png)
// { Driver Code Starts
// Initial template for C++

#include <bits/stdc++.h>
using namespace std;


 // } Driver Code Ends
// User function template for C++

class Solution {
  public:
    int binarysearch(int arr[], int n, int k) {
        int temp=-1;
        for(int i=0;i<=n;i++){
        if(arr[i]==k){
            temp=i;
        }
       
    }return temp;
        
    }
};

// { Driver Code Starts.
int main() {
    int t;
    cin >> t;

    while (t--) {
        int N;
        cin >> N;
        int arr[N];
        for (int i = 0; i < N; i++) cin >> arr[i];
        int key;
        cin >> key;
        Solution ob;
        int found = ob.binarysearch(arr, N, key);
        cout << found << endl;
    }
}
  // } Driver Code Ends

