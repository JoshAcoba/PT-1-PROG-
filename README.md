# PT-1-PROG-

//Name: Josh Martin H. Acoba
// PT #1
// BSIE 1-1


#include <iostream>
using namespace std;
int main() {
    int n, range;
    char ch;

    do {
        cout << "Enter range of numbers: ";
        cin >> range;
        for (int n, count = 1; count <= range; count++) {
            cout << "Enter number " << "[" << count << "]: ";
            cin >> n;
            if (n % 2 == 0) {
                cout << n << " is an EVEN number." << endl;
            }
            else {
                cout << n << " is an ODD number." << endl;
            }
        }
        cout << "Try again [y/n]: ";
        cin >> ch;
        cout << endl;
    } while (ch == 'y');

    return 0;
}
