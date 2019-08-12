---
title: OOP - lexicon overview
layout: post
weight: 10
hidden: true
---


Lesson Plan Template:
===


**Course**: DS   <br/>
**Mod**: Mod 2    V2                <br/>
**Topic**:  OOP Intro Principals and Practice  <br/>
**Amount of time**: 70-90  minutes <br/>
**Author**: Alison Peebles Madigan  

Adapted from the ds-lesson-starters repository [here](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/lesson-plans-by-mod/Module-2/oop-1-lexicon-terms-concepts-brick-10)

***

## Lesson Summary:

This lesson introduces the concept of OOP by building upon student's knowledge of defining function and their previous exposure to instances of class objects through pandas DataFrames. From there, simple class examples are demonstrated, and student's knowledge is checked through exercises asking them to modify and extend these classes with additional functionality. Student's are then posed with a question regarding how to design a class to monitor stock, which should open up a small discussion.

#### Topic:
OOP: Or why a data scientist should care about classes
#### Learn.co material:
Section 10

#### Prerequisite knowledge/ Prework:
- Defining functions
- Pandas dataframes


#### Learning goals for this lesson:

- Goal 1: describe the limits of custom functions
- Goal 2: identify and paraphrase the vocabulary of Object Oriented Programming
- Goal 3: build a new small sample class
- Goal 4: map out the blueprint of a class for the stock monitoring data science pipeline

#### Misconceptions:
OOP is something only PROGRAMMERS do


#### Materials
- slide deck
- ipynb
- airlines databases

***
## Lesson Plan
**Step**: Activation <br/>
**Time**: 5 min

#### Scenario
You want to build an automated datascience pipeline to monitor and predict stock performance. What would you do?

#### Learning Goals:
While we won't complete this today, in order to build that you'd need to:

- Describe the limits of custom functions
- Identify and paraphrase the vocabulary of Object Oriented Programming
- Build a new small sample class
- Map out the blueprint of a class for the stock monitoring data science pipeline

**Step**: Learning goal 1:  describe the limits of custom functions <br/>
**Time**: 5 min
 
_Discussion_

### Review prior knowledge:
- Why do we use functions?
 - they are repeatable! 
 - super cool!
 - save yourself work!
- But how are they like a pipe?
 - things go in and things fall out - nothing stays with the function

 _Fun Billy Mayes slide bit_
 
 _Application_ : Comes at end

**Step**: Learning goal 2:  identify and paraphrase the vocabulary of Object Oriented Programming <br/>
**Time**: 10 min

_Demonstration_

- Guide them through discussion of code along.
- Point out that even when an object has no data, you can still call it's attributes

_Application_

- Have them explore the methods and attributes of data frames


_informal assessment_
Quick knowledge check:

- Where can you find the list of available attributes and methods for a pre-created class?<br>
In the documentation
- what's the key difference between an attribute and a method?<br>
attribute is like a characteristic or stored variable, method is a function within the class
- What is the appropriate sequence of these words? A variable becomes an ___ when you ___ a ___ .
 - A: Initialize
 - B: Class
 - C: Object<br>

A variable becomes an Object when you Initialize a Class.

**Step**: Learning goal 3: build a new small sample class <br/>
**Time**: 15 min

_Demonstrate_:

Walk through car example in student facing content.

**Answer**

```
    def stop(self):
        print('stopped')
        self.moving = False
```

_Application_


**Task:** Make a pizza class

- Pizza should take one topping and the size of the pizza when instantiated
- Pizza should have an attribute toppings that stores toppings in a list
- Pizza should have methods:
	- add_topping
	- print_toppings
	- remove_topping



**Extra Credit**

- Pizza should have an attribute "order_status" that starts as equaling none. 
- order_status should change depending on the methods:
 - done_adjusting_order
 - preparing
 - delivering
 - delivered
- order_status, when called, should return in the form of a sentence.

**Solution**
(Alison is still working on it)

**Step**: Integration:  map out the blueprint of a class for the stock monitoring data science pipeline <br/>
**Time**: 15 min

_Review_: All that they have covered<br>

_Synthesis_:<br>
Make a plan for a stock class

- What would you want it to take when instantiated?
- what methods would you want it to have?
- for predicting, would you want it to default to one modeling technique? or would you be able to specify?
- What input data would it take?
- What attributes would you want to be able to reference?


There is no EXACT solution, but encourage them to mock up the class in code, even if they need to do lots of `### function would be here` text

**Step**: Assessment
**Time**: 15 min

_Scenario_<br>
It's Greg again. 
You overhear him talking to his peers about how OOB is irrelevant to the data science skill set. 
When Greg meets with you for his one-on-one, how would you correct him?

- Have them write down their answers and share in pairs
- then have them write to slack channel the favorite of the two

**Step**: Reflection
**Time**: 5 min

Stop light check!<br>
One item you feel green - ready to go on<br>
One item you feel yellow - kind of get but not quite<br>
One item you feel red - absolutely do not get<br>