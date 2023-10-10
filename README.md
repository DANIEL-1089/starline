#include <iostream>
#include <cstdlib>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <conio.h>

#pragma warning(disable : 4996)

using namespace std;
void starline();


int main()
{
    starline();
    cout << "char    -128...127" << endl;
    cout << "short    -32,768...32,767" << endl;
    cout << "int    system depended" << endl;
    cout << "long   -2,147,483,648...2,147,483,648" << endl;
    starline();

    return 0;
}
void starline() {
    for (int j = 0; j < 45; ++j) {
        cout << '*';
    }
    cout << endl << endl;
}
