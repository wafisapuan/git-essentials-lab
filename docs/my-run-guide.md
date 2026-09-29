# How to Run the Library Demo

## Prerequisites
- Python 3.8 or newer
- Git
- A terminal / command prompt

## Run the Demo
From the repository root:

    python3 run.py demo

## What the Demo Does
The demo loads the sample library catalog and exercises the borrowing
rules under the baseline policy (two books per member, 14-day loans,
100 units per overdue day). It prints the resulting catalog state so
you can verify search and borrowing behavior end to end.