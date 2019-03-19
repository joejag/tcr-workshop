### `test && commit || revert`

### *Joe Wright* & *Keith Harrison* 
#### __@joe_jag__ & __@KeithDHar__

---

## What's been your experience with pairing and/or TDD?

### __(discuss in pairs)__

---

# Intro to the loop

---

![ fill](images/live-die-repeat.jpg)

---

> test && commit || revert. If the tests fail, then the code goes back to the state where the tests last passed
-- Kent Beck

---

```
while true; do
    # wait for change
    ./runTests.sh && git commit -am working || git reset --hard
done
```

---

## Quick demo!

---


# Exercise Time!<br/>__Sharpening your axe__

### (in pairs)

---

## Get your environment ready

1. Get a starter project from <br/> https://github.com/joejag/tcr-starters
1. Use `npx tcr ./runTests.sh` <br/>or your own loop
1. Check reverting works with your editor
1. Go help someone else get ready

---

## How you feel about the prospect of using TCR to build something?

### __(discuss with your table)__


---

# The Exercise

---

## Write down on a post-it how you feel about TCR right now

### __(on your own)__

---

## The problem

---

## Urnfield

* 1 - 2 - 3 - 4 - 5
* / - // - /// - //// - \\

* 6 - 7 - 8 - 9 - 10
* /\\ - //\\ - ///\\ - ////\\ - \\\\

* 11 -  29
* /\\\\ -  ////\\\\\\\\\

---

## Roman Numberals

* 1 - 2 - 3 - 4 - 5 - 6 - 7 - 8 - 9 - 10
* I - II - III - IV - V - VI - VII - VIII - IX - X

---

## On Pairing

* Listen and be willing to try other ideas
* Switch who has the keyboard regulary
* No one in this room is an expert on TCR

---

# Exercise Time!<br/>__TCR your solution__

### (in pairs)

---

* http://bit.do/tcrnumbers

---

## Write down on a post-it how you feel about TCR right now

### __(discuss in group,<br/> write down on your own)__

---

# Limbo

---

## How do you currently integrate changes in your projects?

### __(discuss in pairs)__

---

## TCR is only the beginning

---

## Limbo

```
while true; do
    sleep 1
    git pull --rebase
    git push
done
```

---

# Exercise Time!<br/>__Tradeoff analysis__

### (in your table groups)

---

## Tradeoffs

* Discuss advantages of Limbo
* Discuss disadvantages of Limbo
* Capture them on post-its

---

## Share back your thoughts

### __(one per table)__

---

Thank you!

### __@joe_jag__  *Joe Wright* 

### __@KeithDHar__  *Keith Harrison* 