# lab4.1
#include<iostream>
using namespace std;

int main()
{
	//output welcoming message 
	cout << "Welcome to Food Court!\n\n";

	//output numbered menu items 1 thru 4
	int Rice, Chicken, Beans, Salad;
	int CustomerSelection;

	cout << "Please make a selection from the following menu by inputting the \n";
	cout << "item number and pressing enter\n\n";
	cout << "1. Rice\n";
	cout << "2. Chicken\n";
	cout << "3. Beans\n";
	cout << "4. Salad\n";
	cin >> CustomerSelection;

	// if statements for numbers greater than 4
	if (CustomerSelection >= 5)
		cout << "You have made an invalid selection.";
	// if statement for numbers less than 1
	if (CustomerSelection <= 0)
		cout << "You have made an invalid selection.";
	return 0;

	// if statements for user inputs 1-4
	if (CustomerSelection == 1)
		cout << " How about an order of our juicy chicken to go with that?\n";

	if (CustomerSelection == 2)
		cout << "Great Choice! Thank you for your order!";

	if (CustomerSelection == 3)
		cout << "Enjoy! Thank you for your order!";

	if (CustomerSelection == 4)
		cout << "Yum! Enjoy your salad!";
		

	return 0;
