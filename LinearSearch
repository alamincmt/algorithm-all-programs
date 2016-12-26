/* C++ Program - Linear Search */
		
#include<iostream.h>
#include<conio.h>
void main()
{
	clrscr();
	int arr[10], i, num, n, c=0, pos;
	cout<<"Enter the array size : ";
	cin>>n;
	cout<<"Enter Array Elements : ";
	for(i=0; i<n; i++)
	{
		cin>>arr[i];
	}
	cout<<"Enter the number to be search : ";
	cin>>num;
	for(i=0; i<n; i++)
	{
		if(arr[i]==num)
		{
			c=1;
			pos=i+1;
			break;
		}
	}
	if(c==0)
	{
		cout<<"Number not found..!!";
	}
	else
	{
		cout<<num<<" found at position "<<pos;
	}
	getch();
}

// ======================================== Linear Search Another code =================================================================
#include<iostream>
using namespace std;

int main() {
cout<<"Enter The Size Of Array:   ";
int size;
cin>>size;


int array[size], key,i;

// Taking Input In Array
 for(int j=0;j<size;j++){
 cout<<"Enter "<<j<<" Element: ";
 cin>>array[j];
 }

//Your Entered Array Is
 for(int a=0;a<size;a++){
    cout<<"array[ "<<a<<" ]  =  ";
    cout<<array[a]<<endl;
 }

  cout<<"Enter Key To Search  in Array";
 cin>>key;

    for(i=0;i<size;i++){
      if(key==array[i]){
  cout<<"Key Found At Index Number :  "<<i<<endl;
  break;
    }
 }


if(i != size){
cout<<"KEY FOUND at index :  "<<i;
}
else{
cout<<"KEY NOT FOUND in Array  ";
}
   return 0;
}
