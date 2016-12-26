#include <stdio.h>
 
int main()
{
  int array[100], n, c, d, swap;
 
  printf("Enter number of elements\n");
  scanf("%d", &n);
 
  printf("Enter %d integers\n", n);
 
  for (c = 0; c < n; c++)
    scanf("%d", &array[c]);
 
  for (c = 0 ; c < ( n - 1 ); c++)
  {
    for (d = 0 ; d < n - c - 1; d++)
    {
      if (array[d] > array[d+1]) /* For decreasing order use < */
      {
        swap       = array[d];
        array[d]   = array[d+1];
        array[d+1] = swap;
      }
    }
  }
 
  printf("Sorted list in ascending order:\n");
 
  for ( c = 0 ; c < n ; c++ )
     printf("%d\n", array[c]);
 
  return 0;
}







// ================================================== Here  is another code ========================================================
#include<iostream>
#include<conio.h>
using namespace std;
main()
{
int hold;
int array[5];
cout<<"Enter 5 numbers: "<<endl;
for(int i=0; i<5; i++) { cin>>array[i];
}
cout<<endl;
cout<<"Orignally entered array by the user is: "<<endl;
for(int j=0; j<5; j++)
{
cout<<array[j];
cout<<endl;
}
cout<<endl;
for(int i=0; i<4; i++)
{
for(int j=0; j<4; j++) 
{
if(array[j]>array[j+1])
{
hold=array[j];
array[j]=array[j+1];
array[j+1]=hold;
}
}
}
cout<<"Sorted Array is: "<<endl;
for(int i=0; i<5; i++)
{
cout<<array[i]<<endl;
}
getch();
}


//=========================================== Another code for sort ==========================================
#include<iostream>
 
using namespace std;
 
int main()
{
    int a[50],n,i,j,temp;
    cout<<"Enter the size of array: ";
    cin>>n;
    cout<<"Enter the array elements: "; 
    
    for(i=0;i<n;++i)
        cin>>a[i];
        
    for(i=1;i<n;++i)
    {
        for(j=0;j<(n-i);++j)
            if(a[j]>a[j+1])
            {
                temp=a[j];
                a[j]=a[j+1];
                a[j+1]=temp;
            }
    }
    
    cout<<"Array after bubble sort:";
    for(i=0;i<n;++i)
        cout<<" "<<a[i];
        
    return 0;
}
