# ECE444-F2022-Lab6
## TDD Pros & Cons
### Pros
As tests are written for each feature, it makes the code more modular.

As aforementioned, since the code is more modular, it is easier to maintain post development. Changes form adding features can reuse written tests.

Since tests are modular, the coverage is very high and testing is detailed. This also makes debugging easier since tests give detailed information.

Avoids writing unnecessary code, no extra code will be writting if all tests passed, since feature development starts with writing tests.
### Cons
Makes changes to requirements expensive during development, as both tests and implementation code needs to be changed.

Difficult to find bugs that are in both test code and implementation code. Issues not considered when writing tests can be hard to find.

Slow implementation, as implementations requires accompanied tests for each small feature, it extends implementation time.

TDD requires team wide coverage because it affects planning, so all member of the team must follow TDD.
