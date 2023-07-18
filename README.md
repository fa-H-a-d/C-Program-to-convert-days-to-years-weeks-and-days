#include <stdio.h>

int main() {
    int d, year, week, day;
    printf("Enter a number:");
    scanf("%d", &d);
    year = d / 365;
    printf("%d year\n", year);
    week = (d % 365) / 7;
    printf("%d week\n", week);
    day = d - (year * 365) - (week * 7);
    printf("%d days", day);

    return 0;
}
