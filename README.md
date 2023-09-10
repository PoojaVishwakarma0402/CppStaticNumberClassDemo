# CppStaticNumberClassDemo

#include <iostream>
using namespace std;

class Number{
    public:
    int x;
    static int y;
    void set(){
        cout<<x<<y;
    }
    static void change(Number Temp){
        // cout<<x<<y;   error as x is non static data member
        cout<<Temp.x<<" "<<y;
    }
};

int Number::y=15;

int main() {
    // Write C++ code here
    Number T1,T2,T3;
    T1.x=0;
    T2.x=0;
    T3.x=0;
    T1.set();
    Number::change(T1);
    T1.change(T1);

    return 0;
} 
