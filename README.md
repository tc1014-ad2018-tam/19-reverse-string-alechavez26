# 19-reverse-string-alechavez26
19-reverse-string-alechavez26 created by GitHub Classroom
/* 
 * Alejandra Chavez Cruz
 * A01411970@itesm.mx
 * 18/OCT/19
 *This program will gets a string from the user and then displays it in reverse order.
*/

#include<stdio.h>
#include<string.h>

int main(){
    char str[150];

    //ask to the user for a string
    printf("Give me a string:\n");
    fgets(str, sizeof(str), stdin);

    printf("\nYour text backwards is: ");

    // This part print every character in the string
    for(int x=strlen(str); x>0; x--){
        printf("%c", str[x-1]);
    }

    return 0;
}
