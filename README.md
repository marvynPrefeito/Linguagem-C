1. Crie um programa que calcule a soma de dois números digitados pelo usuário.

#include <stdio.h>

int main() {
    int a,b;
    printf("Insira o Numero 1: \n");
    scanf("%d", &a);
    printf("Insira o Numero 2: \n");
    scanf("%d", &b);
    
    printf("Soma: %d", a+b);
    return 0;
}






2. Faça um programa que verifique se um número digitado pelo usuário é par ou ímpar.


#include <stdio.h>

int main() {
    int a = 1;
    
    while(a != 0){
    printf("Insira um numero:\n");
    scanf("%d", &a);
    if(a % 2 == 0){
        printf("%d é par\n", a);
    }else{
        printf("%d é impar\n",a);
    }
    }

    return 0;
}





4. Crie um programa que calcule a média seis números inteiros digitados pelo usuário.
#include <stdio.h>

int main() {
    int a, b, c, d, e, f, media;
    
    printf("Insira um número: ");
    scanf("%d", &a);
    
    printf("Insira um número: ");
    scanf("%d", &b);
    
    printf("Insira um número: ");
    scanf("%d", &c);
    
    printf("Insira um número: ");
    scanf("%d", &d);
    
    printf("Insira um número: ");
    scanf("%d", &e);
    
    printf("Insira um número: ");
    scanf("%d", &f);
    
    media = a + b + c + d + e + f /6;
    
    printf("A média é:%d", media);
    
    

    return 0;
}







