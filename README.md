#####################String###################################
##############################################################
"this is a string"

'this is too'

"""you can
do triple quotation
for multiple lines"""

'''or you can also 
do with single quotation
just like I did here'''

1 #this is integer
"1" #this is string

word = "Camera"
print (word)
#you will get "word" as an output


##############################################################
##############################################################


##################Numberic objects##########################
##############################################################
# if you type simple number or decimal number with numerical sign, python will simply give you output

#example of interger : 5+5 gives 10

#example of decimal or float: 1.0 + 2.1 gives 3.1

#example of exponentiation: 4 ** 2 gives 16
# '^' symbol is not exponentiation symbol in python

# example of modulo (remainder after dividing one number by another):
# print (16 % 5) gives 1, which is the remainder

#############################################################
##############################################################


####################List#########################
##############################################################
# List has square brancket '[]'
# list can have any type of value, or sub-list inside it
# example: a = [1,2,"anything", 2.0, True, [2,4,'a']]

#list concatenation or adding
#example: a = a + ["better"] gives [1,2,"anything", 2.0, True, [2,4,'a'], "better"], this is adding "better" inside previous list a form line# 49 above
# above in line#52, 0th element=1, 1st element=2, 2nd element="anything", 3rd element=2.0, 4th element=True.. and so one
# it is like this because python count starts with 0th element

#list deletion or removal of element from list
#example: del(a[4]) gives [1,2,"anything", 2.0, [2,4,'a'], "better"], here 'True' is removed, which is the 5th elements of list, but python 4th element



#############################################################
##############################################################

##############Built-in function#########################
##############################################################
 ## to know the type of any value simply do 'type(value)'
 ## example: type(1) gives integer
             type("this") gives str, which is string
             type (True) gives bool, which is boolean
#############################################################
##############################################################



##################Jupyter Notebook tips###########################
##############################################################

# any function with "%" in front of it, in a Jupyter notebook cell is called the magic line function
# % convert cell line as a linux or other terminal line, where you can type command
# example==> %cd c:users/Documents --> this line take you to the current directory
#            %pwd --> this command in a Jupyter notebook cell output pathway to currrent working directory, or shows current directory where you are now       


#in jupyter cell, if you ask it to print multiple output, it will only print the last one
#example by keeping below all in one cell:
#       5 - 5
#       3 + 2
#       2 * 3
#the output will be just 6, as it will just print '2 * 3' value
# solution: add 'print(<value>)' in each line

#############################################################
##############################################################



####NOTES
##DO NOT WRITE PYTHON IN CAMELCASE (camelCase), JUST LIKE WE DO IN JAVA.
## '^' symbol is not exponentiation symbol in python.

