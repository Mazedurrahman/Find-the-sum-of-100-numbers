// Find-the-sum-of-100-numbers
#include<iostream>
#include<conio.h>


using namespace std;
int main()
{
    int a = 100,sum = 0 ;

    for (int i = 1; i <= a; i++)
    {
        sum = sum + i;
    }
    cout << " Total sum is = "<<sum;

    getch();
    return 0;
}
