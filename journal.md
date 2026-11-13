# Dev Journal

## Entry 14: :%s/unfocused/resolute/g
`timestamp: 2026-11-13`

Good afternoon, not morning but at least not night.
2 days ago, I learnt how to use the substitute command in Neovim.
Normally for my usage I would keep a "c" flag, but in the title I am just that confident.

No more will I waste opportunities that could help me build a fulfilling life.
My agenda requires time and focus.
Wasted time can be bandaged but never fully healed; my current attitude is not going to work.
If I come across something I dislike but need to do to achieve my goal, then I do it.

There was a promise I made to my parents.
"I will pause programming while I am in high school to focus on my studies."
I do not know if they actually believe I will; regardless I will keep my future programming secret from them until I graduate.

Lying: strangely, for some reason I find quite entertaining :>
Like a game.
Secretly and quietly, I work on my programming all while getting perfect grades?
To do this I am going to start every morning writing a plan for just the current day.

## Entry 13: Quick? Why not slow and descriptive?
`timestamp: 2026-11-12`

My parents do not like me going on my laptop at night, which is what I have been doing to create my journal entries.
For the last entry, "Quick", I had to slowly sneak to my laptop and *quickly* make the entry and push it.
Writing at night on my laptop is something I also do not like.
I have been given the instruction: "Do not go on your laptop at night", and I am in complete agreement.
In Entry 4, I made a point to take my sleep far more seriously, but that is not what happened.
Now my parents are forcing me not to work on my laptop at night, so I guess that problem is sorted.
Well, why am I writing this at night, you may ask?
(You probably did not, considering the only way to know that is to look at the timestamp for this git commit.)
The answer is: "I forgot".
I have quite a bit more to say, but I am ending it early to get more sleep.
See you in the **morning**.

## Entry 12: Quick
`timestamp: 2026-11-11`

Quick

## Entry 11: Feeling better
`timestamp: 2026-11-10`

Kind of lazy to do an entry. Also the world feels whirly; my head feels like it has gained +2kgs.
Worked on my drama evaluation assignment. Struggled. I also struggle while coding sometimes, but at least that is fun-ish.
This just reminds me that writing an evaluation for school is not my strong suit.
I wish I were good at it because school would be so much easier.
Though I will be good at schoolwork next year.
My friends also helped me with questions I had in regards to my drama evaluation.
A small plan is forming in my mind on how I am to tackle next school year.
This school year is ending soon.
There are several things I need to change. Not going to talk about that now.

## Entry 10: I am kind of sick
`timestamp: 2026-11-09`

Achoo! Uuuuuuuhhhhh. I am going to bed and taking a nap, but I would like to say first: I failed today because I did not follow my plan.
But I made a test for the Canvas class and made a test summary...
Tomorrow will depend on how I feel tomorrow.

## Entry 9: Succeeding to plan is planning to succeed
`timestamp: 2026-11-08`

Created the Canvas class for ayaan-lib-js!
Also, my little brother: I started teaching him how to code.
He is starting with block coding.

Now, about the planning...
it did not go that well, but it did not go that horribly.
Cleaning my desk was not planning, but I think it was useful.
I wanted to create a *personalized* planning method involving my sketchbook.
My sketchbook is written in every day so I thought it would be a good target.
All that said, I did not make my planning method.
If I had tried to make my planning method, then today I would have spent far more time thinking about planning rather than doing any actual planning.
I decided to take a far more pragmatic approach.
Sitting at my recently cleaned desk, I wrote out things I want to focus on in the near future.
This helped me realize my habit of accumulating things without actually understanding how many things I had committed to.
In other words, I was disorganized.
Then I marked tasks that required urgency with an "!".
There was only one task without an exclamation mark: ayaan-lib-js.
For a bit, I must. Maybe in some free time I can work on it?
I planned out how many hours I want to spend on each task this week, and on which day.
I did not give ayaan-lib-js any time.
To be honest, I am making this sound much more dramatic than it is :P
Literally taking a break on a non-urgent project to focus on matters that need more attention right now.
Will be back tomorrow ^-^

## Entry 8: Failing to plan is planning to fail
`timestamp: 2026-11-07`

I pushed ayaan-lib-js onto GitHub. It is now public: `https://github.com/ayaanart/ayaan-lib-js`.
Made tests for reflect() and also refactored it to use throwNonFiniteNumber.
Unrelated, but feeling really good regarding my job; upsettingly, school does not provoke the same feeling :/

Back to coding.
For the time available, I should have done a lot more work.
Not that much programming was done. That is okay. But not much of anything was done.
Too busy having cheap fun.
If I want to be successful in a lot of different things, then I need to start planning.
Luckily, I have built a habit of writing in my dev journal and then taking action on what was written.
This is not really planning, but I can use the fact that I am committed to this journal.
So am I just going to say, "I will start planning from now on"?
Very close...
I will start planning from now on and write about my planning within the dev journal every day until I feel confident that planning is a habit.
Even after planning is a habit, I will occasionally bring it up because it is part of my daily life now.
```
 .-.
 | |
 :::
 |||
 |||
 |||
 |||
 ||| 
 \ /
  Y
```

