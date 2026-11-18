# 🎬 Movie Ticket Booking System

![C](https://img.shields.io/badge/Language-C-00599C?style=flat-square&logo=c&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

A terminal app in C where you pick a movie, see which seats are free, and book one. After booking, you get a ticket printed right in the console. 🍿

I built it to get comfortable with **2D arrays** (the seat map) and keeping track of state across a menu loop.

---

## ✨ Features

- 🎞️ 3 movies to choose from: *Avengers: Infinity War*, *Captain Marvel* and *Spider-Man: Homecoming*
- 💺 A 5 × 5 seat map per movie (`A1` to `E5`)
- ✅ Booked seats are marked on the map, so the same seat can't be sold twice
- 🎟️ Prints a ticket with your name, phone number, movie and seat

## 🚀 Run it

```bash
gcc "Movie Ticket Booking System.c" -o movie
./movie
```

```text
=====Movie Ticket Booking System=====
 1. Show All Movie.
 2. Buy a Ticket.
 3. Exit.
```

Choose **Buy a Ticket**, pick a movie number, then type a seat like `B3`.

## 🧠 What I practiced

- Arrays of structs, with a 2D `bool` array inside each one
- Converting user input like `B3` into array indexes
- Keeping a simple menu loop clean and readable

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
