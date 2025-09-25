# 📓 Day 1: Python Print Function, Debugging, and Input Function  

## 🚀 What I Learned Today  
- How to use the `print()` function in Python.  
- Debugging common syntax errors.  
- String concatenation using `+`.  
- Taking user input with the `input()` function.  

## 💻 Code Snippets / Mini-Project  

# Printing a message
```print("Hello, world!")```



# Interactive greeting program

```
name = input("What is your name?")

print("Hello " + name + "!")
```

# Day 1: Band Name Generator Project

## Tasks:


1. Create a greeting for your program.
2. Ask the user for the city that they grew up in and store it in a variable.
3. Ask the user for the name of a pet and store it in a variable.
4. Combine the name of their city and pet and show them their band name.
5. Make sure the input cursor shows on a new line


## Solutions:
```

print("Welcome to the Band Name Generator\n")<br/>

user_city = input("What city you grew up?\n")

user_pet = input("What is the name of your pet?\n")

band_name = user_city + user_pet

print("Your band name could be: " + user_city + " " + user_pet )
```



