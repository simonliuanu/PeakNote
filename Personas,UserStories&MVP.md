### **Personas**

#### **Persona 1: Corporate Team Manager**

- **Name**: Clark
  
- **Age**: 38
  
- **Occupation**: Project Manager
  
- **Needs**: Efficiently record meeting content and quickly forward it to team members.
  
- **Pain Points**: Manually taking meeting minutes is time-consuming, task assignments are difficult to achieve.
  
- **PeakNote Value**: Automatically generates action items after meetings, improving team execution efficiency. Provides a preview for user to review, modify, and confirm the meeting minutes before forwarding them.
  

#### **Persona 2: Startup Founder**

- **Name**: Wang
  
- **Age**: 32
  
- **Occupation**: CEO of a Startup
  
- **Needs**: Quickly capture key information from multiple meetings and avoid missing critical decisions.
  
- **Pain Points**: Frequent meetings make it hard to manually organize discussion points, and efficient collaboration is essential.
  
- **PeakNote Value**: Provides automated meeting summaries to help review key takeaways. Allows seamless sharing of finalized meeting minutes with Teams colleagues.
  

#### **Persona 3: Executive Assistant**

- Name: Sarah
  
- Age: 35
  
- Occupation: Executive Assistant to C-Suite Leadership
  
- Needs: Efficiently organize and distribute meeting summaries to executives
  
- Pain Points: Manually creating and sending meeting notes to multiple stakeholders is time-consuming and prone to inconsistency
  
- PeakNote Value: Delivers polished meeting summaries with 'Share' button to executives' Outlook inboxes, saving time and ensuring consistent communication. Users can download meeting summaries in PDF or Word format or directly print them with 'Print' button as well.
  

#### Persona 4: Sales Manager

- Name: Miguel
  
- Age: 42
  
- Occupation: Regional Sales Manager
  
- Needs: Track customer conversations and commitments across multiple client meetings
  
- Pain Points: Difficult to document all important details from numerous client meetings while maintaining customer relationships
  
- PeakNote Value: Receives comprehensive meeting summaries with 'Client Meeting' template immediately after client meetings with action items. Provides the ability to share meeting minutes through Outlook to clients.
  

#### Persona 5: HR Director

- Name: Priya
  
- Age: 45
  
- Occupation: Human Resources Director
  
- Needs: Document important details from employee meetings and performance reviews
  
- Pain Points: Struggles to maintain thorough records of sensitive conversations while being fully present during meetings
  
- PeakNote Value: Gets secure, confidential meeting summaries delivered to her Outlook inbox that can be easily filed with employee records.
  

#### Persona 6: IT Administrator

- Name: Derek
  
- Age: 39
  
- Occupation: IT Systems Administrator
  
- Needs: Implement organization-wide meeting solutions that work with existing infrastructure
  
- Pain Points: New software tools often create integration challenges and security concerns
  
- PeakNote Value: PeakNote's seamless Outlook integration and Microsoft SSO login works together, minimizing security risks and deployment challenges. 
  

#### Persona 7: Compliance Officer

- Name: Amara
  
- Age: 41
  
- Occupation: Regulatory Compliance Officer
  
- Needs: Maintain accurate records of compliance meetings and discussions
  
- Pain Points: Missing or incomplete meeting documentation can lead to regulatory issues
  
- PeakNote Value: Delivers meeting mintues from PeakNote to Outlook after meeting, minutes can be easily archived for audit purposes and compliance documentation. Ensures regulatory requirements by allowing a structured  preview before editing and shareing.
  

---

### **User Stories & Scenarios**

#### **User Story 1: Automatic Meeting Summary**

**As a** project manager,  
**I want to** receive an automatically generated meeting summary,  
**so that** I can quickly review key points without going through the entire recording.

**Scenario:**  
Zheng holds a weekly team meeting where important decisions are made. After the meeting, Zheng uses PeakNote to generate a concise summary, including action items and major discussions. Zheng can quickly scan the summary to ensure nothing is missed.

