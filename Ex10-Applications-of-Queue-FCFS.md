# Ex 2E Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. 	Start with process, burst time, and waiting time arrays.
2.	Loopthrough each process from i= 0 to n-1.
3.	Compute tat[i] = burst_time[i] + wait_time[i].
4.	End the algorithm.


## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: ETTA SUPRAJA
RegisterNumber: 212223220022 
*/
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}

```

## Output:

![WhatsApp Image 2025-04-26 at 15 59 23_3dabd34e](https://github.com/user-attachments/assets/a0b75750-a6d5-4876-a5dd-6c4299dd5b25)


## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
