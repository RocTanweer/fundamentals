# Computer Fundamentals Using C

## Steps to run the Programs

### Step 1:

Clone this repository.

```bash
git clone https://github.com/RocTanweer/fundamentals.git

```

### Step 2:

Use the Table of content👇 to navigate to any particular file.

### Step 3:

Open your terminal in the same directory as indicated below👇

### Step 4:

Run the command as directed below👇

## Table of Contents

- [mario](#mario)
  - [easy](#mario-easy)
  - [hard](#mario-hard)
- [greedy](#greedy)
  - [cash](#cash)
- [luhn](#luhn)
  - [credit](#credit)
- [games](#games)
  - [scrabble](#scrabble)
- [math](#math)
  - [euclid](#euclid)

## Mario

These are two program that prints _pyramid_ on the screen like in the mario game.

### Mario Easy

[see the code for this👇](/mario/easy/mario_easy.c)

```bash
~/mario/easy (master) $ ./mario_easy
Height:4
     #
    ##
   ###
  ####
```

### Mario Hard

[see the code for this👇](/mario/hard/mario_hard.c)

```bash
~/mario/hard (master) $ ./mario_hard
Height:4
     # #
    ## ##
   ### ###
  #### ####
```

## Greedy

Greedy is an algorithm that always takes the best immediate, or local, solution while finding an answer.

### cash

This program helps finding the minimum(best immediate) number of coins</br> that a customer is owed for a given number of cents.

[see the code for this👇](/greedy/cash/cash.c)

```bash
~/greedy/cash (master) $ ./cash
How many cents the customer is owed: 43
Number of pennies: 3
Number of nickels: 1
Number of dimes: 1
Number of quarters: 1
```

## Luhn

The Luhn's algorithm or Luhn formula, also known as the "modulus 10" or "mod 10" algorithm,is a simple checksum formula used to validate a variety of identification numbers, such as credit card numbers.

### credit

This program will take a credit card number and tell whether it is _Mastercard_, _American Express(AMEX)_ or _Visa_. It says INVALID, in case the card belongs to none of them.

[see the code for this👇](/luhn/credit/credit.c)

```bash
~/luhn/credit (master) $ ./credit
Enter card_num: 4111111111111111
VISA
```

## Games

These are some command-line games.

### Scrabble

This is a two player game in which both players are suppose to write a word. Player whose word correspond to more points wins. Point of a word is decided by adding points of each character, which is given in the program.

[see the code for this👇](/games/scrabble/scrabble.c)

```bash
~/games/scrabble (master) $ ./scrabble
Player 1: COMPUTER
Player 2: science
Player 1 wins!
```

## Math

These are some programs related to mathematical algorithms and proves.

### Euclid

Euclid's algorithm, is an efficient method for computing the greatest common divisor (GCD) of two integers (numbers), the largest number that divides them both without a remainder.

[see the code for this👇](/math/euclid/gcd.c)

```bash
~/math/euclid (master) $ ./gcd 168 252 329 105 189
gcd is : 7
```
