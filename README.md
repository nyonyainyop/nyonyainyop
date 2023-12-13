#include<cstdlib>
#include<iostream>
using namespace std;
int luassegitiga(int a, int t){
    int luas;
    luas = a*t/2;
    return luas;
}

int main(){
    int a,t,luas;
    a=15;
    t=2;
    luas = luassegitiga(a,t);
    
    cout << "LUAS SEGITIGA =  " <<luas<<endl;
    system("PAUSE");
    return 0;
    
}
