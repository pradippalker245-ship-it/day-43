# day-43
c++ pracatice 
#include <iostream>
using namespace std;

int main()
{
    int a = 10, b = 0;

    try
    {
        if (b == 0)
        {
            throw b;
        }

        cout << a / b;
    }
    catch (int x)
    {
        cout << "Cannot divide by zero";
    }

    return 0;
}
