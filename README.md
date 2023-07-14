# placement-preparation-module
#include <bits/stdc++.h>
using namespace std;

int main() {
	int n;
	cin>>n;
	int maxi=INT_MIN;
	int mini=INT_MAX;
	vector<int>v(n);
	for(int i=0;i<n;i++){
	    cin>>v[i];
	  if(maxi<v[i]){
	     maxi=v[i];
	  }
	  if(mini>v[i]){
	    mini=v[i];
	  }
    }
	cout<<maxi<<endl;
	cout<<mini;
	return 0;
}
