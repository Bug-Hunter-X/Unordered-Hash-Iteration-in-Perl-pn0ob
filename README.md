# Unordered Hash Iteration in Perl
This example demonstrates a common pitfall in Perl when working with hashes: the lack of guaranteed iteration order using the `each` function.  The code iterates through a hash, but the order of key-value pairs printed may vary between Perl versions or even different runs of the same script.

## Solution
The solution involves using a sorted iteration if a specific order is needed.  This example uses `sort` to ensure consistent output.