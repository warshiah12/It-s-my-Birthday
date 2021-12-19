# It-s-my-Birthday
#describe what is happening in the program
#include<iostream>
using namespace std;
int main()
{
	bool mybirthday = true;    //declaring variable 'mybirthday' with datatype bool and initialising it with true
	int age = 18;           //declaring variable 'age' with datatype int and initialising it with value 18
	if (mybirthday == true)    //using if-else statement
	{
		age++;    //using increment operator
		cout << "It is my birthday. I am " << age << " years old";   //if user enters 'true' then if statement will be executed  
	}
	else 
	{
		cout << "It is not my birthday " << endl;  //if the user enters 'false' then else statement will be executed
	}
	return 0;
}
