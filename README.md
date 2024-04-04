
#include <stdio.h>     # <void>라는 헤더 파일을 포함하도록 컴파일러

int main(void)   # main 함수를 정의하는 표준 형식
{
	/*
		첫 번째 작성한 C 프로그램
		2024.04.03
	*/  
	# \*으로 여러 줄 주석을 달 수 있다

	printf("Hello !  \n\n");
	printf("I am a Student. \n");
	printf("%d\n", 1234);
	printf("%d     %d\n", 10, 20);

	return 1;
}

#include <stdio.h>

int main(void) 
{
	int num1 = 12;
	int num2 = 12;
	printf("num1 : %d \n", num1);
	printf("num1++ : %d \n", num1++);
	printf("num1 : %d \n", num1);
	printf("num1++ : %d \n", ++num1);

	/*
	int num1 =  3, num2 = 4;
	int result1 = num1 + num2;
	int result2 = num1 - num2;
	int result3 = num1 * num2;
	int result4 = num1 / num2;
	*/

	// num1 = num2 = 0;

	/*
	printf("num1 : %d, num2 : %d \n", num1, num2);
	printf("%d + %d = %d \n", num1, num2, result1);
	printf("%d - %d = %d \n", num1, num2, result2);
	printf("%d * %d = %d \n", num1, num2, result3);
	printf("%d / %d = %d \n", num1, num2, result4);
	*/

/*
int num;
num = 20;
printf("%d \n", num);
*/


}

///202415026 이세진입니다
