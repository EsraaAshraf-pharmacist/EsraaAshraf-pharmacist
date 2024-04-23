#include <iostream>
#include <string>
using namespace std;


enum gender { male, Female };
struct stradress
{
	string street;
	short buildingNo;
	
};
struct strPersonInfo
{
	string firstName;
	string lasttName;
	short age;
	long ID;
	stradress adress;
	
};

void readInfo(strPersonInfo &Info)
{
	cout << "Please insert First name:" << "\n";
	cin >> Info.firstName;

	cout << "Please insert Last name:" << "\n";
	cin >> Info.lasttName;

	cout << "Please insert age:" << "\n";
	cin >> Info.age;

	cout << "Please insert your ID Number:" << "\n";
	cin >> Info.ID;

	cout << "Please insert adress:" << "\n";
	cin.ignore(1, '\n');
	getline(cin, Info.adress.street);
		
}

void printInfo(strPersonInfo Info)
{
	cout << "*********************************************************" << endl;
	cout << "First name is:" << Info.firstName << "\n";

	cout << "Last name is:" << Info.lasttName << "\n";
	
	cout << "Your Age is:" << Info.age << "\n";
	
	cout << "Your ID is:" << Info.ID << "\n";

	cout << "Your Adress is:" << Info.adress.street << Info.adress.street << "\n";

	cout << "*********************************************************" << endl;
}

int main()
{

	strPersonInfo person1[3];
	readInfo(person1[0]);
	printInfo(person1[0]);

	readInfo(person1[1]);
	printInfo(person1[1]);


	readInfo(person1[2]);
	printInfo(person1[2]);
}
