Smart-evaluation-system

************  installation part guideline   *********************
1. import necessary librabries by 
  pip install pdf2image 
  pip install xlsxwriter
  creat microsoft azure vision api account and get the keys and enpoints. Enter in the wherever asked in code(in line 340-341 ).
2. install poppler and add to PATH 
Link: https://poppler.freedesktop.org/
extract all files and add location of bin to path

3. Copy all images in a separate folder along with code file.

4. Run the script, browse the pdf (assignment)

5. Navigate through pages by using arrow buttons

6. Select add new data, enter details as asked

7. After entering all details close the window

8. To exit from program double click on button

9. Enter name, roll no

10. Click on save

11. Click on preview score

12. Click on find score to get final marks

13. Click on save record to save the record an ouput excel file will be created in the present directory

**********************  Project Abstract   *************************	 

The whole world is facing a huge crisis of COVID pandemic. Every field in world has been faced by a lot of difficulties.
We learned a lot of things from the pandemic. Education field was not exception for this. The mobile phones which were not allowed in classrooms, classroom has been shifted
to this mobile phones. Many things like online quizzes, online assignment, online exams, online viva etc., has been adopted. Teachers had been faced by a lot of difficulties 
while adapting to this changes. In evaluating theory papers, assignments it is really difficult task for them, like they have to download pdf of scanned response sheet from 
each and every student then evaluate them line by line. As they are new to evaluating paper, assignments on screen they require more time it might be 2 -3 times than that of
physically checking. So they are facing headache, stress due to increase in screen time. And more ever it leads to delay in result declaration. So to help teachers in online 
evaluation of papers / assignments we have made this project. 


**********************  Working  ************************************

In our exam of theory paper we write response sheet as Q.1 its answer then Q.2 and its answer then after completing this we take a ruler and underline main points (keywords) of the answer so that it will be easier for examiner to evaluate the response sheet. 

During the time of evaluating our response sheet, examiner have some     model answer sheet which have some must include points (keywords) of that particular question’s answer then examiner tries to find those points (keyword) in our answer and grade the paper according to it.  

We used exactly same method for this project.  

We will prepare a model answer sheet for this it will have some options like enter the number of questions in paper then after that it will says you to fill the keyword (important points) for that question’s answer, after that we will save this file and use this file for every response sheet evaluation.  

When we start this program, our system will convert handwritten or normal text into require text format (lowercase format) to avoid case mistakes in detection. After that it will do slicing operation of the text question wise. if we have written like  

Q.1 ___________  

Q.2____________  

Q.3 ____________.  

Then it will slice text (Q.1---Q.2), text between these is our answer, so it will consider this as answer. 

Then it will start to find the keywords from the model answer sheet. For example, a three marks question has total three keywords in model answer sheet. And our response sheet contains two keywords that are correct from this model answer sheet, then it will store output as obtained marks are two out of three so like this it will calculate marks for all individual question and it will find total obtained marks in the end.  

Those obtained marks will be saved and it can be shown student wise, section wise, question wise marks and final total marks. And after this we can show these marks to students.  




******************  Innovativeness and Show Stoppers  *******************
       
We believe that this is completely innovative idea. 
It’s a solution for real problem faced by our teachers.
So if this will run successfully we can add a lot of features in this system.  

We can use this system to evaluate papers after pandemic also like it will scan the actual paper and evaluates paper directly, 
it will work similar of OMR system which we use for competitive exams. 

We can use this not only in college/universities but also in S.S.C. H.S.C. board examsss where the papers will be in count of lacs where 
it takes 2-3 months to declare result and involves a lot of human efforts and sometimes human errors also. So by using this system it will be super-fast and with less errors. 

Transparency will be there in results as the full process is automatic. 

We can utilize this saved time of teachers to heal today’s damaged educational system due to pandemic and build a new powerful educational system. 

For the sake of hackathon, we will be evaluating based on keywords, we can transform this project into a system with added functionalities such as to detect correct diagram, grammatical correctness and more. 
