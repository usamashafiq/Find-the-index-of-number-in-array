#include<iostream>
#include<conio.h>

#include<string>
using namespace std;

void main() {
	int num[10],a,i,e;
	cout << "Enter a nmbers";

	for (i = 0; i < 10; i++) {
		cin >> num[i];
			
}
	cout << "Enter a number to search" << endl;
	cin >> a;
	for (int q = 0; q < 10; q++) {
		if (num[q] == a) {
			cout << a << " found at index " << q +1<< endl;
			break;
		}
		else {
			cout << "Not found";
			break;
		}
		}
	

	
	_getch();

}
