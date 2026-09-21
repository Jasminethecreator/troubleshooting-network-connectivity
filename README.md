# Troubleshooting Network Connectivity

## Objective

Use the Windows `ping` command to test network connectivity, recognize an unsuccessful test caused by an incorrectly entered destination address, correct the command, and verify successful communication.

## Tools & Environment

* Windows 11
* Command Prompt
* `ping`
* TCP/IP networking
* Microsoft Azure virtual machine

## Troubleshooting Process

1. Opened Command Prompt to test network connectivity.
2. Entered `ping 8.8.8` instead of the intended address, `8.8.8.8`.
3. Observed that the test was unsuccessful.
4. Reviewed the command and identified the incorrectly entered destination address.
5. Corrected the destination to `8.8.8.8` and repeated the ping test.
6. Verified successful communication when the corrected test returned responses with **0% packet loss**.

## Troubleshooting Evidence

### Unsuccessful Ping Test

<img width="450" alt="Unsuccessful ping test after entering an incorrect destination address" src="https://github.com/user-attachments/assets/e96d86a3-47d6-465e-98c1-cde932b256cc" />

*The initial test was unsuccessful after the destination address was entered incorrectly as `8.8.8`.*

### Corrected Ping Test

<img width="450" alt="Successful ping test to 8.8.8.8 with zero percent packet loss" src="https://github.com/user-attachments/assets/914ce988-83cb-4b2d-a062-2a993746d5e7" />

*Corrected the destination to `8.8.8.8` and verified successful communication with 0% packet loss.*

## Verification

The corrected `ping 8.8.8.8` test successfully received responses with **0% packet loss**, verifying network connectivity to the destination.

## Skills Demonstrated

* Network connectivity testing
* Command-line troubleshooting
* `ping` command usage
* TCP/IP fundamentals
* Troubleshooting input errors
* Verification of connectivity
* Windows Command Prompt

## Lessons Learned

This lab reinforced the importance of verifying command syntax and input before assuming that a failed test indicates a network problem. A small input error can produce misleading troubleshooting results, so reviewing the command and repeating the test with the correct destination is an important part of the troubleshooting process.

## Lab Environment

* Microsoft Azure
* Windows 11
* Hands-on networking lab

> **Note:** This project was completed in a lab environment for hands-on IT support and network troubleshooting practice.
