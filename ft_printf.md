# Evaluation Guide: ft_printf

May 2021

## Introduction

Please respect the following rules:

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

- If the evaluating student has not completed that particular
project yet, it is mandatory for this student to read the
entire subject prior to starting the defence.

- Use the flags available on this scale to signal an empty repository,
non-functioning program, a norm error, cheating etc. In these cases,
the grading is over and the final grade is 0 (or -42 in case of
cheating). However, with the exception of cheating, you are
encouraged to continue to discuss your work (even if you have not
finished it) in order to identify any issues that may have caused
this failure and avoid repeating the same mistake in the future.

- Remember that for the duration of the defence, no segfault,
no other unexpected, premature, uncontrolled or unexpected
termination of the program, else the final grade is 0. Use the
appropriate flag. This behaviour will only be accepted if printf
also crashes under the same circumstances.
You should never have to edit any file except the configuration file if it exists.
If you want to edit a file, take the time to explicit the reasons with the 
evaluated student and make sure both of you are okay with this.

- You must also verify the absence of memory leaks. Any memory allocated on the heap must
be properly freed before the end of execution.
You are allowed to use any of the different tools available on the computer, such as
leaks, valgrind, or e_fence. In case of memory leaks, tick the appropriate flag.

---

## Mandatory Part

### Simple Conversion Management
- Simply check each conversion without any flags 'cspdiuxX%'
- Try special cases like 0 or smallest int or empty string or null pointer
- Try with multiple arguments/conversions
- Try the various conversions in the middle of a sentence (with other characters before and/or after)

### Simple Flags Management
- Use the 's' conversion for all the following test
- Check the 'minimum field width' with values bigger, equal and smaller than the string
- Check the 'minimum field width' with values bigger, equal and smaller than the string with -
- Check the 'minimum field width' with values bigger, equal and smaller than the string with 0
- Check the '.' with multiple precisions

### Advanced Flags Management
- Use the 's' conversion for all the following test
- Check '*' as minimum field width (try values like negative one, zero etc.)
- Check '*' as precision (try values like negative one, zero etc.)
- Check '*' as both with/without one other flag (try values like negative one, zero etc.)

### Get Crazy
- Try any combination of flags and conversions
- Check what happens with duplicate flags

---

## Bonus
We will look at your bonuses if and only if your mandatory part is excellent. This means that you must complete the mandatory part, beginning to end, and your error management must be flawless, even in cases of twisted or bad usage. So if you didn't score all the points on the mandatory part during this defence bonuses will be totally ignored.

### nfge
- Check if conversions 'n' 'f' 'g' 'e' are working fine (beware of 'n') with all the flag combinations
- For each working conversion give 1 point
- If all conversions are working give 1 bonus point

### l ll h hh
- Check all the conversions with 'l' 'll' 'h' 'hh' with all the other flag combinations
- For each working flag give 1 point
- If all flags are working give 1 bonus point

### # + space
- Check all the conversions with the flags '#', '+' and space with all the other flag combinations
- For each working flag give 1 point
- If all flags are working give 2 bonus points