This is an H1
================

hello
'ctrl'+'spacebar': 자동완성
graph, flowchart, class???? ddx?

```mermaid
graph TD;
    A얌얌얌얌-->B;
    A얌얌얌얌-->C;
    B-->D;
    C-->D;


```

```mermaid
flowchart LR

A{Hddard} --> |Text| B(Round)
B-->C{Decision}

```
flowchart: 가로인가봐!!
[] : 네모

() : 각이 둥근 네모

{} : 마름모

| | : 화살표중간에 텍스트




```mermaid
classDiagram
Class01 <|--AveryLongClass : Cool
<<Interface>> Class01
Class09 --> C2 : Where am I?
Class09 --*C3
Class09 --|>Class07
Class07 : Objects[] elementData
Class07 : equals ()
Class01 : size()
Class01 : int chimp
Class 01 : int gorilla
class Class10 {
    <<service>>
    int id
    size()
}
```

```mermaid
classDiagram
    Animal <--Duck
    Animal <--Fish
    Animal <--Zebra
    Animal : +int age
    Animal : +String gender
    Animal : +isMammal()
    Animal : +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra
    Zebra: +bool is_wild
    Zebra: +run()
    
```


```mermaid
classDiagram
    class BankAccount
    BankAccount:+String owner
    BankAccount: +Bigdecimal balance
    BankAccount: +deposit(amount)
    BankAccount: +withdrawal(amount)
```

----------------------------------
```mermaid
flowchart LR
    st-->op
    
```
--------------------------
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op

```mermaid
flowchart LR

A{Hddard} --> |Text| B(Round)
B-->C{Decision}

```




