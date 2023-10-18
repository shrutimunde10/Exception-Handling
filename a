#include<iostream>
using namespace std;
int main()
{
    int age;
    cout<<"Enter your age :\n";
    cin>>age;
    try
    {
        if(age>=18)
        {
            cout<<"You are an adult!";
        }
        else
        {
            throw age;
        }
    }
    catch(int mynum)
    {
        cout<<"You are not old enough";
    }
    return 0;
}
/*
Output
Enter your age :
4
You are not old enough

Enter your age :
4
You are not old enough

*/
