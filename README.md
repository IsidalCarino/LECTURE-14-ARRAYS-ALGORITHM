# Standard Library Array Methods
```
#include <iostream>
#include<array>
using namespace std;

int main()
{
    array<string, 4> arr = { "Mars", "Snickers", "Bounty","Wispa" };
    cout << arr.at(1) << endl;
    cout << arr[1] << endl;

    cout << arr.front() << endl;
    cout << arr.back() << endl;

    for (int i = 0; i < arr.size(); i++) {
        cout << arr.at(i) << ", ";
    }
    cout << endl;
}
```
# Algorithm Sorting Example
```
#include <iostream>
#include <array>
#include <algorithm>
using namespace std;

int main()
{
    array<int, 5> numbers = { 33,5,7,99,83 };
    sort(numbers.begin(), numbers.end());
    for (int num : numbers) {
        cout << num << " ";
    }
}

```
# Algorithm Sorting largest to smallest (TRIAL)
```
#include <iostream>
#include <array>
#include <algorithm>
using namespace std;

int main()
{
    array<int, 5> numbers = { 33,5,7,99,83 };
    sort(numbers.begin(), numbers.end());
    reverse(numbers.begin(), numbers.end());
    for (int num : numbers) {
        cout << num << " ";
    }
}
```
# rand fucntion (code that crashed my VISUAL STUDIO)
```
#include <iostream>
#include <array>
#include <algorithm>
#include <random>
using namespace std;

int main()
{
    int randomArry[10];
    for (int i = 10; 1 < 10; i++)
    {
        randomArry[i] = rand() % 50;
        cout << randomArry[i] << endl;
    }srand(time(0));
    
}
```
# EXERCISE 1
```
#include <iostream>
#include <array>
#include <algorithm>
using namespace std;

int main()
{
    int randomArray[1000];
    int x = 0;
    for (int x = 0; x < 1000; x++) {
        randomArray[x] = rand() % 100;
        if (randomArray[x] == 6) {
            cout << randomArray[x] << endl;
            x++;
        }else{
            continue;
        }
    } cout << "^ many 6 ";
}
```
# EXERCISE 2
```
Ms. I'm very sorry I think I will need some help for this.
```
# EXERCISE 3
```
... and for this as well.
```
