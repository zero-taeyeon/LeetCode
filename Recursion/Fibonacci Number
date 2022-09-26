class Solution:
    def fib(self, n: int) -> int:
        visited = {}
        def f(n):
            if n in visited:
                return visited[n]
            elif n < 2:
                return n
            else:
                result = f(n-1) + f(n-2)
                visited[n] = result
                return result
        return f(n)
