//{Driver code starts
//driver code
#include<bits/stdc++.h>
#define 11 long long int
using namespace std;


class Solution
{
    public:
    
    long long int count(long long int n)
    {
    		vector<long long>v(n+1, 0);
    	v[0]=1;
    	for(int i=3;i<=n;i++){
    	    v[i]+=v[i-3];
    	}
    	for(int i=5;i<=n;i++){
    	    v[i]+=v[i-5];
    	}
    	for(int i=10;i<=n;i++){
    	    v[i]+=v[i-10];
    	}
    	
    	return v[n];
    	
    }
};

//{driver code starts.
int  main()
{
int t;
cin>>t;
while(t--)
{
    11 n;
    cin>>n;
    Solution obj;
    cout<<obj.count(n)<<endl;
}
return 0;
}
//} Driver code ends
