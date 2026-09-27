# Java Practice Projects

A collection of Java programs written while learning core concepts — variables, conditionals, loops, arrays, classes, and Swing GUIs. Each folder is a small standalone Maven/NetBeans project.

---

## Console programs — calculators & conditionals

| Project | Description |
|---|---|
| `BEEFIT` | BMI calculator — loops asking for body mass and height via popup dialogs until 0 is entered to stop. |
| `mavenproject1` | Salary increase calculator — asks for current salary and department, applies a 10% or 8% raise. |
| `mavenproject2` | Checks whether a typed month ("january"/"july") matches valid enrollment months. |
| `mavenproject3` | TV price selector demo — shows three TV prices formatted as currency using `DecimalFormat`. |
| `mavenproject4` | TV installment calculator — picks a TV (A/B/C) and works out monthly payments with interest. |
| `mavenproject5` | Cinema ticket pricing by age. *(Bug: `iAge <= 12` is checked twice, so the adult price branch never runs.)* |
| `mavenproject6` | Ticket-by-age calculator. *(Has syntax errors — missing semicolons, misplaced braces — will not compile as-is.)* |
| `mavenproject7` | Movie ticket price by age and student status, using popup dialogs. |
| `mavenproject8` | Same idea as `mavenproject7` — ticket price by age and student flag — syntactically clean. |
| `mavenproject9` | Transport cost calculator — mass, distance, transport mode (Road/Train/Air), insurance, and VAT. *(Total calculation has a logic slip.)* |
| `mavenproject10` | Simple pass/fail check based on mark or attendance sessions. |
| `mavenproject11` | Area calculator for a circle, square, or triangle depending on the user's shape choice. |
| `mavenproject18` | "Lotto" number picker — user enters 5 numbers, program generates 5 random ones. *(Comparison logic is off, so a win can't really be detected.)* |
| `mavenproject20` | Plain "Hello World!" starter template. |
| `mavenproject21` | Mini hotel booking menu — add adults/children, show running balance. *(Menu-loop logic has a couple of bugs.)* |
| `mavenproject22` | Number-guessing game against a random target; counts attempts. |
| `mavenproject23` | Counts how many of 10 entered integers are positive, negative, or zero. |
| `practice11` | Shirt purchase calculator — applies a 20% discount if the order total is over R200. |
| `tickets` | Calculates revenue from student/lecturer ticket sales, with a bulk-sales surcharge. |

## Loops & randomness

| Project | Description |
|---|---|
| `dice` | Coffee/tea order via `switch`, then a `while` loop counting up to simulate rolling toward a "Yatzy" (6). |
| `Random` | Empty shell — imports `java.util.*` but has no logic yet. |
| `RandomNumber` | Number-guessing game (1–100) against the computer. *(Infinite-loop bug in the "too high" branch.)* |
| `mavenproject13` | Generates 3 random unique digits (1–9). *(The "no duplicates" check has a small bug, so duplicates can slip through.)* |
| `mavenproject12` | Reads 4 numbers, meant to flag odd ones. *(The boolean flags are never set to `true`, so it always reports "all even.")* |
| `TestMarks` | Loops asking for test marks out of 60, converts each to a percentage, until the user answers "N". |
| `Activity15` | Loops through a 6-element array asking for subject percentages. *(Array-index bug — `i+1` goes out of bounds.)* |

## Classes & basic OOP

| Project | Description |
|---|---|
| `mavenproject1` (`animal.java`, `dog.java`) | Tiny inheritance example — `dog` extends `animal` and overrides a `speak()` method that prints "barks". |
| `mavenproject14` | Defines a `kb` class for student profiles. *(Main class has compile errors — undefined type, incomplete statement — will not build.)* |
| `mavenproject15` | Meant to capture name/gender via Scanner. *(The public class is named `Entrance`, which doesn't match the filename `Mavenproject15.java`, so it won't compile; also has an infinite-loop bug.)* |
| `mavenproject16` | Incomplete stub — just a broken `package` line, no real class body. |
| `mavenproject19` | Two files working together: `kb.java` captures marks for multiple students and reports pass/fail counts and class average; `Mavenproject19.java` is the entry point that calls it. |
| `practice` | Small student-records app — `Student` class plus a `HashMap`-backed database with a popup menu to capture, search, and display students. *(Constructor args are passed in the wrong order, so ID/Name get swapped.)* |
| `democlass` | Menu demo (deposit/withdraw/check balance) using `switch` — prints the chosen option only, no real banking logic yet. |
| `numbergrid` | Prints a small 2D array as a grid using nested loops. |

## Other

| Project | Description |
|---|---|
| `GUI` | A Swing desktop app with a button that counts and displays how many times it's been clicked. |
| `mavenproject17` | Reads a text file and counts word frequency using a `HashMap`. |

---

### Notes for cleanup
A few projects currently fail to compile and would need fixes before they build: `mavenproject6`, `mavenproject14`, and `mavenproject15`. Several others run but contain logic bugs described above.
