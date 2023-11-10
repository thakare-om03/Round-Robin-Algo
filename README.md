# OS Project of Round Robin algorithm
Program execution sequence:

    1. Taking inputs of queries from user
    2. Sorting all queries according to ArrivalTime
    3. Merging all queries (initial priority to Faculty's query)
    4. Applying RoundRobin algorithm on merged queries
    5. Print the result

Follow these instructions while executing the program:

    1. Enter number of queries between 0 & 120
    2. Make sure to keep value of TimeQuantum minimum
    3. Enter Query Arrival Time in the format of HHMM
        Example: 10:25 should be entered as 1025
    4. Next Query's ArrivalTime must be less than previous Query's CompletionTime (ArrivalTime + BurstTime)
    5. BurstTime must be entered such that (ArrivalTime + BurstTime) < 120
    
