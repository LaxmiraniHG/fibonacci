#include<stdio.h>
#include<math.h>
{
    int first = 0, second = 1, next;
    printf("Fibonacci Series: ");
    for (int i = 0; i < n; i++) {
        if (i == 0) {
            printf("%d ", first);
        } else if (i == 1) {
            printf("%d ", second);
        } else {
            next = first + second;
            first = second;
            second = next;
            printf("%d ", next);
        }
    }
    printf("\n");
}
 {
    if (num <= 1) return 0; // 0 and 1 are not prime
    for (int i = 2; i <= sqrt(num); i++) {
        if (num % i == 0) {
            return 0; // Not prime
        }
    }
    return 1; // Prime
}
long long powerOfXtoX(int x) {
    return pow(x, x);
}

int main() {
    int n, x;





return 0;
}
