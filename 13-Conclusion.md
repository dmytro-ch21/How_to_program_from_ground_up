# Conclusion

## Paradigms are Just Different Styles to Structure and Organize Software
  - The different paradigms are not better or worse than each other, they are just different styles to structure the
    state and behavior of software to provide a solution.
  - Different paradigms can be combined together to create a program that is easier to understand and maintain.
  - Paradigms are not frozen and are constantly evolving as new ideas are added to the software development
    methods to make creating software easier and more effective.
  - Each paradigm has their own trade-offs and costs that must be considered when
    choosing which paradigm is appropriate for a particular problem. Sometimes, the best solution is the simplest one.
  - Paradigms are not dogma, and should not be followed blindly, but should be used as a guide to help
    structure and organization the program to be easiest to understand and change.
  - Paradigms are not independent, and are often used together to create a program that is easier to
    understand and maintain.
 
## Programming Will Always Be a Human Activity - AI Cannot Solve Everything and Requires Human Guidance
  - Solution methods will become a bit more abstract in the future using tools like GitHub copilot, but the
    programmer will still need to know all these details to get the machine to do EXACTLY what they want it to do.
  - We are always going to need people who have various tastes and understandings about humans and the world to
    create software that is useful and effective FOR THOSE PARTICULAR HUMANS.

## You can only learn programming by actually programming
  > Stop Studying Programming
  > - https://www.youtube.com/watch?v=QMbx0dTWJIQ  

## History Graph of Selected Programming languages Referenced In This Document
  > Keynote session: The History of Programming - Mark Rendle [DevCon 2016]
  > - https://youtu.be/Tr9E_vzKRVo
 
  ```mermaid
    graph TB
        MachineLanguage{{Machine Language}} -->|human readable mnemonics| AssemblyLanguage
        AssemblyLanguage{{Assembly Language}} -.->|Procedural & Interpreted|Basic
        AssemblyLanguage{{Assembly Language}} -->|Procedural|COBOL
        AssemblyLanguage{{Assembly Language}} -->|Procedural|Fortran
        AssemblyLanguage{{Assembly Language}} -->|Structured|Algol68
        AssemblyLanguage{{Assembly Language}} -->|Structured|C
        AssemblyLanguage{{Assembly Language}} -->|Structured + low-level|BCPL
        AssemblyLanguage{{Assembly Language}} -->|List-oriented|Lisp
        
        COBOL{{"COBOL"}} -.->|"Easy to 
                              Learn Syntax
                              ⚡️️"|Basic
        Basic{{"BASIC"}} ---> VisualBasic
        Fortran{{"Fortran"}} -.->|"Evaluate 
                                  Formulas
                                  ✨"|Basic
        Algol68{{Algol60, Algol68}} -.->|"for structures, 
                                scopes & syntax
                                ⚡️️
                                "|C
        BCPL{{"BCPL"}} -->|"for types, structures 
                            low-level compilation
                            ✨"|C
        BCPL --> Algol68
        BCPL --> Simula67
        Simula67{{"Simula67"}} -.->|"for pointers & 
                                    other concepts
                                    ✨"|C
        Simula67 -.->|for OOP ideas|Smalltalk
        C{{"C"}} -->Cplusplus
        C -.->Smalltalk
        Simula67 -.->|for COP ideas|Cplusplus
        Cplusplus{{"C++"}} -->|for COP/pseudo-OOP ideas|Java
        Smalltalk -..->|"absconded OOP term 🫤 
                        & some ideas
                        🤔🤨🧐"|Cplusplus
        Java{{Java}} -->Kotlin
        Java -->CSharp
        CSharp{{"C#"}}
        Fortran -.->Algol68
        Smalltalk{{"Smalltalk
                  Originator of term OOP
                  🙂"}} -.->|for OOP ideas|Javascript
        Smalltalk -.->|for OOP ideas|Ruby
        Smalltalk -.->|for OOP ideas|HyperTalk
        Basic -.-> |"for Interpreted & 
                    interactive
                    ⚡️"|Smalltalk
        AssemblyLanguage-.->|"for self-modifying 
                              code @ runtime
                              ✨"|Smalltalk
        
        Lisp{{"Lisp"}} -.->|internal syntax|Javascript
        Java--->|for syntax|Javascript
        Kotlin{{Kotlin}}
        Ruby{{Ruby}}
        HyperTalk{{HyperTalk}}
        Javascript{{Javascript}}
        VisualBasic{{"Visual Basic"}}
    
    Note("Conceptual Inheritance Graph of Selected Languages.
          
          Not exhaustive, not to time scale.
          ⨭⨂⨀⨁⨮")
    A("A") -.-> |means A influenced B.| B("B")
    X("X") --> |means Y descended from X.| Y("Y")
    
  ```

- [Back to Index](README.md)