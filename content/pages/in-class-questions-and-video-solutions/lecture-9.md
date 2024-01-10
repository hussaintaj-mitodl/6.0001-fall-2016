---
content_type: page
description: This page contains in-class questions for Lecture 9.
draft: false
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 9
uid: d168b144-bfeb-0cd9-daf8-c345966e90d4
---
### Getters and Setters

apple\_no\_way

1. here\_here
2. Which of the below is a getter method for the number of wheels?           
      
    get\_weebs 3     
      
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}  
    def get\_wheels():  `abc`         
    {{< /quiz_choice >}}  
      
    def get\_wheels 2     
      
    {{< quiz_choice isCorrect="false" >}}  
    def get\_wheels():        
    {{< /quiz_choice >}}  
    {{< quiz_choice isCorrect="false" >}}  
    def get\_wheels(self):          
    {{< /quiz_choice >}}  
    {{< quiz_choice isCorrect="true" >}}  
    def get\_wheels(self):          
    {{< /quiz_choice >}}{{< /quiz_choices >}}  
    {{< quiz_solution >}}  
      
     

{{< resource uuid="c4e79feb-d329-f620-2a0b-250ea3c746aa" >}}

1. {{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

### Subclass

1. What line could replace `____blank____` to create a class that inherits from `Animal` in the code below?           
      
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}} class Dog(Animal): {{< /quiz_choice >}}          
    {{< quiz_choice isCorrect="false" >}} class Animal(Dog): {{< /quiz_choice >}}          
    {{< quiz_choice isCorrect="false" >}} class Dog(object) {{< /quiz_choice >}}{{< /quiz_choices >}}          
    {{< quiz_solution >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

With this definition of Dog, you run a program with line1, line2, and line3 above. What happens? Refer to the lecture slides for the code making up the "Animal" class.

{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}} Error on (line1) because Dog does not have an \_\_init\_\_ {{< /quiz_choice >}}          
{{< quiz_choice isCorrect="false" >}} Uses the \_\_init\_\_ from Animal, but then an error (line2) because Dog does not have a set\_name method. {{< /quiz_choice >}}          
{{< quiz_choice isCorrect="false" >}} Uses the \_\_init\_\_ and set\_name from Animal, but then an error (line3) because all methods must return something. {{< /quiz_choice >}}          
{{< quiz_choice isCorrect="true" >}} Runs, creates a Dog object with age=7 and name="Ruffles", and prints "ruff ruff" {{< /quiz_choice >}}{{< /quiz_choices >}}          
{{< quiz_solution >}}

{{< resource uuid="3132d269-6354-5a69-3b6e-44be988225f9" >}}

{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

 

```plaintext
____blank____
 def speak(self):
  print("ruff ruff")

(line1) d = Dog(7)
(line2) d.set_name("Ruffles")
(line3) d.speak()
```

```plaintext
----------------------------------
----------- Given ------------
----------------------------------
class Car(object):
 def __init__(self, w, d):
 self.wheels = w
 self.doors = d
 self.color = ""
----------------------------------

(A)    def get_wheels():
 return wheels

(B)    def get_wheels():
 return self.wheels

(C)    def get_wheels(self):
 return wheels

(D)    def get_wheels(self):
 return self.wheels
```