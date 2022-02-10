*Lab report detailing how to copy whole directories from the home desktop to the remote desktop*</br>

**Using `scp -r`**</br>
Syntax for this command is </br>
`scp -r (source) (destination):~/(name)` - Brackets is only for clarity</br> 
* `(source)` - location of repository in local desktop to be copied
* `(destination)` - remote desktop to be accessed and for source repository to be copied to
* `(name)`  - name given for copied repository in remote desktop</br>

**Example**</br>
Example shown are when a repository containing tests for a file called MarkdownParse.java is copied from a local desktop to a remote desktop.</br>

*Example in Images*</br>

These Images will show what you will see if the copy succeeds
![Syntax-1](..\Photos\LR3\Syntax.png)
![Syntax-2](..\Photos\LR3\Syntax2.png)

*Proof that repository works in the remote desktop after copying*<br>

These images show that the repository still works after the repository is copied successfully.
![Proof-1](..\Photos\LR3\Proof1.png)
![Proof-2](..\Photos\LR3\Proof2.png)

*More efficient code for copying and testing*</br>\
By using `;` with `scp` and `ssh`, it is possible to copy and run the repository with its tests more efficiently<br/>
![Combo-1](..\Photos\LR3\Combo1.png)
![Combo-2](..\Photos\LR3\Combo2.png)
![Combo-3](..\Photos\LR3\Combo3.png)
![Combo-4](..\Photos\LR3\Combo4.png)


