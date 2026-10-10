# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [ٌReemas fahad mohammd alqhtani] |
| **Student ID** | 446051392] |
| **University Email** |446051392@std.psau.edu.sa |
| **GitHub Username** | [Reemas-fahad123] |
| **Repository Link** | (https://github.com/Reemas-fahad123/OS-Assignment1-Reemas-alqhtani) |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
-Created GitHub account with university email
-Forked the starter repository and renamed it
-Changed student ID on line 150 to my actual ID (441234567)
-Compiled and ran the program successfully
-Committed and pushed: Set my student ID: 441234567
**Challenges**: Had to install JDK first because javac wasn't recognized
**Solution**: Downloaded JDK 17 and set the PATH variable
**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [September 30, 2026, 7;30  Am]
**What I did** set up the project repository and set up my student ID

**Details**:
- create my account  student emaile and forked the repository .
- name my repository 
- set my student id (446051392)
-  ensured the environment was configured
- Committed and pushed: Set my student ID: 446051392
**Challenges**I faced some initial difficulty downloading the VC code and linking it to GitHub.

**Solution**I downloaded VC code and linked it to GitHub ز

**Time spent**: 20 minutes

---

### Entry 2 - [october 7, 2026, 1:20 Am]
**What I did**:i do feature1 (process priority)


**Details**:added  the priority integer field to the Process class
- updated constructors
- generated random priorities (1–10)
- Display priority when a process enters the ready queue



**Challenges**: i  difficulty adding priority to process class


**Solution**:i test feature1 and every thing is corcct and i commint

**Time spent**:30m

---

### Entry 3 - [october 7, 2026, 7:10 Pm]
**What I did**: i did feature2 Context Switch Counter




**Details**: -  - adedd Add a static counter variable for context switches
- ncremented the counter
- -Displayed the total count in the final statistics summary table
- and i commint

**Challenges** : I encountered difficulties with calculating the total context switch count correctly and faced an error in the sum output.
**Solution**:I fixed the logic error in the context switch incrementation and verified that the total count displayed accurately in the output.

**Time spent**:40m

---

### Entry 4 - [October 09, 2026, 1:40 am]
**What I did**::i did  Feature 3 (Waiting Time and Turnaround Time Tracking)


**Details**::Tracked waiting times
-
-Calculate waiting time for each process
-Use System.currentTimeMillis() to track time
Implemented getTurnaroundTime() method
and i Display a summary table
and i commint .

**Challenges**: error getTurnaroundTime 

**Solution**:  i corrct and fixed eror .

**Time spent**: 45m

---

### Entry 5 - [October 10, 2026, 1:40 AM]
**What I did**:Completed MY_WORK.md documentation

**Details** : Filled in student information and repository links 
and other parts

**Challenges**:  initially found it a bit difficult to fully understand some of the theoretical and technical concepts 
**Solution**:⁠I organized my work step-by-step

**Time spent**:1 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [5 hours]

**Most challenging part**:Debugging code errors during feature implementation including method naming mismatches missing methods and initial logic errors in the context switch counter before correcting the calculation output.

**Most interesting learning**:Connecting theoretical OS concepts to actual Java code and particularly fixing method naming mismatches

**What I would do differently next time**:Trace the existing method names and test small changes frequently to catch logic issues early.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[First, we break the process down into threads to improve responsiveness. How do we create a thread in Java?sentence1
One way is to extend the `Thread` class and override the `run` method; the `start` method is what actually
triggers the execution of the code within `run`.
Another approach uses the `Runnable` interface, which is similar to extending `Thread`.
but involves creating a `Thread` object and passing the `Runnable` instance into its constructor. 
The `Thread.join` method ensures that a task doesn't start until the preceding one has finished—much like how you can't calculate an average until you've calculated the total sum.
The `sleep` method pauses the task for a specific duration.
I found the concept of splitting processes to boost responsiveness really interesting.
I had used Java before without realizing I was working on a single thread.
but I only truly understood this after taking an Operating Systems course.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[To be honest, the assignment was demanding.
yet easy and highly enjoyable. I learned a lot.
though I did face some challenges. 
First, I encountered numerous syntax and logic errors.
Regarding initial difficulties.
I didn't understand how to link GitHub
with VS Code at first; however, a YouTube video helped me set up VS Code easily.
Other challenges included name mismatches in functions,
issues with the context switch counter and console output formatting, 
and
difficulties with debugging. I also struggled specifically with the `getTurnaroundTime` function.Ultimately, these challenges got me used to lengthy assignments, taught me a great deal, made me truly feel like a university student, and enabled me to solve problems in a very organized way.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[As for how I overcame the challenges I faced: first, I took a deep breath and started reading 
the file step-by-step,.
as the details were clearly laid out. Regarding errors,
the error messages weren't actually vague; 
I would review my code for both syntax and logic, understand the issue, and fix it. I tested the code
repeatedly and checked the outputs—for instance, 
I corrected the placement of the counter within the code. I also managed my time effectively by dedicating
a specific slot—like an
hour each day—to reviewing the code and fixing errors.The reason I was able to solve and overcome the difficulties was my calmness and following the written instructions and details provided by Dr Mahdi.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[I love this—it’s actually one of my favorite topics. For instance,
if I have a task, I’ll break it down into smaller parts to make it more manageable. 
A great example is a web browser: one thread handles displaying content while another handles 
receiving data. Another example is a client-server scenario where multiple clients request services online; 
each request is handled by a separate thread, allowing the system to respond to multiple threads simultaneously.Modern software can achieve the highest possible performance without slowness or delay.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[The difference between threads and a process is that a process is a complete entity, whereas a 
thread is a component of that process—essentially, the process is divided into threads (or tasks). 
Threads share the same memory space within the process, making communication between them significantly easier; 
furthermore, a thread is considered a "lightweight" process. The `Process` class I created is a *simulated* process—not an actual 
operating system process—that holds data such as execution time, but it actually runs as a real thread within the 
`addProcessToQueue()` function in `main`.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[If the process has not finished executing, it indicates that it is
a preemptive process—meaning another process has interrupted it. Consequently,
its remaining execution time is updated, and the process is moved to the back of the ready queue; For instance, my program output shows 
that P2 was re-queued multiple times because its large burst time (9142ms) exceeded the quantum limit.
it then returns to the processor based on the processor scheduling order.]

Example from my output:
```
[ Remaining time: 4142ms
  ? P2 yields CPU for context switch

  ? P2( priroty:10) added to ready queue │ Burst time: 9142ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P2]
└───────────────────────────────────────────────────────────────────────────────
]
```

**Explanation of example:**
[p2 has not finished; it is being added to the ready queue.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [In my output, a new process (p1) was created but has not yet entered
2. the processor; it still needs to be added via
3. `addprocesstoqueue()`.]

4. **Runnable**: p1 moves to the ready queue via `processQueue.add(thread)]

5. **Running**: [This is the actual operation of the process—the execution
6.  phase—initiated via `currentThread.start`.]

7. **Waiting**: [Process P1 enters the waiting state using the `sleep` function.]

8. **Terminated**: [Finally, the execution of P1 completed without it having to re-enter the queue, because its remaining time was less than the time quantum.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Processor scheduling]

**Description**:
[Operating systems employ various algorithms—such as those for synchronization—to manage and schedule processes, ensuring fair and organized execution. One such method is the Round Robin algorithm, which guarantees fairness and rapid response times; it assigns a specific time slice to each process, cycling them in and out of execution. This approach significantly improves responsiveness, particularly when handling multiple concurrent tasks, as the operating system rapidly switches execution between them to ensure timely processing.]

**Why Round-Robin works well here**:
[Round-Robin works exceptionally well; I appreciate it because it is inherently fair—and I value fairness. From now on, whenever I cite an example of fairness, it will be Round-Robin. It offers high responsiveness and effective time distribution, where each application or process is allocated a specific duration known as a "time quantum." The transition between open windows—or processes—is called a "context switch," a mechanism that maintains system responsiveness.]

### Example 2: [My favorite example—which I have mentioned before—is customer services or requests.]

**Description**:
[To handle an environment with a massive volume of simultaneous requests—where delays must be avoided—the web server employs a scheduling mechanism that divides processor time equally among active client connections.]

**Why Round-Robin works well here**:
[I used the Round Robin algorithm because it ensures that all requests are executed without delaying any single operation. By assigning a specific time slice—known as a "time quantum"—to each process, the system treats them fairly and prevents any process from waiting indefinitely, thereby avoiding "starvation." In this setup, each process is broken down into threads, and the system switches between requests through a process called "context switching."]

## Summary

**Key concepts I understood through these questions:**
1.The Life of Threads: From Creation to the End
2.How Ready-Queue ​​Works
3.I understood  the Context switching and time quantum

**Concepts I need to study more:**
1.I really want to understand what true synchronization actually is.
2.Calculation of troundtime and waiting time

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
