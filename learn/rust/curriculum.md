# Rust Learning Curriculum

## What to Learn in Rust

This curriculum maps directly to "The Rust Programming Language" book. Each lesson corresponds to a chapter or section in the book, with hands-on exercises to practice what you learn.

**How to use this curriculum:**
1. Read the corresponding chapter in the Rust book
2. Complete the exercises in this lesson/lesson directory
3. Update progress.md to track completion
4. Ask your agent questions about concepts you don't understand

## Chapter 1: Getting Started

### Lesson 1.1 - Installation
**Directory**: `lesson-01-installation/`
**Book**: Chapter 1.1

**Concepts**:
- Installing Rust with rustup
- Checking Rust installation with `rustc --version`
- Local documentation with `rustup doc`
- Text editors and IDEs
- Working offline with dependencies

### Lesson 1.2 - Hello, World!
**Directory**: `lesson-02-hello-world/`
**Book**: Chapter 1.2

**Concepts**:
- Writing and running a Rust program
- Anatomy of a Rust program
- Compiling with rustc
- Formatting with rustfmt

### Lesson 1.3 - Hello, Cargo!
**Directory**: `lesson-03-hello-cargo/`
**Book**: Chapter 1.3

**Concepts**:
- Creating projects with `cargo new`
- Understanding Cargo.toml and Cargo.lock
- Building and running with cargo
- Building for release
- Checking code with `cargo check`
- Cargo conventions

## Chapter 2: Programming a Guessing Game

### Lesson 2 - Building a Guessing Game
**Directory**: `lesson-04-guessing-game/`
**Book**: Chapter 2

**Concepts**:
- Setting up a new project
- Processing user guess
- Generating random numbers
- Comparing guess to secret number
- Allowing multiple guesses with looping
- Handling invalid input
- Using crates from crates.io

This lesson ties together concepts from Chapter 1 with a complete program.

## Chapter 3: Common Programming Concepts

### Lesson 3.1 - Variables and Mutability
**Directory**: `lesson-05-variables/`
**Book**: Chapter 3.1

**Concepts**:
- Variables and immutability
- Mutable variables with `mut`
- Constants with `const`
- Shadowing variables
- Differences between constants and immutable variables

### Lesson 3.2 - Data Types
**Directory**: `lesson-06-data-types/`
**Book**: Chapter 3.2

**Concepts**:
- Scalar types: integers, floats, booleans, characters
- Integer overflow
- Floating-point types
- Boolean type
- Character type
- Compound types: tuples
- Compound types: arrays
- Invalid array element access

### Lesson 3.3 - Functions
**Directory**: `lesson-07-functions/`
**Book**: Chapter 3.3

**Concepts**:
- Function definitions with `fn`
- Function parameters
- Statements vs expressions
- Functions with return values
- Returning early from functions

### Lesson 3.4 - Comments
**Directory**: `lesson-08-comments/`
**Book**: Chapter 3.4

**Concepts**:
- Single-line comments with `//`
- Multi-line comments with `/* */`
- Doc comments with `///` and `/** */`
- Using `cargo doc` to generate documentation

### Lesson 3.5 - Control Flow
**Directory**: `lesson-09-control-flow/`
**Book**: Chapter 3.5

**Concepts**:
- `if` expressions
- Using `if` in a `let` statement
- Repeating code with `loop`
- Returning values from loops
- Conditional loops with `while`
- Looping through collections with `for`
- Countdown with `for`

## Chapter 4: Understanding Ownership

### Lesson 4.1 - What is Ownership?
**Directory**: `lesson-10-ownership/`
**Book**: Chapter 4.1

**Concepts**:
- Ownership rules
- Variable scope
- The `String` type
- Memory and allocation
- Ways variables and data interact
- Variables and data interacting with clone
- Stack-only data: Copy
- Ownership and functions
- Return values and scope

### Lesson 4.2 - References and Borrowing
**Directory**: `lesson-11-references/`
**Book**: Chapter 4.2

**Concepts**:
- References and borrowing
- Mutable references
- Dangling references
- The rules of references

### Lesson 4.3 - The Slice Type
**Directory**: `lesson-12-slices/`
**Book**: Chapter 4.3

**Concepts**:
- String slices
- String literals as slices
- String slices as parameters
- Other slices

## Chapter 5: Using Structs to Structure Related Data

