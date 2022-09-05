#include <stdio.h>
Int main() {
    Char str[1000], ch;
    Int count = 0;

    Printf(“Enter a string: “);
    Fgets(str, sizeof(str), stdin);

    Printf(“Enter a character to find its frequency: “);
    Scanf(“%c”, &ch);

    For (int i = 0; str[i] != ‘\0’; ++i) {
        If (ch == str[i])
            ++count;
    }
