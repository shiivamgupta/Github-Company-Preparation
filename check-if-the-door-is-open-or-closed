// { Driver Code Starts
#include <bits/stdc++.h>
using namespace std;

 // } Driver Code Ends
class Solution {
  public:
    int *checkDoorStatus(int N) {
        int *s = (int *)malloc(N*sizeof(int));
        for(int i=1;i<=N;i++)
        {
            int x = sqrt(i);
            if(x*x == i){
                s[i-1] = 1;
            }
            else{
                s[i-1] = 0;
            }
        }
        return s;
        // code here
    }
};

// { Driver Code Starts.
int main() {
    int t;
    cin >> t;
    while (t--) {
        int N;
        
        cin>>N;

        Solution ob;
        int* ptr = ob.checkDoorStatus(N);
        for(int i=0 ; i<N ; i++)
            cout<<ptr[i]<<" ";
        cout<<endl;
    }
    return 0;
}  // } Driver Code Ends
