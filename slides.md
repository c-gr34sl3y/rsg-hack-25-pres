# RSG Hackathon 2025
### S6: "Advent of Code"  

---

## Intro

- V. brief overview of AoC and why we like it
- Today and how things will run
- Getting Started Guide

---

## What is Advent of Code?

- A "mostly perl" annual set of programming challenges following Advent
- Interested in a deeper drive from Eric Wastl? A very entertaining presentation here: [https://www.youtube.com/watch?v=uZ8DcbhojOw](https://www.youtube.com/watch?v=uZ8DcbhojOw)
 (particularly fun showing how he emergency scaled up his infrastructure at the beginning in 2015!)
- For us? A good structure for "working together collaboratively, learning new or polishing existing skills"
- 

---

## Our year - 2015

- First year of AoC
- Puzzles range from easy to challenging
- Themes include Santa's journey, elves, and more

---

## Getting Started

0. Find some people to work with. We want people working together in at least pairs.
  
1. We're going to work with puzzles set in AoC 2015. So [https://adventofcode.com/2015](https://adventofcode.com/2015)
2. Login and create an account, authenticating with one of the 4 options - Github recommended
3. (Optional) - if you want to join the private leaderboard, go to [https://adventofcode.com/2015/leaderboard](https://adventofcode.com/2015/leaderboard/private) and use the code: 3434143-9fd3e2cf
4. ????
5. Have fun!
---

## Getting Inputs

Everyone's inputs will be different for each problem. 

You can either

### A) Manually Download the Inputs
1. Go to each day’s puzzle page on [Advent of Code 2015](https://adventofcode.com/2015).
2. Scroll to the bottom and click on **"Get your puzzle input"**.
3. Save the file manually as `dayX.txt` (where X is the day number).

### B) Use a Helpful Tool (`advent-of-code-data`)
You can automate the input retrieval process by [advent-of-code-data](https://github.com/wimglenn/advent-of-code-data).

To install it, use `pip`:

```bash
pip install advent-of-code-data
```

#### Prerequisites for using the tool:
1. **A login for Advent of Code 2015**: Sign in on [Advent of Code](https://adventofcode.com/2015).
2. **Your session ID cookie**: To retrieve your personalized inputs, you'll need your session cookie.
   - Login on AoC with your account (e.g., GitHub or Google).
   - Open your browser's developer console (right-click → **Inspect** → **Network** tab).
   - Visit a puzzle page (e.g., [day 1](https://adventofcode.com/2015/day/1/input)).
   - Look for the `session=...` cookie in the **Request Headers**.
   - Add this session ID to your environment by setting `AOC_SESSION` or by writing it to `~/.config/aocd/token`.

Once everything is set up, you can use the tool to download your inputs for all days:

```bash
# Download inputs for all 25 days
for day in {1..25}; do
    aocd $day 2015 > "inputs/day${day}.txt"
done
```

