//Jane Cristel Bohol
//Performance Task #1
//October 15 2021

#include <iostream>

using namespace std;

int main(){

    int range, n;
    
        cout << "Enter range of numbers : ";
        cin >> range;
        
        cout << "Enter " << range << " consecutive numbers: ";
        cin >> n;

    if (n %2 == 0)
    {
        cout << n << " is an even number \n";

    }

    else
    {
        cout << n << " is an odd number \n";
    
    }

    while(n != range)
    {
        cin >> n;

        if (n  %2 == 0)
    {
            cout << n << " is an even number \n";
    }

        else 
    {
            cout << n << " is an odd number \n";
     }
        
    }
    

    return 0;
}
