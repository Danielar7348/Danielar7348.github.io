---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Cuba by Daniela Robles

## Describe your program

-   What country did you design for? I designed for the Cuban Flag.
-   What grade do you expect? I expected a grade of apprentice.

<!--- Delete this comment and add your writing -->

## Current output

-   Insert an image that your program currently produces. 

* * *
![Flag](/images/flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point?
<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. 
-   Explain each argument in the code section. 
-   Tell us how it functions independently and within the whole program 

* * *

```
A significant part of my program is properly plotting the exact measurements of the flag, because the process was not as easy,especially because the flag has certain shapes that isn't as easy to measure and code it. My flags process was a bit hard because I wasn't as sure if I had the right measurements and there was times where I found myself lost and confused because I wasn't sure what the measurements were.
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
(define size 10)
(put-image (star (* size 6) "solid" "whitesmoke")
                                 (* size 7) (* size 16)
(put-image (rotate 270(triangle (* size 30) "solid" "firebrick"))
                      (* size 12) (* size 14)
                      (put-image (rectangle  (* size 60) (* size 7) "solid" "whitesmoke")
                                 (* size 20) (* size 21)
                                 (put-image (rectangle (* size 60) (* size 7) "solid" "whitesmoke")
                                           (* size 20) (* size 8) 
                                            (rectangle WIDTH HEIGHT "solid" "navy")))))
(define WIDTH (* size 45))
(define HEIGHT (* size 29))

```
