# RSG Hackathon 2025
### S6: "Advent of Code"

---

## Intro

- Overview of AoC
- How things will run today
- Getting started and setup

<img src="assets/icons/bluebear640px-cropped-80x80.png" class="custom-icon" alt="Custom Icon">

---

## What is Advent of Code?

- Since 2015, an annual set of programming challenges following Advent

- Interested in a deeper drive from Eric Wastl? A very entertaining presentation here: [https://www.youtube.com/watch?v=uZ8DcbhojOw](https://www.youtube.com/watch?v=uZ8DcbhojOw)
 (particularly fun showing how he emergency scaled up his infrastructure at the beginning in 2015!)

- For us? A good structure for "working together collaboratively, learning new or polishing existing skills"

- We're working with the 2015 set of challenges.

<img src="assets/icons/bluebear640px-cropped-80x80.png" class="custom-icon" alt="Custom Icon">

---

## Getting Started

0. Find some people to work with. We want people working together in at least pairs.
1. We're going to work with puzzles set in AoC 2015. So [https://adventofcode.com/2015](https://adventofcode.com/2015)
2. Login and create an account, authenticating with one of the 4 options - Github recommended
3. (Optional) - if you want to join the private leaderboard, go to [https://adventofcode.com/2015/leaderboard](https://adventofcode.com/2015/leaderboard/private) and use the code: 3434143-9fd3e2cf
4. ????
5. Have fun!

<img src="assets/icons/bluebear640px-cropped-80x80.png" class="custom-icon" alt="Custom Icon">

---

## Getting Inputs

<div style="text-align: left; padding: 20px;">
Everyone's challenge inputs are different. To get them, either:

Manually Download the Inputs

1. Go to each day’s puzzle page on [Advent of Code 2015](https://adventofcode.com/2015).
2. Scroll to the bottom and click on **"Get your puzzle input"**.
3. Save the file manually as `dayX.txt` (where X is the day number).

<img src="assets/icons/bluebear640px-cropped-80x80.png" class="custom-icon" alt="Custom Icon">

---

## Getting Inputs (Continued)

<div style="text-align: left; padding: 20px;">
Automate the input retrieval process by [advent-of-code-data](https://github.com/wimglenn/advent-of-code-data).

Install with pip:

```bash
pip install advent-of-code-data
```

Then:
1. Login to [Advent of Code 2015](https://adventofcode.com/2015)
2. **Get your session ID cookie**

- Open your browser's developer console (right-click → **Inspect** → **Network** tab).
- Visit a puzzle page (e.g., [day 1](https://adventofcode.com/2015/day/1/input)).
- Look for the `session=...` cookie in the **Request Headers**.
- Add this session ID to your environment by setting `AOC_SESSION` or by writing it to `~/.config/aocd/token`

3. Then use the tool to download your inputs for all days:

```bash
# Download inputs for all 25 days
for day in {1..25}; do
    aocd $day 2015 > "inputs/day${day}.txt"
done
```
<img src="assets/icons/bluebear640px-cropped-80x80.png" class="custom-icon" alt="Custom Icon">
