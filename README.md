# vote-elligibility
#include<iostream>
int main(){
	
	char  age;
	std::cout<<"enter your age:"<<age;
	std::cin>>age;
	if (age>=18){
				std::cout<<"you are elligible to vote now!!YAY!!.get ready to play part in choosing your leader."; 
	}
		
	else{
	
		std::cout<<"sorry you are not elligible to vote.";
	}
    return 0;		
		
}

