# Word Maze

Given a 2D grid of characters and a word, determine if the word exists in the grid by moving to adjacent cells (up, down, left, right). Each cell can be used at most once in the path.

## Input
N M
grid of N rows, M columns
word

## Constraints
1 ≤ N, M ≤ 10
Word length ≤ 20

## Output
YES or NO

## Examples
Input:
3 4  
ABCE  
SFCS  
ADEE  
ABCCED  
Output:
YES

Input:
3 4  
ABCE  
SFCS  
ADEE  
SEE  
Output:
YES

