#include<stdio.h>

int main() {
	
	int score = 0;//점수
	int sum = 0;  //총합
	int mean = 0; //평균
	int i;
	

	for (int i = 1; i <= 5; i++) {
		scanf_s("%d", &score);
		if (score < 40)
			score = 40;
		sum += score;
	}
	mean = sum / 5;
	printf("%d", mean); 
}
