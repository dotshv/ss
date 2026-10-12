# IGNOU ASSIGNMENT

**Course Code:** BCSL-013
**Course Title:** Computer Basics and PC Software Lab
**Assignment Number:** BCA_NEW/BCAOL(I)L-013/Assign/2026-27
**Maximum Marks:** 100

**Student Name:** ________________________
**Enrollment No.:** ________________________

---

**Q1 (a): Write and run the following Linux commands and attach the screenshots of the output of each command.**

**Answer:**

*(Note to student: You must execute these commands in your Linux terminal and take screenshots of the outputs as requested by the assignment.)*

**i) history**
This command displays the list of previously executed commands in the terminal session.
**Command:** `history`

**ii) info**
This command reads documentation in the info format, providing detailed manuals for other commands.
**Command:** `info` (or specifically: `info ls`)

**iii) cp**
This command copies files or entire directories from one location to another.
**Command:** `cp source_file.txt destination_file.txt`

**iv) who**
This command shows a list of users who are currently logged into the Linux system.
**Command:** `who`

**v) cmp**
This command compares two files byte by byte and outputs the location of the first difference.
**Command:** `cmp file1.txt file2.txt`

**vi) cat**
This command concatenates files and prints their contents on the standard output screen.
**Command:** `cat my_file.txt`

**vii) more**
This command is a pager that displays the contents of a text file one screen (or page) at a time.
**Command:** `more large_file.txt`

**viii) wc**
This command prints the newline, word, and byte counts for a specified file.
**Command:** `wc my_file.txt`

**ix) mkdir**
This command is used to create a new, empty directory.
**Command:** `mkdir my_new_folder`

**x) grep**
This command searches for a specific string pattern or word inside a file and prints the matching lines.
**Command:** `grep "search_term" my_file.txt`

---
<br>

**Q1 (b): Create a text file in Linux containing two paragraphs that outline the advantages of the Linux operating system. Make a copy of this file named “assignment.txt”. Count how many times the word “the” appeared in this file. Display the file permissions of the file “assignment.txt”. Now, change the file permissions of this file to r--r--r--.**

**Answer:**

Here is the exact sequence of commands executed in the Linux terminal to perform the required tasks:

**Step 1: Create the initial text file and write two paragraphs.**
**Command:** `cat > linux_advantages.txt`
*(Type the following text and press `Ctrl + D` to save the file)*
> Linux is a highly secure and open-source operating system. Because the source code is visible to everyone, the global community of developers can quickly find and fix vulnerabilities, making it less prone to viruses compared to other operating systems.
> 
> Another major advantage is its flexibility and cost-effectiveness. The OS is completely free to use, and it can run on a wide variety of hardware, from old desktop computers to the most powerful servers in the world.

**Step 2: Make a copy of this file named "assignment.txt".**
**Command:** `cp linux_advantages.txt assignment.txt`

**Step 3: Count how many times the word "the" appeared in this file.**
**Command:** `grep -o -i "the" assignment.txt | wc -l`

**Step 4: Display the file permissions of "assignment.txt".**
**Command:** `ls -l assignment.txt`

**Step 5: Change the file permissions of this file to r--r--r--.**
**Command:** `chmod 444 assignment.txt`
*(You can verify this worked by running `ls -l assignment.txt` again)*

---
<br>

**Q2: Create a presentation using any Presentation software on the topic “Advantages and Disadvantages of Using AI” (minimum 8 slides). The slides should have the following features: All slides should use a common design template, add an audio file, add a video file (full-screen), timer-based transitions, proper headings and slide notes, one image related to the topic per slide. Write the sequence of steps that you have performed to create these slides.**

**Answer:**

**Sequence of Steps performed in MS PowerPoint:**

**1. Creating the Presentation & Applying a Template:**
*   Opened MS PowerPoint and created a "Blank Presentation".
*   Navigated to the **Design** tab on the top ribbon.
*   Selected a professional theme from the "Themes" gallery to apply a common, uniform design template to all slides.
*   Added 8 slides by pressing `Ctrl + M` multiple times.

**2. Adding Content, Headings, and Slide Notes:**
*   **Slide 1:** Title: "Advantages and Disadvantages of Using AI".
*   **Slide 2:** Heading: "Introduction to AI". Added bullet points explaining basic AI concepts.
*   **Slide 3 to 5:** Headings for Advantages (e.g., "Automation", "24/7 Availability", "Faster Decision Making").
*   **Slide 6 to 7:** Headings for Disadvantages (e.g., "High Cost of Creation", "Lack of Human Creativity").
*   **Slide 8:** Title: "Conclusion".
*   For each slide, I clicked on the **"Notes"** button at the bottom of the screen and typed relevant speaker notes (e.g., "Welcome the audience and introduce the topic of Artificial Intelligence.").

