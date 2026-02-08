Protein Gap Assistant – V1-
------------------------------------------------------------------------

A minimal, protein-first Progressive Web App designed to help users consistently hit their daily protein target with the least possible mental effort.

This app intentionally avoids being a full nutrition tracker.

🎯 Product Goal
------------------------------------------------------------------------

Help users answer one question per day:

“How much protein do I still need to eat today?”

🧠 Core Philosophy
------------------------------------------------------------------------

Consistency beats precision

Fewer decisions → better adherence

Protein is the primary nutritional lever for physique improvement

If daily protein intake is adequate, most other nutritional factors naturally fall into place.

✅ V1 Scope (Locked)
------------------------------------------------------------------------
Included
-------------------------
Protein goal calculation based on bodyweight and activity level

Text-based meal logging

Automatic protein calculation from logged foods

Daily protein progress and remaining amount

Simple food basket for quick protein gap suggestions

Installable Progressive Web App (PWA)

Explicitly Excluded
-------------------------

The following are intentionally out of scope for V1:

Calories

Carbohydrates

Fats

Amino acids (BCAA, EAA, leucine, etc.)

Body types (skinny-fat, ectomorph, endomorph)

Height, age, or climate-based logic

Image recognition

Voice input

AI-generated recommendations

Full food databases

All excluded items may be considered only after V1 is shipped and validated.



🧮 Protein Goal Calculation (Final)
----------------------------------------------------------------------------------------------------------
Formula
Daily Protein (grams) = Bodyweight (kg) × Activity Multiplier

Activity Multipliers
Activity Level	Multiplier
Sedentary	1.6
Moderate	1.8
Heavy Training	2.0

Default selection: Moderate (1.8)

Users may manually change activity level at any time

Rounding Rule

To reduce cognitive load, the final protein target is rounded to the nearest 5 grams.

Example:

Weight: 70 kg
Activity: Moderate (1.8)

Raw calculation: 70 × 1.8 = 126 g
Final target: 125 g/day

🔍 Transparency Policy
---------------------------------------------------------------------------------------------------
The app always shows the formula used

No hidden logic or “AI guessing”

Users can see and override their protein target

Trust is built through clarity, not complexity.

🧩 Product Promise (V1)
-----------------------------------------------------------------------------------------
“Log what you eat.
See how much protein is left.
Get a simple suggestion to close the gap.”

🚀 Technology Stack
Frontend
-----------------------------------------
React + TypeScript

Progressive Web App (PWA)

Responsive, mobile-first UI

Backend
------------------------------------------
Node.js

Express

TypeScript

PostgreSQL

Prisma ORM

JWT-based authentication

🔒 Scope Freeze Notice

V1 scope is frozen.
--------------------------------------------------------------------------------------------------------------------
Any new ideas must be written in a separate V2 Ideas section and must not affect V1 implementation or timelines.

Shipping a focused product is the priority.

📌 Status

Protein Gap Assistant – V1
In active development.
