- 👋 Hi, I’m @Muhmmad-Abdullah261
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Muhmmad-Abdullah261/Muhmmad-Abdullah261 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 ___________________________________________________________MY PROJECT //PARKING MANAGMENT_______________________________________________________________________________________________________________
 
#include <iostream>

using namespace std;

int main() {
    int r=0;
    int c=0;
    int b=0;
    int u_input;
    int amount = 0, count = 0;

    // Display menu
    cout << "Press 1 for rickshaw" << endl;
    cout << "Press 2 for car" << endl;
    cout << "Press 3 for bus" << endl;
    cout << "Press 4 to show the record" << endl;
    cout << "Press 5 to delete the record" << endl;

    cin >> u_input;

    if (u_input == 1) {
            if (count<=50){
                    r++
        amount = amount +100;
        count++;
            }
            else{
                cout<<"no more cars parking is full"<<endl;
            }
    }
    // Add cases for other transportation options and actions here

    // Show the record (example)
   else  if (u_input == 2) {
        if (count<=50){
                c++
        amount =amount + 200;
        count++;
        }
        else{
                cout<<"no more cars parking is full"<<endl;
            }
    }
    else  if (u_input == 3) {
            if (count<=50){
                    b++
        amount =amount +300;
        count++;
            }
            else{
                cout<<"no more cars parking is full"<<endl;
            }
    }
    else  if (u_input == 4) {
    cout<<"*******************************************"<<endl;
        cout<<"the total amount="<<amount<<endl;
        cout<<"the total number vehicles parked="<<count<<endl;
         cout << "total number of rickshaw" <<r<< endl;
         cout << "total number of car" <<c<< endl;
         cout << "total number of bus" <<b<< endl;
    cout<<"*******************************************"<<endl;
    }
       else  if (u_input == 5) {
        amount = 0;
        count=0;
        cout<<"*******************************************"<<endl;
        cout<<"RECORD DELETED"<<endl;
         cout<<"*******************************************"<<endl;

    }
    else{

        cout<<"invalide number";
    }
    return 0;
}
