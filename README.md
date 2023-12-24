# Word-Counter
Count the number of words in the entered text.
def word_count(text):
    words = text.split()
    return len(words)

input_text = input("Enter text: ")
count = word_count(input_text)
print("Word Count:", count)
