# 27.3.2019 #

## Perverted authorities ##

Often a software developer take over the resposibilites of the authorities.
Because the authorities are not do what they are should do.

Authority                                             | Boss
----------------------------------------------------- | --------------------------------------------------------
Can do what they want<br> to people to do unter them  | Can NOT do what they want<br>the people do under them                    


For example if there is a authority which
one person under them. And the ony person goes 
is sick or away in vacation the authority can
do the work of the persn. The difference to a
boss is that he can not do the work because
he has never done it.

If you have bosses in your company instead of "good" authorities it will
create always trouble, because they are in charge and must make decision
from things they have never done themselves and so they did know why to
decide.
		  
		  
# 22.3.2019 #

## Pseudo-Scrum ##

I nearly every company I was who setup Scrum in their company
they end in a pseudo-scrum. When I first read the rule of scrum
I was very excited and positiv about this process. But later
when you saw how it was in real life and what happened after
a while. I saw remain a 'pseudo'-scrum culture which is not the
real scrum. They use Jira for Task have some meetings like
Planing, Daily and Retros. But there is no positive attitude
of people anymore. What stays over is like a burned-out hull.
On the outside it looks like scrum but inside the people know
it is dead.

# 20.3.2019 #

## Wrong decisions ##

### Complicated technology ###

Choosing complicated technolgy always leads to problems in future
It is important to play with technology to find technology from
made from people that really "keep it simple".

### Complicated thinking people ###

Complicated thinking did not know they are complicated thinkers
It is important to hire the right people for a project at the
start of the project.


# 12.3.2019 #

## Problem with Scrum as (external) authority ##

### Compensating authorities ###
* Scrum does not solve problems with false authority
* Team as shared authority (self-help group)
* No work leads to arguing and dicussion
* Gelled Team that take over as authority

### Team is responsible ###
* The responsibility is shared to all members of team like in a democracy
* The one who talks the best and has the best arguments often lead indirect


# 7.3.2019 #

## Usability in Coding ##

 * Normal we talk of usability in terms of using an application or an object.
 * Coders are user of code. 
 * Code needs to be readable and understandable and learnable (usability for coders)
 * Code needs to nbe maintain able 
 * So code do not can be complicated

# 6.3.2019 #

## Always at least 3 Teams ##

Everything good is 3.

You need a team
* for the past
* for the current
* for the future

Also these three times work parallel and change. The current team with be the
past team in the future. The future team will get a current team. And the past
team with fade out on the other new people will come for the future team. You
can also compare it with the 3 generation you have in families. The kids, the
parent and the grandparent. This system works.

The team for the past need to maintain especially the old software.
The team for the current is the team that active with the current task of current software.
And the team for the future needs to research and beginn the future products.

The current team has to learn from the future team. The past team form the current team.
So you have consistantly knowledge transfer.

Mostly we only have one team and they have todo all 3 areas which is not good.
Often the past is a burden for the current team. Also hinders the current to do things
for the future. So old things that hold the future which is comming if you want or not back.

Often manager for to make thoughts for the future and for the past. They stick in the daily
life of the current. But if you want or not the future is coming and if you want to survive
int he future you have to care and the past. Because the past can be a stone on your leg that
holds you back in going into the future. And the company be in danger to going to die.

## Network-based programming ##

### Examples of networks ###

* Human body blood stream
* Human brain cell network
* Electricity grid



# 18.9.2017 #

# Repair Guide Heading #

*Citate*

## Introduction

## Solution

## Problem

---

# Design Problem with Layers #

## Introduction

Layered architecture are very important to seperate
responsibility of each layer.
The user interface layer is responsible for
having a usable interface between human and the
business layer.
The business layer is reponsible to do the business
logic of the application. But not to have an
interface for the end user. 
The data access or persistence layer is responsible
to store and load data for the business layer.
The data layer have no user interface. The
business layer has no user interface. It is simple
not in his reponsibility.
Each Layer work hand in hand with each neighbour layer.
The user interface layer does not work with the data layer.
They are not neighbour and must not know each other or
even must not no that each other exists. 
For instance some software have no graphical interface,
but only a API (advanced programming interface).

## Solution

Design your business seperate from user interface and
data access (persistance) layer. Do not care how the
user interface will look like. Do not care how the
data is stored in the persistence layer. Do this first
and do your business write. 
Do not make the mistake design first a user interface
if you do not know your business logic.
Do not design your data tables before you do not know
your business.

