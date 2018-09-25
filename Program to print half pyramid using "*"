#include <iostream>

using namespace std;

int main()
{
			   //first triangle
	for (int row = 1; row <= 10; row++)  //sets the row for triangles
	{
		for (int i = 1; i <= row; i++)  //sets the column for the first triangle    
			cout << "*";
		for (int spaces = 0; spaces <= 10 - row; spaces++) //sets the spaces for the first triangle
			cout << " ";

		//second triangle
		for (int i = 10; i >= row; i--)   //sets the column for the second triangle 
			cout << "*";
		for (int spaces = 0; spaces < row; spaces++)
			cout << " ";

		//third triangle
		for (int spaces = 0; spaces < row; spaces++)  //for triangle 3 and 4 reversing the loop pattern
			cout << " ";							 //from triangle one and two
		for (int i = 10; i >= row; i--)
			cout << "*";

		//fourth triangle
		for (int spaces = 0; spaces <= 10 - row; spaces++)
			cout << " ";
		for (int i = 1; i <= row; i++)
			cout << "*";

		cout << endl;

	}

	system("pause");
	return 0;
}
