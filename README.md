# helloworld
This is for practice

#include <stdio.h>

int main() {
    int n;
    printf("Enter the number of integers: ");
    scanf("%d", &n);

    int arr[n];
    int sum = 0;

    printf("Enter %d integers:\n", n);
    for(int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
        sum += arr[i];
    }

    double average = (double)sum / n;
    printf("The average is: %.2f\n", average);

    return 0;
}
