# CSC-289 Wireframing Assignment - Task 2.1 & 2.2 COMPLETE

**Student Name**: laila s
**Date**: today
**Assignment**: Practice User Story Wireframing + AI Prompt Log  

---

## 📋 Task 2.1: Practice User Story Selection

### Practice User Story (Exact Copy)
> **As a student**, I want to **view my course grade breakdown with category weights and scores** so that **I can understand how my final grade is calculated**.  
> 
> **Acceptance Criteria**:
> - Show overall course grade (percentage and letter grade)  
> - List all grading categories (e.g., Assignments 40%, Quizzes 30%, Projects 30%)
> - Show current score for each category  
> - Display points earned vs. points possible
> - Include a visual representation (chart or progress bars)

---

##  Task 2.2: AI-Assisted Brainstorming

###  Step 1: My Exact AI Prompt (Copy to your AI Prompt Log)
"I'm creating a wireframe for a grade breakdown interface. Here's the user story:

Practice User Story: As a student, I want to view my course grade breakdown with category weights and scores so that I can understand how my final grade is calculated.

Acceptance Criteria:

Show overall course grade (percentage + letter grade)
List grading categories (Assignments 40%, Quizzes 30%, Projects 30%)
Show current score per category (earned/possible points)
Visual representation (progress bars or chart)
Mobile-responsive
Give me:

Recommended 2-3 screen layout (header, main content, nav)
Specific Google Stitch components to use (exact shapes/text)
Annotation examples for interactions
Design rationale paragraph I can adapt
Mobile considerations"

# AI Response Summary (Key Takeaways)
SCREEN 1:
```
+------------------------------------------+
|  [←]   CSC-289: Web Development          |
|        87% (B+)              [Refresh]   |
+------------------------------------------+
|                                          |
|         +------------+                   |
|        /   87%      \                    |
|       |    (B+)      |    Overall: 87/100|
|        \            /     13 points away |
|         +------------+     from A       |
|                                          |
+------------------------------------------+
|  ASSIGNMENTS (40%)          92/100  A    |
|  [===================----]  92%     [>]  |
+------------------------------------------+
|  QUIZZES (30%)              85/100  B    |
|  [==================-----]  85%     [>]  |
+------------------------------------------+
|  PROJECTS (30%)             78/100  C    |
|  [===============-------]  78%     [>]   |
+------------------------------------------+
|                                          |
|  WHAT'S NEXT                             |
|  Final Exam (20%) - Not yet available   |
+------------------------------------------+
|                                          |
|  [🏠 Home]  [📊 Grades]  [👤 Profile]     |
|                                          |
+------------------------------------------+
```
SCREEN 2: Category Detail ├── HEADER: Back + "Assignments (40%) 92/100" └── MAIN: Itemized table + progress bar

STITCH COMPONENTS:

Progress Bar (#4CAF50, 87% width)
Pie Chart (87% green/13% red)
Badge ("40%", green)
Card Container (rounded, 20px padding)


### AI Tool Used

- [ ] ChatGPT
- [ ] Claude
- [ ] Blackbox AI
- [ ] Other: ___________

### Key AI Suggestions (Summary)

1. **2-screen layout**: Overview screen with overall grade + category list, Detail screen for individual categories
2. **Header placement**: Overall grade (87% B+) prominently displayed in header
3. **Progress bars**: Visual progress indicators for each category showing earned/possible points
4. **Card-based layout**: Each category as a card with name, weight %, score, and progress bar
5. **Bottom navigation**: Standard mobile navigation with Home, Grades, Profile tabs
6. **Pie/Donut chart**: Visual representation of overall grade and category weights

---

