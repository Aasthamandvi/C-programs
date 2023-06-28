# C-programs
This file shows the programs of c+
#include<iostream>
 using namespace std;
class employee
{
int empcode;
char empname[20];
 public:
 void getdata()
 {
cout<<"enter employee code="
cin>>empcode;
cout<<"enter empname="
cin>>empname;
}
void display()
{
cout<<"employee code="<<empcode<<endl
cout<<"employee name=<<empname<<endl;
}
};
int main()
{
employee em[61;
for(int i=0;i<6;i++)
{
em[i].getdata();
}
for(int i=0;i<6;i++)
{
em[i].display();
}
return 0;
}
