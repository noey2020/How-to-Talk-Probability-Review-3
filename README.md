# How-to-Talk-Probability-Review-3

December 23, 2020

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me! 😊

- When we're dealing with multiple random variables,
for instance, a patient's heart rate, cholesterol level,
blood pressure, whether they're ill, and so on,
the easiest situation is when all these random variables
are independent of each other, when they don't influence
each other.
In those cases, we can just model each of them separately,
and not worry about interactions between them.
The more interesting situation by far though is when
they are dependent, and then we need ways of understanding
and quantifying this dependence.
So today, we'll begin by formally defining what it means
for two variables to be independent, and then we'll start
looking at dependence more closely.
Okay, so this is the formal notion of independence.
We say two random variables, X and Y are independent,
if the probability that X takes on some value little X,
and simultaneously, Y takes on some value little Y.
It's just a probability that X is little X
and that Y takes on the value little Y.
In other words, X being equal to little X does not
either make it more likely or less likely
that Y will be equal to little Y.
They don't influence each other.
Let's see an example of this.
Suppose you have a standard deck of 52 cards,
and you pick a card at random.
And you define two random variables based on this card.
X is the suit, clubs, spades, hearts, and so on.
And Y is the number on the card.
Six, seven, eight, jack, queen, king.
Are X and Y independent?
Yes they are.
Let's see why that's the case.
Intuitively it makes sense.
But formally, let's look at an example.
What is the probability, for example,
that X is heart and Y is six?
What is the probability of getting the six of hearts?
Well, it's one out of 52 cards, so it's one over 52.
Now, what is the probability, just by itself
that X is hearts?
If you pick a card at random, the probability
of getting a heart is a quarter since there are four suits.
And what's the probability that Y by itself is six?
If you pick a card at random, the probability
of getting a six is one out of 13.
And indeed, one over 52 is equal to
a quarter times one over 13.
And so these two variables are independent.
Let's do another example.
Suppose you have a fair coin and you flip it 10 times.
And you let X be the total number of heads you see,
and let Y be the very last toss, heads or tails.
Are these independent of each other?
So intuitively, these do not seem independent.
For example, if X is large, if there were lots of heads,
then it makes it more likely that the last toss
was also a heads.
It seems like they really influence each other.
But let's see more precisely why this formula breaks down.
Why is this formula violated?
Let's just look at a particular setting.
What is the probability that X is 10 and Y is tails?
What is the probability that all 10 tosses are heads,
but the last toss is a tails?
Clearly zero, it cannot happen.
But now if you look at these two events separately,
the probability that all 10 coin tosses are heads
is greater than zero, it's a half, times a half,
times a half, 10 times.
So that's one over two to the 10th.
And the probability that the last toss is tails
is just a half.
And clearly zero is not equal to one over two to the 10
times a half.
And so these variables are not independent.
They are dependent.
Here's another example.
So now we have two variables, X and Y,
which each take on values minus one, zero, or plus one.
The distribution is summarized in this table over here.
For example,
this entry over here
means that the probability that X is negative one and
Y is one is a .24.
So that's what this table means.
Needless to say, the numbers in the table add up to one.
Are X and Y independent?
Well, we have to check this formula.
In order to do that, we have everything we need
for the left hand side, but now for the right hand side,
we need the individual distributions for X just by itself,
and Y just by itself.
Let's obtain those.
Let's look at X by itself.
X can take on value either minus one, zero, or plus one.
What are the probabilities of these?
Well, the probability that X is minus one,
X can be minus one in three ways.
Any of the three situations on this line,
so we just add them up.
The probability that X is minus one is .4 plus .16 plus .24,
which is .8.
What is the probability that X is zero?
That's on this line, so we add up those numbers,
and we get .1.
And what is the probability that X is one?
That's this line, and that's again .1.
And of course, these things add up to one again.
That's the distribution of X.
Now let's go ahead and do the same thing for Y.
So we have Y over here.
It takes on values minus one, zero, or plus one.
And the probability that Y is minus one
is this line over here, so it's .5.
The probability that it's zero is this line here,
so it's .2.
And the rest is of course .3.
So that's the distribution of Y.
Now to check if these are independent,
we have to check that every entry in this table
of the joint distribution, is the product
of the corresponding entries in the
individual distributions.
So for example, let's look at this entry here.
For X equals minus one, and Y equals one.
Is this equal to this number times this number?
Yes it is.
That entry is okay, and in that way we keep going
and we check all nine of these entries,
and it turns out that in every case,
the entry in this table is equal to the product
of the corresponding entries in the individual tables.
So this, for example, is equal to this times this.
And so X and Y are independent.
So now we'll start talking about dependence.
Let's just start with a little bit of a total experiment.
Suppose you pick a person at random
from whatever city you're living in,
and let H be their height and W be their weight.
Are H and W independent of each other?
Intuitively, one would think that they are not.
The reason for that is that people who are taller
are also likely to be heavier.
So it seems like there's some sort of correlation
between that.
A positive correlation, in fact.
We would expect height and weight
to be positively correlated.
Here's a picture of what it might look like.
What I've drawn over here is,
suppose one took a sample of about 20 people
and plotted their heights and weights.
It might look something like this.
There's a general upward trend.
People who are taller tend to be heavier.
Now, of course, knowing someone's height,
you can't exactly predict their weight.
And nor is it a hard and fast rule.
For example,
this person over here is taller than that person,
and is also lighter.
But there is a general trend that the points
are sloping upwards.
And what this also means is that we would expect
the average of height times weight
to be greater than the average height
times the average weight.
This is because the large values of H
tend to be paired with the large values of W.
So if you multiply them together,
you get a sort of squaring effect.
So the average of H times W
is likely gonna be higher than the average H
times the average W.
This is what positive correlation looks like.
The other two types of correlation
are negative correlation and a complete lack of correlation.
In negative correlation, the points
rather than seeming to slope upwards, are sloping downwards.
Like this.
And in this picture, the larger values of X
tend to get paired with the smaller values of Y.
As a result, one would expect that the average value
of X times Y is actually less than the average X
times the average Y.
And then there's a situation where
no matter how large or small X is,
the Ys on average tend to have the same mean.
And that situation is called uncorrelated.
Over there we would expect that the average value
of X times Y is just the average X times the average Y.
This is a spread of points that's neither sloping upwards
or downwards.
This is a very hand wavy and qualitative view
of correlation.
Can we come up with a precise formula for this?
An actual number that captures correlation?
And this was something that was done
by Carl Pearson at the beginning of the 20th century.
He was interested in the correlation
between a father's height and his son's height.
And so what he did, is he obtained data
from about 2,000 father/son pairs, and he plotted them.
That's the scatter plot you see over here.
On the X axis are the fathers' heights,
and on the Y axis are the sons' heights.
For example, this over here comes from a father/son pair
in which the father is about 66 inches,
and the son is about 60 inches.
What you can see over here is a general upward trend.
There does seem to be a positive correlation.
What Pearson did, was to define something
called a correlation coefficient.
This is a number between minus one and plus one
that captured the degree of correlation.
So a value of minus one means perfect negative correlation.
And a value of plus one means perfect positive correlation.
Let's see some examples of these values.
When the correlation coefficient is one,
like in this picture, there's a perfect linear relationship
between the two variables.
Then when the correlation drops a little bit, to say .75,
there's still a very clear upward trend.
When the correlation drops further to .25,
the points start to look a little bit more like a blob.
The case where r equals zero, is the uncorrelated situation.
Now when the values start to drop below zero,
then we get the symmetric situation
with negative correlation.
It moves more and more towards a perfect linear,
but negatively sloped relationship.
What is the formula?
How does one obtain this value, r?
In many ways, we anticipated it
when we were back here.
We said that one way to determine correlation
is to compare the expected value of XY
with the expected value of X times the expected value of Y.
So let's just look at these two quantities,
the left hand side and right hand side,
and look at their difference.
This is what we call the covariance.
The covariance between two variables, X and Y,
is just the expected value of XY
minus expected value of X times expected value of Y.
When this is positive, it means
we have a positive correlation.
When it's negative, we have a negative correlation.
And when it's zero, X and Y are uncorrelated.
A very nice, simple measure of dependence.
Now the one drawback to this, is that it actually
is not necessarily in the range minus one to plus one.
You can show mathematically that the range
that covariance lies in is minus the standard deviation of X
times the standard deviation of Y.
That's the smallest it can be.
All the way to the standard deviation of X
times the standard deviation of Y.
It lies somewhere in that range.
If we want to normalize it, to a value in the range
minus one to plus one, what should we do?
Let's just divide it by the standard deviations of X and Y.
And that is Pearson's correlation coefficient.
It's a nice, normalized value in the range
minus one to plus one.
One interesting question is how this relates
to independence.
When two variables are independent,
we know that they are gonna be uncorrelated.
But it turns out that the reverse need not be the case.
Variables being uncorrelated is actually
a much weaker condition than them being independent.
It's quite possible to have two variables
that have zero correlation, but are dependent on each other.
So it's a one way relationship.
Independent means uncorrelated, but uncorrelated
does not mean independent.
Let's finish with an example, a numeric example
where we can actually see these numbers at work.
Here we have a pair of variables, X and Y,
and we want to figure out the covariance and correlation
between them.
We want to figure out the level of dependence
between these two variables.
Let's write down the formula again,
just to remind ourselves.
The covariance of X and Y is the expected value of XY
minus the expected value of X times the expected value of Y.
In order to figure this out, we do need to figure out
the expected value of X and the expected value of Y.
So let's start by doing that.
Let's just look at X by itself.
X takes on values either minus one or plus one.
The probability that X is minus one,
well X is minus one in these two lines,
so the probability is a sixth plus a third, which is a half.
So the probability that X is plus one, is also a half.
And this means that the expected value of X is just zero.
While we're at it, let's also do the variance.
The variance of X is the expected value of X squared
minus the expected value of X squared.
Let's see what that is.
X is either minus one or plus one,
so X squared is always one.
The expected value of X squared is just one.
This we know is zero, so the variance is one.
That means that the standard deviation of X is also one.
The typical distance of X from the mean is one.
And in fact, that makes perfect sense,
since the distance of X from the mean is always exactly one.
Now let's go ahead and do Y.
Y is either minus three or plus three.
And it's minus three in these two lines,
and that's probability of a half.
And plus three is probability of half,
so the expected value of Y is again zero.
And the variance of Y is the expected value of Y squared
minus the value of Y, the whole thing squared.
So Y squared, Y is either minus three or plus three.
So Y squared is exactly nine.
The expected value of Y squared is nine.
The variance of Y is nine, which means
its standard deviation is three.
The typical distance of Y from its mean is three.
In fact, it's always distance three from its mean.
Great.
Now in order to compute the covariance,
we also need X times Y.
Let's do that, too.
Let's leave a little space for it here.
X times Y is either minus three or plus three.
The probability of minus three,
it's minus three in these two lines.
It's minus three probability 2/3
and plus three probability 1/3,
which means that the expected value of XY
is minus three times 2/3 plus three times 1/3,
which is minus one.
Good.
So now we have everything we need for the covariance of XY.
It is minus one minus zero, so it's minus one.
There is a negative correlation between X and Y.
Now to get the actual correlation coefficient,
we divide by the standard deviations.
We take the covariance and we divide it
by the standard deviation of X
and the standard deviation of Y.
And so that's minus one.
The standard deviation of X is one.
The standard deviation of Y is three.
So the correlation is -1/3.
There's a weak negative correlation
between these two variables.
That's it for our probability review.
We're now in a situation where we can start doing
generative modeling in which we are able
to actually capture the dependence between features
in order to get more accurate classification.

