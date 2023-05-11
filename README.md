
# 2_vowel_filter_lab_decorators

Having the following code:
def vowel_filter(function):

    def wrapper():

        # TODO: Implement

    return wrapper
   
Complete the code, so it works as expected:
Test Code
@vowel_filter
def get_letters():
    return ["a", "b", "c", "d", "e"]

print(get_letters())

Output

["a", "e"]
    
    
    

