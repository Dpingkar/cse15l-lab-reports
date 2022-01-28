*Lab Report detailing test and changes to MarkdownParse using vscode and github*<br/>

**First Changes**<br/>
* [Link to tester](https://github.com/Dpingkar/markdown-parse/blob/bc2864af1b6ab8584b65b4349cec5ee761fc51c6/test2.md)
* *Change Log*![Change Log](..\Photos\LR2\ChangeLog1.png)
* *Symptom*![Symptom](..\Photos\LR2\Symptom1.png)
* Without the changes, the code would loop endlessly as due to the current Index not changing past 0, the exit criteria for the for loop will never be achieved. This is because the tester is missing either `[,],(`or`)`.<br/>
<br/>

**Second Changes**<br/>
* []