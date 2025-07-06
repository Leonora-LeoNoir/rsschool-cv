# LEONORA KOLESSOVA
### JUNIOR FRONTEND DEVELOPER
### AGE 29 YERS
***

![avatar](image/ava.png)

***
# CONTACT INFORMASHION
***
**Phone:** +7(777) 577 91 77

**E-mail:** assassya200895@gmail.com

**Telegram:** @LeonoraR
###### [Leonora-LeoNoir](https://github.com/Leonora-LeoNoir "GitHub link")
***

# ABOUT ME
***
I studied to be a [programmer](#3), and I've been working in IT all my life. I am a fast learner and am eager to learn new things.

There are skills in [video editing](#1) and [photo processing](#2).

In my free time from studies and work I am engaged in writing.
***

# SKILLS
***
* Programming
    * HTML
    * CSS
    * Python
    * Borland Delphi 
    * MS Visual C++

* Working with Graphics<a id="2"></a>
    * Adobe Photoshop
    * Adobe Illustrator
    * Figma
    * Affinity Disigner

* Video editing<a id="1"></a>
    * Davinche Resolv
    * CapCut
    * Adobe After Effects
***

# CODE EXAMPLE
***
**A game of moving around the squares**
> Assignment : Create a Turtle class that stores the x and y positions of the turtle, and s - the number of cells it moves per move
> this class has methods:
> 
> ● go_up() - increases y by s
> 
> ● go_down() - decreases y by s
> 
> ● go_left() - decreases x by s
> 
> ● go_right() - increases y by s - Most likely the condition is a typo, I do it as it should be done with coordinates, I increase x instead of y. 
> 
> ● evolve() - increases s by 1
> 
> ● degrade() - decreases s by 1 or throws an error when s may become ≤ 0.
> 
> count_moves(x2, y2) - returns the minimum number of actions for which the turtle can get to x2 y2 from the current position.
``` # -*- coding: utf-8 -*-
class cherepashka (object):
    def __init__(self, x = 0, y = 0, s = 1):
        self.x = x
        self.y = y
        self.s = s

    def go_up(self):
        self.y += self.s
        print(f"Черепашка прошла наверх на {self.y}")
        
    def go_down(self):
        self.y -= self.s
        print(f"Черепашка прошла вниз на {self.y}")
    
    def go_left(self):
        self.x -= self.s
        print(f"Черепашка прошла налево на {self.x}")
        
    def go_right(self):
        self.x += self.s
        print(f"Черепашка прошла направо {self.x}")

    def evolve(self):
        self.s += 1
        print(f"Черепашка теперь может проходить {self.s} клеток за раз")
        
    def degrade(self):
        self.s -= 1
        if self.s <= 0:
            print(f"Черепашка не может не двигаться")
        else:
            print(f"Черепашка теперь может проходить {self.s} за раз")
        return 

    def count_moves(self, x2, y2):
        dx = abs(self.x - x2)
        dy = abs(self.y - y2)
        if dx % self.s != 0 or dy % self.s != 0:
            return "Невозможно дойти точно до нужной точки с текущим шагом"
        return (dx // self.s) + (dy // self.s)
```    
``` 
t = cherepashka()

print("На какой клетке по X, должна оказаться черепашка: ")
n = int(input())
print("На какой клетке по Y, должна оказаться черепашка: ")
m = int(input())

print(f"Минимальное количество шагов до {n, m}:", t.count_moves(n, m))  
```
```
while True:
    print("Команды: u -вверх, d - вниз, l -  влево ,r - вправо, e -увеличить кол-во шагов, x -уменьшить количество шагов, stop - выход")
    command = input("\nВведите команду: ").strip().lower()
    if command == "u":
        t.go_up()
        print(f"Минимальное количество шагов до {n, m}:", t.count_moves(n, m)) 
    elif command == "d":     
        t.go_down()
        print(f"Минимальное количество шагов до {n, m}:", t.count_moves(n, m)) 
    elif command == "l":
        t.go_left()
        print(f"Минимальное количество шагов до {n, m}:", t.count_moves(n, m))   
    elif command == "r":
        t.go_right()
        print(f"Минимальное количество шагов до {n, m}:", t.count_moves(n, m)) 
    elif command == "e":
        t.evolve() 
    elif command == "x":
        t.degrade()
    elif command == "stop":
        break
    else:
        print("Неизвестная команда") 
```
# WORK
***
Content specialist at DN.ru
***

# EDUCACION
***
* Secondary professional: Programmer Technician - Almaty Technical-Economic College<a id="3"></a>
* Unfinished higher education (3rd semester) Fullstack Developer - Synergy University
* Courses
    * HTML&CSS
    * Web Design
***

# LANGUAGES
***
* Russian - Native
* English - A1/A2
***