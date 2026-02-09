# Assignment-2-Instructions
Instructions for Assignment 2

This document explains:
- how to accept the assignment,
- what you need to complete for Assignment 2, and
- how the cross-validation (peer check) works for Assignment 2.

Please read it carefully before starting!

---

## Part 0: Common Problems

1. Make sure you properly terminate your process so that the card can be freed for others.
2. If you believe the card needs a reset due to buggy programs, you can run `tt-smi --reset`. This will reset all the cards on the machine, so use with responsibility.
3. Rememember you need to have the python environment active if you would like to use `tt-smi` commands, or the python packages of `tt-metal`.

## Part 1: Do the Lab 

1. (Similar to Assignment 1) Accept the assignment at https://classroom.github.com/a/_k75MDZx and also accept the invitation sent to your GitHub account email address.

1. Read the Lab 2 instructions here:
   https://github.com/tenstorrent/tt-metal/blob/main/docs/source/tt-metalium/tt_metal/labs/matmul/lab2/lab2.rst
   
3. Complete the exercises by following the instructions in the lab document.

4. Save evidence that your code runs correctly, such as terminal outputs, logs, screenshots etc. In particular, do not forget to include the statistics and plots required in the exercises.

5. You will need to submit your source codes for the two following exercises particularly:
   - **Exercise 1:** Implement matrix multiplication on multiple Tensix cores by modifying your Lab 1 solution. 
   - **Exercise 2:** Implement a blocked multi core matrix multiplication with data reuse on the device.
     
## Part 2: Cross-Validation (Peer Review) 

You will be randomly assigned with another classmate (details will be announced later).

For cross-validation, you will:

1. Grant access to the classmate you are assigned to.
1. Follow your assigned classmate’s `README.md` and try to reproduce their results.
1. Check whether your output matches what they claim. Note down if something does not work or if the results does not match with the evidence provided.
1. Save evidence of your cross validation attempts and open an issue on your assigned classmate's repo with these evidences. (e.g., do your plots generally match theirs?)
1. Use the Part 1 checklist below in your opened issue and feel free to add comments or questions.
1. You can also reply to the issue opened by your assignmed classmate in your own repo.
   
---

## Assignment 2 Checklist

### Part 1: Your Lab

- ⬜ Completed **Exercise 1** (matrix multiplication on multiple Tensix cores)
- ⬜ Completed **Exercise 2** (blocked multi core matrix multiplication with data reuse)
- ⬜ Saved run evidence (logs, terminal output, screenshots, etc.) and the required plots.
- ⬜ **Exercise 1** matches the reference implementation
- ⬜ **Exercise 2** matches the reference implementation
- ⬜ Clear instructions to reproduce the results
- ⬜ All work committed and pushed to your GitHub Classroom repository

### Part 2: Cross-Validation

- ⬜ Read and followed the assigned classmate’s `README.md`
- ⬜ Successfully reproduced and verified their results
- ⬜ Documented and pushed your reproduction attempts

  
