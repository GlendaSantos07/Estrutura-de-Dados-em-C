Faça um programa que lê uma matriz de 3x3 elementos usando um comando for, e multiplique cada elemento por 5 e imprime o resultado.

# include <stdio.h>
# include <conio.h>
# include <locale.h>

int main(){
	setlocale(LC_ALL, "Portuguese");
float m[3][3];
int i,j;
for (i=0;i<3;i++){
	for(j=0;j<3;j++){
		printf("Digite um número ");
		scanf("%f",&m[i][j]);
	}
}
printf("\n\nA matriz é\n\n");
for (i=0;i<3;i++){
	for(j=0;j<3;j++){
		printf("%.2f\t",m[i][j]);
	}
	printf("\n");
}
printf("\n\nA matriz multiplicada por 5\n\n");
for (i=0;i<3;i++){
	for(j=0;j<3;j++){
		m[i][j]=5*m[i][j];
		printf("%.2f\t",m[i][j]);
	}
	printf("\n");
}
	getch();
	return 0;
}
