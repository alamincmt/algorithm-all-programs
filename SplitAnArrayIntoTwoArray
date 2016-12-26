//Program to split an array into two arrays (in an efficient way)

# include<iostream>

using namespace std;

int main()
{
 
          int a[4],b[4],c[8],i,j;
          cout<<"ENTER THE ELEMENTS OF COMPOSITE ARRAY:\n";
         
         for(i=0; i<8 ;i++)            //Loop for input
         {
                  cout<<"c["<<i<<"]=";
                  cin>>c[i];
         }
         cout<<endl; 
 
         for(i=0,j=0 ; j<8 ; i++,j+=2)
        {
                a[i]=c[j];
                b[i]=c[j+1];
        }
  
        cout<<"\nPRINT THE ELEMENTS OF ARRAY1:\n";
        for(i=0; i<4 ;i++)            //Loop for output
        {
                cout<<"b["<<i<<"]=";
                cout<<b[i]<<endl;
        }
 
        cout<<"\nPRINT THE ELEMENTS OF ARRAY2:\n";
        for(i=0; i<4 ;i++)            //Loop for output
       {
               cout<<"a["<<i<<"]=";
               cout<<a[i]<<endl;
       }
  
        return 0;
}
