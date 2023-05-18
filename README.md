# Commencement Address
## UC Berkeley, Data Science, 2023
### Prof. Joseph M. Hellerstein
#

Good evening Graduates!!! We are SO *VERY* **PROUD** of you all!!

As a Professor here at Berkeley who designed some of your Data Science courses, I’m in the unique position to be able to confirm that you worked your little golden bear *tails* off to get to this day. You *earned* this celebration. Be proud!

Candidly, though, this bizarre ritual of foolish robes and foppish hats --- this is only *partially* for you. It is also --- some would say *mostly* --- for the people who got you here. Your parents. Grandparents. Guardians. Your relations. Your ... correlations. Perhaps some of you have little nieces and nephews ... in the remainder of this lecture we shall refer to them as Minibatches. Terminology aside, the point is this: many, many people helped to get each of you to this day.

And now, because this lecture is as much for family as it is for students, I have the opportunity to review some of the introductory material you already know, in preparation for the exam. (I’m sorry, what’s that? Dean Chayes? This is a commencement address, not a lecture? As my own college-aged children will tell you, I tend to lecture a lot. Professors gotta profess! Stand back!) We'll cover four topics: Relations, Correlations, Transactions and a Domain Emphasis ... that's right!

## Relations
Our first topic today is one that I teach in Data Science 101. It’s the definition of a *relation*. I’m sorry to tell you, moms, dads, grandparents ... in Mathematics, a *relation* is nothing more or less than a set of ordered pairs *(x, y)*. A textbook example is the relation "greater than", which contains all pairs such that *x* is greater than *y*. You know .. like the pair (x = 10, y = 9) --- 10 is greater than 9 --- and a large number of pairs where *x = Berkeley* and *y = any other University in the universe*. Yes, we have mathematically represented the fact that Berkeley is the greatest University in the Universe. Nobody said Relations cannot be opinionated. And we love them for it, don't we?

Meanwhile, in Computing the term *relation* covers any *set of tuples of the same arity*. Or in plain English, a relation is table of data in rows and columns. Yes, relations are data too! And with these higher-arity relations, we can get more expressive in the data we represent. In fact we can have relations --- data --- that relate other relations to each other! We call these *Relationships*. Yes, that's a technical term as well. Let me give you an example.

Let's imagine a relation---a data table---that represents the graduates of the Class of 2023. Each row will represent a unique Graduate. We'll have a column for your student ID, another for your name, another for GPA, location of your first kiss, favorite professor --- you know, the many features that make you You. Then we might have a second relation we'll call Issues. Each row will be a unique challenge that we face in our world today. This relation might have any number of rows, growing over time. And it will surely have a huge number of columns that capture the particulars and nuance of each Issue.

But I want you all to focus on another relation, a third relation that connects the first two. This is a *relationship* ... one that we'll call Impact. Its first column records a student ID from the Graduates relation. Its second column records the ID of an issue in the Issues relation. So each row of Impact connects a particular Graduate to a particular Issue. This relationship will capture and quantify the ways in which the class of 2023 impacts the world's issues. 

I cannot *wait* to see how this relationship grows over time. As Graduates of Berkeley's Data Science program, this is your mission and your superpower: to connect to Issues. To form relationships. To add to the record.

## Correlations
Our second topic in today’s lecture is *Correlation*. No, a correlation is not a very important family member. Correlation is a statistical term --- a measure of how related two things are. 
Correlations are empirical --- we observe them, we measure them. (Hence the term Data *Science*.)
For example, an observant Data Science student might notice the following correlation: each day that a Berkeley student skips a class, a parent somewhere bursts into tears. Yes, it's true. There are correlations between your behavior and other people's lives. Don't let anyone say you didn't learn a moral code here at Berkeley.

Now, can anybody tell me what Correlation does not equal?  That’s right: Correlation does not equal Causation. A classic example here is intelligence and mortality. Did you know that 100% of people with an IQ above 130 end up dead? Yes, it's true. Now, only 3% of the general population has an IQ that high, but a much larger percentage of this graduating class does --- because as everybody here knows, you all are very, very smart. So, is it especially scary for you Graduates? It shouldn't be. In truth, the odds of death are no different for smart people than the rest of the population. Intelligence does not *cause* mortality. Nor, my friends, does it cause virtue. Or vice. 

But I do know --- based in part on my observations teaching at Berkeley --- that intelligence is correlated with the magnitude of other variables, like the size and scope of your role in our world. That means that you, Graduates, are more likely to have an impact on the Issues --- and more likely to have a *larger* impact on the Issues --- than the average person. And I hope that's a good thing. Because you people --- you brilliant Graduates, so full of potential ---  we need you to have large, **positive** impact. What's the saying? With great power comes a strong positive correlation with responsibility? Something like that.

