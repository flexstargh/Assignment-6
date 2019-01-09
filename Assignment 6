#include <iostream>

using namespace std;
void bubblesort(int Sortlist[],int length); //function prototype
void bubblesort(int Sortlist[], int length) // we create a function for the bubblesort
{
    int temp;
    int a;
    int b;
    for (a=1;a<length;a++)
    {
        for (b=0;b<length - a;b++)
        {
            if(Sortlist[b] < Sortlist[b+1])
            {
                temp = Sortlist[b];
                Sortlist[b]=Sortlist[b+1];
                Sortlist[b+1] = temp;
            }
        }
    }
}
int main()
{
    int x;
    int Sortlist[10];
    cout << " Enter 10 numbers" <<endl;
    for(x=0;x<10;x++)
    {
        cin >> Sortlist[x];
    }

    bubblesort(Sortlist,10);

    for(x=0;x<10;x++)
    {
        cout << Sortlist[x] << " ";
    }

    return 0;
}
