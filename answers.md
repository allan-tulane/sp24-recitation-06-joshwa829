# CMPS 2200 Recitation 06
## Answers

**Name:**_______Joshua Allison__________________
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** Work = 1 + W(n-1) + W(n-2) -> O(2^n)

- **3)** Span = 1 + S(n-1) -> O(n)

- **4)**  If you print the counts at each iteration when recursively getting the fib number at the 9th index. The pattern is printed below [0, 0, 0, 0, 0, 0, 0, 1] [0, 0, 0, 0, 0, 0, 1, 1] [0, 0, 0, 0, 0, 1, 1, 1] [0, 0, 0, 0, 1, 1, 1, 1] [0, 0, 0, 1, 1, 1, 1, 1] [0, 0, 1, 1, 1, 1, 1, 1] [1, 2, 2, 1, 1, 1, 1, 1] [2, 3, 2, 2, 1, 1, 1, 1] [2, 3, 3, 2, 1, 1, 1, 1] [3, 5, 3, 2, 2, 1, 1, 1] [3, 5, 3, 3, 2, 1, 1, 1] [3, 5, 4, 3, 2, 1, 1, 1] [4, 7, 5, 3, 2, 1, 1, 1] [5, 8, 5, 3, 2, 2, 1, 1] [5, 8, 5, 3, 3, 2, 1, 1] [5, 8, 5, 4, 3, 2, 1, 1] [5, 8, 6, 4, 3, 2, 1, 1] [6, 10, 7, 4, 3, 2, 1, 1] [7, 11, 7, 5, 3, 2, 1, 1] [7, 11, 8, 5, 3, 2, 1, 1]
You can notice a pattern that resembles a truangle. The initial rows start with 0 and 1s, changing the right most 0 to 1 at the nth position of the array. This occurs until a 1 gets to the left position. Column wise they somewhat resemble the fib sequence, although not applicable for every row.

- **6)** The max amount of times fib_top_down(i) will be called is n. Work = O(n) and Span = O(n)

- **8)** The maximum number of times that Fi will get read is n-2 times. The work and span for the Bottom-up will be O(n)