### Lesson 5.1 - Defining and Instantiating Structs
**Directory**: `lesson-13-structs/`
**Book**: Chapter 5.1

**Concepts**:
- Defining structs
- Using tuple structs without named fields
- Unit-like structs
- Ownership of struct data

### Lesson 5.2 - An Example Program Using Structs
**Directory**: `lesson-14-struct-example/`
**Book**: Chapter 5.2

**Concepts**:
- Building a program to calculate area
- Refactoring with tuples
- Refactoring with structs
- Adding useful functionality with derived traits

### Lesson 5.3 - Methods
**Directory**: `lesson-15-methods/`
**Book**: Chapter 5.3

**Concepts**:
- Defining methods
- Methods with more parameters
- Associated functions
- Multiple impl blocks

## Chapter 6: Enums and Pattern Matching

### Lesson 6.1 - Defining an Enum
**Directory**: `lesson-16-enums/`
**Book**: Chapter 6.1

**Concepts**:
- Enum definition
- Enum values
- The `Option` enum and its advantages over Null

### Lesson 6.2 - The match Control Flow Construct
**Directory**: `lesson-17-match/`
**Book**: Chapter 6.2

**Concepts**:
- Matching with `Option<T>`
- Matches are exhaustive
- `_` placeholder

### Lesson 6.3 - Concise Control Flow with if let
**Directory**: `lesson-18-if-let/`
**Book**: Chapter 6.3

**Concepts**:
- `if let` syntax
- Combining `if let`, `else if`, and `else if let`
- Comparison: `match` vs `if let`

## Chapter 7: Packages, Crates, and Modules

### Lesson 7.1 - Packages and Crates
**Directory**: `lesson-19-packages-crates/`
**Book**: Chapter 7.1

**Concepts**:
- Packages and crates
- Creating a binary package
- Creating a library package
- Package conventions

### Lesson 7.2 - Control Scope and Privacy with Modules
**Directory**: `lesson-20-modules/`
**Book**: Chapter 7.2

**Concepts**:
- Module basics
- Module nesting
- Module paths
- Private vs public
- Relative paths
- Relative paths with `super`
- Bringing paths into scope with `use`
- Creating idiomatic paths with `use`
- Differentiating types vs functions
- Using `as` to provide new names
- Re-exporting names with `pub use`
- Using external packages
- Nested paths with `use`
- The glob operator

### Lesson 7.3 - Paths for Referring to an Item in the Module Tree
**Directory**: `lesson-21-paths/`
**Book**: Chapter 7.3

**Concepts**:
- Exposing paths with `pub`
- Starting relative paths with `super`
- Absolute paths
- Relative paths
- Making structs and enums public

### Lesson 7.4 - Bringing Paths Into Scope with the use Keyword
**Directory**: `lesson-22-use/`
**Book**: Chapter 7.4

**Concepts**:
- Using `use` to bring paths into scope
- Using `as` to provide new names
- Re-exporting names with `pub use`
- Using external packages

### Lesson 7.5 - Separating Modules into Different Files
**Directory**: `lesson-23-module-files/`
**Book**: Chapter 7.5

**Concepts**:
- Module file hierarchy
- `mod.rs` convention
- File structure best practices

## Chapter 8: Common Collections

### Lesson 8.1 - Storing Lists of Values with Vectors
**Directory**: `lesson-24-vectors/`
**Book**: Chapter 8.1

**Concepts**:
- Creating a new vector
- Updating a vector
- Dropping a vector drops its elements
- Reading elements
- Iterating over values
- Using an enum to store multiple types

### Lesson 8.2 - Storing UTF-8 Encoded Text with Strings
**Directory**: `lesson-25-strings/`
**Book**: Chapter 8.2

**Concepts**:
- What is a string?
- Creating a new string
- Updating a string
- Concatenation with `+` or `format!`
- Indexing into strings
- Slicing strings
- Methods for iterating over strings
- Bytes and scalar values and grapheme clusters

### Lesson 8.3 - Storing Keys with Associated Values in Hash Maps
**Directory**: `lesson-26-hash-maps/`
**Book**: Chapter 8.3

**Concepts**:
- Creating a new hash map
- Accessing values
- Updating a hash map: overwriting, only inserting if key has no value, updating based on old value
- Hashing functions

## Chapter 9: Error Handling

### Lesson 9.1 - Unrecoverable Errors with panic!
**Directory**: `lesson-27-panic/`
**Book**: Chapter 9.1

