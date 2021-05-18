# BoolStringRev

def isPalindrome(str):
 
    if str is None or not str:
        return False
 
    i = 0
    j = len(str) - 1
    while i < j:
        if str[i] != str[j]:
            return False
        i = i + 1
        j = j - 1
 
    return True
 
 
if __name__ == '__main__':
 
    str = "XYBYBYX"
 
    if isPalindrome(str):
        print("Palindrome")
    else:
        print("Not Palindrome")
