<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->
<!-- markdownlint-disable MD012 -->
<!-- markdownlint-disable MD036 -->
<div id="top-of-doc"></div>

## Readme File | bash-script-medium | October 5 2024 |

Discover the power of bash scripting for HTML/CSS/JAVASCRIPT in this Medium article. Unleash the potential to automate and simplify your web development tasks.

[My Github](https://github.com/popados) | [Jump to End](#end-of-doc)

---

### Specifications

- **Writing Medium Articles for Devslopes Web Academy**

  > Each module, students are encouraged to pen a Medium article about a topic or experience they've engaged with during their studies. The primary emphasis should be on the coding aspects.

  - **Objectives**

    - Writing and publishing articles on Medium serves multiple purposes:

    - Enhancing your online visibility for potential employers or recruiters.
    - Establishing your online presence as a developer.
    - Reinforcing your understanding of the current module's content.

  - **Potential Article Topics**

    1. Challenges faced or solutions found during the module's final assignment

       - Narrate the context that led to the problem.
       - Detail your resolution approach with code snippets.
       - Provide references to the documentation that assisted you.

    2. A particular concept prevalent in the software development domain (Tutorial Format)

       - Introduce the concept and elaborate on its significance in the development community and potential applications.
       - Illustrate the concept using code snippets.
       - Identify scenarios or applications where this concept is pivotal.
       - Conclude by listing resources or documentation that delve deeper into the concept.
       - Common Concerns
       - Redundancy: Remember that the tech world often involves revisiting and iterating on established ideas. A significant chunk of articles can seem repetitive. Focus on delivering your unique perspective.
       - Accuracy: While it's essential to be accurate, it's okay if you aren't exhaustive in your explanations. Ensure your statements align with established documentation, and always cite your sources.
       - Embedding Code on Medium
       - To seamlessly integrate a code snippet into your article:

  - **Article Submission Guidelines**

    - Comprise between 3-5 paragraphs.
    - Include at least 2 code snippets.
    - Stay relevant to the current module's themes.
    - Maintain a logical article structure (e.g., Introduction, Demonstration, Solution, Conclusion).
    - Ensure your article has been "Published" on Medium.com.
    - Submit your work as a .txt or .rtf file containing the article's URL on medium.com using the provided submission form.

---

### 001 | 10/5/2024 - Friday/Saturday

Discover the power of bash scripting for HTML/CSS/JAVASCRIPT in this Medium article. Unleash the potential to automate and simplify your web development tasks.

- **Examples**

  - Basic scripts
  - Cat command
    - Editing a file
  - Creating your own commands
    - Variables

Starting with bash scripting is fairly simple the required tools are:

- GitBash [x]
- text editor [x]
- some coding knowledge [x]

Using GitBash the user can open the shell directly to the location where you want to run your commands.

Show the script doing these functions:

- echo [x]
- date - place the date(day-month-year) up to time
- cat - catenate a file. Adds text to a file with in and out commands.
- EOF - END OF FILE. DESIGNATES WHERE THE FILE ENDS.
- Variables
- basic commands i.e: touch, vi, cat, rm(never use), mv, cp, and cd.

The function will be created using a set of commands piped or run right after eachother. Stringing together commands `touch; mkdir; cat; cd; echo;` respectively are used to create new files, directories, edit files, change directories, and print statements.

A basic knowledge of coding is helpful. The idea is to create functions that help the user create templates in seconds rather than copying and pasting. In this specific case, we are talking about writing a script for boilerplate and default HTML/CSS/JAVASCRIPT. Much of the work is done in a second text editor; it could be VSCode or something else like Notepad++. This tutorial will use Notepad++. Using GitBash and a text editor like Notepad++ or VSCode will enable you to write a script that will automate your HTML/CSS templates.

```bash
function greet() {
   echo 'Hello' $1'!'
   world='hello, world'
   echo $world $1
}
```

To start this process you should create a `.bash_profile.sh` file. This will enable you to write your own functions that will serve as commands or aliases. Each new command will be started with `function name(){#code}` which allows you to chain commands together such as creating a command that outputs the name entered. `function name(){echo $1}` to understand this you must learn how the `$1` is used as an input variable. To use `$1` the command is entered like normal such as `ls` however because there is a variable argument you must enter a parameter. Entering the command shown above is `greet Nik` would output `hello Nik! hello, world Nik`.

While writing the script you want to structure it in the correct `source` folder. Using GitBash you can reach this directory with `cd ~`. Create a file called `.bash_profile.sh` using the `touch` command.

```bash

function make_html () {
   touch $1.html
   echo "create $1.html"

   cat <<-- _EOF_ > $1.html
      <!DOCTYPE html>
      <html>
         <head>
            <meta name="google" content="notranslate">
            <meta charset="UTF-8">
            <title> $1 </title>
            <link href="./css/default.css" rel="stylesheet" />
            <link href="./css/styles.css" rel="stylesheet" />
            <link href="./css/responsive.css" rel="stylesheet" />
            <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
         </head>
         <body>
         </body>
      </html>
   _EOF_
}


```

`_EOF_` in this script means "End of File" which is used for the cat command to know where to stop writing text.

This code block shows how to make a boilerplate bash command that allows the user to execute command `make_html $1` to create a html file called `1$.html`. Where the `$1` is your passed argument.

---

## End of Documents

---

[Jump to Top](#top-of-doc)

<div id="end-of-doc"></div>

<details>
   <summary>
      Notes :
   </summary>
</details>