**Concepts**:
- Unwinding and aborting on panic
- Using panic! macro
- Panicking on simple errors
- Using panic! in testing
- Using panic! in examples and prototypes

### Lesson 9.2 - Recoverable Errors with Result
**Directory**: `lesson-28-result/`
**Book**: Chapter 9.2

**Concepts**:
- Matching on Result
- Matching on different errors
- Using `?` operator
- Error propagation shortcuts
- Where `?` can be used

### Lesson 9.3 - To panic! or Not to panic!
**Directory**: `lesson-29-error-guidelines/`
**Book**: Chapter 9.3

**Concepts**:
- Guidelines for error handling
- Examples of when to panic
- Creating custom types for validation
- Building tests for custom types

## Chapter 10: Generic Types, Traits, and Lifetimes

### Lesson 10.1 - Generic Data Types
**Directory**: `lesson-30-generics/`
**Book**: Chapter 10.1

**Concepts**:
- In function definitions
- In struct definitions
- In enum definitions
- In method definitions
- Performance of generic code

### Lesson 10.2 - Defining Shared Behavior with Traits
**Directory**: `lesson-31-traits/`
**Book**: Chapter 10.2

**Concepts**:
- Defining a trait
- Implementing a trait on a type
- Default implementations
- Traits as parameters
- Trait bounds
- The `+` syntax for multiple trait bounds
- Clearer trait bounds with `where` clauses
- Returning types that implement traits
- Using trait bounds to conditionally implement methods
- Blanket implementations

### Lesson 10.3 - Validating References with Lifetimes
**Directory**: `lesson-32-lifetimes-deep/`
**Book**: Chapter 10.3

**Note**: This is an in-depth lesson. You may also reference lessons 26-30 in Phase 9.

**Concepts**:
- Prevents dangling references
- The borrow checker
- Generic lifetimes in functions
- Lifetime annotation syntax
- Lifetime annotations in function signatures
- Thinking in terms of lifetimes
- Lifetime annotations in struct definitions
- Lifetime elision
- Lifetime annotations in method definitions
- The static lifetime
- Generic type parameters, trait bounds, and lifetimes together

## Chapter 11: Writing Automated Tests

### Lesson 11.1 - How to Write Tests
**Directory**: `lesson-33-testing-basics/`
**Book**: Chapter 11.1

**Concepts**:
- Anatomy of a test function
- The `assert!` macro
- The `assert_eq!` macro
- The `assert_ne!` macro
- Adding custom failure messages
- Checking for panics with `should_panic`
- Testing complex conditions

### Lesson 11.2 - Controlling How Tests Are Run
**Directory**: `lesson-34-running-tests/`
**Book**: Chapter 11.2

**Concepts**:
- Running tests in parallel or sequentially
- Ignoring some tests unless specifically requested
- Running tests by function name
- Running ignored tests
- Running all tests regardless of ignoring

### Lesson 11.3 - Test Organization
**Directory**: `lesson-35-test-organization/`
**Book**: Chapter 11.3

**Concepts**:
- Unit tests
- Integration tests
- Submodules in integration tests
- Binary crates with integration tests

## Chapter 12: An I/O Project: Building a Command Line Program

### Lesson 12 - Building a Command Line Program
**Directory**: `lesson-36-command-line-tool/`
**Book**: Chapter 12

**Concepts**:
- Accepting command line arguments
- Reading a file
- Refactoring to improve modularity and error handling
- Building with test-driven development
- Working with environment variables
- Writing to standard error instead of standard out

This chapter is a hands-on project that combines many concepts learned so far.

## Chapter 13: Functional Language Features: Iterators and Closures

### Lesson 13.1 - Closures
**Directory**: `lesson-37-closures-deep/`
**Book**: Chapter 13.1

**Note**: You may also reference lesson 27 in Phase 9 for more on closures.

**Concepts**:
- Capturing the environment with closures
- Closure type inference and annotation
- Storing closures using generic parameters and `Fn` traits
- Caching results with lazy evaluation

### Lesson 13.2 - Processing a Series of Items with Iterators
**Directory**: `lesson-38-iterators-deep/`
**Book**: Chapter 13.2

**Note**: You may also reference lesson 17 in Phase 5 for more on iterators.

**Concepts**:
- The `Iterator` trait and the `next` method
- Iterating over an immutable reference
- Iterating over a mutable reference
- Iterating over ownership
- Methods that consume the iterator
- Methods that produce other iterators
- Methods that produce other collections

