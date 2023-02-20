# Terminal Text

![logo](https://github.com/bazzzaka/terminal_text/blob/main/img.png)

**Terminal Text** repositories,   
which allows you to output text with different stylized colors in the terminal.   
You need to pass any information to the class `TerminalText`, for example:  
```python
from terminal_text import TerminalText


some_data_to_print = 'DATA. It`s can be anything data.'
TerminalText(some_data_to_print).info()
```  
Console output:
![logo](https://github.com/bazzzaka/terminal_text/blob/main/example.png)

It contains methods for output text with certain colors and styles, such as   
|Function name |Description          |
|--------------|---------------------|
|`header()`    | Print purple text   |
|`tips()`      | Print blue text     |
|`recommend()` | Print cyan text     |
|`info()`      | Print green text    |
|`warning()`   | Print yellow text   |
|`fail()`      | Print red text      |
|`text_error()`| Print bold text     |
|`underline()` | Print underline text|
  

The class also includes the `report_to_slack()` and `report_to_discord()`   
methods that allow you to send error reports to Slack and Discord.   
For Slack and Discord you need token, you can add this in `.env` file.  

### Version 0.2
The program will be supported and developed.   
Currently, the development is being carried out for report in telegram.  
The concept on analysis of errors by artificial intelligence is being developed.
  

