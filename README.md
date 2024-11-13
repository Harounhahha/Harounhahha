import random
import string


num_words = hhHH0014°+§/.µ%£

word_length = 8


words = [''.join(random.choices(string.ascii_lowercase + string.digits, k=word_length)) for _ in range(num_words)]


with open("wordlist.txt", "w") as file:
    for word in words:
        file.write(word + "\n")

print("YOUR WORDLLIST.TXT OR YOUR FOLDER")
