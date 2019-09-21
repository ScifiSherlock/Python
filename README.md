# Exercise 1: A taste of Python

Follow these instructions to complete the exercise. 

If you have trouble, please post on [the discussion forum on GitHub](https://github.com/orgs/uh-eng-3041-2019/teams/students)!

1. Once you've accepted the assignment on GitHub Classroom and you see your repository on GitHub, head over to [CSC Notebooks](https://notebooks.csc.fi) and login to the service.

2. Launch your instance and wait for JupyterLab to start.

3. Open Terminal.

4. Switch back to GitHub on your browser. Move to your assignment repository and clone the assignment using the green button on the top right-hand side of the page. Make sure you clone the repository via **HTTPS**. 
  
6. Return to Terminal on your instance and clone the assignment repository by entering the following command:

`git clone <ENTER ADDRESS OF YOUR REPOSITORY HERE>`

To exemplify, I would clone the first exercise using the following command:

`git clone https://github.com/uh-eng-3041-2019/exercise-1-thiippal.git`

The repository address has been copied on your clipboard: press <kbd>Shift</kbd>+<kbd>Insert</kbd> (or <kbd>Command</kbd>+<kbd>V</kbd> on Apple) to paste the address on Terminal.

After pressing enter, GitHub will prompt you for your username and password.

7. This will clone the assignment on your instance to a directory named `exercise-1-<YOUR GITHUB USERNAME>`.

8. Navigate to the new directory in JupyterLab and open the Jupyter Notebook named `exercise_1.ipynb`.

9. Follow the instructions given in the Jupyter Notebook. Remember to execute the cells by choosing the **Run** menu or choosing **Run selected cells** (or press <kbd>Shift</kbd>+<kbd>Enter</kbd>).

10. When you have completed the exercise, save the Notebook by entering the **File** menu and choosing **Save** (or press <kbd>Command</kbd>+<kbd>S</kbd>).

11. When you are ready to submit your work, switch back to Terminal on your instance. 

12. Make sure you are in the directory containing the notebook you just saved. If you're in doubt, use the command `pwd` to get your current location. Use `cd <ENTER THE NAME OF THE DIRECTORY HERE>` to change to the directory containing the repository if necessary (see step 7).

14. Add the Jupyter Notebook to the list of files to be committed back to your GitHub repository by entering the following command: `git add exercise_1.ipynb`

15. Then stage the files for commit by entering the following command: `git commit -m "add exercise"`

As you can see, the flag `-m` is used to define a message to accompany the commit.

16. Finally, push the changes to GitHub using the following command: `git push`

GitHub will again prompt you for your username and password for authentication.

You should then see a message such as the one below:

```
Counting objects: 3, done.
Delta compression using up to 16 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 554 bytes | 184.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uh-eng-3041-2019/exercise-1-thiippal.git
  9d0bffd..dfe6729  master -> master
```

Congratulations! You've just successfully returned the assignment to GitHub!
