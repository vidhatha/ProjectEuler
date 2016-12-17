#include <iostream>

using namespace std;

int main(){
    int t;
    cin >> t;
    for(int a0 = 0; a0 < t; a0++){
        int n;
        cin >> n;
        unsigned long long num =0;
        num = (n-1)/3;
        unsigned long long int threetotal = (3*num*(num+1))/2;

        num = (n-1)/5;
        unsigned long long int fivetotal = (5*num*(num+1))/2;
        
        num = (n-1)/15;
        unsigned long long int fifteentotal = (15*num*(num+1))/2;
        
        unsigned long long int sum = threetotal + fivetotal - fifteentotal;
             
        cout<<sum<<endl;
    }
    
    return 0;
}

