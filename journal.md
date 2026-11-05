# Dev Journal

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
