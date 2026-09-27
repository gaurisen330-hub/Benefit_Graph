# Labh-Path

### One Person → 20 Government Schemes

Labh-Path is a citizen-focused platform that helps people find government schemes based on their personal details and understand the steps required to access them.

The main idea is to go beyond simply showing a list of schemes. Labh-Path tries to show **which benefits may be relevant, what documents are missing, whether another scheme or enrollment is required, and what the user should do next.**

---

## Problem

There are many government schemes for different categories of citizens. However, finding a suitable scheme is not always enough.

A citizen may still have questions like:

- Am I eligible for this scheme?
- Which documents are required?
- What should I apply for first?
- Is another scheme or enrollment required?
- Which benefits can I access after completing one step?
- What should I do next?

Searching and checking schemes one by one can make this process confusing.

---

## Our Solution

Labh-Path takes basic information about a citizen, such as:

- Location
- Age
- Occupation
- Education
- Income
- Family/household details
- Accessibility requirements
- Existing benefits
- Available documents

The system uses this information to create a **Labh-Path** instead of only displaying scheme names.

```text
Citizen
   ↓
Eligibility Check
   ↓
Benefit Graph
   ↓
Missing Documents
   ↓
Scheme Dependencies
   ↓
Priority
   ↓
Personalized pathway

---

## Example

Suppose a citizen is potentially eligible for two government schemes.

### Scheme A

Eligible ✓

Missing:
- Income Certificate

### Scheme B

Eligible ✓

Requires:
- Scheme A Enrollment

Instead of simply showing both schemes, Labh-Path creates a possible pathway:

```text
Citizen
   ↓
Get Income Certificate
   ↓
Apply for Scheme A
   ↓
Complete Scheme A Enrollment
   ↓
Scheme B becomes actionable
   ↓
Apply for Scheme B


---

## Main Features

- 👤 Citizen Profile
- 🧠 Eligibility Checking
- 🕸️ Benefit Dependency Graph
- 📄 Missing Document Detection
- 🔗 Scheme Dependency Mapping
- 🎯 Benefit Prioritization
- 🛣️ Personalized Benefit Pathway
- 🤖 AI-based Assistance
- 🌐 Multilingual Support
- 📊 Application Tracking

---

## 🔄 Scheme Management & Updates

Government schemes and their eligibility requirements can change over time. New schemes may also be introduced.

Labh-Path is designed to allow authorized users to add new schemes and update existing scheme information without rebuilding the complete application.

The admin can:

- Add new government schemes
- Edit scheme details
- Update eligibility criteria
- Update required documents
- Update income or location requirements
- Add or modify scheme dependencies
- Activate or deactivate schemes

### Update Flow

```text
New / Updated Scheme
        ↓
    Admin Panel
        ↓
  Update Scheme Data
        ↓
 Update Eligibility Rules
        ↓
   Benefit Graph


---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- Python
- Flask

### Database
- SQLite

### AI / Intelligent Processing
- Python
- NLP
- RAG
- LLM

### Benefit Graph
- NetworkX
- JavaScript-based graph visualization

### Development Tools
- Git
- GitHub
- VS Code
        ↓
Updated C

---

## 🔮 Future Scope

Labh-Path can be further improved and expanded with the following features:

- Integration with verified government scheme data and official APIs
- Automatic updating of newly launched or modified schemes
- Support for more Indian regional languages
- Voice-based citizen assistance
- Mobile application
- Real-time application status and notifications
- Digital document verification
- Offline or low-connectivity support
- Personalized notifications for newly available benefits
- Advanced benefit and dependency graph analysis
- Integration with more government digital services

The long-term goal is to make Labh-Path a continuously updated platform that helps citizens not only discover government benefits, but also understand and complete the steps required to access them.




itizen Pathways
