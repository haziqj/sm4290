# SM-4290 Research Project Presentations

** THANK YOU EVERYONE FOR MAKING THE PRESENTATION SESSION A SUCCESS. WELL DONE! **

UBD 2019S1 batch (Statistics group). 

- Date: Monday 20/4/2020 
- Time: 9.00am-12.00pm
- Format: 20 minute slots (10min presentation, 10min Q&A)
- Online Zoom meeting (sent in the e-mail)

** ***Please logon as early as 0845. We will start at 0900 sharp.*** **

## Schedule

| ﻿Ser. | Time slot | Presenter                 | Topic                                                                             |
|---|-----------|------------------------------|-----------------------------------------------------------------------------------|
|   | 0845-0900 |                              | Admin                                                                             |
| 1 | 0900-0920 | 16B2199 Al Muizz             | The statistical analysis on unemployment in Brunei                                |
| 2 | 0925-0945 | 16B2068 Nurhafizah           | Statistical analysis on UBD dormitory students' academic performance              |
| 3 | 0950-1015 | 16B2181 Rossmadalina         | Allelopathic potential of invasive *Acacia holosericea* on germination and growth of Bario and Laila paddy |
| 4 | 1020-1040 | 16B2153 Siti Nurfarhana      | The statistical investigation on the possible factors of crime in London boroughs |
| 5 | 1045-1105 | 16B2187 Mohammad Izzul Islam | Statistical analysis on drug abuse in Brunei Darussalam                           |
| 6 | 1110-1130 | 16B2070 Md Nur Waizudin      | Bayesian variable selection for linear models                                     |
| 7 | 1135-1155 | 16B2092 Ida Haizatultasha    | Crime and the factors affecting it in Brunei Darussalam                           |

## Instructions to students

- Please ensure that you have good internet connectivity and a quiet space to do the presentations.
- It is recommended that you use a computer/laptop to join the meeting.
- Prepare your powerpoint/PDF slides that you are presenting. The host will give you presenter access so you can share your slides with everyone. If you have not used Zoom before, then please practice it beforehand (with your friends, perhaps).
- Importantly, make sure your microphone is working. If possible, use a headset. Again, test this before joining the Zoom meeting.
- Please join the Zoom meeting <u>at least</u> **one slot** before your scheduled slot.
- Please use the naming format `<STUDENT ID> <FIRST NAME>` for your name when you join the Zoom meeting.
- You do not have to use the camera, but it would be better if you did. It would be nice to see a human face while the presentation is going on!
- You may leave the meeting when you are done, but *you are encouraged to sit in for your friends' presentations*. It's a good opportunity to learn about each other's topics and also presentation skills. Plus, you should give each other encouragement to do public speaking.

## Advice to students

- Condensing two semesters worth of work into 10 minutes can be challenging. Choose only the most important and noteworthy results to share.
- Ensure that you presentation is cohesive: there should be a beginning, a middle and an end which all flows together nicely.
- If you're struggling what to talk about, just picture telling the audience a story: what is the research problem, what have you done, and what have you found out?
- **Practice, practice, practice!** Public speaking may not come naturally to everyone, so it really helps if you practice beforehand. This way you can time your presentation accordingly and make adjustments if necessary, too.
- Supplement your slides with appropriate graphics/tables and plan what you want to say during the presentation. It's a bad habit to just read off the presentation slides. 
- Do not panic. You are in a safe environment. No one will make fun of you if you accidentally slip up! 
- Speak clearly and at a normal pace.
- Anticipate what questions might be asked of your presentation so you can be prepared.
- Have fun, and don't forget to smile!


## Random arrangements of students

To ensure fairness, the order in which you are presenting has been randomised.

```r
set.seed(134)
akira.students <- sample(c("16B2092", "16B2181", "16B2187", "16B2199"))
haziq.students <- sample(c("16B2070", "16B2068", "16B2153"))
c(sapply(seq_len(4), function(i) append(
  akira.students[i], 
  haziq.students[i],
  i
)))[seq_along(c(akira.students, haziq.students))]
## [1] "16B2199" "16B2068" "16B2181" "16B2153" "16B2187" "16B2070" "16B2092"
```

Run this code in R for yourself 😀
