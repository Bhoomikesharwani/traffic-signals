# Traffic parking
#include<iostream>
using namespace std;
int main(){
cout<<"\tC A R  P A R K I N G"<<endl;
int enter;
int car=0,bike=0,rikshaw=0;
while(true)
{
cout<<"Press 1 to enter car "<<endl;
cout<<"Press 2 to enter bike "<<endl;
cout<<"Press 3 to enter rikshaw "<<endl;
cout<<"Press 4 to show record "<<endl;
cout<<"press 5 to delete the record "<<endl;
cout<<"Press 6 to exit "<<endl;
cin>>enter;
if(enter==1)
{
car++;
cout<<"car is Added "<<endl;
}
else if(enter==2)
{
bike++;
cout<<"bike is Added "<<endl;
}
else if(enter==3)
{
rikshaw++;
cout<<"Rikshaw is Added "<<endl;
}
else if(enter==4)
{
cout<<"Car "<<car<<endl;
cout<<"Bike"<<bike<<endl;
cout<<"Rikshaw "<<rikshaw<<endl;
}
else if(enter==5)
{
car=0;
bike=0;
rikshaw=0;
}
else if(enter==6)
{
exit(0);
}
else{
cout<<"Invalid input"<<endl;
}
}
return 0;
}
