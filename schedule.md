---
layout: page
title: Schedule
---

<p class="message">
  Hey there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>

Share the schedule for your *Workshop.*


### Collaboration Plan
 {% include mermaid.html %}

<div class="mermaid">
gantt
        dateFormat  YYYY-MM-DD
        title Example Gantt

        section Administration
        Start Course                :crit, done, admin1, 2015-09-08, 1d
        Cr/D/F Grading Change Date  :crit, done, admin2, 2015-09-22, 1d
        Withdrawal Date             :crit, done, admin3, 2015-10-16, 1d
        End Course                  :crit, done, admin4, 2015-12-04, 1d

        section Class
        Vectors                     :crit, done, des1, 2015-09-08, 12d
        Differentiation             :crit, done, des2, after des1, 28d
        Integration                 :crit, done, des3, after des2, 16d
        Vector Fields               :crit, done, des4, after des3, 24d

        section Exams
        Midterm1    :crit, mt1, 2015-10-15, 2d
        Midterm2    :crit, mt2, 2015-12-01, 2d
        Final       :crit, final1, 2015-12-10, 2d

        section Homework
        Assignments :crit, A1, 2015-09-08, 89d
        Epic1       :epic1, 2015-10-29, 2d
        Epic2       :epic2, 2015-11-23, 2d
  
</div>
