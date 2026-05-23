Step-by-Step Process: Building a simple agent Promise Oy Employee Support Assistant in Microsoft Copilot Studio

This process shows the steps taken using Microsoft Copilot Studio. It shows how to create a simple employee support assistant for Promise Oy that can answer questions about:

* Office Hours
* IT Contact Details
* Company Portal Access

What I built

My AI assistant will answer questions like:

Employee Question	Assistant Response
“What time does the office open?”	Office hours
“How do I contact IT?”	IT support details
“How do I access the company portal?”	Portal access instructions

STEP 1 — Open Copilot Studio

Go to:

Microsoft Copilot Studio

Sign in with your Microsoft account.

STEP 2 — Create a New Agent

1. Click Create

2. Select New Agent

Agent Name	Promise Oy Employee Assistant
Description	Helps employees with office information and IT support

STEP 3 — Add the Agent Instructions

Then click Save.

STEP 4 — Open the Topics Section

After the agent is created:

1. Look at the left menu
2. Click Topics
3. Click + New Topic

STEP 5 — Create Topic 1: Office Hours

Topic Name

Office Hours

Add Trigger Phrases

Add these 3 trigger phrases:

1. What are the office hours?
2. When does the office open?
3. What time does Promise Oy close?

Add the Response

Click the message node and type:

“Promise Oy office hours are Monday to Friday, 8:00 AM to 5:00 PM.”

STEP 6 — Create Topic 2: IT Contact Details

Click + New Topic again.

Topic Name

IT Support

Add Trigger Phrases

1. How do I contact IT?
2. What is the IT support email?
3. I need technical support

Add the Response

“You can contact Promise Oy IT Support at:
itsupport@promise.oy.com or call +358 1234 5678.”

STEP 7 — Create Topic 3: Company Portal Access

Click + New Topic again.

Topic Name

Company Portal Access

Add Trigger Phrases

1. How do I access the company portal?
2. Where is the employee portal?
3. I cannot log into the company portal

Add the Response

“Employees can access the company portal at:
https://portal.promise.oy.com using their company email and password.”

STEP 8 — Save All Topics

After creating each topic:

1. Click Save

STEP 9 — Test in the Test Canvas

On the right side of Copilot Studio, open the Test Your Agent panel.

Type each question one by one.

Test Example 1 — Office Hours

Question:

What are the office hours?

Expected Answer:

promise Oy office hours are Monday to Friday, 8:00 AM to 5:00 PM.

Test Example 2 — IT Support

Question:

How do I contact IT?

Expected Answer:

You can contact Promise Oy IT Support at:
itsupport@promise.oy.com or call +358 1234 5678.

Test Example 3 — Company Portal

Question:

How do I access the company portal?

Expected Answer:

Employees can access the company portal at:
https://portal.promise.oy.com using their company email and password.

What my Agent Can Do

My Promise Oy Employee Support Assistant can now:

* Answer employee FAQs
* Respond automatically using trigger phrases
* Help employees find IT support
* Guide employees to the company portal
* Be tested directly inside Copilot Studio
* <img width="1915" height="849" alt="Screenshot 2026-05-22 053745" src="https://github.com/user-attachments/assets/6b659f06-cc6e-46f0-8e8e-3bf3b1219683" />
<img width="1765" height="750" alt="Screenshot 2026-05-22 050321" src="https://github.com/user-attachments/assets/3e8b49ca-6396-4fa7-adfb-931d5a64804f" />
<img width="1906" height="715" alt="Screenshot 2026-05-22 051734" src="https://github.com/user-attachments/assets/bc7e0fe0-2f68-4a84-9289-139d2f210d21" />
<img width="1803" height="809" alt="Screenshot 2026-05-22 050651" src="https://github.com/user-attachments/assets/bb582c34-ea01-489e-86ac-34ff42934206" />
