#include<stdio.h>
int main()
{
	int Patient_ID;
	char name[30];
	float Consultationfee, Labfee, Medicinefee;
	float bill;
	printf("Enter Patient ID: %d");
	scanf("%d",&Patient_ID);
	printf("Enter Patient Name:%c");
	scanf("%c",&name);
	printf("Enter Consultationfee: %f");
	scanf("%f",&Consultationfee);
	printf("Enter Labfee: %f");
	scanf("%f",&Labfee);
	printf("Enter Medicinefee: %f");
	scanf("%f",&Medicinefee);
	bill=Consultationfee+Labfee+Medicinefee;
	printf("Patient Bill Receipt");
	printf("Patient Id: \n",Patient_ID);
	printf("Patient Name: \n",name);
	printf("Consultation Fee: \n",Consultationfee);
	printf("Lab Fee: \n",Labfee);
	printf("Medicine Fee: \n",Medicinefee);
	printf("Total Bill \n", bill);
	return 0;
}