I included some posts for reference.

https://github.com/noey2020/How-to-Talk-Probability-Review-2

https://github.com/noey2020/How-to-Talk-Generative-Modeling-in-One-Dimension

https://github.com/noey2020/How-to-Talk-Probability-Review-1

https://github.com/noey2020/How-to-Talk-Generative-Approach-to-Classification

https://github.com/noey2020/How-to-Talk-of-Fitting-a-Distribution-to-Data-

https://github.com/noey2020/How-to-Talk-of-Host-of-Prediction-Problems

https://github.com/noey2020/How-to-Talk-of-Useful-Distance-Functions

https://github.com/noey2020/How-to-Talk-of-Improving-Nearest-Neighbor

https://github.com/noey2020/How-to-Talk-of-Prediction-Problems

https://github.com/noey2020/How-to-Talk-Matlab-Tricks-and-Tweaks

https://github.com/noey2020/How-to-Talk-Trading-and-Investing

https://github.com/noey2020/How-to-Work-in-Matlab-Development-Environment

https://github.com/noey2020/How-to-Talk-Vaccines

https://github.com/noey2020/How-to-Talk-Regression-in-Matlab

https://github.com/noey2020/How-to-Get-Started-in-Matlab

https://github.com/noey2020/How-to-Convert-Data-from-Web-Service-Using-Matlab

https://github.com/noey2020/Quote-for-the-Day

https://github.com/noey2020/How-to-Talk-Good-Investment-Strategy

https://github.com/noey2020/How-to-Talk-of-Good-Plan

https://github.com/noey2020/Thought-for-the-Day

https://github.com/noey2020/How-to-Talk-Stock-Watch-of-the-Day

https://github.com/noey2020/How-to-Talk-Data-Science

https://github.com/noey2020/How-to-Talk-Fundamental-Analysis

https://github.com/noey2020/How-to-Read-Company-Profiles

https://github.com/noey2020/How-to-Import-Data-from-Spreadsheets-and-Text-Files-Matlab-Without-Coding

https://github.com/noey2020/How-to-Talk-Model-of-Stock-Market-Prices-

https://github.com/noey2020/How-to-Talk-Digital-Wallets

https://github.com/noey2020/How-to-Talk-Investing

https://github.com/noey2020/How-to-Double-Your-Money-in-5years

https://github.com/noey2020/How-to-Talk-Matlab

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!
