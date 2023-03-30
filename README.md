# testing2

def wordCount(sentence):
    words = 1
    for i in sentence:
#        print (i)
        if (i == " "):
            words = words + 1
    return words

userIn = input("What would you like your string to be?")
numWords = wordCount(userIn)
print("there are", numWords, "words in that string")
