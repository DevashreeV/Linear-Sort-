# Linear-Sort-
A sorting technique called linear sort, sometimes referred to as counting sort, sorts an array of numbers by calculating the number of times each integer appears in the array and then utilising that information to assign each integer to its proper position in the sorted order.

    #include <stdio.h>
    int main()
    {

        int arr[5]={1,3,5,2,10};
        int n;
        int i;
        printf("Enter a number");
        scanf("%d",&n);
        if(n>arr[4])
        {
            printf("not found");
        }

        else
        {
            for(i=0;i<5;i++)
            {
                if(n==arr[i])
                {
                    printf("found at %d",i);
                    break;
                }
            }
            if(i==5)
            {
            printf ("not found");
            }

        }
    }
    
    
    


Explanation:

1.It requests the user to input a number n using the scanf() method after initialising the integer array arr with five members.

2.The next step is to determine whether the entered number n is bigger than the final entry of the array arr. The programme outputs "not found" if n is bigger than the last member of the array since the number cannot be present in the sorted array.

3.The programme utilises a for loop to search the array arr for the entered number n if n is less than or equal to the final entry of the array. If n is discovered in the array, the programme displays "found at" and the index of the first place n appears in the array, then uses the break statement to end the loop. The programme prints "not found" once the loop is complete if n cannot be found in the array.

OUTPUT:

![Screenshot (737)](https://user-images.githubusercontent.com/91966097/234371994-87e209c6-29c7-404b-aa2c-8a3e46a03685.png)

    