Write a simple console application and use the
business layer.

[User Interface]    [Data Access Layer]
	    ^          ^
             \        /
	      v      v
	  [Business Layer]


# 16.9.2017 #

## List of contents

* Mission Goals

* Identify unclean code 

	* Weed seed
	* Foo Bar
	
* Clean up instruction (like iFixit Repair your code)

	* Design
	
		* Architecture
			* Fix incompetent software architect :-)
			* Fix to much table in database in DB (blowed DB)
			* Fix to much properties forms in UI (blowed UI)
			* Fix business logic in every layer of BL (UI, DB, ...)
			* Fix no existing API in BL
			
		* Minimum 3-Tier-Application
		* Client Server
		* Useful Patterns
		* Abstraction
			* Power of Abstraction
		
	* Implementation
	
		* Naming
			* Classes
			* Variables
			* Function and Methods
	
	* Tests
	
		* TDD (only fun if you like it)
	
	* Production
		
		* Count the Costs
		* Make it new and transform?


# 15.9.2017 #


## List of contents

* Mission Goals

* Identify unclean code 

	* Weed seed
	* Foo Bar
	
* Clean up instruction (like iFixit Repair your code)

	* Design
	
		* Architecture
		
			* Fix to much 
		* Minimum 3-Tier-Application
		* Client Server
		* Useful Patterns
		* Abstraction
			* Power of Abstraction
		
	* Implementation
	
		* Naming
			* Classes
			* Variables
			* Function and Methods
	
	* Tests
	
		* TDD (only fun if you like it)
	
	* Production
		
		* Count the Costs
		* Make it new and transform?


## Mission

People should clearly see why their code got unclean
and clean it themselves.

After you cleaned up your code you, should enjoy
to work on your code again.

Like clean up a messy flat you should enjoy to
live in your flat. If you mess it up again 
yu should be able to clean it up again and
again. To make your flat a better place to live.

## iFixIt / iCleanUp

iCleanUp for software is that was is iFixit for hardware

Repair your thinking phase (collecting information). 
Repair your design.
Repair your tests.
Repair your production code.

## Service

The service is to help people to fix their error
in any phase design, implementation, test, production.

The early you catch the better.


# 14.09.2017 #

## Things that lead to unclean code

... being a full stack developer (you can not be expert in all)
... being new in a big project that runs over years and you does not have all the information in the brain the other have that exists for
... being pride and believe you can all
... having non-IT leaders in authority (see youtube video "the Expert")

## Unclean code leads to ...

... to more unclean code (if new people come in)
... 


# 13.09.2017 #

## Unclean code leads to ...

... burn out
... frustration
... confusing your brain
... headache
... stiff neck
... muscle tension
... dizzyness
... fights at home
... kill family (divorce)
... and much more bad fruits

## Farmer boys and girl in the IT ##

This topic sounds sarcastic, but it only address the issue that people
work as software developer that not called to be a software developer.
Then they are lacking on talents.

## Role of talented (or gifted) person ##

Talents you can not learn, it is given as a gift to a person
with a purpose. Some want to be software developer, but have no
talents. You can not compensate missing talents with more
education.

## Fixing the wrong thing!! ##

Car diesel pump example 1400€ compared to a small pump.

To few software developer people. True, but not the truth.
Leaders in all level are imcompetent.

## Start with business layer, know your business ##

.. not user interface layer
.. not backend layer / persistence layer

Software if often made in layers. Most used is a 3-layered-Architectur
to seperate User Interface, Business Logic and Data Persistance.

Some project start with an existing database and later build
a user interface and business layer on it. This can lead to unclean load.
Because they are built in the wrong other.

I does not like this king of picture
[ User Interface Layer ]
[    Business Layer    ]
[     Data Layer       ]

Your business is your center you are building around.
From your business you can design your UI layer. 
From your business you can design your data layer.
Not the other way around.

Your business and your business object, classes, services
are your foundation of the building. It is the corner stone
this has to be set in the right way. Then you can build up
on top of this a persistance layer and a user interface.

 [ User Interface Layer ]   [     Data Layer       ]
                [    Business Layer    ]

Some start with the user interface and later make the business layer.

