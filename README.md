# BenefitGraph

### One Person → 20 Government Schemes

BenefitGraph is a citizen-focused platform that helps people find government schemes based on their personal details and understand the steps required to access them.

The main idea is to go beyond simply showing a list of schemes. BenefitGraph tries to show **which benefits may be relevant, what documents are missing, whether another scheme or enrollment is required, and what the user should do next.**

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

BenefitGraph takes basic information about a citizen, such as:

- Location
- Age
- Occupation
- Education
- Income
- Family/household details
- Accessibility requirements
- Existing benefits
- Available documents

The system uses this information to create a **benefit graph** instead of only displaying scheme names.

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

Instead of simply showing both schemes, BenefitGraph creates a possible pathway:

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

BenefitGraph is designed to allow authorized users to add new schemes and update existing scheme information without rebuilding the complete application.

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
        ↓
Updated Citizen Pathways
