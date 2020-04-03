# Challenge Fix-my-code 0x00
Fix code challenge for find out the error and fix it on scripts of Ruby, Javascript, Python and C languages. 

## Fix code on next languages
- Ruby
- Javascript
- Python
- C

## Requirements
- Ubuntu 14.04 LTS
- ruby 1.9.3p484 (2013-11-22 revision 43786) [x86_64-linux]
- Node JS v10.14.2
- Python 3.4.3 (default, Nov 12 2018, 22:25:49) / [GCC 4.8.4] on linux
- gcc version 4.8.4 (Ubuntu 4.8.4-2ubuntu1~14.04.4)

## Challenges

### 1. FizzBuzz
Please take a look at my implementation of FizzBuzz in Python: [source code](https://github.com/holbertonschool/Fix-my-code-0/blob/master/0-fizzbuzz.py)

Something is going wrong...

```bash
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz
26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```

**15** should print **_FizzBuzz_** not ~~Fizz~~

**Answer file:** [0-fizzbuzz.py](https://github.com/gogomillan/Fix_My_Code_Challenge/blob/master/0x00-challenge/0-fizzbuzz.py)


### 2. Print square
Please take a look at my implementation of printing a square in Javascript: [source code](https://intranet.hbtn.io/rltoken/1HbXCw-nF028p5VlBAfedQ)

Something is going wrong...

```bash
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```

**./1-print_square.js 10** should print a square of **_size 10_**

**Answer file:** [1-print_square.js](https://github.com/gogomillan/Fix_My_Code_Challenge/blob/master/0x00-challenge/1-print_square.js)

### 3. Sort
Please find here my implementation of sorting arguments in Ruby: [source code](https://intranet.hbtn.io/rltoken/5E7Rrq_70OutipYULjh6Gw)

Something is going wrong...

```bash
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```

**Answer file:** [2-sort.rb](https://github.com/gogomillan/Fix_My_Code_Challenge/blob/master/0x00-challenge/2-sort.rb)

### 4. User password
Please find here my implementation of a User class in Python: [source code](https://github.com/holbertonschool/Fix-my-code-0/blob/master/3-user.py)

Something is going wrong...


```bash
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```

My tests should not print any error...

**Answer file:** [3-user.py](https://github.com/gogomillan/Fix_My_Code_Challenge/blob/master/0x00-challenge/3-user.py)

### 5. Double linked list
Please find here my implementation of a Double linked list in C: [source code](https://intranet.hbtn.io/rltoken/YvS8G70JQA-5q_qce9MjIg)

Something is going wrong...

.md:not(.use-csslab) pre code.wrap {
  white-space: pre-wrap;
}
```bash wrap
$ gcc -Wall -pedantic -Werror -Wextra main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```

It doesnt look right...

**Answer file:** [4-delete_dnodeint](https://github.com/gogomillan/Fix_My_Code_Challenge/tree/master/0x00-challenge/4-delete_dnodeint)

## Author
- Gonzalo Gomez Millan  |  :octocat: [Github](https://github.com/gogomillan)

## License
MIT [Read more ...](https://github.com/gogomillan/Fix_My_Code_Challenge/blob/master/LICENSE)

