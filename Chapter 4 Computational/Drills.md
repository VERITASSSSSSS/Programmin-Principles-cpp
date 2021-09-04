# Drills

1.  Write a program that consists of a  `while`-loop that (each time around the loop) reads in two  `int`s and then prints them. Exit the program when a terminating  `'|'`  is entered.

	```cpp
	#include <iostream>
	#include <vector>
	using namespace std;

	int main()
	{
		int i, j;
		while (cin >> i >> j)
		{
			cout <<"Value I is: " << i << '\t' <<"Value j is:" << j;
		}
		return 0;
	}
	```
	The input and output of this program is :

	```cpp
	1 4
	Value I is: 1   Value j is:4
	3 5
	Value I is: 3   Value j is:5
	3 5
	Value I is: 3   Value j is:5
	```
	
2.  Change the program to write out  `the  smaller  value  is:`  followed by the smaller of the numbers and  `the  larger  value  is:`  followed by the larger value.

	```cpp
	#include <iostream>
	#include <vector>
	using namespace std;

	int main()
	{
		int i; int j;
		while (cin >> i >> j)
		{
			if (i < j)
				cout << "The Smaller Value is: " << i << '\n' << "The Larger Value is: " << j<<"\n\n";

			else
				cout << "The Smaller Value is: " << j << '\n' << "The Larger Value is: " << i << "\n\n";
		}
		return 0;
	}
	```
	The input and output of this program is :

	```cpp
	4 32321
	The Smaller Value is: 4
	The Larger Value is: 32321

	4 29
	The Smaller Value is: 4
	The Larger Value is: 29

	27 298
	The Smaller Value is: 27
	The Larger Value is: 298
	```
	3.   Augment the program so that it writes the line  `the  numbers  are  equal`  (only) if they are equal.

	```cpp
	#include <iostream>
	#include <vector>
	using namespace std;

	int main()
	{
		int i; int j;
		while (cin >> i >> j)
		{
			if (i == j)
				cout << "The  numbers " << i << " & " << j << " are  equal";

			else if (i < j)
				cout << "The Smaller Value is: " << i << '\n' << "The Larger Value is: " << j << "\n\n";

			else 
				cout << "The Smaller Value is: " << j << '\n' << "The Larger Value is: " << i << "\n\n";

		}
		return 0;
	}

	```
	The input and output of this program is :

	```cpp
	6 6
	The numbers 6 & 6 are equal

	9 123
	The Smaller Value is: 9
	The Larger Value is: 123

	213 6
	The Smaller Value is: 6
	The Larger Value is: 213
	```

> Written with [StackEdit](https://stackedit.io/).


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM4MzMxMTk2MSwxNDIzMjk1MjEwLC00Mz
I4NDAwNjNdfQ==
-->