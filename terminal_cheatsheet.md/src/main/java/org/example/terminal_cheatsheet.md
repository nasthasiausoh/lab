# Terminal cheatsheet

## Helpful git commands for desktop:
* `mdkir `- create new folder
* `touch` - create new file 
  * (remember to add the extension such as .txt, .pdf etc)
* `cd` - change directory
  *  (typing cd.. will take you back by one parent directory)
* `ls` - lists folders and files
  * variations of `ls` are `ls -l`, `ls -a`, and `ls -la` (shows a more detailed breakdown)
* `pwd` - tells you the pathway being used
* `open` - opens folder/file
  * `open .` the `.` means current directory. Therefore running `open .` will open up the entire folder, and you will be able to see the files within it
* `mv` - used to move or rename files.
* `cp` - used to copy
* `rm` - used to remove
    >Note: Be careful when using `rm` command because once you remove this, it is permanently deleted. You will NOT be able to retrieve this. Furthermore, NEVER type `rm -rf ~` into the terminal. This will delete all the files in the home directory and essentially break your computer!

  * `rm -r insertdirectorynamehere` - used to delete a directory
    > Note: We have to include the `-r` otherwise git will respond with `rm: insertdirectorynamehere: is a directory`.The -r means recursively. Therefore, running this code will delete the files from your folder.



### How to create folders within folders:
``` 
Example: To create the bnta_work folder which contains week 01 and days 1 - 5:

Using the following git code:

Documents cd 
➜  ~ mkdir bnta_work
➜  ~ mkdir bnta_work/week_01
➜  ~ mkdir bnta_work/week_01/day_1
➜  ~ mkdir bnta_work/week_01/day_2
➜  ~ mkdir bnta_work/week_01/day_3
➜  ~ mkdir bnta_work/week_01/day_4
➜  ~ mkdir bnta_work/week_01/day_5 

```
### Useful tips for labelling folders/files:
- Do not put spaces in between words.
- Instead use:
  - snake_casing
  - camelCasing
  - PascalCasing
  - or kebab-casing.

  
## Git/Github Lessons:

Git is primarily a Command Line (Terminal) tool. Working on the terminal/command line tool is faster and better. You can use 'gooeys' to make Git easier to use, but it is best to avoid these.

- Git = what is happening on the machine (locally). 
- GitHub = remote (i.e. like a cloud). 

> So, we use Git to make changes within the terminal and then you can `commit` and `push` that code onto GitHub. Then other people can view and use your code (if your repo is public).

SSH keys are unique to each user. Having one essentially tells Git/ GitHub that the laptop/computer being used is a trusted device. As a result, you will not need to verify each time you use it. 
> Note: If you use another device, you will need to generate a new SSH key and authorise this through Git. These sets can be found in the c9_coursenotes.

### How to Create a New GitHub Repository:
1. Go to GitHub
2. Go to new repository
2. Name the repo (usually the same name as the work)
3. Make it public - not private
4. Then make sure that you press SSH
5. Copy the 2nd section’s code (the bit beneath “ …or push an existing repository from the command line”)
6. Then paste this into the terminal.


### Git steps:
- `git init` -  Initialising the repo (this defines our repository).  
- `git add` – Stages the file to let Git know you want to record the modifications/changes made to the file. 
- `git commit` – Commits the staged modifications/changes in the history.
  - Essentially saving what you have done and then the file will be considered as unmodified. 
  ```
   Note: When using `git commit` you must add a message to it. For example:
       git commit -m"adding facts about penguins" 
      (i.e. a comment on the code).
  ```
- `git push `– Sends your newly modified/changed code to Github and safely stores it for your own and others’ use.

### Useful tips while doing this:
- Use `git status`. This will tell us what files we have on the stage.
- Use `git log` to check if your `commit` has worked. To close the window pop out, press the `Q` key.
- Use `git add .` to add everything that is here into the folder. This will update Git that modifications have been made.
  - Then you would have to do `git status` to update the changes to be committed. Then do `git commit` (with your message) to "clear it off the stage". Then use `git log` to double-check your commits have been executed. Then do `git push` to 'upload' this to your Github repository.




## Markdown formatting tricks:
- Using `*` or `-` will bullet point text.
- Using `>` will format text in a grey box with a blue strip. Shown below:
  > Lab work 1 example
- Using `backticks (same key by ~)` puts specified text in a grey box. This is good for emphasising particular text.
  - Using `triple backticks` will give us a page wide block. For example:
``` 
Side note: 
If placing code within the block given by the triple backticks, you can put
the name of the coding language used besides the top 3 backticks.
This is useful as it will visualise and highlight the code in a way that is
similar to the coding editor.
```

## Keyboard tips:
If you are stuck within a window and you do not know how to exit, try `Control C`, `Control D` or `Q`. One of these might work.

You can use `command` + `Tab` to switch between tabs.
You can also use `F3` OR `swipe three fingers upwards` to select tabs within your desktops. This is very helpful when using two screens.




