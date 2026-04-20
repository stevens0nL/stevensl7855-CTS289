
---
**FRAME 1 TITLE**: "US2a - Job Detail"

1. HEADER: "[← Back]" "Job Detail" 

2. JOB INFO (375x200, light gray rect):
   "React Dashboard" (24pt)
   "TechCo needs modern admin dashboard..." (14pt, 3 lines)
   💼 TechCo | $800 fixed | 7 days | Remote
   "React, Node.js, Figma" (chips)

3. ACTION BUTTONS:
   Blue rect: "Apply Now" (150x50)
   Gray rect: "Save Job" (120x50)

**ANNOTATIONS**:
- "Apply → US2b Form"

---

**FRAME 2 TITLE**: "US2b - Apply Form" 

1. HEADER: "[← Job Detail]" "Send Proposal"

2. PREFILLED INFO:
   Rects: "John Doe" | "$45/hr" | "React, Node, Figma" (read-only)

3. PITCH TEXTAREA (355x120, dashed border):
   "Tell client why you're perfect..." (14pt)
   "Type your pitch (298/300 chars)" 

4. PORTFOLIO UPLOAD:
   Dashed rect: "📎 Upload Portfolio (PDF)"
   "No file selected"

5. SUBMIT BUTTON: "Send Proposal →" (green, 200x55)
   *(Add loading spinner rect nearby)*

**SUCCESS STATE** (duplicate frame):
   Green checkmark + "Proposal #247 sent to TechCo!"
   "Check Proposals tab for updates"

**ANNOTATIONS**:
- "Inline validation: green/red borders"
- "Success → Dashboard US3"
---
**FRAME TITLE**: "US3 - Proposals Dashboard"

1. HEADER: "[≡]" "My Proposals" "[+] New"

2. STATS CARD (375x80, blue rect):
   "5 Proposals Sent" (20pt) | "2 Interviews" (16pt green)
   "This Week ↑3" (14pt)

3. PROPOSAL CARDS x3 (355x100 each):
   Card 1: "React Dashboard" | 💼 TechCo | "Sent 2h ago" 
            [Badge: Pending] | "Follow up →"
   
   Card 2: "Logo Design" | 🎨 StartupX | "Interview Tomorrow"
            [Badge: Interview] | "Prep notes"
   
   Card 3: "FB Ads" | 📈 GrowthCo | "Hired! $600"
            [Badge: Won ✓] | "Start project"

4. FILTER TABS: "All" | "Pending" | "Won" (underlined)

5. BOTTOM BUTTONS:
   "New Proposal" (blue) | "Messages" (purple)

**ANNOTATIONS**:
- "Tap card → details/messages"
- "Badges consistent colors app-wide"
- "Filter persists"
