# Calculate-Simple-Interest-in-cpp-

#include<iostream>
#include<conio.h>
using namespace std; 

float SI()
{
float p, r, t; 
  cin>>p>>r>>t; 
   return ((p*r*t)/100); 
} 
  
 int main (){
   float S;
   S= SI();
  cout<<S; 
  return 0;
}
