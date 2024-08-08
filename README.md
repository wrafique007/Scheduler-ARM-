# Project Description
I developed a small scheduler on Cortex M4 using SYS TICK, PENDSV and SVC exceptions. Details are given below:
* Scheduler has been implemented using Round Robin scheduling policy, where each task is given equal amout of time in a circular manner
* There are 4 tasks and each task has its own private stack
* PENDSV exception is used for context store and restore for a specific task
* SYSTICK exception is used to keep track of time allocated to each task

# Hardware Used
  * MCU = STM32F407VG
  * Debugger = ST-LINK/V2-A

# Software Used
 * STM32CubeIDE

# Source Code Description
 * Src/main.c  : This file contains the scheduler and exception handlers code
