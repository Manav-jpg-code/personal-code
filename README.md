#include <iostream>
using namespace std;

int main(){
    cout << "\033[31mHello ";
    cout << "\033[33mWorld";
    cout << "\033[0m" << endl;
    
    return 0;
}
