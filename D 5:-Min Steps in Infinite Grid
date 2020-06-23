class Solution:
    def coverPoints(self, A, B):
        no = 0
        for i in range(len(A)-1):
           no += max(abs(A[i] - A[i+1]), abs(B[i] - B[i+1]))
        return no
