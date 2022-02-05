#include <stdio.h>
int main(){
	int i,k,j,yildiz,bosluk;
	yildiz=1;
	bosluk=43;
	printf("\n");
	for (i=1; i<=19; i++){
		for(k=1; k<bosluk; k=k+1) printf(" ");
		for(j=1; j<=yildiz; j++)  printf("*");
		printf("\n");
		bosluk--;
		yildiz=yildiz+2;}

	return 0;

}
