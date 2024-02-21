# lab1
i need a change
#include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "ru");
	int abc, a, b, c, ab, bc;
	cin >> abc;
	a = abc / 100;
	b = abc / 10 - abc / 100 * 10;
	c = abc % 10;
	ab = b / a;
	bc = c / b;
	if (ab == bc)
	{
		cout << "Цифры данного трехзначного числа образуют геометрическую прогрессию" << endl;
	}
	else
	{
		cout << "Цифры данного трехзначного числа не образуют геометрическую прогрессию" << endl;
	}
}
changes for branch2
