# Python-practice-string-methods-

**1. Concatenate two strings and print the result.**

 
 <code>
string1 = "Hello"
string2 = "World"
result = string1 + " " + string2
print("Concatenated String:", result)
</code>

 
**2. Find and print the length of a given string.**


<code>
string = "Python is fun!"
length_of_string = len(string)
print("Length of the string:", length_of_string)
</code>


**3. Convert a string to uppercase and lowercase, and print both versions.**


<code>
convert = "Hello World"
uppercase = convert.upper()
lowercase = convert.lower()
print("Uppercase:", uppercase)
print("Lowercase:", lowercase)
</code>


**4. Print the first three characters, last three characters, and a substring in the middle.**


<code>
first_three_chars = string[:3]
last_three_chars = string[-3:]
middle_substring = string[len(string)//2 - 2:len(string)//2 + 2]
print("First three characters:", first_three_chars)
print("Last three characters:", last_three_chars)
print("Middle substring:", middle_substring)
</code>


**5. Reverse a given string and print the result.**


<code>
reversed = string[::-1]
print("Reversed string:", reversed)
</code>


**6. Count the number of occurrences of a specific character in a given string.**


<code>
specific_character = 'y'
count_occurrences = string.count(specific_character)
print(f"Occurrences of '{specific_character}':", count_occurrences)
</code>


**7. Repeat a given string three times and print the result.**


<code>
repeated = string * 3
print("Repeated string:", repeated)
</code>


**8. Remove any leading or trailing whitespaces from a string and print the cleaned version.**


<code>
string_with_whitespace = "   Python Programming   "
cleaned_string = string_with_whitespace.strip()
print("Cleaned string:", cleaned_string)
</code>


**9. Check if a specific substring is present in a given string.**


<code>
specific_substring = "is"
substring_present = specific_substring in string
print(f"'{specific_substring}' present in string:", substring_present)
</code>


**10. Split a sentence into a list of words and print the result.**


<code>
sentence_to_split = "This is a sample sentence."
split_words = sentence_to_split.split()
print("Split words:", split_words)
</code>


**11. Replace a specific word in a sentence with another word and print the modified sentence.**


<code>
word_to_replace = "sample"
replacement_word = "great"
modified_sentence = sentence_to_split.replace(word_to_replace, replacement_word)
print("Modified sentence:", modified_sentence)
</code>


**12. Find and print the index of a specific character in a given string.**


<code>
specific_char = 'n'
char_index = string.index(specific_char)
print(f"Index of '{specific_char}':", char_index)
</code>


**13. Convert a sentence to title case and print the result.**


<code>
sentence_to_title_case = "python is amazing"
title_case_string = sentence_to_title_case.title()
print("Title case string:", title_case_string)
</code>


**14. Use string formatting to create a sentence with variables and print the result.**


<code>
name = "Radion"
age = 19
formatted_sentence = f"{name} is {age} years old."
print("Formatted sentence:", formatted_sentence)
</code>


**15. Check if a given string is a palindrome and print the result.**


<code>
given_palindrome = "radar"
is_palindrome = given_palindrome == given_palindrome[::-1]
print("Is the string a palindrome?", is_palindrome)
</code>

