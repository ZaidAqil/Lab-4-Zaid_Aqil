# Lab-4-Zaid_Aqil
// MUHAMMAD ZAID AQIL B031910152
#include <iostream>
#include <string>
#include <string>
using namespace std;

void star()
{
    cout<<"This Is Lab 4"<< endl;
    cout<<"Za8 Aqil, Do Exercise" <<endl;
    
}
int main()
{
    star();
    float price=9.90;
    int quantity;
    int DISC=10;
    float totalprice=0;    
    cout<<"Enter the quantity of purchase please." <<endl;
    cin>>quantity ;
    totalprice=(price*quantity)*(100-DISC)/100.00;
    cout<<"The total price is:RM" <<totalprice ;
    
    return 0;
}
