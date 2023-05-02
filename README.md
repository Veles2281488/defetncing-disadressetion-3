#include <iostream>

using namespace std;

int main()
{
	int *a = new int(10);

	cout << "adress \t *a\t b\n";

	cout << a << '\t' << *a << endl;
	(*a)++;
	cout << a << '\t' << *a << endl;
	(*a++);
	cout << a << '\t' << *a << endl;
	*a++;
	cout << a << '\t' << *a << endl;

	return 0;

}