### Lesson 13.3 - Improving Our I/O Project
**Directory**: `lesson-39-improve-cli/`
**Book**: Chapter 13.3

**Concepts**:
- Using iterators to improve the CLI tool
- Refactoring functions to use iterator methods
- Making code clearer and more concise
- Testing iterator adaptors

### Lesson 13.4 - Comparing Performance: Loops vs. Iterators
**Directory**: `lesson-40-performance-comparison/`
**Book**: Chapter 13.4

**Concepts**:
- Performance of iterators
- Zero-cost abstractions
- Benchmarking loops vs iterators
- Understanding compiler optimizations

## Chapter 14: More about Cargo and Crates.io

### Lesson 14.1 - Customizing Builds with Release Profiles
**Directory**: `lesson-41-release-profiles/`
**Book**: Chapter 14.1

**Concepts**:
- Release profiles
- Configuring release profiles
- Optimizing for compilation speed
- Optimizing for runtime performance
- Custom profiles

### Lesson 14.2 - Publishing a Crate to Crates.io
**Directory**: `lesson-42-publishing-crates/`
**Book**: Chapter 14.2

**Concepts**:
- Making useful documentation comments
- Making useful error messages
- Creating testable code examples
- Creating workspaces
- Binary crates vs library crates
- Publishing to crates.io
- Version management

### Lesson 14.3 - Cargo Workspaces
**Directory**: `lesson-43-cargo-workspaces/`
**Book**: Chapter 14.3

**Concepts**:
- Creating a workspace
- Creating the second crate in the workspace
- Running tests in a workspace
- Building the workspace
- Dependencies on external crates

### Lesson 14.4 - Installing Binaries with cargo install
**Directory**: `lesson-44-cargo-install/`
**Book**: Chapter 14.4

**Concepts**:
- Installing binaries from crates.io
- Installing custom tools
- Updating installed binaries
- Custom installation paths

### Lesson 14.5 - Extending Cargo with Custom Commands
**Directory**: `lesson-45-custom-cargo-commands/`
**Book**: Chapter 14.5

**Concepts**:
- Making custom cargo commands
- Adding binaries to PATH
- Custom cargo subcommands

## Chapter 15: Smart Pointers

### Lesson 15.1 - Using Box<T> to Point to Data on the Heap
**Directory**: `lesson-46-box-pointer/`
**Book**: Chapter 15.1

**Concepts**:
- Using a `Box<T>` to store data on the heap
- Enabling recursive types with boxes
- Cons List example
- Boxed recursive types

### Lesson 15.2 - Treating Smart Pointers Like Regular References
**Directory**: `lesson-47-deref-trait/`
**Book**: Chapter 15.2

**Concepts**:
- Implementing the `Deref` trait
- Implicit `Deref` coercion
- How `Deref` coercion works
- Similarities between `Box<T>`, `Rc<T>`, and references

### Lesson 15.3 - Running Code on Cleanup with the Drop Trait
**Directory**: `lesson-48-drop-trait/`
**Book**: Chapter 15.3

**Concepts**:
- Implementing the `Drop` trait
- Dropping values early with `std::mem::drop`
- Memory and resource cleanup
- Drop order

### Lesson 15.4 - Rc<T>, the Reference Counted Smart Pointer
**Directory**: `lesson-49-rc-pointer/`
**Book**: Chapter 15.4

**Concepts**:
- Using `Rc<T>` to share data
- Cloning `Rc<T>` increases reference count
- Shared ownership
- Reference counting

### Lesson 15.5 - RefCell<T> and the Interior Mutability Pattern
**Directory**: `lesson-50-refcell/`
**Book**: Chapter 15.5

**Concepts**:
- Enforcing borrowing rules at runtime with `RefCell<T>`
- Interior mutability pattern
- Using `RefCell<T>` with `Rc<T>`
- Runtime borrowing rules

### Lesson 15.6 - Reference Cycles Can Leak Memory
**Directory**: `lesson-51-reference-cycles/`
**Book**: Chapter 15.6

**Concepts**:
- Creating a reference cycle
- Preventing reference cycles
- Using `Weak<T>` instead of `Rc<T>`
- Tree-like data structures

## Chapter 16: Fearless Concurrency

### Lesson 16.1 - Using Threads to Run Code Simultaneously
**Directory**: `lesson-52-threads/`
**Book**: Chapter 16.1

