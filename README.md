# csc3150-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSC3150 Assignment 2 Solved](https://www.ankitcodinghub.com/product/csc3150-assignment-2-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121152&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3150 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Homework Requirements

Environment

If you follow the tutorials then your VM setting should be fine, though verify your environment again is recommended.

4.4 or 5.10.x is ok (Test Environment). You can use the following command to get it.

Submission

Violation against the format requirements will lead to grade deduction.

Here is the format guide. The project structure is illustrated as below. You can also use ls command to check if your structure is fine. Structure mismatch would cause grade deduction.

Please mark whether you have finished bonus in your report.

Please compress all files in the file structure root folder into a single zip file and name it using your student id as the code showing below and above, for example, Assignment_2_118010001.zip. The report should be submitted in the format of pdf, together with your source code. Format mismatch would cause grade deduction. Here is the sample step for compress your code.

Task Description

In the “”source/”” directory of Assignment 2, you are required to complete the multithread program to implement the game “Frog crosses river”.

Game rules:

A river has logs floating on it, and a frog must cross the river by jumping on the logs as they pass by.

Objects:

Log: =================

Frog: 0

River bank: |||||||||||||||||||||

When the game starts, the frog stands in the middle of bottom bank of river. The user can control the frog jumps by keyboards. The logs will move from left to right or right to left staggerly. Please take care of the edge cases.

still on it.

Function Requirements (90 points):

To run the template, you will see the frog stands in the middle at bottom bank of river. There are 9 blank rows which means the river. Compile the program to see the static output. (5 points)

right or from right to left. (20 points)

You should create pthread and use mutex lock for logs and frog movement control. (30 points)

“kbhit” function is provided for keyboard capture. You should complete the jump rules for keyboard actions. And the frog’s position should be updated when keyboard hits. (15 points)

When the logs are moving, the program should be able to judge the game status (win, lost or quit).

Print out the message for user whether he/she wins or lost the game. (15 points) If the user quits the game, print the message. (5 points)

Demo Output

Bonus Task (10 pionts)

Attention: The bonus task has no relationship with the the above game “Frog crosses river”.

In the “3150-p2-bonus-main/” directory of this bonus task, you have to implement correctly two important functions of a thread pool. The two functions in async.c are as follows:

1. void async_init(int num_threads)(3 points)

2. void async_run(void (*handler)(int), int args) (7 points).

head)

When no jobs are coming, your threads created in async_init have to go to sleep and is not allowed to do busy waiting like while(1){sleep(any);}, and when jobs are coming a sleeping thread in your thread pool must wake up immediately (that is, no sleep() call is allowed).

async_run should be asynchronous without further call to pthread_create, that is it should return immediately before the job is handled (in the code we give you, async_run runs synchronously, so you need to rewrite the function)

After finishing these two function and the implementation of thread pool, you can make with the provided Makefile and a http server will be run based on the thread pool you implement so that you can see whether your implementation works or not.

Please see the directory 3150-p2-bonus-main and read README.md in detail to do this bonus task.

What is a thread pool? Please see: https://en.wikipedia.org/wiki/Thread_pool.

Report (10 points)

Write a report for your assignment, which should include main information as below:

Grading rules

Bonus 10 points

Report 10 points

Completed with good quality 80 ~ 90

Completed accurately 80 +

Fully Submitted (compile successfully) 60 +

Partial submitted 0 ~ 60

No submission 0
