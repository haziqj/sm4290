# SM-4290 Research Project Presentations

UBD Maths majors who started their final year project in 2019S2 (Statistics group). 

- Date: Monday 23/11/2020 
- Time: 9.00am-11.30am
- Format: 20 minute slots (10min presentation, 10min Q&A)
- Venue: [TBC] *one of the tutorial rooms in FOS*

## Schedule

| ﻿Ser. | Time slot | Presenter                 | Topic                                                                             |
|---|-----------|------------------------------|-----------------------------------------------------------------------------------|
|   | 0845-0900 |                              | Admin                                                                             |
| 1 | 0900-0920 | 16B9065 Nor Hanisah          | TBC                                |
| 2 | 0925-0945 | 16B9066 Nursyazwani          | Analysis on Cardiac Arrhythmia              |
| 3 | 0950-1010 | 16B9002 Siti Nur Afiqah      | TBC |
| 4 | 1015-1035 | 16B9028 Azamuddin      | The Mathematics of Monopoly  |
| 5 | 1040-1100 | 16B9049 Mohd Ameer Ariffin | TBC                          |
| 6 | 1105-1125 | 16B9034 Sabrina      | Which Method Predicts Recidivism Best: Comparing Statistical, Machine Learning and Data Mining Predictive Model                                     |

## Instructions to students

- Please arrive early. We shall start at 0900 sharp. 
- We will be using one laptop (Apple MacBook) which will already be connected to the projector. Therefore, you may either a) e-mail your slides to me **the night before** the presentation day and I will prepare the files in a folder on the Desktop; or b) bring your own pendrive with the slides loaded on it. <u>We want to ensure a smooth transition between speakers.</u>
- You may use MS PowerPoint, Apple Keynote, PDF or HTML format for your slides.
- Please kindly ensure that your talk will be at most 10 minutes in length. The talks will be moderated and you may be asked to stop prematurely if you exceed the given time.
- The audience will be Drs. Haziq and Akira, plus some other academic staff, and other maths coursemates. 

> We hope to see everyone there at 0900, regardless of what time slot your presentation is at. *You are encouraged to sit in for the entire duration of the presentations.* It's a good opportunity to learn about each other's topics and also presentation skills. Plus, you should give each other encouragement to do public speaking.

<!-- - Please ensure that you have good internet connectivity and a quiet space to do the presentations.
- It is recommended that you use a computer/laptop to join the meeting.
- Prepare your powerpoint/PDF slides that you are presenting. The host will give you presenter access so you can share your slides with everyone. If you have not used Zoom before, then please practice it beforehand (with your friends, perhaps).
- Importantly, make sure your microphone is working. If possible, use a headset. Again, test this before joining the Zoom meeting.
- Please join the Zoom meeting <u>at least</u> **one slot** before your scheduled slot.
- Please use the naming format `<STUDENT ID> <FIRST NAME>` for your name when you join the Zoom meeting.
- You do not have to use the camera, but it would be better if you did. It would be nice to see a human face while the presentation is going on!
- You may leave the meeting when you are done, but *you are encouraged to sit in for your friends' presentations*. It's a good opportunity to learn about each other's topics and also presentation skills. Plus, you should give each other encouragement to do public speaking.
 -->

## Advice to students

- Condensing two semesters worth of work into 10 minutes can be challenging. Choose only the most important and noteworthy results to share.
- Ensure that you presentation is cohesive: there should be a beginning, a middle and an end which all flows together nicely.
- If you're struggling what to talk about, just picture telling the audience a story: what is the research problem, what have you done, and what have you found out?
- **Practice, practice, practice!** Public speaking may not come naturally to everyone, so it really helps if you practice beforehand. This way you can time your presentation accordingly and make adjustments if necessary, too.
- Supplement your slides with appropriate graphics/tables and plan what you want to say during the presentation. It's a bad habit to just read off the presentation slides. 
- Do not panic. You are in a safe environment. No one will make fun of you if you slip up! 
- Speak clearly and at a normal pace.
- Anticipate what questions might be asked of your presentation so you can be prepared.
- Have fun, and don't forget to smile!

## Random arrangements of students

To ensure fairness, the order in which you are presenting has been randomised.

```r
set.seed(221020)
akira.students <- sample(c("16B9002", "16B9049", "16B9065"))
haziq.students <- sample(c("16B9034", "16B9066", "16B9028"))
c(sapply(seq_len(4), function(i) append(
  akira.students[i], 
  haziq.students[i],
  i
)))[seq_along(c(akira.students, haziq.students))]
## [1] "16B9065" "16B9066" "16B9002" "16B9028" "16B9049" "16B9034"
```

Run this code in R for yourself 😀
