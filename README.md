#include <iostream>
using namespace std;

int main() {
    double radius, area;
    cout << "Enter the radius of the circle: ";
    cin >> radius;
    area = 3.14159 * radius * radius;
    cout << "Area of the circle: " << area << endl;
    return 0;
}
