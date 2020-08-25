# Database Challenges

## Question 1

Please see the attached EDR diagram image. The diagram was submitted as a solution to storing employee Cellphone data, voice and sms usage.
Discuss at least one improvement that can be done to the ERD.

## Question 2

An analyst has asked you to run a query to see the number of movie tickets per genre that was sold in December last year. The data he needs is spread across two tables.


Table Examples:


[Tickets] (Stores all the movie tickets sold) 


TicketID	| #Seat Number | #MovieID
--- | --- | --- |
10 | 1A | 1
20 | 2B | 2
30 | 4C | 3


[Movies] (Stores all the different Movies)


MovieID	| #Name | #Genre 
--- | --- | --- |
1	| Citizen Kane | Drama
2 | Shutter Island | Mystery
3 | Scarecrow | Comedy


Using a SQL script, retrieve the data the analyst requires.

# Back-end Code Challenges
* Only send back the code required for your the challenges

## Question 1

Write a C# method that will take, as input, a string and dependent on the string length prints out the following:
1. If the length is a multiple of 2 your method must print out "Stack"
2. If the length is a multiple of 4 your method must print out "Overflow"
3. If the length is a multiple of 2 and 4 your method must print out "Stack Overflow!"

## Question 2
This task is about code refactoring. Below you are given 4 classes Animal, Dog, Horse and Sheep.

You need to refactor Dog, Horse and Sheep as you see fit. The goal is to make the classes more maintainable. You should apply any principles or patterns you think are necessary.

Don't make any change to the class Animal.

```csharp
    public class Animal
    {
        public string Eat()
        {
            Console.WriteLine("Yummy");
        }

        public virtual string MakeNoise()
        {
            Console.WriteLine("DurrrDurrr");
        }
    }
    
    class Dog
    {
        public string Eat()
        {
            return "Yummy";
        }

        public virtual string MakeNoise()
        {
            return "Woof";
        }
    }
    
    class Horse
    {
        public string Eat()
        {
            return "Yummy";
        }

        public virtual string MakeNoise()
        {
            return "Neigh";
        }
    }
    
    class Sheep
    {
        public string Eat()
        {
            return "Yummy";
        }

        public virtual string MakeNoise()
        {
            return "Baaah";
        }
    }
}

```
# Front-end Code Challenges

## Question 1
Given the below code snippet, solve the problems that follow:

```html
<div id="firstDiv" class="red-card">
<div id="secondDiv" class="red-card">

<style>
    #secondDiv {
        background: orange;
    }

    div {
        height: 150px;
        width: 150px;
        background: green;
    }

    .red-card {
        background: red;
    }

    .yellow-card {
        background: yellow;
    }
</style>
```

1. What will the colour of both div elements be?
2. How would you dynamically target ```firstDiv``` and make it's colour pink? (provide the code snippet)
3. How would you dynamically target ```secondDiv``` and add the ```yellow-card``` class to its class list? (provide the code snippet)

## Question 2
Consider the function below:

```javascript
function legal(x) {
    console.log(x);
    var x;
}
```

1. Why will the function be parsed correctly? 
2. How could you introduce a stricter syntax to variable/function declaration and avoid this behaviour?
