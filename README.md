# philosophy
The core values that inform Mosaic's design

Mosaic is born of a frustration with some aspects of the Rails doctrine.

Rails frustrations:
  * Poor separation of concerns, can query and update database from inside of view
  * Performant and scalable code requires discipline beyond what the framework encourages
  * Testing code that interacts with the database requires either mocking complex relationships or expensive tests that interact with DB
  * Composability and code reuse are an afterthought

TODO - sit down and rephrase/rethink all of this with Michael

Mosaic design:
  * Separate concerns
  * Declare dependencies
  * Encourage composability
  * Collaboration in large teams is of the utmost importance
