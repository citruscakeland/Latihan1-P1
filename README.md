# Latihan1-P1

#include <iostream>
using namespace std;

int main(){
	char kata[] = {'p', 'e', 'n', 's', 'i', 't'};
	cout << kata;
	cout << " dibalik menjadi ";
	
	int i;
	while(kata[++i] != '\0');
	i--;
	
	for(int j=i; j>=0; j--)
	cout << kata[j]; 
}
