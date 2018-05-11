# codingBat
Java 

Warmup 1: The parameter weekday is true if it is a weekday, and the parameter vacation is true if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return true if we sleep in.
  sleepIn(false, false) -> true
  sleepIn(true, false) -> false
  sleepIn(false, true) -> false 

Warmup 2: Given an int n, return the absolute difference between n and 21, except return double the absolute difference if n is over 21.
  diff21(19) -> 2
  diff21(10) -> 11
  diff21(21) -> 0

Warmup 3: We have a loud talking parrot. The "hour" parameter is the current hour time in the range 0..23. We are in trouble if the parrot is talking and the hour is before 7 or after 20. Return true if we are in trouble. 
  parrotTrouble(true, 6) -> true
  parrotTrouble(true, 7) -> false
  parrotTrouble(false, 6) -> false
