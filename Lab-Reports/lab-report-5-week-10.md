*Lab report entailing difference between own code and code given by professor*<br>

**How different testers are found**
1. Opened the **test-files** folder
2. Manually and randomly looked through the tests and checking what each test tested.
3. Found  two tests:<br>
      * 513.md<br>![513.md](../Photos/LR5/513-raw.png) 
      * 324.md<br>![324.md](../Photos/LR5/342-raw.png)
      <br>
4. Copied the two tests into own repository, and ran to get results

**Test 513.md**<br>
* *Own Code Test results*<br>![Own513](../Photos/LR5/Own-Code-513.png)
* *Class Code Test results*<br>![MD513](../Photos/LR5/MD-513.png)
* *Expected output based on preview*<br>![Expected513](../Photos/LR5/513-Expected.png)

* Own output is incorrect based on the preview as the expected output should be `[/uri]`

* *To Fix*<br>
For my own code, the bug is from the fact that my own code does not have any conditions in regards to ticks. The expected output is located in between the two ticks of the code, which would mean that a condition has to be set that a link between two ticks would be prioritised over other conditions.
Code is shown below:<br>![Own](../Photos/LR5/Own.png)

**Test 324.md**<br>
* *Own Code Test results*<br>![Own342](../Photos/LR5/Own-Code-342.png)
* *Class Code Test results*<br>![MD342](../Photos/LR5/MD-342.png)
* *Expected output based on preview*<br>![Expected342](../Photos/LR5/342-Expected.png)

* Neither outputs are correct based on the preview as the expected output should be `[]`

* *To Fix*<br>
For my own code, the bug is from the fact that my own code does not have any conditions in regards to ticks. The expected output is located in between the two ticks of the code, which would mean that a condition has to be set that a link between two ticks would be prioritised over other conditions.
Code is shown below:<br>![Own](../Photos/LR5/Own.png)
