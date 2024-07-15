#include <iostream>
using namespace std;
int main(){
    cout << "Which operation do you want to perform (+,-,*,/,%) : ";
    char operation;
    cin >> operation;

    int a,b;
    cout << "Type 1st number:";
    cin >> a;

    cout << "Type 2nd number:";
    cin >> b;

    cout << "The value of " << a << operation << b << " is: ";

    switch(operation){
        case '+': cout << (a+b) << endl;
            break;

        case '-': cout << (a-b) << endl;
            break;

        case '*': cout << (a*b) << endl;
            break;

        case '/': cout << (a/b) << endl;
            break;

        case '%': cout << (a%b) << endl;
            break;

        default: cout << "Invalid case" << endl;
            break;
    }

    return 0;
}
