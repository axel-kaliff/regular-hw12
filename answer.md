
#Exercise 1 
| size / complexity| log n  | n | n log n | n^2 | n^3 | 2^n | n! |
| ------------- |:-------------:| -----:|-----:|-----:|-----:|-----:|-----:|
| 1     | 0         | 1      | 0     | 1| 1| 2| 1|
| 10    | 3.321     | 10     | 33| 100   | 1000| 1024| 362880|
| 100   | 6.643     | 100    |664|10000  | 1e6 | 1.26e30| 9e157|
| 1000  | 9.966     | 1000   | 9966| 1e6   | 1e9 | 1e301| 4e2567|
| 10000  | 13.2877  | 10000  | 13288|1e8   | 1e12| 1.9e3010| 2.8e35659|
| 100000 | 16.609   | 100000 | 1.7e6|1e10  | 1e15| 9.9e30102| 2.8e456573|
| 1000000 | 19.9315 | 1000000| 1.9e7|1e12  | 1e18| 9.9301029| 8e5565708|

#Exercise 2

| T(n)| 1 second  | 1 minute | 1 hour | 1 day | 1 year | 
| ------------- |:-------------:| -----:|-----:|-----:|-----:|
| log n     | inf!| inf!| inf!| inf!| inf!| 
| n | e9 | 6e10| 3.6e12 | 8.64e13| 3.2e16|
| n log n| 4e7 | 2e9| 9.8e10| 2.1e12| 6.4e14|
| n^2| 31 623| 244 949| 1.8e6| 9e6| 1.8e8|
| n^3| 1000| 3914| 15326| 44208| 3e5| 
| 2^n| 29.9| 35.8| 41.7| 46.2| 54.8| 
| n!| 12.2| 13.9| 15 | 16.5 | 18.5| 


#Exercise 3

- f2 
-f5
-f1
-f3
-f4
-False, the fastest growing function determines the order (n^2)
-True, the fastest growing function determines the order
-False, Big Theta implies big O, which would mean that O(n^3), which is not true
-True, assume lower limit (n = 1) and you can simplify the left hand side to 1

#Exercise 3

-O(n)
-O(n)
-O(n^2) 
-O(n^2)
-O(n^3)

#Exercise 3

The order of O(g(n)) is determined by the highest order funcion in g(n). Therefore (n+1)^3 O(n^3),
The mathematical definitions of Big O implies that O(g(n)) cannot grow faster than g(n), which is true in this case since n^3 ≤ C * (n + 1)^3.


#Exercise 3


