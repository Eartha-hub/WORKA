#include <iostream>
using namespace std;
int main()
{
    int number;
	float base=0.0,height=0.0,side=0.0,radius=0.0,area=0.0;
	cout<<"1.Triangle Area\n";
	cout<<"2.Square Area\n";
	cout<<"3.Circle Area\n";
	cin>>number;
	switch(number){
	case 1:
	cout<<"Enter you base : ";
	cin>>base;
	cout<<"enter you height : ";
	cin>>height;
	area=base*height/2;
	cout<<"Triangle area = "<<area;
	break;
	case 2:
		cout<<"enter your side : ";
		cin>>side;
		area=side*side;
		cout<<"Square area = "<<area;
		break;
	case 3:
	cout<<"enter you radius : ";
	cin>>radius;
	area=3.14*radius*radius;
	cout<<"Circle area = "<<area;
	break;
	default:cout<<"you enter the wrong number !!! ";
		
	}
}
