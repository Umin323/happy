#include <stdio.h>

int main() {
    int num1, num2, sum;

    printf("첫 번째 숫자를 입력하세요: ");
    scanf("%d", &num1);

    printf("두 번째 숫자를 입력하세요: ");
    scanf("%d", &num2);

    sum = num1 + num2;

    printf("두 수의 합: %d\n", sum);

    return 0;
}
