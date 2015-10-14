This is a html exam/quiz solution which can create multiple choice question,multiple choice question with multiple correct answers,True-False question, Drag-Drop Math question. And this project also responsive!

This project is Javascript/JQuery/Html/CSS.  I use JQuery UI, Bootstrap.

Here is the link you can play.

All the questions are generated based on the exam.xml. So you don't need to hard code it, and you don't need to have html knowledge. Inside the exam.xml, I explained how to use this form.

In the main page, I use iframe to load each question by the question type that means each type of question has a specific file to handle the logic, and the main page(index) will collect the info sent by the file.  So, it's easy in the future to expand another types of question and combine them together.

I still remember I spend a lot of time to create/debug the drag-drop-match type questions.

686DBA19-3F32-4D10-834E-1A252737686D

This is a Match question.  You can drag the options, which display at the bottom, to fill the answer area.  I spent a lot time to make the drag-drop hot area work perfectly, for example: when you drag part of the pic over the answer box, it automatically position it for you, when you drag another pic over a filled answer box, it automatically replace with the new one, and put the old one back to the original place, etc.

The Exam Summary button allows you to overview all the questions and quick jump to question.  You 2A821F09-AEC3-49DF-8D55-B9BE688F8A57can view how many you answered, jump to question, go back or grade the exam.

If you grade your exam without answer all your questions. It will give you a alert.
966802E5-2068-4315-922D-21F230FC53AF



D36E86A8-1DC6-462A-856B-4B867DC49F291A87254C-3B3E-45C7-9411-CAD27C01B861

You have the option to put a image with your answer, and it's perfectly responsive!







05855886-80C4-41B6-BC73-340074BF1217After you submit your exam, it will give you a summary, and show you which answer is wrong and you can go to that course to review again. (It won't display the correct answer)
