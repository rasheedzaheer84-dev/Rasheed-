       #include <iostream>
using namespace std;

int main() {
    float a, b;

    cin >> a >> b;

    cout << "Sum = " << a + b;

    return 0;
}


#include <iostream>
using namespace std;

int main() {
    int side;

    cin >> side;

    int perimeter = 4 * side;

    cout << "Perimeter = "
         << perimeter
         << ", Double perimeter = "
         << perimeter * 2;

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int base, power;

    cin >> base >> power;

    cout << base << " ^ "
         << power << " = "
         << pow(base, power);

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int base, power;

    cin >> base >> power;

    cout << base << " ^ "
         << power << " = "
         << pow(base, power);

    return 0;
}

#include <iostream>
#include <string>
using namespace std;

int main() {
    string sentence;

    getline(cin, sentence);

    cout << "You said: "
         << sentence;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    if (num % 2 == 0)
        cout << num << " is even";
    else
        cout << num << " is odd";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;

    int largest = (a > b) ? a : b;

    cout << "Largest = " << largest;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int a, b, c;
    cin >> a >> b >> c;

    if (a < b) swap(a, b);
    if (a < c) swap(a, c);
    if (b < c) swap(b, c);

    cout << "Sorted: "
         << a << " "
         << b << " "
         << c;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    cout << "Result = "
         << 5 * 4 + 2;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    cout << "Result = "
         << (2 + 3 * 4 / 2 - 1);

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    int d1 = num / 1000;
    int d2 = (num / 100) % 10;
    int d3 = (num / 10) % 10;
    int d4 = num % 10;

    cout << "Digit1=" << d1
         << ", Digit2=" << d2
         << ", Digit3=" << d3
         << ", Digit4=" << d4;

    return 0;
}

#include <iostream>
#include <string>
using namespace std;

int main() {
    string feedback;

    getline(cin, feedback);

    cout << "Your feedback: "
         << feedback;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    if (num % 5 == 0)
        cout << "Divisible by 5";
    else
        cout << "Not divisible by 5";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    if (num >= 10 && num <= 20)
        cout << num << " is in range [10,20]";
    else
        cout << num << " is not in range [10,20]";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    string username;

    cin >> username;

    cout << "Welcome "
         << username;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    int d1 = num / 1000;
    int d2 = (num / 100) % 10;
    int d3 = (num / 10) % 10;
    int d4 = num % 10;

    cout << "Reversed = "
         << d4
         << d3
         << d2
         << d1;

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int num;
    cin >> num;

    cout << "abs(" << num << ")="
         << abs(num);

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    cout << "Name: Rashid" << endl;
    cout << "Last Name: Zaheer";

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double num;
    cin >> num;

    double root = cbrt(num);

    cout << root << " "
         << root << " "
         << root;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;
    cin >> num;

    cout << "Square = "
         << num * num
         << ", Cube = "
         << num * num * num;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int x = 10;

    cout << "Address of x = "
         << &x;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;
    cin >> num;

    string binary = "";

    while(num > 0) {
        binary = char((num % 2) + '0') + binary;
        num /= 2;
    }

    cout << "Binary = " << binary;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;

    double sum = 0;

    for(int i = 1; i <= n; i++)
        sum += 1.0 / i;

    cout << "Sum of series = "
         << sum;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int age;
    cin >> age;

    if(age >= 18)
        cout << "You can drive";
    else
        cout << "You cannot drive";

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    int a = 10, b = 5, c = 2;

    cout << "Without parentheses: "
         << a / b * c << endl;

    cout << "With parentheses: "
         << a / (b * c);

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    string username;
    string password;

    cin >> username >> password;

    if(username == "admin" && password == "1234")
        cout << "Login successful";
    else
        cout << "Login failed";

    return 0;
}

#include <iostream>
#include <iomanip>
using namespace std;

int main() {

    float f = 1.0f / 3.0f;
    double d = 1.0 / 3.0;

    cout << fixed;
    cout << "float: " << setprecision(8) << f << endl;
    cout << "double: " << setprecision(16) << d;

    return 0;
}

#include <iostream>
#include <iomanip>
using namespace std;

