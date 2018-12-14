---
layout: post 
title: "Flag Project in Process" 
date: 2018-12-14
---

This week I started to code my Cuban Flag and it was a very long process because it took me a while to figure out the measurements of each stripe and the meaurements of the size of the layout, and the size of the triangle that the Cuban Flag has.
```
(put-image (star 60 "solid" "whitesmoke")
                                 70 160
(put-image (rotate 270(triangle 300 "solid" "firebrick"))
                      120 140
                      (put-image (rectangle  600 70 "solid" "whitesmoke")
                                 200 210
                                 (put-image (rectangle 600 70 "solid" "whitesmoke")
                                            200 80 
                                            (rectangle WIDTH HEIGHT "solid" "navy")))))
(define WIDTH 450)
(define HEIGHT 290)
```
