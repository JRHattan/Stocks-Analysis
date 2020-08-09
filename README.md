#Stock VBA Analysis
#John Hattan
#purpose

#the assignment introduced us to creating a code for datasets
that, unlike previous excel work for a static dataset, would
be used on data that's rapidly changing or across several
near-identical datasets. In this case, sorting the data for every year
would mean creating a very similar code numerous times.
this process allows one to simply type in the year every time. 

#The process of refactoring shows that not all code is equal. 
in the initial module's case, the code has to loop several times
to get the results. With only a few things being pulled in this set,
it results in less than a second, but adding more variables pulled or
more data volume may eventually the code it takes ten minutes.
refactoring can make the code run more efficiently, reducing the total time
the code needs to run.

#Analysis

#Through running the code, and by seeing Total_2017.png versus Total_2018.PNG, we see 2017 
had much better return rates than 2018.ENDP and RUN were the only two stocks consistently 
growing while TERP consistently fell, albeit at relatively small rates. While markets constantly 
change and cannot be perfectly predicted, this gives us a glimpse of what to avoid and invest in.
3,306,038,200 is the total daily count of 2018 versus 3,166,639,100 in 2017, making them
seem relatively comparable to each other. the

#general advantages:
#Overall, if creating the code took equal time, refactored code appears superior.
Even though the difference amounted to a mere split second in this case,
more complex codes or bigger data would mean the dataset takes longer to run.
The main issue appears to be an issue of quantity of time spent building the
code versus the amount of time saved executing it. in this case again, the 
code took significantly longer to code (although that may be more a statement about
my coding skills) and next to no time. 

#The refactored code, in my opinion, also seems less easy to read from 
an outside perspective, and may be harder to show to someonewithout coding 
experience, making the messier but easier to read code better for reading. When examining 
Prefactored_Code.png versus Refactored_code.png, refactored uses variables
in ways that may not make immediate sense, while prefactored mostly uses i = or i <>, seemingly
simpler math, to say values are or aren't equal. In regards to which is "better"
with this dataset, it really appears to be more a matter of preference.