int main() {

    float f = 1.0f / 3.0f;
    double d = 1.0 / 3.0;

    cout << fixed;
    cout << "float: " << setprecision(8) << f << endl;
    cout << "double: " << setprecision(16) << d;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    int a = 5, b = 10;

    a = a ^ b;
    b = a ^ b;
    a = a ^ b;

    cout << "After swap: a="
         << a
         << ", b="
         << b;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    int a, b, c;
    cin >> a >> b >> c;

    cout << "Result = "
         << (a + b) * c;

    return 0;
}

#include <iostream>
#include <string>
using namespace std;

int main() {

    string address;

    getline(cin, address);

    cout << "Your address: "
         << address;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    float a, b, c;

    cin >> a >> b >> c;

    float avg = (a + b + c) / 3;

    cout << "Average = " << avg;

    if(avg > 50)
        cout << ", Above average";
    else
        cout << ", Below average";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;

    cin >> num;

    if (num >= 50 && num <= 100)
        cout << num << " is between 50 and 100";
    else
        cout << num << " is not between 50 and 100";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int a, b, c;

    cin >> a >> b >> c;

    if (a == 0 || b == 0 || c == 0)
        cout << "At least one number is zero";
    else
        cout << "No zero found";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    double c;

    cin >> c;

    double f = (9.0 / 5.0) * c + 32;

    cout << "Fahrenheit = "
         << f;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    char ch;

    cin >> ch;

    cout << "Next character = "
         << char(ch + 1);

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    float a, b, c, d;

    cin >> a >> b >> c >> d;

    float avg = (a + b + c + d) / 4;

    cout << "Average = " << avg;

    if (avg > 60)
        cout << ", Above 60";
    else
        cout << ", Below 60";

    return 0;
}

#include <iostream>
#include <string>
using namespace std;

int main() {
    string text;
    cin >> text;

    cout << "Length = " << text.length();

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int a = 10;
    float b = 5.5;
    char c = 'A';

    cout << a << " " << b << " " << c;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;

    for(int i = 2; i <= 10; i += 2) {
        cout << n << "x" << i << "=" << n*i << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int a, b, c;
    cin >> a >> b >> c;

    cout << "Result = "
         << (a % b) + (b % c);

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;
    cin >> num;

    if(num >= 0 && num <= 100)
        cout << "Between 0 and 100";
    else
        cout << "Out of range";

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int num;
    cin >> num;

    if (num < 5 || num > 10)
        cout << "Number is less than 5 or greater than 10";
    else
        cout << "Number is in range 5 to 10";

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    const int x = 10;

    // x = 20;  // ❌ خطا: نمی‌توان مقدار const را تغییر داد

    cout << "Compilation error: assignment of read-only variable";

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {

    float x = 1e-50f;

    cout << "Underflow: " << x;

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double x;
    cin >> x;

    cout << "sqrt(" << x << ") = "
         << sqrt(x);

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double num;
    cin >> num;

    cout << "Square root of " << num << " = "
         << pow(num, 0.5);

    return 0;
}

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double degree;
    cin >> degree;

    double rad = degree * 3.14159265 / 180.0;

    cout << "sin(" << degree << ")=" << sin(rad)
         << ", cos(" << degree << ")=" << cos(rad);

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int fact = 1;

    for(int i = 1; i <= 5; i++) {
        fact *= i;
    }

    cout << "Factorial of 5 = " << fact;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    float base, height;

    cin >> base >> height;

    cout << "Area = " << (base * height) / 2;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    int myVar = 10;
    int myvar = 20;

    cout << "myVar = " << myVar << endl;
    cout << "myvar = " << myvar;

    return 0;
}

#include <iostream>
using namespace std;

int main() {

    cout << "Teacher Profile" << endl;
    cout << "----------------" << endl;
    cout << "Name: Mr. parwiz" << endl;
    cout << "Specialization: Computer Science" << endl;
    cout << "Experience: 1 years" << endl;
    cout << "Teaching Skill: Excellent" << endl;
    cout << "Behavior: Professional and kind" << endl;
    cout << "Important: Motivates students and explains clearly";

    return 0;
} # Rasheed-