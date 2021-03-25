//For 2-D matrix changing the row into column and column into row.

#include<bits/stdc++.h>
using namespace std;
int main() {
	int a,b;
	cin>>a>>b;
	int n[a][b],z[b][a];
	for(int i=0;i<a;i++) { 
		for(int j=0;j<b;j++) {
			cin>>n[i][j];
		}
	}
	for(int i=0;i<a;i++) { 
		for(int j=0;j<b;j++) {
			z[j][i]=n[i][j];
		}
	}
		for(int i=0;i<b;i++) { 
		for(int j=0;j<a;j++) {
			cout<<z[i][j]<<" ";
		} cout<<endl;
	}
	return 0;
}
