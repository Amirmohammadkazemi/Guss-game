#include<iostream>
#include<conio.h>
#include<stdlib.h>

using namespace std;

bool val=true;
int g,a;

/* Functions */
int random(int r){
	r=rand()%11; //rand % (10-0+1)+0
	
	return r;
}

int main(){
	
	while(val==true){
		cout<<"Enter a number between 0,10: ";
		cin>>g;
		cout<<endl;
		a=(random(g));
		if(g==a){
			cout<<"-------------------- \a"<<endl;
			cout<<"Your guss was right...!";
			val=false;
		}
		else{
			val=true;
		}
		
	}
	getch();
	return 0;
}
