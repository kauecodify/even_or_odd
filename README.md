# even_or_odd
#include <stdio.h>
int main () {
    int num;
    printf ("\n Digite um Número inteiro: ");
    scanf ("%d", &num);
    if (num % 2 == 0) {
        
        printf ("\n O número é par");
        
    } else {
        printf ("\n o número é impar");
    }
    
    return 0;
    
}