**3. Inserting Images:**
*   On every single slide, I went to the **Insert** tab -> **Pictures** -> **This Device**.
*   Selected a relevant AI-related image, inserted it, and resized it to fit beautifully within the slide layout.

**4. Adding Audio and Video Files:**
*   **Audio:** Selected Slide 1, went to the **Insert** tab -> **Audio** -> **Audio on My PC**. Selected a background music file. Under the Audio Format tab, I set it to "Play Across Slides".
*   **Video:** Selected Slide 8, went to the **Insert** tab -> **Video** -> **Video on My PC**. Inserted an AI conclusion video. I clicked on the video, went to the **Playback** tab, and checked the **"Play Full Screen"** checkbox.

**5. Applying Timer-Based Transitions:**
*   Went to the **Transitions** tab.
*   Selected a transition effect (e.g., "Fade").
*   On the far right, in the "Timing" group, I unchecked "On Mouse Click".
*   I checked the box for **"After"** and set the timer to `00:05.00` (5 seconds).
*   Clicked **"Apply To All"** so every slide automatically advances after 5 seconds without user input.

**6. Printing Handouts:**
*   Went to **File** -> **Print**.
*   Under the Settings dropdown, changed "Full Page Slides" to **"4 Slides Horizontal"** in the Handouts section. 
*   Saved the document as a PDF to be attached to the assignment.

---
<br>

**Q3 (a): Use a Word Processor to create a document about the “Use of AI in Learning” of about 2 pages. It should include: a multi-level list highlighting features, a table consisting of Tool and its use, and a paragraph about “Learning without AI tools”. Write the sequence of steps.**

**Answer:**

**Sequence of Steps performed in MS Word:**

**1. Document Setup & Paragraph Typing:**
*   Opened MS Word, selected a blank document. Typed the main heading "Use of AI in Learning", increased the font size, and centered it.
*   Typed an introductory paragraph. Then, typed the specific heading "Learning without AI tools" and wrote a paragraph detailing traditional learning methods like physical books, chalkboards, and manual research under it.

**2. Multi-Level List:**
*   Navigated to the **Home** tab -> Paragraph group.
*   Clicked the **Multilevel List** icon and selected a standard format (1., 1.1, a., etc.).
*   Typed the primary feature (e.g., "1. Personalized Learning Experiences"). 
*   Pressed `Enter`, then pressed the `Tab` key on the keyboard to indent to the next level, and typed details (e.g., "a. Customizes study material based on student speed").

**3. Inserting a Table:**
*   Went to the **Insert** tab -> **Table**. Selected a 2x4 grid using the visual tool.
*   In the first row, typed headers: "AI Tool" in Column 1, and "Use in Learning" in Column 2. Made the text bold.
*   Filled in the remaining rows with data (e.g., ChatGPT -> Generates explanations; Grammarly -> Assists in writing). 
*   Applied a professional table style from the **Table Design** tab to add borders and shading.

---
<br>

**Q3 (b): Design a flyer on the topic “Learning Through Open University System”. Use different styles, sizes, fonts, colours and effects. Write the sequence of steps that you have performed.**

**Answer:**

**Sequence of Steps performed in MS Word:**

**1. Page Layout & Background:**
*   Went to the **Layout** tab -> **Margins** and selected "Narrow" to maximize flyer space. Set **Size** to A4.
*   Went to the **Design** tab -> **Page Color** and chose a soft light blue shade. 
*   Clicked **Page Borders** and added an attractive, thick box border to frame the flyer.

**2. Main Title (WordArt):**
*   Went to the **Insert** tab -> **WordArt**. Chose a 3D shadow effect style. 
*   Typed "Learning Through Open University System". Increased the font size to 48, applied the color Navy Blue, and centered it at the top of the page.

**3. Content, Styles, and Effects:**
*   Inserted floating text boxes (**Insert** -> **Text Box**) for different sections like "Why Choose Us?", "Maximum Flexibility", and "Affordable Education". 
*   Highlighted the text and changed fonts to "Arial Black" for headings and "Calibri" for body text.
*   Applied vibrant font colors (Dark Orange and Green) from the **Home** tab.
*   Applied text effects like *Shadow* and *Glow* to the section headings using the Text Effects tool.

**4. Inserting Images:**
*   Inserted a high-quality picture of a student studying at a laptop (**Insert** -> **Pictures** -> **This Device**). 
*   Right-clicked the image, selected **Wrap Text** -> **Tight**, and positioned it attractively in the center of the flyer.

---
<br>

**Q4: Create a worksheet containing the mark list of the students of a class. Enter all labels. Write the sequence of steps that you have performed to create the formulae in different cells.**

**Answer:**

