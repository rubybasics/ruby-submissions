Assessed By: Beth Sebian

Repo: https://github.com/cmacaulay/headcount

Notes: 
* i0-4 running, 6 started
* Really strong testing, some gaps, but altogether solid
* Ruby style generally solid. Some opportunities for refactoring long methods and splitting into smaller methods (style and encapsulation issue)
* Good use of enumerables

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations

* 4: Application fulfills all expectations of Iterations 0 - 6 *as well as* one additional, comparable Iteration of your own design.
* 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6
* **2: Application has some missing functionality but no crashes**
* 1: Application crashes during normal usage

### 2. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
* **2: Application makes some use of tests, but the coverage is insufficient**
* 1: Application does not demonstrate strong use of TDD

### 3. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* **3: Application effectively breaks logical components apart but breaks the principle of SRP**
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 4. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* **3:  Application shows strong effort towards organization, content, and refactoring**
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 5. Enumerable & Collections

* **4: Application consistently makes use of the best-choice Enumerable methods**
* 3: Application demonstrates comfortable use of appropriate Enumerable methods
* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques
* 1: Application demonstrates deficiencies with Enumerable and struggles with collections

### 6. Code Sanitation

The output from `rake sanitation:all` shows...

* **4: Zero complaints**
* 3: Five or fewer complaints
* 2: Six to ten complaints
* 1: More than ten complaints