## Entry 7: Promise to push ayaan-lib-js
`timestamp: 2026-11-06`

Guess what happened? STEADY PROGRESS!!!
I finished all the tests for both throwNonFiniteNumber and adjustSeparation.
Did a small refactor and split the file testing.js that stored all the testing tools into a folder called testing-tool.
Each function now has its own file and JSDoc.
Improved assertThrow to be able to check if *multiple* different pieces of text exist in the error message.
That said, I did not really want to do coding today.
It is just that I so badly wanted to finish this.
Also I kind of want to go now and do other things :P
Before I leave I want to make a promise to push ayaan-lib-js onto GitHub (and also make a repo for it!).
So it should be public tomorrow ^-^

## Entry 6: Building Foundation
`timestamp: 2026-11-05`

Progress has been steady. But I feel like it is kind of slow.
I feel I have been building the foundation for *soooo looooooooong*.
And I am not even done building the foundation! That said, I am quite close.
Got a solid file structure and got my tests under control-ish.
I also got a helper function for throwing non-finite numbers. It is called... "throwNonFiniteNumber".
It gives a nice error message and can give TypeError or RangeError, but more costly.
Remember in entry 4 about the benchmarks? throwNonFiniteNumber is the same logic of the slow one, just now in a helper function and it only runs if the function finds one of its args invalid after doing a cheap simple check.

You know, I am now quite used to running tests and running local servers.
Typed `python -m http.server 8000` far too many times, before I learnt the power of a hard refresh (CTRL+SHIFT+R).
I do not need to stop the server and restart the local server everytime I make a change to the code.
Doing that may not even run the new code! It could just be loaded from the browser’s cache (304 was a source of confusion).

Then I looked at how many days I have been working on this lib. It has only been 2 days :/
Today is the third day. Oh well.
I think my days are stretching out because of all the other things happening besides school work.
Got a few performances coming up soon.
Got a few *assignments* coming up soon.
My coding skill is > my skill at school work.
The problem is that... I am a beginner programmer.
Anyway, I am off to dream!
```
    Z
   z
/\.    /\
  \/\ /  \
  /  \    \
 /    \    \
```

## Entry 5: Tests, tests, tests, tests!
`timestamp: 2026-11-04`

All tests passed! But not for long.
Having a few issues but I will tell you about that *tomorrow*.
Today I feel locked in and want to work on the code.
I decided to quickly do this and get back to coding.
Forgetting to do a dev log because I was having too much fun coding is still considered forgetting!

## Entry 4: Testing, 1, 2, 3, 4, skip a few 150 million
`timestamp: 2026-11-03`

Managed to work on Ayaan-JS-lib.
Did not really make anything new, per se, but I consider today productive.
There was a function in the lib and I was making some error handling.
That error handling then evolved into taking the args and placing them into an object, and making pairs using that object with Object.entries() and then destructuring those pairs.
Allowing me to loop the args with both args name and value.
I got to learn about destructuring when I did this. It was fun.
Anyway, I worried about performance.
This is meant to be a cheap function.
I then learnt *how* to make benchmarks as I attempted to benchmark them.
10 million calls per run. 5 runs for each of the 3 variants of checks: none, min, full (full creates objects and destructures them).
- None and Min took around 85 ms per run (basically a tie)

- Full took around 1630 ms per run

Big diff. (I also made sure to give a few warm-up runs)

But now I am planning to have a bare minimum check that then goes into the full check that will give a nice error message.
Best of both worlds ^-^. Though I was not productive with regards to schoolwork :/
Also from now on, getting a good night's sleep will be taken far more seriously.

## Entry 3: Successful day
`timestamp: 2026-11-02`

I am quite happy that I kept my promise from entry 2.
But not surprised!
The aim.md, rules.md and README.md were all built.
My science assignment I also completed.
Tomorrow work on the Ayaan-JS-lib will be done.
Ding! Ding! Ding! Why did I do that?
It is because the dings on my phone when people send messages in the group make me happy.
It also is very distracting, but I do not need to focus *too* hard on this.

## Entry 2: Not a particularly successful day
`timestamp: 2026-11-01`

I did do things...
but I should have done way more.
So I am making a promise to myself that my next entry will be titled: *Successful day*.
Anyway. See you tomorrow I guess.

## Entry 1: Hello World
`timestamp: 2026-10-31`

First entry in my public journal.
I will let the readme explain my aim.
Right now I kind of do not want to do an entry.
Just not vibing it.
Also I should work on dinner and then getting to bed.
```
Z
 z
   ^o^
```
