# Python-Projects-Calorie-Calculator 🐍
This repo contains python code that generates the sum total of your calorie intake for a given day.<br>
Run the code.


Python
```python
#this is a calorie counter python program

date = input("What day is it today: ")
print(date)
breakfast = input("How many calories did you have for breakfast? ")
print(breakfast)
lunch = input("How many calories did you have for lunch? ")
print(lunch)
dinner = input("How many calories did you have for dinner? ")
print(dinner)
snack = input("How many calories did you have for your snack? ")
print(snack)

sum = int(breakfast) + int(lunch) + int(dinner) + int(snack)

print(f"Calorie content for {date}: {sum}")
```

Output
```python
What day is it today: Tuesday
Tuesday
How many calories did you have for breakfast? 100
100
How many calories did you have for lunch? 200
200
How many calories did you have for dinner? 100
100
How many calories did you have for your snack? 50
50
Calorie content for Tuesday: 450
```
