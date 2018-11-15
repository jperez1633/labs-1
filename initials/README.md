# Initials

## tl;dr

Implement a program that, given a person’s name, prints a person’s initials, per the below.

```
$ ./initials
Regulus Arcturus Black
RAB
```

{% next %}

## Getting Ready

First, take a self-paced tour through a few coding examples that are likely to prove quite useful to you as you work on this and some future problems in this unit, the source code for which can be found at http://bit.ly/2zPo948.

Here is the first of those videos.

{% video https://www.youtube.com/watch?v=BYbuuUntOZ4&feature=youtu.be&list=PLhQjrBD2T380sc-fXwl1sviA-twxFduVU %}

Others can be found at: 

{% next %}

## Implementation Details

Design and implement a program, initials, that, given a person’s name, prints a person’s initials.

Implement your program in a file called initials.c.

Your program should prompt a user for their name using get_string to obtain their name as a string.

You may assume that the user’s input will contain only letters (uppercase and/or lowercase) plus single spaces between words. You don’t need to worry about names like Joseph Gordon-Levitt, Conan O’Brien, or David J. Malan!

Your program should print the user’s initials (i.e., the first letter of each word in their name) with no spaces or periods, followed by a newline (\n).

You may assume that the only spaces in the user’s input will be single spaces between words.

{% next %}

## Usage

Your program should behave per the examples below. Assumed that the underlined text is what some user has typed.

```
$ ./initials
Zamyla Chan
ZC
```

```
$ ./initials
robert thomas bowden
RTB
```

{% spoiler "Hints" %}

{% video https://www.youtube.com/watch?time_continue=9&v=UItYCp0Ivqg %}

{% endspoiler %}

## How to Submit

Execute the below, logging in with your GitHub username and password when prompted. For security, you'll see asterisks (`*`) instead of the actual characters in your password.

```
submit50 cs50/2018/ap/initials/less
```

To make sure you get 5/5 for style, you may want to execute style50 first.

```
style50 initials.c
```

