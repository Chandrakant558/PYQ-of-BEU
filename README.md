<B>
write a c++ program to find the sum of the series 1+3+5+.....+n.
</B>
#include <iostream>
using namespace std;
int main ()
{
    int n,sum=0;
    cout<<"write the term of series"<<endl;
    cin>>n;
    for (int i = 1; i<n; i+=2)
    {
        sum+=i;
    }
    cout<<"sum is "<< sum <<endl;
    return 0;
}
