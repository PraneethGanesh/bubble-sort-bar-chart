# bubble-sort-bar-chart

This Python code visualizes the process of bubble sort using a bar chart. The code is structured as follows:

1. Imports:
matplotlib.pyplot is used for plotting the bar charts.
random is used to generate random data for sorting.
time is imported but not used in the code.
2. Functions:
bubble_sort(data):

This function implements the bubble sort algorithm.
It iterates over the list of data, comparing adjacent elements and swapping them if they are in the wrong order.
After each swap, the current state of the data is displayed using a bar chart, with the bars temporarily colored yellow to indicate an ongoing operation and then green after the comparison.
plt.pause(0.2) is used to slow down the visualization to see the sorting process, and plt.clf() clears the figure to prepare for the next frame.
generate_data(size):

This function generates a list of random integers between 1 and 100, with the size specified by the size parameter.
3. Main Execution:
main():
Generates random data of size 30.
Plots the initial unsorted data in blue.
Calls the bubble_sort(data) function to sort the data, visualizing each step.
Finally, it displays the sorted data using a bar chart colored in pink.
4. Execution:
The script runs the main() function if executed as the main program, showing the data before and after sorting, along with the sorting process animation.

This Python code visualizes the process of bubble sort using a bar chart. The code is structured as follows:

1. Imports:
matplotlib.pyplot is used for plotting the bar charts.
random is used to generate random data for sorting.
time is imported but not used in the code.
2. Functions:
bubble_sort(data):

This function implements the bubble sort algorithm.
It iterates over the list of data, comparing adjacent elements and swapping them if they are in the wrong order.
After each swap, the current state of the data is displayed using a bar chart, with the bars temporarily colored yellow to indicate an ongoing operation and then green after the comparison.
plt.pause(0.2) is used to slow down the visualization to see the sorting process, and plt.clf() clears the figure to prepare for the next frame.
generate_data(size):

This function generates a list of random integers between 1 and 100, with the size specified by the size parameter.
3. Main Execution:
main():
Generates random data of size 30.
Plots the initial unsorted data in blue.
Calls the bubble_sort(data) function to sort the data, visualizing each step.
Finally, it displays the sorted data using a bar chart colored in pink.
4. Execution:
The script runs the main() function if executed as the main program, showing the data before and after sorting, along with the sorting process animation.
Summary:
The code visually demonstrates the bubble sort algorithm using bar charts in Python. Each step of the sorting process is animated, allowing viewers to observe how bubble sort repeatedly swaps adjacent elements until the entire list is sorted.
The code visually demonstrates the bubble sort algorithm using bar charts in Python. Each step of the sorting process is animated, allowing viewers to observe how bubble sort repeatedly swaps adjacent elements until the entire list is sorted.
