# function2
#include <iostream>
using namespace std;
 
 void printAverage(double a,double b,double c){
     double avg=(a+b+c)/3;
     cout<<"ededi orta="<<avg<<endl;
 }
 int main(){
     double a,b,c;
     cout<<"3 eded daxil edin"<<endl;
     cin>>a>>b>>c;
    printAverage(a,b,c);
    return 0;
}
