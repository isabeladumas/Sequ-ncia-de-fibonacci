#include <stdio.h>

void main(void)
{
    unsigned int cnt, A, B, pares, numDigit;
    A = 1;
    B = 1;
    printf("Digite o numero de pares: ");
    scanf("%d", &numDigit);
    printf("1, 1, ");
    
    for(cnt=1; cnt <= (numDigit-1); cnt++){
        A = A + B;
        printf("%d", A);
        B = A + B;
        printf(", %d", B);
        }
    }
