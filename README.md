# Advanced-Arrays


## 5 Integers
    #include <iostream>
    using namespace std;
    int main()
    {

		int n[5];
		
		cout << "Enter 5 integers:" << endl;

		for (int i = 0; i < 5; i++) {

			cin >> n[i];


		}
		cout << endl;
		cout << "The numbers are" << endl;
		for (auto i : n[5]) {
			cout << i << endl;
		}
## Snacks
     #include <iostream>
    using namespace std;
    int main()
    {
	string snacks[3][4] =
	{
    {"Galaxy silk", "Mars Bar", "Snickers","Bounty"},//first row
    {"Flavoured Youghurt", "Oman chips","Oreo","Lays"}, //second row
    {"Apple", "Banana","Orange","Pear"} //third row
	};

	for (int i = 0; i < 3; i++)
	{
		for (int j = 0; j < 4; j++)
		{
			cout << snacks[i][j] << " - ";
		}
		cout << endl;
	}

## Art
    #include <iostream>
    using namespace std;
    int main()
    {


	char art[5][5] = {
	{ '-', '-', '-', '-', '-'},
	{ '-', '0', '-', '0', '-' },
	{ '-', '@', '@', '@', '-' },
	{'-', '^', '^', '^', '-'},
	{ '-', 'v', 'v', 'v', '-'}
	};

	for (int i = 0; i < 5; i++) {
		for (int j = 0; j < 5; j++) {
			cout << art[i][j];
		}
		cout << endl;
	}
	return 0;

    }
