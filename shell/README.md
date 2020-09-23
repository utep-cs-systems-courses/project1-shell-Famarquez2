The following Python file is for the unix shell commands.
The result of this is to create a shell similar to terminal. The bash commands shall include:

       $                       - To print string
       
       $ ls | sort -r)         - For piping and sorting result
       
       $ $ find/etc -print &   - For running background task(Having a task run on the background
       
       $ ls > /tmp/files.txt)  - redirection of input and output
       
       $PATH                   - Finding the directory, folder or file path
       
       cd       - change directory
       exit     - end unix shell
       cat      - concatenate
       date 
       time

Running the program:
  1. Open terminal/shell in either a virtual machine or IDE
  2. Change directory to shell
  3. In the bash prompt, input "python3 shell.py"
  4. To run testShell.sh, run program while running shell.py
     - The following command is for both virtual machine and IDE are:
        1. "sh testShell.sh $" 
  5. To exit unix shell, simply type exit to return to bash prompt🥴

The following program was taken from last semester (Spring 2020) when I attempted to take
Theory of Operating Systems with Dr. Roach. I have for the most part converted my code from
C to python, however I've run into an issue with piping.
