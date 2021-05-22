# Evaluation Guide: ft_server

May 2021

---

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

---

## General instructions

### verifications

- Check if all the necessary configuration files of the server are in the folder srcs.
- Check if the Dockerfile is at the root of the repository.
- Run the "docker build ." command.

---

## Mandatory part

The project consists of setting up a functional web server with Docker. Check if all the next points are respected. At the first error, you stop the correction and set the grade to zero.

### Docker environment

- Verify if the evaluated has only one container.
- Verify if the container is build with Debian Buster.
- Verify if you can run the container with "docker run xxx" without problems. (xxx is the name of the docker you've just built)

### Server instructions

- Verify if the evaluated uses Nginx (you can read the Dockerfile).
- Verify if the server runs multiple services (WordPress and phpMyAdmin).
- Verify if the server redirects to the correct website, according to the url. 
- Verify if Nginx uses the SSL protocol.
- Verify if the server is running with an autoindex which can be deactivated when the container is launched (via an environment variable for example).

### Run website, run!

- Verify if the WordPress website runs entirely with the MySQL database. You can go to the site, log in, and watch the database.
- Verify if the SQL database works with phpMyAdmin. You should see the WordPress tables and data.
