# months
enter a month number a it will tell you what season it is now
#include <iostream>
  
  

using namespace std;

int main()
{
    int month;

    cout << "Enter the month number: ";
    cin>>month;

    switch(month){
    case 1:
        cout<<"Winter";
        break;
        case 2:
        cout<<"Winter";
        break;
        case 3:
        cout<<"Spring";
        break;
        case 4:
        cout<<"Spring";
        break;
        case 5:
        cout<<"Spring";
        break;
        case 6:
        cout<<"Summer";
        break;
        case 7:
        cout<<"Summer";
        break;
        case 8:
        cout<<"Summer";
        break;
        case 9:
        cout<<"Fall";
        break;
        case 10:
        cout<<"Fall";
        break;
        case 11:
        cout<<"Fall";
        break;
        case 12:
        cout<<"Winter";
        break;
        default:
            cout<<"There is only 12 months in a year. Please try again!";
            break;
    }


    return 0;
}