## Transactions
Which brings me to my third technical topic, Transactions. This is a topic from my own research specialization, Database Systems.

Now the idea of transactions goes back thousands of years. If I trade you a sheep for 7 chickens, that is a transaction. In fact there are Sumerian tablets going back 5,000 years, recording transactions like this on clay tablets. Today we can digitally record billions of transactions every day. 

To achieve this, somebody had to define transactions mathematically, so they could be codified in software. 
That somebody was a mentor of mine, Jim Gray, Berkeley's first PhD in Computer Science and one of Berkeley's many Turing Award winners.
So what is a transaction mathematically? Well, a transaction is a finite sequence of actions. The key property of a transaction is that it be Atomic --- either all of the actions are allowed to go forward, or none of them are. Either I get all 7 chickens and you get 1 sheep, or nothing changes hands. 
The decision point for a transaction is called the Commit Point. And note this: transaction commit is achieved via a unanimous protocol --- one requiring all parties to agree. 

So this is how you get the work done: Transactions capture an execution plan --- they actually make changes in the Impact table, something we were simply describing and observing before. Transactions are the persistent, stepwise execution of significant actions, one after another, solemnized by a group so that all parties commit. This is the way we make change, friends. This is the work of making a difference.

And here's another thing: transactions do more than just add to your Impact. Even if they're small! Transactions can make you a better and more successful person. The more you transact, the more connections you make with others. The more you learn. The larger your community. Social network theory teaches us that having a large number of small connections --- weak ties, they're called --- makes people more open to new ideas, and more able to adapt to new challenges. So, Graduates, I hope you will transact a lot, in many relationships. I hope you will commit together. I hope you will keep on learning. 

## Domain Emphasis: Psychology
So far, this last lecture I'm imposing on you has been largely focused on mathematical and computational topics.

But one of the unique features of the Data Science degree you Graduates pursued is the Domain Emphasis, in which each one of you studied *another* academic domain 
and looked at ways that your Data Science knowledge can have impact in that domain. 
I am so very proud of your breadth. Our breadth. We did not choose to spend our formative years at a vocational school, or some mere "institute of technology". We chose to attend a proper University of Higher Learning. And as Data Science majors, you graduates have all taken the opportunity offered by our University's breadth with your Domain Emphasis.

In that spirit, my lecture today will also have a Domain Emphasis: the field of Psychology. And for a moment, what I'd like to discuss is a serious matter. The psychological data, from the CDC and others, shows that the last years have been hard on young people --- on you folks --- in unprecedented ways. This is not just a bunch of numbers for me. I have college-aged kids myself. I know that you have struggled in ways that my generation, your parents' generation, did not.

And yet you Graduates in the Greek Theater today made it. You made it. I'm so proud of you. I don't doubt that you bear scars, one way or another. And maybe you have friends who didn't make it, or didn't make it yet. I understand that. I hope you do too. Keep helping each other.

Now, earlier in this lecture I took advantage of the English language, I exploited the way that our words can have many meanings. That is to say I made some Dad Jokes. At this juncture I'd like to redefine some of our key Data Science terms once again --- this time, as they're used in the field of Psychology. Notably the distinction between Transactional and Relational contracts between people.

In Psychology, *transactional* contracts are bounded, impersonal obligations. They generally emphasize specific tasks, time
frames and monetary returns with little emphasis on extended relationships between the parties. By contrast, *relational* contracts include additional aspects; they involve long-term, 
less-defined, socio-emotional obligations, characterized by attributes such as trust. The relational 
contracts are the deep ones, the ones that last, the ones that matter most to long-term success for individuals and organizations. Even though they're the hardest to quantify and describe!

It's so critical to realize, in the midst of all your technical and mathematical excellence, in your pursuit of data and its analysis, that the world is a complex network of these unquantifiable human relationships. The world is full of people. It's messy. Complicated. Much too hard to model accurately, I don't care how many billions of parameters you use.

## Conclusion
As I said before, to make change we have to *transact* --- we have to commit together to persistent action. But remember, in the end, it's the Relational *interactions* that sustain us. Consider that word carefully: "interactions". Actions *between* people. Those relationships are what really matters. The pairs (x, y) where x is a person --- You --- and y is another person. I said earlier that transactions are your method for Impact. But Interactions ... those are the actions that will make your life meaningful. The actions that will do the most good, psychologically, are relational in this sense.

Graduates! Enough lecturing. Look at you! You're young and accomplished. You're brilliant and you're beautiful. You're dressed in the most ridiculous outfits, but you're bursting with potential. You did it! Your future is here! And to every thing there will be a season --- a time to transact, a time to interact; a time to relate, a time to correlate; a time to cause and a time to commit. But for today ... well today is a time to celebrate! Because, Class of 2023, it's your Graduation Day!  Congratulations to you all! Well Done! Go Bears!

