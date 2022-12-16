[Advanced and Robot Programming](https://corsi.unige.it/en/off.f/2022/ins/60228?codcla=10635)<br>
**Programmer:** [Ankur Kohli](https://github.com/ankurkohli007)<br>
[M.Sc Robotics Engineering](https://corsi.unige.it/corsi/10635)<br>
[University of Genoa (UniGe)](https://unige.it/en)<br>
**Supervisor:** [Prof. Renato Ugo Raffaele Zaccaria](https://rubrica.unige.it/personale/VUFOXVhs) & [Prof. Simone Macciò](https://rubrica.unige.it/personale/UUNAWFho)

## Dining Philosopher Problem ##

  ■ Five philosophers are in a **thinking - eating** cycle.<br>
  ■ When a philosopher gets hungry, he sits down, picks up **his left** and then **his right** chopsticks, and eats.<br>
  ■ A philosopher can eat only if he has **both** chopsticks.<br>
  ■ After eating, he puts down both chopsticks and thinks.<br>
  ■ This cycle continues.<br>

![alt text](image1.png)

The above figure shows the brief structure of the **Dining Philosopher Problem**.

## Assignment Requirements ##

* Solved the problem with 5 processes, one per philosopher. Each philosopher is endless cycling, with randomly variable period (random "eating" time).

* A further process stores, using shared memory, the 5 forks.

* Each philosopher prints on the screen what is doing. The same is done for the forks status.

* Show that the solution never gets deadlocked, by making the philosophers to pick up simultaneously the 5 forks.


