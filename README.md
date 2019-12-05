#include<iostream>

using namespace std;

int main()
{
    int No_1;
    int No_2;
    
    int sum;
    
    cout<<"Please enter the 1st number:";
    cin>>No_1;
    
    cout<<"Please enter the 2nd number:";
    cin>>No_2;
    
    sum=No_1+No_2;
        cout<<"      "<<endl;
        cout<<"Sum = "<<sum<<endl;
    
    if(sum>No_1){
        cout<<"               "<<endl;
        cout<<"Sum is greater!"<<endl;
    }
    
    return 0;
}
