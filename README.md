# Homework8
#define _CRT_SECURE_NO_DEPRECATE
#include <stdio.h>
#include <locale.h>
#define _USE_MATH_DEFINES
#include <math.h>



int main() {
    setlocale(LC_CTYPE, "RUS");
    int N;
    double s = 0.0;

    printf("Введите целое число N: ");
    scanf("%d", &N);
    for (int i = 1; i <= N; i++){
    s += pow(i, i);
}
printf("Сумма 1^1 + 2^2+...+%d^%d=%.0f\n",N,N,s);

return 0;
}
