#include <map>
#include <set>
#include <list>
#include <cmath>
#include <ctime>
#include <deque>
#include <queue>
#include <stack>
#include <string>
#include <bitset>
#include <cstdio>
#include <limits>
#include <vector>
#include <climits>
#include <cstring>
#include <cstdlib>
#include <fstream>
#include <numeric>
#include <sstream>
#include <iostream>
#include <algorithm>
#include <unordered_map>

using namespace std;


int main(){
    int ar[6][6];
    int sum=0;
    int big=0;
    for(int i=0;i<=5;i++)
        {
        for(int j=0;j<=i;j++)
            cin>>ar[i][j];
         cout<<endl;
        }
    
    for(int i=0;i<=3;i++)
        {
        for(int j=0;j<=i+2;j++)
            {
            sum=ar[i][j]+ar[i][j+1]+ar[i][j+2]+ar[i+1][j+1]+ar[i+2][j]+ar[i+2][j+1]+ar[i+2][j+2];
            
        }
        if(sum>big)
                big=sum;
        
    }
    cout<<big;
    return 0;
}
