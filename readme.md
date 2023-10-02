# thrift

----------



> thrift 的强大之处在于它能通过IDL(Interface Definition Language)来定义通用的服务接口，然后将服务接口编译成不同语言的代码，实现跨语言的功能。


----------


### thrift 实现游戏匹配系统



----------

项目结构图 `tree thrift_lesson`
```
thrift_lesson/
|-- game
|   `-- src
|       |-- client.py
|       `-- match_client
|           |-- __init__.py
|           |-- __pycache__
|           |   `-- __init__.cpython-38.pyc
|           `-- match
|               |-- Match.py
|               |-- __init__.py
|               |-- __pycache__
|               |   |-- Match.cpython-38.pyc
|               |   |-- __init__.cpython-38.pyc
|               |   `-- ttypes.cpython-38.pyc
|               |-- constants.py
|               `-- ttypes.py
|-- match_system
|   `-- src
|       |-- main.cpp
|       |-- match_server
|       |   |-- Match.cpp
|       |   |-- Match.h
|       |   |-- match_types.cpp
|       |   `-- match_types.h
|       `-- save_client
|           |-- Save.cpp
|           |-- Save.h
|           `-- save_types.h
|-- readme.md
`-- thrift
    `-- match.thrift
```



----------


  

```
该项目主要分为三个部分：game、match_system、thrift,其中需要我们实现的只有game中的client端，match_system中的client端和server端

```

`他们之间的逻辑关系如下图所示：`
----------

![thrift图示.png](https://cdn.acwing.com/media/article/image/2023/10/02/251762_89ec368f61-thrift图示.png) 

----------


