# Gruppe 3 - Uptight Wealth
*Ikke vores valg af gruppenavn*

**Gruppemedlemmer:**
- Cahit
- Marcus
- Michael

# The Necromancer Recruitment Service

<img src="https://sorelosergames.dk/____impro/1/onewebmedia/Cover360Test.jpg?etag=%222353cb-5d7c9cc3%22&sourceContentType=image%2Fjpeg&ignoreAspectRatio&resize=1838%2B919&extract=174%2B36%2B1464%2B762&quality=85" alt="Necromancer Inc">

## Assignment 1: Prepare the Ritual
For the Perceptron, we are going to need a activation_function, and a perceptron_function
1. Make an **activation_function**, that takes a value, and return **1** if the ```value > 0```, and otherwise returns **0**
2. Test the **activation_function**, using an array of numbers from -3 to 3, with an increment of 0,3. Plot the results, to give a visual indication of the response from the activation_function
3. Make a **perceptron_function**, that takes two arrays, **inputs** and **weights** for those inputs, and returns a sum from the dotted outcome of the arrays. 
4. Test the **perceptron_function**, by feeding it the following, and get 26 as the result:
```python
perceptron_function([3,4,5], [1,2,3])
```

## Assignment 2: Judge the bodies
1. Read in the dataset [**undeads.csv**](https://raw.githubusercontent.com/Micniks/Python-Week12-Group-3-Assignments/main/undeads.csv) into a pandas dataframe, and display the dataset.
2. Make a new scatter plot with datapoints of Age vs Durability from the dataset. Choose different colors for **Zombie** and **Skeleton**
3. Now change the 'Type' column to represent **Zombie as 1** and **Skeleton as 0**
4. Use these weights herè in order [-9, 7], [-8, 7], [-7, 7] to determine if the following 5 undeads are skeletons or zombies: 
```python
[[47, 41.2, 'Skeleton'], [44, 76.0, 'Zombie'], [59, 36.4, 'Skeleton'], [52, 68.0, 'Zombie'], [51, 39.6, 'Skeleton']]
```
5. Which of the three weights get's the most correct?
6. Find the (approximately) optimal weights using the perceptron learning algorithm
7. Plot the division line

<img src="https://i.pinimg.com/originals/fc/4d/de/fc4dde5d86103120bab08199d5b00143.jpg" alt="Necromancer Inspection" width="500">

_______________________

Vi benytter datasættene: [undeads dataset](https://raw.githubusercontent.com/Micniks/Python-Week12-Group-3-Assignments/main/undeads.csv)

Dette github repository er tilrettet opgavestillinger, så udspecifieret her: [Uge7 Opgave](https://docs.google.com/document/d/1ojSiBWwLo4-Rc7763vx6aVEYdNluATOMja9qqk4dodU/edit#) 