**Concepts**:
- Creating a new thread with `thread::spawn`
- Waiting for all threads to finish
- Using `join` handles
- Thread execution order

### Lesson 16.2 - Transfer Data Between Threads with Message Passing
**Directory**: `lesson-53-channels/`
**Book**: Chapter 16.2

**Concepts**:
- Channels and ownership transfer
- Creating multiple producers with `clone`
- `mpsc`: multiple producer, single consumer
- Sending messages between threads

### Lesson 16.3 - Shared-State Concurrency
**Directory**: `lesson-54-shared-state/`
**Book**: Chapter 16.3

**Concepts**:
- Using `Mutex<T>` for mutual exclusion
- Sharing `Mutex<T>` between multiple threads
- Multiple ownership with `Rc<T>`
- Atomic reference counting with `Arc<T>`
- Thread-safe smart pointers

### Lesson 16.4 - Extensible Concurrency with Send and Sync
**Directory**: `lesson-55-send-sync/`
**Book**: Chapter 16.4

**Concepts**:
- The `Send` trait for safe transfer
- The `Sync` trait for safe sharing
- Implementing `Send` and `Sync`
- Most types are `Send` and `Sync`

## Chapter 17: Fundamentals of Asynchronous Programming

**Note**: This chapter is newer in the Rust book. Consider it Phase 11.

### Lesson 17.1 - Futures and the Async Syntax
**Directory**: `lesson-56-async-basics/`
**Book**: Chapter 17.1

**Concepts**:
- Futures
- Async syntax
- The `async` keyword
- The `await` keyword
- Async functions

### Lesson 17.2 - Applying Concurrency with Async
**Directory**: `lesson-57-async-concurrency/`
**Book**: Chapter 17.2

**Concepts**:
- Async runtime
- Running async code
- Converting sync code to async
- Async vs sync performance

### Lesson 17.3 - Working With Any Number of Futures
**Directory**: `lesson-58-multiple-futures/`
**Book**: Chapter 17.3

**Concepts**:
- Joining futures
- Selecting futures
- Race conditions in async
- Concurrent async operations

### Lesson 17.4 - Streams: Futures in Sequence
**Directory**: `lesson-59-streams/`
**Book**: Chapter 17.4

**Concepts**:
- Streams concept
- Stream trait
- Processing streams
- Error handling in streams

### Lesson 17.5 - A Closer Look at the Traits for Async
**Directory**: `lesson-60-async-traits/`
**Book**: Chapter 17.5

**Concepts**:
- Future trait
- Stream trait
- Pinning
- Async traits

### Lesson 17.6 - Futures, Tasks, and Threads
**Directory**: `lesson-61-futures-tasks/`
**Book**: Chapter 17.6

**Concepts**:
- Futures and tasks
- Tasks vs threads
- Task scheduling
- Async runtime internals

## Chapter 18: Object Oriented Programming Features

### Lesson 18.1 - Characteristics of Object-Oriented Languages
**Directory**: `lesson-62-oop-characteristics/`
**Book**: Chapter 18.1

**Concepts**:
- Objects contain data and behavior
- Encapsulation
- Inheritance
- Polymorphism
- Rust's approach to OOP

### Lesson 18.2 - Using Trait Objects to Abstract over Shared Behavior
**Directory**: `lesson-63-trait-objects/`
**Book**: Chapter 18.2

**Concepts**:
- Trait objects for polymorphism
- Dynamic vs static dispatch
- Object safety
- Boxed trait objects

### Lesson 18.3 - Implementing an Object-Oriented Design Pattern
**Directory**: `lesson-64-oop-pattern/`
**Book**: Chapter 18.3

**Concepts**:
- State pattern implementation
- Trade-offs of design patterns
- OOP patterns in Rust

## Chapter 19: Patterns and Matching

### Lesson 19.1 - All the Places Patterns Can Be Used
**Directory**: `lesson-65-pattern-locations/`
**Book**: Chapter 19.1

**Concepts**:
- `match` arms
- `if let` expressions
- `while let` expressions
- `for` loops
- `let` statements
- Function parameters

### Lesson 19.2 - Refutability: Whether a Pattern Might Fail to Match
**Directory**: `lesson-66-refutability/`
**Book**: Chapter 19.2

**Concepts**:
- Irrefutable patterns
- Refutable patterns
- When to use which
- Pattern matching errors

