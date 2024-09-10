#include <iostream>
using namespace std;
int missing_num(int arr[],int n) {
    
    int count= (n + 1) * (n + 2) /2;
    int totalc  = 0;

    for (int i=0;i<n;i++){
        totalc += arr[i];

    }
    return count - totalc;

}
int main() {
    int n;
    cout<<"enter the size of the array = "<<endl;
    cin>>n;
    int arr[n];
    cout<<"enter the data {1,2,3,4,5,6,7,8,9} :\n";
    for(int i=0;i<n;i++){
        cin>>arr[i];
    }
    int missing_number = missing_num(arr,n);
    cout<<"the missing number is: "<<missing_number<<endl;
}
