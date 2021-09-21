# Libft - My first C library

<h1 name ="content" align = "center">📋 Table of contents</h1>
<p align = "center">
  <a href = "#intro">Intro</a> -
  <a href = "#goal">Goal</a> -
  <a href = "#tec">Tecnology</a> -
  <a href = "#function">Functions</a> -
  <a href = "#how">How to use</a> -
  <a href = "#test">Tests</a> -
  <a href = "#update">Update</a> -
  <a href = "#author">Author</a>
</p>

<a name="intro"/> <h2> Intro </h2> </a>
- This was my first project at école 42 SP after their basecamp (3 weeks of intense code learning. Where I learned C and shell commands for the first time).
- The hardest part of the project was to get all the information from the basecamp and put together to create the library. I had to make sure that my base was good, so I could move forward to bigger projects.
- I learned about Libraries, Header Files, Makefile.
- Also I challenge myself to do the bonus and learned about Structs and Linked List.
- Because this was my first project, I used test create by other students to test my functions. So I could focus on learning the basics first and create a strong base.
- The functions that use malloc don´t free the memmory so it is important to remember to use free after using any of them.
<p></p>
<a href = "#content">📋</a>

<a name="goal"/> <h2> 🎯 Goal </h2> </a>
- This first project is used to reinforce basic concepts learned during the basecamp of école 42:
  - Basic concepts like variables, function, pointers and memmory allocation.
  - It is also an introduction to concept of Libraries, Header files, Makefile, Structs and Linked Lists.
<p></p>
<a href = "#content">📋</a>

<a name="tec"/> <h2> 🛠️ Tecnology </h2> </a>
- Language: C
- VS code
- WSL ubuntu
- Norminette 42 (code norm used by école 42)
- Remote SSH access to iMac for tests.
<p></p>
<a href = "#content">📋</a>

<a name="function"/> <h2> 📚 Functions </h2> </a>

Memmory    | String     | Char       | Print         | Conversion | Linked List 
---        | ---        | ---        |---            |---         |---
ft_calloc  | ft_strlen  | ft_isalpha | ft_putchar_fd | ft_toupper | ft_lstnew
ft_memset  | ft_strlcy  | ft_isdigit | ft_putstr_fd  | ft_tolower | ft_lstadd_front
ft_bzero   | ft_strlcat | ft_isalnum | ft_putendl_fd | ft_atoi    | ft_lstsize
ft_memcpy  | ft_strchr  | ft_isascii | ft_putnbr_fd  | ft_itoa    | ft_lstlast
ft_memccpy | ft_strrchr | ft_isprint | &nbsp;        | &nbsp;     | ft_lstadd_back
ft_memmove | ft_strnstr | &nbsp;     | &nbsp;        | &nbsp;     | ft_lstdelone
ft_memchar | ft_strncmp | &nbsp;     | &nbsp;        | &nbsp;     | ft_lstclear
ft_memcmp  | ft_strdup  | &nbsp;     | &nbsp;        | &nbsp;     | ft_lstiter
&nbsp;     | ft_substr  | &nbsp;     | &nbsp;        | &nbsp;     | ft_lstmap
&nbsp;     | ft_strjoin | &nbsp;     | &nbsp;        | &nbsp;     | &nbsp;
&nbsp;     | ft_strtrim | &nbsp;     | &nbsp;        | &nbsp;     | &nbsp;
&nbsp;     | ft_split   | &nbsp;     | &nbsp;        | &nbsp;     | &nbsp;
&nbsp;     | ft_strmapi | &nbsp;     | &nbsp;        | &nbsp;     | &nbsp;

<p></p>
<a href = "#content">📋</a>

<a name="how"/> <h2> 📖 How to use </h2> </a>

- Clone the repository
```bash
git clone https://github.com/GitFlaviobc/Libft.git
```
Inside the Project folder:
- to create the library
```bash
make
```
or
```bash
make all
```
- to delete all obj (.o) files created
```bash
make clean
```
 - to delete all created files
```bash
make fclean
```
 - to delete all files and recreate the library
```bash
make re
```

<p></p>
<a href = "#content">📋</a>

<a name="test"/> <h2> 👨‍💻 Tests </h2> </a>
- Note: I didn't created any of the test, I just used them to check my project. All credit goes to their creators. <p></p>
  - [libftTester](https://github.com/cclaude42/PFT_2019) <p></p>
  - [libft-unit-test](https://github.com/alelievr/libft-unit-test) <p></p>
  - [Libftest](https://github.com/cacharle/ft_printf_test) <p></p>
  - [libft-war-machine](https://github.com/ska42/libft-war-machine)
- All tests were done on the browser connect with SSH to an iMac.
<p></p>

###### *42 changes the projects from time to time, and the test keep being updated to follow it. So this project may be outdated for the tests.

<p></p>
<a href = "#content">📋</a>

<a name="update"/> <h2> 🆙 Updates </h2> </a>
- The code I sent to evaluation will be kept the same. Any update will be on the update folder.⚠️🚧
<p></p>
<a href = "#content">📋</a>

<a name="author"/> <h2> 😀 Author </h2> </a>
Name: Flávio Bonini Campos
<p></p>

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/flaviobc88/)
<p></p>
<a href = "#content">📋</a>
<p></p>
