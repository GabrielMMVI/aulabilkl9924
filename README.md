# aulabilkl9924
// Code

#include <stdio.h>

#define PI 3.14

float raioCircunferencia(float raio){
    return PI * raio * raio;
}
int main (void) {
    float raio2;
    float calculo;

    printf("Digite o raio que deseja: ");
    scanf("%f", &raio2);

    calculo = raioCircunferencia(raio2);

    printf("O resultado e: %.2f", calculo);
    return 0;
}
