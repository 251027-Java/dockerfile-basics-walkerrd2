[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/JKXAIznf)
# Lab: Container Fun

## Goal
Get comfortable with the Docker CLI by using a lightweight Alpine container.

## Requirements
1.  **Pull**: Pull the `alpine` image.
2.  **Run**: Run it interactively (`-it`).
3.  **Explore**:
    -   Run `ls -la`.
    -   Check the OS version: `cat /etc/os-release`.
4.  **Modify**:
    -   Alpine doesn't have `curl` by default.
    -   Install it: `apk add curl`.
    -   Use it: `curl google.com`.
5.  **Clean**: Exit and remove the container.

## Deliverable
Take a screenshot of your terminal showing the output of the `curl` command inside the container.
