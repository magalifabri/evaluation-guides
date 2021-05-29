# Evaluation Guide: Libft

May 2021

## Introduction
- Remain polite, courteous, respectful and constructive
throughout the evaluation process. The well-being of the community
depends on it.

- Identify with the person (or the group) evaluated the eventual
dysfunctions of the work. Take the time to discuss
and debate the problems you have identified.

- You must consider that there might be some difference in how your
peers might have understood the project's instructions and the
scope of its functionalities. Always keep an open mind and grade
him/her as honestly as possible. The pedagogy is valid only and
only if peer-evaluation is conducted seriously.

## Guidelines
- Only grade the work that is in the student or group's
GiT repository.

- Double-check that the GiT repository belongs to the student
or the group. Ensure that the work is for the relevant project
and also check that "git clone" is used in an empty folder.

- Check carefully that no malicious aliases was used to fool you
and make you evaluate something other than the content of the
official repository.

- To avoid any surprises, carefully check that both the evaluating
and the evaluated students have reviewed the possible scripts used
to facilitate the grading.

- Do not blindly trust any script the tester could be wrong !

- Check the makefile no wildcard, no relink or the final grade is 0.

- Use make, then make --trace to be sure.

- If the evaluating student has not completed that particular
project yet, it is mandatory for this student to read the
entire subject prior to starting the defence.

- Use the flags available on this scale to signal an empty repository,
a norm error, cheating etc. In these cases,
the grading is over and the final grade is 0 (or -42 in case of
cheating). However, with the exception of cheating, you are
encouraged to continue to discuss your work (even if you have not
finished it) in order to identify any issues that may have caused
this failure and avoid repeating the same mistake in the future.

- You should never have to edit any file except the configuration file if it exists.
If you want to edit a file, take the time to explicit the reasons with the
evaluated student and make sure both of you are okay with this.

- You must also verify the absence of memory leaks. Any memory allocated on the heap must
be properly freed before the end of execution.
You are allowed to use any of the different tools available on the computer, such as
leaks, valgrind, or e_fence. In case of memory leaks, tick the appropriate flag.

---

## Mandatory part
You must test each of the function of the libft, using your own tests.

### Libc Functions #1
Test every function and make sure they're working properly:
- ft_memcpy
- ft_memccpy
- ft_memset
- ft_bzero
- ft_memmove
- ft_memcmp
- ft_memchr
Is it working?

### Libc Functions #2
Test every function and make sure they're working properly:
- ft_strlen
- ft_isalpha
- ft_isdigit
- ft_isalnum
- ft_isascii
- ft_isprint
Is it working?

### LibC functions #3
Test every function and make sure they're working properly:
- ft_toupper
- ft_tolower
- ft_strchr
- ft_strrchr
Is it working?

### LibC functions #4
Test every function and make sure they're working properly:
- ft_strlcat
- ft_strlcpy
- ft_atoi
- ft_strnstr
- ft_strncmp
- ft_calloc
- ft_strdup
Is it working?

### Added functions #1
Test every function and make sure they're working properly:
- ft_substr
- ft_strjoin
- ft_putchar_fd
- ft_putstr_fd
- ft_putendl_fd
- ft_putnbr_fd
Is it working?

### Added functions #2
Test every function and make sure they're working properly:
- ft_strmapi
- ft_strtrim
- ft_split
- ft_itoa
Is it working?

---

## Bonus
We will look at your bonuses if and only if your mandatory part is excellent. This means that you must complete the mandatory part, beginning to end, and your error management must be flawless, even in cases of twisted or bad usage. So if you didn't score all the points on the mandatory part during this defence bonuses will be totally ignored.

### ft_lstnew
Is it working?

### ft_lstdelone
Is it working?

### ft_lstclear
Is it working?

### ft_lstadd_front
Is it working?

### ft_lstadd_back
Is it working?

### ft_lstsize
Is it working?

### ft_lstlast
Is it working?

### ft_lstiter
Is it working?

### ft_lstmap
Is it working?