My experience over years you have to start with the business first.
You have to know you business. 

Some do not know their business and want to make an application.
If always use a house construction as metapher. If you do not
know that kind of house you want how could you implement it.
Some sit in meeting and says we want a house. Right a task
build a house and next they implementation starts. Someone
starts to build a house and when it is finished. Someone came
and look at and says this is not exactly what we want. But you
does not say how it should look. You only said build a house and
I build one. If you know what you not want. Do you know what
you want?

## Unclean factor

Everything is multiplying. If you have an error in the design it costs
you less to fiy, but this error costs a lot when you have in production.

unclean information factor * unclean design factor * unclean impl factor * unclean 

Clean/Unclean code = Information * Design * Test * Implementation

50% * 70% * 80% = 28% (of 100%) 

Less then 50% its is unclean code.
More then 50% it is clean code.

The early you catch your "uncleaness" better it is.

## Costs

IBM System Science Institute says to find a bug costs for instance in production 100
times more then in design phase.

Design 		  1x
Impl 		 10x
Testing 	 15x
Production 	100x

(see "The Ourageous Cost of Skipping TDD & Code Reviews" from Eric Elliot)



## Role of design

Good design lead to compact error free code. Non-spagetti.
Good design simplify.

## Change, Change, Change, ...

Change is a live style. If you learn new things you
automatically change. But if you does not want to change
then you does not new anything new.

Some protect things tht should change and they hinder
that new things come in that necessary to grow up.

## Boss vs. Authority

Lack of good authority leads to bosses. (little mafia)

## Who is the boss

Sometimes the boss is not the boss. Sometimes take the role
of the boss, because of lake of authority and also they
have the power to do things.

## Keep it complicated

A complicated thinker will always made out of simple or normal thing
a comlpicated thing.

(e.g. 16 pages DWGTiler vs. 4 Pages)

## Weed seed is growing

Unclean design spread out and product weed software.
Weed is growing with every feature you build in.

(e.g. 30 sensor, 50 reports)

A sign is if you inplement a feature and you have
to change it always n-times in the code.

If you have n different content types and you change
and you change it not on one position but have to change
it n-times.

# Simple Robust Good Programming #

## if (obj == null) ##
I do not like NullReference Exception. Why?

First a NullReferenceException is not an exception. If you create a variable that has not value. Is not an exception. Perhaps you have a variable that is empty. Not set. Not defined. The reason why you get a NullReferenceException is, you want access a property from an object that does not exists or is empty or undefined or not set. Whatever? It is more something like.

var a = string.Empty;  // This has a type string but is empty
var b = double.NaN;    // This has a type double and is NaN - Not a Number;
var c = undefined;     // This has not type - Empty what? NotDefined what? 

What means Null? Null means that the object does not exists or is empty or is not defined or whatever. You have yourself define what you mean with null. So why this is an exception? If you have fill out a form where you fill out your FirstName, LastName and you have not started to fill the form out, then the fields in the form are empty. And also the whole the form self is empty.

*Example 1:*

Let say we have Form with your Person data to fill out:

~~~
-------- FORM ----------------

FirstName: [________]
 
 LastName: [________]

 Birthday: [________]     

------------------------------
~~~

The class that stores the Data of the Form:

 ~~~
class Person
{
	string FirstName; // this should string.Empty
	string LastName;  // this should string.Empty, too
}
~~~
PROBLEM!! Person.Empty is static Reference to an Empty object.

~~~
var aPerson = Person.Empty;
aPerson.FirstName = "foo";
aPerson.LastName = "bar";
~~~

Sets the properties of this static object !!

~~~
var person = Person.Empty;
person.Age; // Undefined or Empty

var person = Null;
person.FirstName; // Bang -> NullReference Exception
~~~

Why should every have an exception!! Exception. An empty field or object or glas of water is not an exception. It has a defined state. Empty!!

*Example2:*

~~~
List aList;

aList.Count // Bang -> NullReference

Why a list is not Empty?

var aList = List.Empty;
var aList = []; // JavaScript Empty list in JavaScript

aList.Count // 0
aList.Select(x => x+1) // still an empty list


aList.FirstOrDefault(); // What is the default ?
aList.First(); // On an emtpy list is what?
~~~

## Why we use Null? ##

