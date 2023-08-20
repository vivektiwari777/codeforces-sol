<img width="701" alt="image" src="https://github.com/vivektiwari777/codeforces-sol/assets/125742021/234a4f8f-f6a1-48ee-88f6-41751e45d7a2">
<img width="680" alt="image" src="https://github.com/vivektiwari777/codeforces-sol/assets/125742021/eea02d9d-597d-4fe0-8931-d5b623bc9dc3">
code--
#include <iostream>
#include <string>
using namespace std;
int main() {
    int n;
   cin >> n;
    string str;
   
    for (int i = 0; i <n; i++) {
       cin>>str;
        if (str.length() <= 10){
            cout << str << endl;
            
        }
        else{
            cout << str[0] << (str.size()-2) << str[str.size() - 1] <<endl;
        }
    }
    return 0;
}