### Lesson 19.3 - Pattern Syntax
**Directory**: `lesson-67-pattern-syntax/`
**Book**: Chapter 19.3

**Concepts**:
- Matching literals
- Matching named variables
- Multiple patterns
- Matching ranges
- Destructuring structs
- Destructuring enums
- Destructuring nested structs and enums
- Ignoring values
- Extra conditionals with match guards
- Binding patterns

## Chapter 20: Advanced Features

### Lesson 20.1 - Unsafe Rust
**Directory**: `lesson-68-unsafe-rust/`
**Book**: Chapter 20.1

**Concepts**:
- What unsafe is and isn't
- Dereferencing raw pointers
- Calling unsafe functions or methods
- Accessing or modifying mutable static variables
- Implementing unsafe traits
- Accessing fields of unions

### Lesson 20.2 - Advanced Traits
**Directory**: `lesson-69-advanced-traits/`
**Book**: Chapter 20.2

**Concepts**:
- Associated types
- Default generic type parameters
- Fully qualified syntax
- Supertraits
- Newtype pattern

### Lesson 20.3 - Advanced Types
**Directory**: `lesson-70-advanced-types/`
**Book**: Chapter 20.3

**Concepts**:
- Using the newtype pattern for type safety
- Creating type aliases
- The never type `!`
- Dynamically sized types
- Sized trait

### Lesson 20.4 - Advanced Functions and Closures
**Directory**: `lesson-71-advanced-functions/`
**Book**: Chapter 20.4

**Concepts**:
- Function pointers
- Returning closures
- Using the `Fn` traits as trait bounds

### Lesson 20.5 - Macros
**Directory**: `lesson-72-macros/`
**Book**: Chapter 20.5

**Concepts**:
- The difference between macros and functions
- Declarative macros with `macro_rules!`
- Procedural macros
- Attribute-like macros
- Function-like macros
- Custom derive macros

## Chapter 21: Final Project: Building a Multithreaded Web Server

### Lesson 21 - Building a Multithreaded Web Server
**Directory**: `lesson-73-web-server/`
**Book**: Chapter 21

**Concepts**:
- Building a single-threaded web server
- From single-threaded to multithreaded server
- Graceful shutdown and cleanup
- Handling requests
- Sending responses
- Using threads for concurrency

## Appendices

### Appendix A - Keywords
**Directory**: `appendix-keywords/`
**Book**: Appendix A

### Appendix B - Operators and Symbols
**Directory**: `appendix-operators/`
**Book**: Appendix B

### Appendix C - Derivable Traits
**Directory**: `appendix-traits/`
**Book**: Appendix C

### Appendix D - Useful Development Tools
**Directory**: `appendix-tools/`
**Book**: Appendix D

### Appendix E - Editions
**Directory**: `appendix-editions/`
**Book**: Appendix E

### Appendix F - Translations of the Book
**Directory**: `appendix-translations/`
**Book**: Appendix F

### Appendix G - How Rust is Made and “Nightly Rust”
**Directory**: `appendix-nightly/`
**Book**: Appendix G

---

## How to Use This Curriculum

1. **Start at Chapter 1**: Read the corresponding book chapter first
2. **Do the lesson exercises**: Complete exercises in the lesson directory
3. **Update progress.md**: Track completed lessons and exercises
4. **Ask agent for help**: Reference `AGENTS.md` for teaching philosophy
5. **Follow the book**: This curriculum is designed to be used alongside the Rust book

## Book Reference Links

- **The Rust Book**: https://doc.rust-lang.org/book/
- **Standard Library**: https://doc.rust-lang.org/std/

## Learning Approach

This curriculum provides **hands-on exercises** that reinforce concepts from each book chapter. Unlike just reading the book, you'll write code for each concept, helping solidify your understanding.

**For each chapter:**
1. Read the chapter in the Rust book (20-30 minutes)
2. Complete the exercises (30-60 minutes)
3. Review what you've learned (10 minutes)
4. Update progress.md (5 minutes)
5. Ask your agent questions as needed

**Total time per chapter**: ~1-2 hours

**Total curriculum time**: ~50-100 hours (depending on pace)

---

**Note**: This curriculum covers Rust book Chapters 1-21 + Appendices, with 1-4 lessons per chapter depending on complexity. Some complex chapters (like ownership, modules, and advanced features) have multiple lessons to ensure thorough understanding.