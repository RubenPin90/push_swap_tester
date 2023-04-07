
# Push_swap_tester
The bash script checks the input, output, and memory leaks for your push_swap program. You need to run the program in the directory where your push_swap and checker_linux program are.

## Usage

To use this tester, run
```
./test_push_swap.sh 	<min_value> 	<max_value> 	<numbers_to_generate>
```
For example, to test push_swap with a range of -100 to 100, generating 150 random numbers, and testing for non-valid characters, use the command:

```
./test_push_swap.sh -100 100 150
```
*minimum value, *maximum value, and *number of random numbers to generate.


Output
The script generates random numbers within the given range and tests the push_swap program with them.

If the output desired and there are no memory-leaks the checker program returns "OK" otherwise it will show "KO"

```
Output: OK
Valgrind: OK
```

# Note
This bash script only works in combination with a checker file. Please ensure that the checker program is in the same directory as the push_swap program before running the script.