Because it is in the languages. And nobody think about if this should exists. Null was a mistake of ...
Some languages does not have the concept of Null.
Visual Basic:
VB is good because of the Variant Datatyp. A variable could IsNull or IsEmpty. JavaScript Example:

> a = {}
> a.b // undefined
> a.b = 3
> a.b // 3

## Lambda(OO) ##
The idea behind lambda(OO) is: Lambda means function. OO means object. The object are data. The function create, delete, change and convert data object.

~~~
var objB = func(objA);
var intA = convert(intStr);
~~~

## Lambda Cells ##
To get more robust code I tried to simulate a brain cell. With input values and an output value. If the imput changes the output is also changing according what the function of the cell is. Or you set the input values and invoke a calc to calculated the output.

*Example:*

~~~
class ConvertCell
{
	// Input
	string InputValue { private get; set; }
	
	// Output
	int OutputValue   { get; private set; }

	public ConvertCell()
	{
		InputValue = string.Empty;
		OutputValue = int.Empty; // or int.Undefined
	}
	
	// Input -> Output
	// Output = func(Input)
	public bool Calc()
	{
		if (string.IsEmpty(InputValue))
		{
			OutputValue = Int.Empty;
			return true; // Success state
		}
	
		int i;
		var success = int.TryParse(InputValue, out i);
		
		if (success)
		{
			OutputValue = i;
			return true; // Success state
		}
		
		return false; // Failed state
	}
}

var aCell = new ConvertCell() 
{
	InputValue = "123";
};

var success = aCell.Calc();

if (success) // on success the output value is valid
{
	Console.Write(aCell.OutputValue);
} 
else
{
	Console.Write("Conversion Failed");	
}
~~~

Can you imagine that a program exists of millions of small lambda-cells? There could be a "RangeCell". A Range cell has as input a start number and count and give you a list a numbers.

There could be a "AverageCell". A Average cell has as input a list of number and as output it gives you the average of this values. What cells you would like to have?

Think about cells like as small Lego(R) stones where you can build up a robust application.
Do you mean State or Exception?
If you have an operation is it always good to have a status code. On the status code you could react. There is not need for throwing exception. Because this is not an Exception. What is better?

~~~
var aString = "a123b";

var success = int.TryParse(aString, out i);
~~~

or

~~~
int.Parse(aString) // Bang!! Exception
~~~

Why is this an exception? The string you want to convert into an integer is not present an integer. I want to give example, I beliebe is not ok:

~~~
int a = int.Empty;
try
{
	a = int.Parse("12a3");
}
catch(Exception)
{
	// What to do here?
}
~~~

An exception is an exception something that is out of the rule. If an electric worker switch off the current and the computer goes out and you did not know it, this is an exception. Something that happend that you not expect. If you parse an integer the string could be a integer or not. So it is much better to give back the information successfully converted or not. Then you can act on that information.

## High Order Properties ##

~~~ 
class Person
{
	string LastName;
	string FirstName;
	double Height;
	double Weight;
}
~~~

or

~~~
class Person
{
	Name LastName; // This Properties are all Empty n
	Name FirstName;
	Length Height;
	Weight Weight;
}
~~~

## Values have Units ##

1m + 1mm = 1.001m or 1001mm

Angle  - Rad/Degree/Gon
Length - Meter/Centimeter/Millimeter/...
Time   - Hour/Second/Minutes

1sec + 1hours = 1h1sec;

ISO Units.
Importance of Layered Architecture

    User Interface Layer (GUI or CLI) (interface to human)
    Application Layer (create/delete/change data)
    DataStorage or Persistence Layer (load/store data) 

## Programmer Friendly Libraries ##

We often her the word user-friendly application. But what is you sit the whole day on the computer as programmer. A user of a computer the main task is to write program. To make user-friendly application you have to enjoy what you are doing. And to enjoy what you are doing, programming. You have to use programmer-friendly libraries and programming languages and tools. Programming is often very frustrating for instance if to have to write monoton code. If your library is not easy to handle. If things are not working as they should be and you does not have the source and could not debug why a thing is not happening. The best things you learn to code are very good example. A good example in the whole not only small part. To see how for instance a good 3-tier-application is working. Often die Developer-Network webside have only simple small peaces of stone but not the whole picture. And they are very often lack on good example. I do not believe that the best programmers write this documentation. I believe that hired middling are there to write shallow documentation examples. 
