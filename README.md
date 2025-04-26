# cs61a-project-1-the-game-of-hog-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Project 1-The Game of Hog Solved](https://www.ankitcodinghub.com/product/cs61a-project-1-the-game-of-hog-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86434&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A Project 1-The Game of Hog  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

<p style="text-align: center;"><img data-recalc-dims="1" decoding="async" class="aligncenter lazyloaded" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/09/180.png?w=980&amp;ssl=1" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/09/180.png?w=980&amp;ssl=1">Higher-order functions to Order higher rolls.

<h1>Introduction</h1>
Important submission note: For full credit:

Submit with Phase 1 complete by Tuesday, Sept 6, worth 1 pt.

Submit the complete project by Friday, Sept 9.

Try to attempt the problems in order, as some later problems will depend on earlier problems in their implementation and therefore also when running ok tests.

You may complete the project with a partner.

You can get 1 bonus point by submitting the entire project by Thursday, Sept 8 You can receive extensions on the project deadline and checkpoint deadline, but not on the early deadline, unless you’re a DSP student with an accommodation for assignment extensions.

In this project, you will develop a simulator and multiple strategies for the dice game Hog.

You will need to use control statements and higher-order functions together, as described in Sections 1.2 through 1.6 of <a href="http://composingprograms.com/">Composing</a> <a href="http://composingprograms.com/">Programs</a> <a href="http://composingprograms.com/">(http://composingprograms.com)</a><a href="http://composingprograms.com/">,</a> the online textbook.

When students in the past have tried to implement the functions without thoroughly reading the problem description, they’ve often run into issues. 😱 Read each description thoroughly before starting to code.

<h2>Rules</h2>
In Hog, two players alternate turns trying to be the rst to end a turn with at least GOAL total points, where GOAL defaults to 100. On each turn, the current player chooses some number of dice to roll, up to 10. That player’s score for the turn is the sum of the dice outcomes. However, a player who rolls too many dice risks:

Sow Sad. If any of the dice outcomes is a 1, the current player’s score for the turn is 1 .

In a normal game of Hog, those are all the rules. To spice up the game, we’ll include some special rules:

Pig Tail. A player who chooses to roll zero dice scores 2 * abs(tens – ones) + 1 points; where tens , ones are the tens and ones digits of the opponent’s score. The ones digit refers to the rightmost digit and the tens digit refers to the second-rightmost digit.

<h3>Examples</h3>
Example 1:

The opponent has 46 points, and the current player chooses to roll zero dice. 2 * abs(4 – 6) + 1 = 5 , so the player gains 5 points.

Example 2:

The opponent has 73 points, and the current player chooses to roll zero dice. 2 * abs(7 – 3) + 1 = 9 .

Square Swine. After a player gains points for their turn, if the resulting score is a perfect square, then increase their score to the next higher perfect square. A perfect square is any integer n where n = d * d for some integer d .

A player has 12 points and rolls 3 dice that total 13 points. Their new score would be 25, but since 25 is 5 squared, their score is increased to 6 squared: 36.

Example 2:

A player has 12 points and rolls 3 dice that total 12 point. Their new score would be 24, which is not a perfect square.

Example 3:

A player has 0 points and rolls 5 dice, but one is a 1, so their new score would be

<ol>
<li>1 is a perfect square, and so their score is increased to 4.</li>
</ol>
Example 4:

A player has 80 points and rolls 10 dice, but three are 1’s, so their new score would be 1. 81 is 9 squared, so their new score is 10 squared: 100. They win the game.

<h1>Download starter les</h1>
To get started, download all of the project code as a <a href="https://cs61a.org/proj/hog/hog.zip">zip</a> <a href="https://cs61a.org/proj/hog/hog.zip">archive</a> <a href="https://cs61a.org/proj/hog/hog.zip">(hog.zip)</a><a href="https://cs61a.org/proj/hog/hog.zip">.</a> Below is a list of all the les you will see in the archive once unzipped. For the project, you’ll only be making changes to hog.py .

hog.py : A starter implementation of Hog dice.py : Functions for making and rolling dice ucb.py : Utility functions for CS 61A

hog_ui.py : A text-based user interface (UI) for Hog ok : CS 61A autograder

tests : A directory of tests used by ok

Please do not modify any les other than hog.py .

<h1>Logistics</h1>
The project is worth 25 points, of which 1 point is for submitting Phase 1 by the checkpoint date of Tuesday, Sept 6.

You will turn in the following les:

hog.py

You do not need to modify or turn in any other les to complete the project. To submit the project, run the following command:

You will be able to view your submissions on the <a href="http://ok.cs61a.org/">Ok</a> <a href="http://ok.cs61a.org/">dashboard</a> <a href="http://ok.cs61a.org/">(http://ok.cs61a.org)</a><a href="http://ok.cs61a.org/">.</a>

For the functions that we ask you to complete, there may be some initial code that we provide. If you would rather not use that code, feel free to delete it and start from scratch. You may also add new function de nitions as you see t.

However, please do not modify any other functions or edit any les not listed above. Doing so may result in your code failing our autograder tests. Also, please do not change any function signatures (names, argument order, or number of arguments).

Throughout this project, you should be testing the correctness of your code. It is good practice to test often, so that it is easy to isolate any problems. However, you should not be testing too often, to allow yourself time to think through problems.

We have provided an autograder called ok to help you with testing your code and tracking your progress. The rst time you run the autograder, you will be asked to log in with your Ok account using your web browser. Please do so. Each time you run ok , it will back up your work and progress on our servers.

The primary purpose of ok is to test your implementations.

We recommend that you submit after you nish each problem. Only your last submission will be graded. It is also useful for us to have more backups of your code in case you run into a submission issue. If you forget to submit, your last backup will be automatically converted to a submission.

If you do not want us to record a backup of your work or information about your progress, you can run

With this option, no information will be sent to our course servers. If you want to test your code interactively, you can run

with the appropriate question number (e.g. 01 ) inserted. This will run the tests for that question until the rst one you failed, then give you a chance to test the functions you wrote interactively.

You can also use the debugging print feature in OK by writing

which will produce an output in your terminal without causing OK tests to fail with extra output.

<h1>Getting Started Videos</h1>
These videos may provide some helpful direction for tackling the coding problems on this assignment.

<table width="560">
<tbody>
<tr>
<td width="560"><a href="https://www.youtube.com/watch?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q&amp;v=RFEnP-pU2U4">[CS 61A FA22] Hog Problem #1 Getting Started</a></td>
</tr>
</tbody>
</table>
<a href="https://youtu.be/playlist?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q">YouTube</a> <a href="https://youtu.be/playlist?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q">link</a> <a href="https://youtu.be/playlist?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q">(https://youtu.be/playlist?list</a><a href="https://youtu.be/playlist?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q">=</a><a href="https://youtu.be/playlist?list=PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q">PLx38hZJ5RLZd6XziWoQAonk-XrAaWww5Q)</a>

<h1>Phase 1: Rules of the Game</h1>
In the rst phase, you will develop a simulator for the game of Hog.

<h2>Problem 0 (0 pt)</h2>
The dice.py le represents dice using non-pure zero-argument functions. These functions are non-pure because they may have di erent return values each time they are called, and so a side-e ect of calling the function may be changing what will happen when the function is called again. The documentation of dice.py describes the two di erent types of dice used in the project:

Fair dice produce each possible outcome with equal probability. The four_sided and

six_sided functions are examples.

Test dice are deterministic: they always cycle through a xed sequence of values that are passed as arguments. Test dice are generated by the make_test_dice function.

Before writing any code, read over the dice.py le and check your understanding by unlocking the following tests.

This should display a prompt that looks like this:

You should type in what you expect the output to be. To do so, you need to rst gure out what test_dice will do, based on the description above.

You can exit the unlocker by typing exit() .

Typing Ctrl-C on Windows to exit out of the unlocker has been known to cause problems, so avoid doing so.

<h2>Problem 1 (2 pt)</h2>
Implement the roll_dice function in hog.py . It takes two arguments: a positive integer called num_rolls giving the number of dice to roll and a dice function. It returns the number of points scored by rolling the dice that number of times in a turn: either the sum of the outcomes or 1 (Sow Sad).

Sow Sad. If any of the dice outcomes is a 1, the current player’s score for the turn is 1 .

<h3>Examples</h3>
Example 1: The current player rolls 7 dice, 5 of which are 1’s. They score 1 point for the turn.

Example 2: The current player rolls 4 dice, all of which are 3’s. Since Sow Sad did not occur, they score 12 points for the turn.

To obtain a single outcome of a dice roll, call dice() . You should call dice() exactly

num<u>_</u>rolls times in the body of roll_dice .

Remember to call dice() exactly num_rolls times even if Sow Sad happens in the middle of rolling. By doing so, you will correctly simulate rolling all the dice together (and the user interface will work correctly).

Note: The roll_dice function, and many other functions throughout the project, makes use of default argument values—you can see this in the function heading: def roll_d<span style="text-decoration: line-through;">i</span>ce(num_rolls, dice=six_sided): …

The argument dice=six_sided means that when roll_dice is called, the dice argument is optional. If no value for dice is provided, then six_sided is used by default.

For example, calling roll_dice(3, four_sided) , or equivalently roll_dice(3, dice=four_sided) , simulates rolling 3 four-sided dice, while calling roll_dice(3) simulates rolling 3 six-sided dice.

Understand the problem:

Before writing any code, unlock the tests to verify your understanding of the question:

Write code and check your work:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 2 (2 pt)</h2>
Implement tail_points , which takes the player’s opponent’s current score opponent_score , and returns the number of points scored by Pig Tail when the player rolls 0 dice.

Pig Tail. A player who chooses to roll zero dice scores 2 * abs(tens – ones) + 1 points; where tens , ones are the tens and ones digits of the opponent’s score. The ones digit refers to the rightmost digit and the tens digit refers to the second-rightmost digit.

The opponent has 46 points, and the current player chooses to roll zero dice. 2 * abs(4 – 6) + 1 = 5 , so the player gains 5 points.

Example 2:

The opponent has 73 points, and the current player chooses to roll zero dice. 2 *

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

You can also test tail_points interactively by running python3 -i hog.py from the terminal and calling tail_points on various inputs.

<h2>Problem 3 (2 pt)</h2>
Implement the take_turn function, which returns the number of points scored for a turn by rolling the given dice num_rolls times.

Your implementation of take_turn should call both roll_dice and tail_points rather than repeating their implementations.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 4 (1 pt)</h2>
Add functions perfect_square and next_perfect_square so that square_update returns a player’s total score after they roll num_rolls . You do not need to edit the body of

square_update .

Square Swine. After a player gains points for their turn, if the resulting score is a perfect square, then increase their score to the next higher perfect square. A perfect square is any integer n where n = d * d for some integer d .

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 5 (5 pt)</h2>
Implement the play function, which simulates a full game of Hog. Players take turns rolling dice until one of the players reaches the goal score, and the nal scores of both players are returned by the function.

To determine how many dice are rolled each turn, call the current player’s strategy function (Player 0 uses strategy0 and Player 1 uses strategy1 ). A strategy is a function that, given a player’s score and their opponent’s score, returns the number of dice that the current player will roll in the turn. An example strategy is always_roll_5 which appears above play .

To determine the updated score for a player after they take a turn, call the update function. An update function takes the number of dice to roll, the current player’s score, the opponent’s score, and the dice function used to simulate rolling dice. It returns the updated score of the current player after they take their turn. Two examples of update functions are simple_update and square_update .

If a player achieves the goal score by the end of their turn, i.e. after all applicable rules have been applied, the game ends. play will then return the nal total scores of both players, with Player 0’s score rst and Player 1’s score second.

Some example calls to play are:

play(always_roll_5, always_roll_5, simple_update) simulates two players that both

always roll 5 dice each turn, playing with just the Sow Sad and Pig Tail rules.

play(always_roll_5, always_roll_5, square_update) simulates two players that both

always roll 5 dice each turn, playing with the Square Swine rule in addition to the Sow Sad and Pig Tail rules (i.e. all the rules).

Important: For the user interface to work, a strategy function should be called only once per turn. Only call strategy0 when it is Player 0’s turn and only call strategy1 when it is Player 1’s turn.

Hints:

If who is the current player, the next player is 1 – who .

To call play(always_roll_5, always_roll_5, square_update) and print out what happens each turn, run python3 hog_ui.py from the terminal.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

Check to make sure that you completed all the problems in Phase 1:

Then, submit your work before the checkpoint deadline:

When you run these ok commands, you’ll still see that some tests are locked because you haven’t completed the whole project yet. You’ll get full credit for the checkpoint if you complete all the problems up to this point.

Congratulations! You have nished Phase 1 of this project!

<h1>Interlude: User Interfaces</h1>
There are no required problems in this section of the project, just some examples for you to read and understand. See Phase 2 for the remaining project problems.

<h2>Printing Game Events</h2>
We have built a simulator for the game, but haven’t added any code to describe how the game events should be displayed to a person. Therefore, we’ve built a computer game that no one can play. (Lame!)

However, the simulator is expressed in terms of small functions, and we can replace each function by a version that prints out what happens when it is called. Using higher-order functions, we can do so without changing much of our original code. An example appears in hog_ui.py , which you are encouraged to read.

The play_and_print function calls the same play function just implemented, but using:

new strategy functions (e.g., printing_strategy(0, always_roll_5) ) that print out the scores and number of dice rolled. a new update function ( square_update_and_print ) that prints the outcome of each turn. a new dice function ( printing_dice(six_sided) ) that prints the outcome of rolling the dice.

Notice how much of the original simulator code can be reused.

Running python3 hog_ui.py from the terminal calls play_and_print(always_roll_5, always_roll_5) .

<h2>Accepting User Input</h2>
The built-in input function waits for the user to type a line of text and then returns that text as a string. The built-in int function can take a string containing the digits of an integer and return that integer.

The interactive_strategy function returns a strategy that let’s a person choose how many dice to roll each turn by calling input .

With this strategy, we can nally play a game using our play function:

Running python3 hog_ui.py -n 1 from the terminal calls

play_and_print(interactive_strategy(0), always_roll_5) , which plays a game betweem a

human (Player 0) and a computer strategy that always rolls 5.

Running python3 hog_ui.py -n 2 from the terminal calls

play_and_print(interactive_strategy(0), interactive_strategy(1)) , which plays a game

between two human players.

You are welcome to change hog_ui.py in any way you want, for example to use di erent strategies than always_roll_5 .

<h1>Phase 2: Strategies</h1>
In this phase, you will experiment with ways to improve upon the basic strategy of always rolling ve dice. A strategy is a function that takes two arguments: the current player’s score and their opponent’s score. It returns the number of dice the player will roll, which can be from 0 to 10 (inclusive).

<h2>Problem 6 (2 pt)</h2>
Implement always_roll , a higher-order function that takes a number of dice n and returns a strategy that always rolls n dice. Thus, always_roll(5) would be equivalent to always_roll_5 .

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 7 (2 pt)</h2>
A strategy only has a xed number of possible argument values. In a game to 100, there are

100 possible score values (0-99) and 100 possible opponent_score values (0-99), giving 10,000 possible argument combinations.

Implement is_always_roll , which takes a strategy and returns whether that strategy always rolls the same number of dice for every possible argument combination.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 8 (2 pt)</h2>
Implement make_averaged , which is a higher-order function that takes a function

original_function as an argument.

The return value of make_averaged is a function that takes in the same number of arguments as original_function . When we call this returned function on the arguments, it will return the average value of repeatedly calling original_function on the arguments passed in.

Speci cally, this function should call original_function a total of total_samples times and return the average of the results of these calls.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Problem 9 (2 pt)</h2>
Implement max_scoring_num_rolls , which runs an experiment to determine the number of rolls (from 1 to 10) that gives the maximum average score for a turn. Your implementation should use make_averaged and roll_dice .

If two numbers of rolls are tied for the maximum average score, return the lower number.

For example, if both 3 and 6 achieve a maximum average score, return 3.

You might nd it useful to read the doctest and the example shown in the doctest for this problem before doing the unlocking test.

Important: In order to pass all of our tests, please make sure that you are testing dice rolls starting from 1 going up to 10, rather than from 10 to 1.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

<h2>Running Experiments</h2>
The provided run_experiments function calls max_scoring_num_rolls(six_sided) and prints the result. You will likely nd that rolling 6 dice maximizes the result of roll_dice using sixsided dice.

To call this function and see the result, run hog.py with the -r ag:

In addition, run_experiments compares various strategies to always_roll(6) . You are welcome to change the implementation of run_experiments as you wish. Note that running experiments with tail_strategy and square_strategy will not have accurate results until you implement them in the next two problems.

Some of the experiments may take up to a minute to run. You can always reduce the number of trials in your call to make_averaged to speed up experiments.

Running experiments won’t a ect your score on the project.

<h2>Problem 10 (2 pt)</h2>
A strategy can try to take advantage of the Pig Tail rule by rolling 0 when it is most bene cial to do so. Implement tail_strategy , which returns 0 whenever rolling 0 would give at least threshold points and returns num_rolls otherwise. This strategy should not also take into

account the Square Swine rule.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

You should nd that running python3 hog.py -r now shows a win rate for tail_strategy close to 57%.

<h2>Problem 11 (2 pt)</h2>
A better strategy will take advantage of both Pig Tail and Square Swine in combination. Even a small number of pig tail points can lead to large gains. For example, if a player has 31 points and their opponent has 42, rolling 0 would bring them to 36 which is a perfect square, and so they would end the turn with 49 points: a gain of 49 – 31 = 18!

The square_strategy returns 0 whenever rolling 0 would result in a score that is at least threshold points more than the player’s score at the start of turn.

Before writing any code, unlock the tests to verify your understanding of the question:

Once you are done unlocking, begin implementing your solution. You can check your correctness with:

You should nd that running python3 hog.py -r now shows a win rate for square_strategy close to 62%.

<h2>Optional: Problem 12 (0 pt)</h2>
Implement final_strategy , which combines these ideas and any other ideas you have to achieve a high win rate against the baseline strategy. Some suggestions:

If you know the goal score (by default it is 100), there’s no bene t to scoring more than the goal. Check whether you can win by rolling 0, 1 or 2 dice. If you are in the lead, you might decide to take fewer risks.

Instead of using a threshold, roll 0 whenever it would give you more points on average than rolling 6.

You can check that your nal strategy is valid by running ok .

<h1>Project submission</h1>
Run ok on all problems to make sure all tests are unlocked and pass:

You can also check your score on each part of the project:

Once you are satis ed, submit to complete the project.

Congratulations, you have reached the end of your rst CS 61A project! If you haven’t already, relax and enjoy a few games of Hog with a friend.

&nbsp;
