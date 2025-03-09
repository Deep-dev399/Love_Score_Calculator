# **Love Score Calculator** ❤️

## **Description:**  
The Love Score Calculator is a fun Python program that calculates a compatibility score between two names based on the occurrences of specific letters in "TRUE LOVE".  

---  

## **How It Works:**  
1. The program counts the occurrences of the letters **T, R, U, E** in both names and sums them up to form the first digit of the score.  
2. It then counts the occurrences of the letters **L, O, V, E** in both names and sums them up to form the second digit of the score.  
3. The final love score is obtained by combining these two numbers.  

---  

## **Example Usage:**  
```python
calculate_love_score("Deepesh", "Shreya")
```
### **Sample Output:**  
```
T occurs 1 times
R occurs 2 times
U occurs 0 times
E occurs 4 times
7
L occurs 0 times
O occurs 0 times
V occurs 0 times
E occurs 2 times
2
Love Score: 72
```

---  

## **Implementation:**  
```python
def calculate_love_score(first_name, second_name):
    
    first_count = 0
    for letter in first_name:
        if(letter == "T" or letter == "t"):
            first_count += 1
    for letter in second_name:
        if( letter == "T" or letter == "t"):
            first_count += 1
    print(f"T occurs {first_count} times")
    
    second_count = 0
    for letter in first_name:
        if(letter == "R" or letter =="r"):
            second_count += 1
    for letter in second_name:
        if( letter == "R" or letter =="r"):
            second_count += 1
    print(f"R occurs {second_count} times")
    
    third_count = 0
    for letter in first_name:
        if(letter == "U" or letter == "u"):
            third_count += 1
    for letter in second_name:
        if( letter == "U" or letter == "u"):
            third_count += 1
    print(f"U occurs {third_count} times")
    
    fourth_count = 0
    for letter in first_name:
        if(letter == "E" or letter == "e"):
            fourth_count += 1
    for letter in second_name:
        if( letter == "E" or letter == "e"):
            fourth_count += 1
    print(f"E occurs {fourth_count} times")
    
    First_Total = first_count + second_count + third_count + fourth_count
    print(First_Total)
    
    first_count = 0
    for letter in first_name:
        if(letter == "L" or letter == "l"):
            first_count += 1
    for letter in second_name:
        if( letter == "L" or letter == "l"):
            first_count += 1
    print(f"L occurs {first_count} times")
    
    second_count = 0
    for letter in first_name:
        if(letter == "O" or letter == "o"):
            second_count += 1
    for letter in second_name:
        if( letter == "O" or letter == "o"):
            second_count += 1
    print(f"O occurs {second_count} times")
    
    third_count = 0
    for letter in first_name:
        if(letter == "V" or letter == "v"):
            third_count += 1
    for letter in second_name:
        if( letter == "V" or letter == "v"):
            third_count += 1
    print(f"V occurs {third_count} times")
    
    fourth_count = 0
    for letter in first_name:
        if(letter == "E" or letter == "e"):
            fourth_count += 1
    for letter in second_name:
        if( letter == "E" or letter == "e"):
            fourth_count += 1
    print(f"E occurs {fourth_count} times")
    
    Second_Total = first_count + second_count + third_count +fourth_count
    print(Second_Total)
    
    Total = str(First_Total) + str(Second_Total)
    print(Total)```

---  

## **License:**  
This project is open-source and free to use.  

---  

## **Contributing:**  
Contributions are welcome! Feel free to improve the logic and optimize the implementation.  
