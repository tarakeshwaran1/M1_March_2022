#ifndef TRAIN_TICKET_RESERVATION_H_INCLUDED
#define TRAIN_TICKET_RESERVATION_H_INCLUDED
#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
#include<string.h>

/**************GLOBAL VARIABLES*******************/
//ALl the globle variables and the composite data types will be declared here
typedef struct{
	char name[50];
	int train_num;
	int num_of_seats;
}pd;




/**************FUNCTION PROTOTYPE*******************/
//function prototypes to be used
void reservation(void);							//main reservation function
void viewdetails(void);							//view details of all the trains
void cancel(void);
void printticket(char name[],int,int,float);	//print ticket
void specifictrain(int);						//print data related to specific train
float charge(int,int);							//charge automatically w.r.t number of seats and train
void login();


#endif // TRAIN_TICKET_RESERVATION_H_INCLUDED

