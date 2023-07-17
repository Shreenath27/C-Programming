// C Program to implement Call by reference
#include <stdio.h>

// Call by reference
void swap(int* x, int* y)
{
	int temp = *x;
	*x = *y;
	*y = temp;
}

int main()
{
	int x = 1, y = 5;
	printf("Before Swapping: x:%d , y:%d\n", x, y);

	// Calling the function
	swap(&x, &y);
	printf("After Swapping: x:%d , y:%d\n", x, y);

	return 0;
}
