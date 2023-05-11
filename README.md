0x00. AirBnB clone - The console
================================

Group projectPythonOOP

-   By: Guillaume

### Concepts

*For this project, we expect you to look at these concepts:*

-   [Python packages](https://intranet.alxswe.com/concepts/66)
-   [AirBnB clone](https://intranet.alxswe.com/concepts/74)

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230511%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230511T101749Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=73e20150b6cc2e4c5f13ecc12ceb9eb643b08a4627ad773d3d57b98428df6640)

Background Context
------------------

### Welcome to the AirBnB clone project!

Before starting, please read the **AirBnB** concept page.

#### First step: Write a command interpreter to manage your AirBnB objects.

This is the first step towards building your first full web application: the **AirBnB clone**. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration...

Each task is linked and will help you to:

-   put in place a parent class (called `BaseModel`) to take care of the initialization, serialization and deserialization of your future instances
-   create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
-   create all classes used for AirBnB (`User`, `State`, `City`, `Place`...) that inherit from `BaseModel`
-   create the first abstracted storage engine of the project: File storage.
-   create all unittests to validate all our classes and storage engine

### What's a command interpreter?

Do you remember the Shell? It's exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

-   Create a new object (ex: a new User or a new Place)
-   Retrieve an object from a file, a database etc...
-   Do operations on objects (count, compute stats, etc...)
-   Update attributes of an object
-   Destroy an object

Resources
---------

**Read or watch**:

-   [cmd module](https://intranet.alxswe.com/rltoken/8ecCwE6veBmm3Nppw4hz5A "cmd module")
-   [cmd module in depth](https://intranet.alxswe.com/rltoken/uEy4RftSdKypoig9NFTvCg "cmd module in depth")
-   **packages** concept page
-   [uuid module](https://intranet.alxswe.com/rltoken/KfL9TqwdI69W6ttG6gTPPQ "uuid module")
-   [datetime](https://intranet.alxswe.com/rltoken/1d8I3jSKgnYAtA1IZfEDpA "datetime")
-   [unittest module](https://intranet.alxswe.com/rltoken/IlFiMB8UmqBG2CxA0AD3jA "unittest module")
-   [args/kwargs](https://intranet.alxswe.com/rltoken/C_a0EKbtvKdMcwIAuSIZng "args/kwargs")
-   [Python test cheatsheet](https://intranet.alxswe.com/rltoken/tgNVrKKzlWgS4dfl3mQklw "Python test cheatsheet")
-   [cmd module wiki page](https://intranet.alxswe.com/rltoken/EvcaH9uTLlauxuw03WnkOQ "cmd module wiki page")
-   [python unittest](https://intranet.alxswe.com/rltoken/begh14KQA-3ov29KvD_HvA "python unittest")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/uV5eZkRZ_XEqYbgPd-0CWw "explain to anyone"), **without the help of Google**:

### General

-   How to create a Python package
-   How to create a command interpreter in Python using the `cmd` module
-   What is Unit testing and how to implement it in a large project
-   How to serialize and deserialize a Class
-   How to write and read a JSON file
-   How to manage `datetime`
-   What is an `UUID`
-   What is `*args` and how to use it
-   What is `**kwargs` and how to use it
-   How to handle named arguments in a function
