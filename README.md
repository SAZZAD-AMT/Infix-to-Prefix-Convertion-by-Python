# Infix-to-Prefix-Convertion-by-Python

def isOperator(c):
    return (not (c >= 'a' and c <= 'z') and not(c >= '0' and c <= '9') and not(c >= 'A' and c <= 'Z'))
    
def getPriority(C):
    if (C == '-' or C == '+'):
        return 1
    elif (C == '*' or C == '/'):
        return 2
    elif (C == '^'):
        return 3
    return 0
 def infixToPrefix(infix):
    operators = []
    operands = []
 
def infixToPrefix(infix):
    operators = []
    operands = []
    
Step 1: Reverse the infix string. Note that while reversing the string you must interchange left and right parentheses.
Step 2: Obtain the postfix expression of the infix expression Step 1.
Step 3: Reverse the postfix expression to get the prefix expression