**Sequence of Steps performed in MS Excel:**

**1. Entering Labels and Student Data:**
*   In row 1, I typed the exact headers provided in the question: `Student Name`, `Marks in Hindi out of 200`, `Marks in Maths out of 200`, `Marks in Finance out of 400`, `Total (out of 800) (T)`, `Percentage of Marks (P)`, `Division (D)`.
*   I manually filled rows 2 through 6 with the provided student names (Arvind, Ajay, Rehman, Roger, Samay, Baljeet) and their respective subject marks.

**2. Calculating Total (T):**
*   Clicked on cell **E2** (Total column for the first student, Arvind).
*   Typed the SUM formula: `=SUM(B2:D2)`
*   Pressed `Enter`. To apply this to all students, I clicked cell E2 again, grabbed the small square at the bottom right (fill handle), and dragged it down to cell E7.

**3. Calculating Percentage (P):**
*   Clicked on cell **F2** (Percentage column for Arvind).
*   Typed the formula: `=(E2/800)*100`
*   Pressed `Enter`. Dragged the fill handle down from F2 to F7 to apply the percentage calculation to all students.

**4. Calculating Division (D) using a Nested IF Formula:**
*   Clicked on cell **G2** (Division column for Arvind).
*   To satisfy all the given conditions (>=75, >=60, >=50, >=35, Fail), I typed the following nested IF formula exactly:
    `=IF(F2>=75, "1st with Distinction", IF(AND(F2>=60, F2<75), "1st Division", IF(AND(F2>=50, F2<60), "2nd Division", IF(AND(F2>=35, F2<50), "3rd Division", "Fail"))))`
*   Pressed `Enter`. Dragged the fill handle down from G2 to G7. Excel automatically evaluated the division for every student based on their calculated percentage.

**5. Final Formatting:**
*   Selected the entire table range, went to the Home tab, and clicked "All Borders" to make the grid visible. Made the header row bold.

---
<br>

**Q5: Use MS Outlook or any other email software to perform the following tasks. Write the sequence of steps that you have performed in different parts of this question.**

**Answer:**

**Sequence of Steps performed in MS Outlook:**

**a) Create a weekly meeting schedule for a group of 4 friends on the agenda “Group Study Schedule”. (Three consecutive weeks)**
1.  Opened MS Outlook and clicked on the **Calendar** icon located at the bottom left navigation pane.
2.  Clicked on the **"New Meeting"** button on the Home tab ribbon.
3.  In the "To" field, I typed the email addresses of my 4 friends.
4.  In the "Title" field, I typed exactly: **Group Study Schedule**.
5.  Set the start date and time for the first meeting. 
6.  Clicked on the **"Make Recurring"** (or Recurrence) button in the ribbon.
7.  In the dialog box, selected **"Weekly"**, checked the specific day of the week, and under the "Range of recurrence" section, selected "End after: **3 occurrences**". 
8.  Clicked OK, then clicked "Send".

**b) Write an email to your friends inviting them to attend the group study. Create your Signature and add it.**
1.  **Create Signature:** Went to **File** -> **Options** -> **Mail** -> **Signatures**. Clicked "New", named it "MySignature", and typed my full name and contact details. Set it as default for new messages, then clicked OK.
2.  **Write Email:** Clicked on the **"New Email"** button. The signature appeared automatically at the bottom of the blank email.
3.  Added the 4 friends' email addresses in the "To" field.
4.  Typed Subject: "Invitation for Group Study Session".
5.  Typed Body: "Hi friends, I am hosting a group study session this weekend to cover our upcoming assignment. Please let me know if you can attend."
6.  Clicked "Send".

**c) Create a message that should be sent to your friends inviting them to a discussion on the future of computing.**
1.  Clicked on the **"New Email"** button.
2.  Added friends' email addresses in the "To" field.
3.  Typed Subject: "Discussion on the Future of Computing".
4.  Typed Body: "Hello everyone, I would love to get your thoughts on where computing is heading in the next decade, especially regarding Quantum computing and AI. Let's discuss this over a video call tomorrow evening."
5.  Clicked "Send".

**d) Configure your mail account to delete all emails automatically from any junk mail account.**
1.  In the Outlook Inbox, I right-clicked on a spam email received from a junk sender.
2.  Hovered over **"Junk"** in the drop-down context menu and selected **"Junk E-mail Options..."**.
3.  Went to the **"Blocked Senders"** tab and ensured the junk email address was added to the list.
4.  In the same dialog box, navigated to the **"Options"** tab.
5.  Checked the critical box that says: **"Permanently delete suspected junk e-mail instead of moving it to the Junk E-mail folder."**
6.  Clicked OK. This completely bypasses the junk folder and permanently deletes spam immediately upon arrival.
