# tourism-project
#include <stdio.h>

int main()
{
    int choice;
    int budget;

    printf("some title\n");

    printf("\n1. Location s);
    printf("\n2. Find Hotel");
    printf("\n3. Recommendation");
    printf("\n4. Exit");

    printf("\n\nEnter your choice: ");
    scanf("%d", &choice);

    if (choice == 1)
    {
        printf("locations");

        printf("\n1. Some place");
        printf("\n   cool places");
        printf("\n  ");
        printf("\n    ");

        printf("\n\n2. Another");
        printf("\n   cool places");
        printf("\n  ");
        printf("\n   ");

        printf("\n\n3.another");
        printf("\n   cool places");
    }

    else if (choice == 2)
    {
        printf("hotels");

        printf("\nGoa");
        printf("\n1. Beach View Hotel - Rs.1500/night");
        printf("\n2. Guest House - Rs.1000/night");

        printf("\n\nJaipur");
        printf("\n1. Some other Hotel - Rs.1800/night");
        printf("\n2. Some other- Rs.900/night");

        printf("\n\nKerala");
        printf("\n1. Some other - Rs.2000/night");
        printf("\n2. Some other - Rs.1000/night");
    }

    else if (choice == 3)
    {
        printf("recommendations");

        printf("\nEnter your budget: Rs.");
        scanf("%d", &budget);

        if (budget < 3000)
        {
            printf("Recommended Destination: some place");
            printf("\nReason: Affordable travel");
        }
        else if (budget < 7000)
        {
            printf("\nRecommended Destination: some place");
            printf("\nReason: Good options for a budget-friendly trip.");
        }
        else
        {
            printf("\nRecommended Destination: some place");
            printf("\nReason: Some reason");
        }

    }

    
    else if (choice == 4)
    {
        printf("\nThank you");
    }

    else
    {
        printf("\nInvalid choice!\n");
 }
}
