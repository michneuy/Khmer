//# Khmer
#include<iostream>
#include<windows.h>
using namespace std;
int main(){
	int number,end;
			/*This is a Display:
				Enter number:2
				How many times?10
				________________
				2 x 1 = 2
				2 x 2 = 4
				2 x 3 = 6
				2 x 4 = 8
				2 x 5 = 10
				2 x 6 = 12
				2 x 7 = 14
				2 x 8 = 16
				2 x 9 = 18
				2 x 10 = 20
				_________________*/
	cout<<"*****WELCOME*****\n\n";
	cout<<"Enter number:";
	cin>>number;
	cout<<"\nHow many times?";
	cin>>end;
	cout<<"\n________________\n";
	for(int i=1;i<=end;i++){
		cout<<number<<" x "<<i<<" = "<<number*i<<endl;
	}
	cout<<"_________________\n";
	system("pause");
	}

