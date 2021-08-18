## FUNCTIONAL PROGRAMMING

### Functional Programming Concepts

**1-What is functional programming?**

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

**2-What is a pure function and how do we know if something is a pure function?**

we know a function is pure if it satisfies to questions : does it return the same result if given the same argument?and does it not cause any observable side effects?

**3-What are the benefits of a pure function?**

Testing

**4-What is immutability?**

we say immutable if it's cannot be changed. Immutable if it's state cannot be changed after they have been created.

**5-What is Referential transparency?**

when a function consistently returns the same result with like arguments . it's the result of using pure functions and immutable data.

### Node JS Tutorial for Beginners #6 - Modules and require()

**1-What is a module?**

Module's consist of like logical code . the module code will serve a certain functionality .

**2-What does the word ‘require’ do?**

it allows us to use other files in the file that requires the external file or module.


**3-How do we bring another module into the file the we are working in?**

we need to require a function in the file that is to be used. we can set this as variable and then use the variable as an object to access the module's exports.

**4-What do we have to do to make a module available?**

we need to export the module from the file where it exists.