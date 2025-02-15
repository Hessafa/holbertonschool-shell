<h1 style="font-size: 3em; "> Shell, init files, variables and expansions</h1>
<p align="center"> <img src="https://media.giphy.com/media/AbDb2PniluFwY/giphy.gif" width="25%" /> </p>
🖥️ This project is part of my studies at Holberton School by Tuwaiq Academy <td><a href="https://tuwaiq.edu.sa/holberton">Holberton School by Tuwaiq Academy</a></td>

<h2>Description</h2>
<p> Shell, Process, and Expansion

This project covers shell scripting fundamentals, environment variables, expansions, and file manipulation in Unix/Linux.

## Key Concepts:

- **Shell Commands**: Understand expansions, command substitution, and the `$ ls -l *.txt` command.
- **Variables**: Learn about local and global variables, special shell variables like `HOME`, `PATH`, and `$?`.
- **Shell Initialization**: Study system and user initialization files (`/etc/profile`, `~/.bashrc`).
- **Aliases**: Create, manage, and disable aliases to streamline workflows.

## Requirements:

- Scripts must be 2 lines long.
- Use `#!/bin/bash` as the first line.
- Make scripts executable and avoid `&&`, `||`, `;`, `bc`, `sed`, or `awk`.
- Test scripts on **Ubuntu 20.04 LTS**.

By the end of this project, you'll be comfortable with shell scripting and managing your environment in Unix/Linux.
</p>


<h2 style="font-size: 2.5em; color: darkblue;">Tasks Files</h2>
<p>The following is a list of files that are part of this project:</p>

<table border="1" style="border-collapse: collapse; width: 100%;">
  <thead style="background-color: #FFB6C1; color: darkblue;">
    <tr>
      <th><strong>Filename</strong></th>
      <th><strong>Description</strong></th>
    </tr>
  </thead>
  <tbody style="background-color: #ADD8E6;">
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/0-alias">0-alias</a></td>
      <td>Create a script that creates an alias.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/1-hello_you">1-hello_you</a></td>
      <td>Create a script that prints hello user, where user is the current Linux user.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/2-path">2-path</a></td>
      <td>Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/3-paths">3-paths</a></td>
      <td>Creates a script that counts the number of directories in the PATH.</td>
    </tr>
     <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/4-global_variables">4-global_variables</a></td>
      <td>Creates a script that lists environment variables.</td>
    </tr>
   <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/5-local_variables">5. Local variables</a></td>
      <td>Creates a script that lists all local variables and environment variables, and functions.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/6-create_local_variable">6-create_local_variable</a></td>
      <td>Creates a script that creates a new local variable.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/7-create_global_variable">7. Global variable</a></td>
      <td>Creates a script that creates a new global variable.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/8-true_knowledge">8-true_knowledge</a></td>
      <td>Writes a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.</td>
    </tr>
     <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/9-divide_and_rule">9-divide_and_rule</a></td>
      <td>Writes a script that prints the result of POWER divided by DIVIDE, followed by a new line.</td>
    </tr>
      <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/10-love_exponent_breath">10-love_exponent_breath</a></td>
      <td>Writes a script that displays the result of BREATH to the power LOVE</td>
    </tr>
     <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/11-binary_to_decimal">11-binary_to_decimal</a></td>
      <td>Writes a script that converts a number from base 2 to base 10.</td>
    </tr>
     <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/12-combinations">12-combinations</a></td>
      <td>Creates a script that prints all possible combinations of two letters, except oo.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/13-print_float">13-print_float</a></td>
      <td>Writes a script that prints a number with two decimal places, followed by a new line.</td>
    </tr>
     <tr>
      <td><a href="https://github.com/Hessafa/holbertonschool-shell/blob/main/init_files_variables_and_expansions/14-decimal_to_hexadecimal">14-decimal_to_hexadecimal</a></td>
      <td>Writes a script that converts a number from base 10 to base 16.</td>
    </tr>
  </tbody>
</table>




<h2>Articale Post</h2>
<p style="text-align: center;">
  <a href="https://www.linkedin.com/pulse/what-happens-when-you-type-ls-c-hit-enter-hessah-alotaysh-un0be/" target="_blank">
    <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGUwbXV0c2lpdDN6NWxjZ2pxamx0NmlodDIwb3ZvYTBmYm5pNDV1NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/34V1UW9TIPolunWE40/giphy.gif" style="display: block; margin: 0 auto;" width="25%" height="25%" />
  </a>
