# Amanda Hanway - Streaming Data, Module 4
- Date: 1/29/23

# streaming-04-bonus-hanway

## Overview:
- Bonus_emitter_of_tasks.py
    - This program reads two columns of data from a csv file 
    - then sends the data as a message to two queues on the RabbitMQ server
    - The script incorporates code from v2_emitter_of_tasks.py 
- Bonus_listening_worker.py
    - This program continously listens for messages on two queues
    - When a message is received, it transforms the data and writes to an output file
    - The script incorporates code from v2_listening_worker.py 
- CSV Data Source
    - The insurance_data.csv file contains demographic and health factors from insurance claims
    - Link to source: https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health?resource=download

## Instructions:
- Open three terminals
    - Two terminals will execute the listening worker program
    - One terminal will execute the emitter of tasks program

## Screenshot - Program Running in Multiple Terminals
- using VS Code (listening) and Command Prompt (emitting)

![Using Multiple Terminals](one_emitter_two_listeners_bonus.png)