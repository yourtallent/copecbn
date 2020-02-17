```cpp
#include <iostream>

using namespace std;

int main()
{
    int N;
    cin >> N;
    int Even=0;
    int Odd=0;
    int Positive=0;
    int Negative=0;
    for (int i=1; i<=N; i++) {
        int x; cin >> x;
        if (x%2==0) Even=Even+1;
        else { Odd=Odd+1; }
        if (x>0) Positive=Positive+1;
        if (x<0) Negative=Negative+1;
    }
    cout << "Even: " << Even << endl;
    cout << "Odd: " << Odd << endl;
    cout << "Positive: " << Positive << endl;
    cout << "Negative: " << Negative << endl;
   return 0;





}


