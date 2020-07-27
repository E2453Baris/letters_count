sentence = input("Enter a sentence: ")

def letters_count(sentence):
    dict = {}
    for i in sentence:
        keys = dict.keys()
        if i in keys:
            dict[i] += 1
        else:
            dict[i] = 1
    return dict
print(letters_count(sentence))
