# Pablo Corbalán | Python Jr Dev.

-----------------------

**Python3** developer that loves learning new things. As I love Python most of my projects are built using it.

```python
from datetime import date

class ReadMe:
    def __init__(self, username = "PabloCorbCon", year = date.today().year()): #Get the current year

        self.__username = username
        self.__name = 'Pablo Corbalán'
        self.__country = 'Spain'
        self.__year = year
        self.__tools = []

        #Add languages
        self.__add_tools(['Python', 'HTML', 'CSS', 'JS', 'C#'])

    def __add_tools(tools_to_add):

    	self.__tools.extend(tools_to_add)

PabloCorbCon = ReadMe()
```

You can check my Twitter (where i spend all the time here): https://twitter.com/pablocorbcon
