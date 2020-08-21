# Dragon (Object Programming Language)

### Introduction
Dragon and DragonScript are a very high level 6th generation programming language that is inspired from ECMAScript 6 (JavaScript), Python3, and Ruby. Unlike JavaScript where everything is represented as a function. This computer language represents as objects and rules (in the form of functions) which govern how these objects behave in our environment. 

Dragon is compiled with a High Level Assembler (HLA). Its sister langauge, DragonScript, is one abstraction layer above Dragon. DragonScript utilizes a JIT (Just In Time) style interpretter; which is similiar to our compiler. The interpretter uses prebuilt binaries that Dragon compiles to.

### Archecture 

![Image of Dragon Programming Language Lifecycle](https://github.com/dreamscale-io/Dragon/blob/master/Screen%20Shot%202019-12-20%20at%203.45.28%20PM.png?raw=true)

### Theory
Everything in dragon is considered an *Object*; therefore any function F would be part of object O, and can be represented as 

```mathematica
f(x) = o(f(x))
```

where f of x is a transformation on our base object prototype data structure typically typed as

```
<class>o(input){output}
```

given statement as defined above, we can deduce that a given program is a series (or array) of statements. This would be represented by an array of functional object statements.

```
O[<class>o(input){output}, ...]
```

Within fluid systems such as quantum mechanics, evolutionary systems like genectics, and artificial intelligence require anaylitical continuence of problem solving. This theory can be translated to MIP* = RE problem solving, where a series of cross examined interrogators and provers provides equal reliable results verses using a singleton state which may or not need to iterate infinity to determine if in fact the solution is correct. These principals are very important when it comes to developing 6th generation computer programs that bridge the realm of classical and quantum computing. By extending the scope of core data structures in computer software programs into a lower level, such as functions as objects, expands our programs abilities to interact with quantum system. Take for example a simple computer program that models visual input as a quantum system in real-time by storing pixel information into an array of qubits. 

Dragon allows us to structure our states at a very high level. This capability allows our programs to mutate and transform data without the overhead and security required to instantiate new functions. This is akin to writing a mathematical algorithm that changes uniquely everytime you try to complete the statement. Alan Turing discovered this with his Halt program test which checks to see if a programs statement will cause the program to halt or loop forever, Turing ended up discovering that the solution is impossible to solve. However, he theorized about using quantum systems to solve such things.


### Example
Now  lets take a look at a simple dragon program that prints some text on the console terminal.

```dragon
-- a simple hello world program written in Dragon
program: HelloWorld;
:uses: Console;

-- allocate memory and pointers
:assign: :text: @String;
:assign: :print: => @text;

-- define object
@print: =>
  :write: "Hello " + @text;

-- execute our procedure
:execute: => 
  @print: "World";
  :quit:0;
```

One feature of Dragon which is sort of a throw back, is the ability to inline WASM directly into your code. The compiler and interpretter will detect automagically and wrap the specific inlined code blocks with the appropiate data structure using the magic of object autoclassification and context resource injectors. These are more advanced topics which will be covered by future versions of Dragon

Alot of the syntax and terms are inspired and pay homage to our legacy of HyperTalk and Pascal. Which in this century are to most just memories. However, if one researchs the history of some of our more modern and popular languages such as JavaScript, Ruby, or Python, you find they are in essences deriavatives of Turbo Pascal and HyperTalk. These legacy languages , the first generation of high-level programming languages, employed advanced natural language syntax and stateful function transformations; which are very useful for state machine algorithms and evolutionary systems. 

As technology divergese from closed and private archecture and PSI (program structure interfaces - used by firmware and BIOS); as articial intelligent evolutionary systems and tensor membrane's require, We required state based control systems that are able to process control functions in real-time. Dragon is similiar to a pheonix of the modern 5th gen programming languages, allowing for programs which require order of magnitude greater precision than our existing 32 and 64 bit mode operating systems.

At the heart of all systems authored with Dragon, is a micro kernel and virtual machines; not unlike it's cousin, Java's. The primary difference one can assertain between Dragon and Java is that Java requires a java runtime environment (JRE) to be install on the operating system. Dragon's compiler however includes an encryption micro bootloader and nanokernel which our software will run within. These are native to the operating, as they are compiler into assmebly which is interpretted in realtime by the operating system. This is made possibly by phenomenal advancements in memory access and storage. 
