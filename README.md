# C++ Practice Program – Input and Output

This is my second C++ practice program where I learned how to:
- Take integer input from the user using `cin`
- Display the value using `cout`

## 📄 Code

```cpp
#include <iostream>
using namespace std;

int main()
{
    int a;
    cout << "Enter integer number:" << endl;
    cin >> a;
    cout << "Your stored value is => " << a;
    return 0;
}
