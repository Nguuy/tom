include<stdio.h>

int main()

   int min(int a[], int n) {

	// 2 3 7 8 9 24 57 22

	int min = a[0];

	for(int i=1; i<n; i++)	
	
		if(a[i] > min)

			min = a[i];

	return min;
}
