# Intro to AI on RISC-V
A hands-on workshop

-----------------------------------------------------------------

[BACK to HOMEPAGE](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/README.md)


-----------------------------------------------------------------
![remix](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/fedora_remix_dark_blue_and_white.png) 

![DeepComputing](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/DeepComputing-logo.gif)

----------------------------------------------------------------


## Overview
> It's time for the Main Event - playing with AI!!!

![AI Takes over the world](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/AI-running01.gif)

> 

----------------------------------------------


## Demo Three:  Running AI (Web Chatbot)
Matt & Yuning will demonstrate running ollama locally with RISC-V on Fedora 42.
Quick discussion on the how and the why this is more than cool - but critical.



> 


----------------------------------------------
>

## Hands-on Exercise One:
**Overview:**  In this exercise we will install, configure, and experiment with AI. 


### Step 1:
> Assuming we are running after a fresh reboot.
> Log into the Gnome Desktop.
> Open a terminal, then drag it to fill the left half of the screen.
> In that terminal's toolbar click on View --> Zoom Out (two times). This will reduce the font size in the window.

```

$ btop


```

![btop](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-btop.png)

### Step 2:
> now open another terminal window and resize it to fill only the upper right corner of the screen.

```

$  sudo ./start-server.sh

```

![start-server](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-start-server.png)

>

### Step 3:
> While that is running...
> Open the **Files** application.
> Double-click on **ollama-deepseek7b.html** , this will open a browser window. Resize the browser window to take up more than half of the lower right side of the screen.

>

![files](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-click-html-file.png)


### Step 4:
> This is where the fun starts.
> Type a question into the window.


>**PLEASE NOTE:  The first time a question is asked - the model must be loaded**


>**This process takes about 3-4 minutes - please be patient..**

![First Web Prompt](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-AI-prompt1.png)

>An example question...

![question](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-question.png)

>And a witty reply...

![response](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3-response.png)





----------------------------------------------




## Demo Four: Manually running AI
> Matt will demo command line usage of AI.


----------------------------------------------

## Hands-on Exercise Two:
**Overview:** In this exercise will will run AI via the console.


### STEP 1: 
> Open a terminal - set the window size and location to take up a small corner of the screen.

```

$  sudo -i 

#  es_ollama serve

```

### STEP 2: 
> Open another terminal - set this one's size to take up the bottom corner of the screen.
> In the terminal's View settings - Zoom out (twice)...This will enable the command to display properly.

```

$ btop

```

### STEP 3: 
> Open another terminal - set this one to take up the entire right sidew of the screen.
> Let's see what models are available locally.

```

$  sudo -i

#  es_ollama list


NAME                 ID            SIZE            MODIFIED
my-deepseek:latest   a7a9b3d5623a  2.2 GB          9 days ago

# 

```

### STEP 4:
> Let's run that model and play with it some...
> In the right side terminal window - run the following command to start the model.

```

#  es_ollama run my-deepseek

>>> Send a message (/? for help?

```

### STEP 5:
> Engage the model - ask it some questions.

> When exhausted by the AI's witty charm - exit out of all windows...


----------------------------------------------

## Hands-on Exercise Three:
**Overview:**  In this glorious exercise we'll run a DeepSeek7B model on NPU via the console.


```

$ sudo /opt/eswin/sample-code/npu_sample/qwen_sample/bin/es_qwen2 /opt/eswin/sample-code/npu_sample/qwen_sample/src/deepseek_7b_1k_int8_peer/config.json

```

> Please be patient this may take a couple of minues to load the model.

> **Fun Challenge:** Let's see who can make AI halucinate the most. For something without real feelings - it can get rather ...verbose.

> **The Winner - by a vote of your peers** might just get a signed copy of Matt's book...


-------------------------------------------------

![starting](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3c-AI-greeting.png)



![coexist](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3c-coexist.png)


![inclusive](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab3c-inclusive.png)

--------------------------------------------------

## THANK YOU

## We hope you have enjoyed this workshop

--------------------------------------------------



