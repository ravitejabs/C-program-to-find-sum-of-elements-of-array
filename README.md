#include <iostream>

int main() {
    // Define an array
    int arr[] = {1, 2, 3, 4, 5};
    int size = sizeof(arr) / sizeof(arr[0]); // Calculate the size of the array
    int sum = 0;

    // Loop through the array and calculate the sum
    for(int i = 0; i < size; i++) {
        sum += arr[i];
    }

    // Print the sum
    std::cout << "Sum of all elements in the array: " << sum << std::endl;

    return 0;
}# C-program-to-find-sum-of-elements-of-array
