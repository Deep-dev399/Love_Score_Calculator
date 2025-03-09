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
    first_count = sum(1 for letter in first_name + second_name if letter.lower() in "true")
    second_count = sum(1 for letter in first_name + second_name if letter.lower() in "love")

    love_score = int(str(first_count) + str(second_count))
    print(f"Love Score: {love_score}")

calculate_love_score("Deepesh", "Shreya")
```

---  

## **License:**  
This project is open-source and free to use.  

---  

## **Contributing:**  
Contributions are welcome! Feel free to improve the logic and optimize the implementation.  
