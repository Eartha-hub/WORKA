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
#include  <iostream>

using namespace std;

int main() 
{
	float water;
	cout<<"Enter water : ";
	cin>>water;
	if(water<500){
		water=water*6.75;
		cout<<"water : "<<water;
	}else if(water>100&&water<499){
		water=water*5.25;
		cout<<"water : "<<water;
	}else if(water>500&&water<999){
		water=water*4.75;
		cout<<"water : "<<water;
	}else if(water>=1000){
		water=water*3.25;
		cout<<"water : "<<water;
	}
}
#include  <iostream>

using namespace std;

int main() 
{
	int num;
	cout<<"Enter water";
	cin>>num;
	if(num<500){
		cout<<"general user";
	}else if(num>500&&num<2999) {
		cout<<"small business";
	}else if (num>3000){
		cout<<"large business";
	}
}
#include  <iostream>

using namespace std;

int main() 
{
float num;
cout<<"Enter number : ";
cin>>num;
if(num<12){
	cout<<"kid";
}
else if (num>13&&num<19){
	cout<<"young";
}else if (num>20&&num<39){
	cout<<"Early adult";
}else if (num>40&&num<59){
	cout<<"Late adult";
}else if ( num>60){
cout<<"Late adult";
}
 }
 
 #include  <iostream>

using namespace std;

int main() 
{	
	int computer;
	
		while(computer<=5){
		computer=computer+1;
		cout<<"computer\n";
	}
}
	
