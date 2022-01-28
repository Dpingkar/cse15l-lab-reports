*Lab Report detailing test and changes to MarkdownParse using vscode and github*<br/>

**First Changes**<br/>
* Link to tester: [test2.md](https://github.com/Dpingkar/markdown-parse/blob/bc2864af1b6ab8584b65b4349cec5ee761fc51c6/test2.md)
* *Change Log*![Change Log](..\Photos\LR2\ChangeLog1.png)
* *Symptom*![Symptom](..\Photos\LR2\Symptom1.png)
* *Explanation* : <br/>Without the changes, the code would loop endlessly as due to the current Index not changing past 0, the exit criteria for the for loop will never be achieved. This is because the tester is missing either `[,],(`or`)`.<br/>
<br/>

**Second Changes**<br/>
* Link to tester: [test3.md](https://github.com/Dpingkar/markdown-parse/blob/main/test3.md)
* *Change Log*![ChangeLog](..\Photos\LR2\ChangeLog2.png)
* *Symptom*![Symptom](..\Photos\LR2\Symptom2.png)
* *Explanation* :<br/>
The output is supposed to be an empty array, as in **test3.md**, the `[ ]` and the `( )` are on different lines, which would not make it a valid link on the page. However, the output before changes still determines the link to valid and parses the link. With the changes, a condition is given that `]` and `(` are to only be one index apart, preventing this error to occur again.<br/>
<br/>

**Third Changes**
* Link to tester: [test4.md](https://github.com/Dpingkar/markdown-parse/blob/main/test4.md)
* *Change Log*
* *Symptom*
* *Explanation*: 