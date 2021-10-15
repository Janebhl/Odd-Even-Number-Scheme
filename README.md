//Jane Cristel Bohol
//Performance Task #1
//October 15 2021

#include <iostream>

using namespace std;

int main(){

    int range, n, i = 0;
    
        cout << "Enter range of numbers : ";
        cin >> range;
        
        cout << "Enter " << range << " consecutive numbers: ";
        cin >> n;

    if (n % 2 == 0)
    {
        cout << n << " is an even number \n";
        i++;

    }

    else
    {
        cout << n << " is an odd number \n";
        i++;
    
    }

    while(i != range)
    {
        cin >> n;

        if (n  %2 == 0)
    {
            cout << n << " is an even number \n";
            i++;
    }

        else 
    {
            cout << n << " is an odd number \n";
            i++;
     }
        
    }
    

    return 0;
}