#### **User Story 2: Task Assignment Based on Speakers’ Inputs**

**As a** team leader,  
**I want to** have tasks automatically assigned to speakers based on their statements,  
**so that** I can streamline the delegation process and improve accountability.

**Scenario:**  
During a product planning meeting, team members discuss their responsibilities. Zheng usese PeakNote to identify the tasks mentioned and assigns them to the relevant team members, reducing manual effort for the manager.

#### **User Story 3: Post-Meeting Transcription**

**As a** remote team member,  
**I want to** access a transcript of the meeting after it ends,  
**so that** I can review the discussion even if I joined late or missed part of it.

**Scenario:**  
Lucy, working from a different time zone, joins the meeting 15 minutes late. After the meeting ends, Lucy opens PeakNote to generates a meeting minutes, allowing her to catch up on everything that was discussed and action items assigned to her.

#### **User Story 4: Post-Meeting Summary Preview and Editing**

**As an** executive assistant,  
**I want to** preview the generated meeting minutes in markdown format,  
**so that** I can make necessary modifications before finalizing the summary.

**Scenario:**  
After a high-stakes meeting, Sarah accesses the A4 portrait preview of the generated meeting summary. She quickly edits key points using the toolbar above the A4 portrait and confirms formatting before finalizing it as a document to distribute to executives.

#### **User Story 5: Meeting Summary Export and Sharing**

**As a** sales manager,  
**I want to** download the finalized meeting summary in PDF format or share it with Teams colleagues,  
**so that** I can ensure proper documentation and collaboration.

**Scenario:**  
After an important client meeting, Miguel finalizes the meeting summary with 'Client Meeting' template and chooses to download a PDF version for documentation. Additionally, he shares it directly with his sales team via Outlook in Teams to keep everyone aligned.

#### **User Story 6: Link‑Based Summary Generation**

**As a** busy team lead,  
**I want to** paste a Microsoft Teams meeting link into PeakNote and instantly receive a summary,  
**so that** I can quickly obtain the summary in a convenient and error-free way.

**Scenario:**  
John Smith pastes a meeting URL into PeakNote. The tool retrieves the recording and returns a structured summary of discussion points, decisions, and action items within minutes, enabling him to move on quickly.

#### **User Story 7: Multi‑Template Summaries**

**As a** project manager,  
**I want to** generate one‑click summaries in different formats (Standard, Client, Scrum, Daily Stand‑up),  
**so that** each audience receives a record tailored to their needs.

**Scenario:**  
Emily hosts various meetings. After each session, she selects “Client,” “Scrum,” “Daily Stand‑up,” or “Standard” in PeakNote. The system instantly outputs a pre‑formatted summary, eliminating manual re‑editing.

---

## 1. Core Value Proposition

**Problem Solved by PeakNote**: Post-meeting documentation and summarization are time-consuming and prone to missing critical information.  
**Core Value**: Transforms meeting recordings into structured summaries, saving time for professionals and enhancing team collaboration efficiency.

## 2. Target Users

- Users who frequently attend meetings
  
- Small team leaders and project managers
  
- Professionals who need to track decisions and action items
  

## 3. Core Features (Simplified Version)

### Essential Features (Phase 1)

- **Upload Meeting Links**: Supports Teams meeting links
  
- **Template Selection**: Initially supports four meeting types
  
- **AI Summary Generation**: Extracts key points and action items
  
- **View & Download**: Print, PDF export, and email sharing
  

### Deferred Features (Future Iterations)

- ~~Complex meeting history management~~ (replaced with simple list view)
  
- ~~Historical meeting record search functionality~~ (not implemented in MVP phase)
  
- ...
  

## 4. Streamlined User Flow

1. Conduct your meeting in Teams
2. Upload meeting link
  
3. Wait for processing notification
  
4. View and download summary
  

## 5. Rapid Iteration Plan Post-Launch

Based on early customer feedback, priority will be given to:

1. Summary quality optimization
  
2. User interface improvements
  
3. Adding additional features requested by customers
