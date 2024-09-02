def isPalindrome(s):
    return s == s[::-1]
s = input("Enter the string : ")
ans = isPalindrome(s)
if ans:
    print("Palindrome")
else:
    print("Not Palindrome")
