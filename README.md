# File Integrity Monitor

## Introduction

File Integrity Monitor is a tool used to monitor the integrity of the files in the given sub-folder provided by the user. We created an integrity baseline for the target files/folders using the SHA-512 hashing algorithm. The tool continuously makes comparisons of actual files vs baseline and raises alerts if any deviation occurs. Also sends alerts to the user upon detecting any kind of compromise in the file integrity.

During a cyber attack, it is important to detect any change made to the important files that hold the customer data contain the web config, or contain the backup files. Whether some of them are deleted, removed or any kind of action is made that compromises on the CIA triads. (Integrity here). It is important to alert the user before the company suffers a data breach or another user's data gets stolen.

This tool helps us to achieve that


## Baseline files contained in the folder
