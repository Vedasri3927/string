#include <stdio.h>
#include <string.h>
int main() {
    char str1[100], str2[100], str3[100];
         printf(“25331A05D6\n”);
printf("Enter string 1:\n");
    scanf("%s", str1);
    printf("Enter string 2:\n");
    scanf("%s", str2);
   // Copy str1 into str3
    strcpy(str3, str1);
    printf("Copied string: %s\n", str3);
    // Concatenate str2 to str1
    strcat(str1, str2);
    printf("Concatenated string: %s\n", str1);
    // Compare str2 and str3
    int cmp = strcmp(str2, str3);
    if (cmp == 0) {
        printf("Equal\n");
    } else {
        printf("not equal\n");
    }
    // Length of str3
    printf("Length of copied string: %lu\n", strlen(str3));
    return 0;
}
