def palindrome(n,k):
    for i in range(1,k):
        o=int(str(n)[::-1])
        n=n+o
        if str(n)==str(n)[::-1]:
            return([i,n])
            break
    return [-1,-1]
print(palindrome(89, 30))
