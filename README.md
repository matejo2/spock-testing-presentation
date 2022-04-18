# spock-testing-presentation

This is the current structure for my spock presentation.

Slides are made with the reveal js framework :) 
--

Spock Testing Framework

- maybe add some history to it

- what features are there? 
    - main feature is you can powerfully describe what it does
    - failures of tests are easily visible
    - no more mocking frameworks

- it is written in groovy, but fear not! 
  If you can write java this is no problem for you
  
- HOW TO USE IT
  
- the super basic expect test
  - easiest, most basic way to use it. you probably wont see it that much, but its a basic
  - the test names are strings, so you can describe the teast really accurately
    
- given-when-then structure
    - most of the time you will see/use this structure
    - spock orders the things, given is the setup, when is the thing you want to execute, then lets you assert everthing
    
- exception handling
    - thrown(exception)

- mocking (generally)
    - N * MockOfThing 
    - MyMockClass mock = Mock()
    - no extra testing framework like in junit
    - mocks are also stubs you can assign value to them mock << 42

- parameterized tests (they suck in junit)
    - data tables
    - much, much easier than in junit


- How to use it in actuallity
    - dependencies b=tch
    - when using spring, also use spock-spring
    
--