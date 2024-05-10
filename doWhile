
// Online C++ Compiler - Build, Compile and Run your C++ programs online in your favorite browser

#include<iostream>

using namespace std;

int main()
{
    int ans;
    int passcode = 1232;
    int tries = 0;
    cout<<"Hello\n";
    do{
        cout<<"You have 2 tries to open this locker\n";
        cout<<"Enter your 4 digit code(4 digit)\n";
        cin>>ans;
        tries += 1;
        cout<<tries<<" try so far.\n";
    }while(ans != passcode && tries < 2);
    if(ans == passcode){
        cout<<" Your code matched";
    }else{
        cout<<"You got locked.\n"
        <<"Try after 20 minutes.\n"
        <<"Thank you"<<endl;
    }
    return 0;
}
