#🧾 Shopping Cart Billing System — Final Release

🎓 Software Testing Project | Boundary Value Analysis (5/5) • Confidence Testing • Equivalence Class Partitioning

#📖 Overview

This project demonstrates a realistic interactive billing system built using Gradio — designed to teach and apply the principles of Boundary Value Analysis (BVA), Confidence Testing, and Equivalence Class Partitioning (ECP) in software testing.

The app provides:

A professional, animated UI
A 5-point boundary testing suite
Dynamic discount computation
Session history tracking
Receipt generation (HTML → PDF)

#🧩 Features

✅ Boundary Value Analysis (5/5) — Auto-tests min, min+1, threshold, just-above, and max cases
✅ Confidence Testing — Ensures stable outputs across repeated runs
✅ Equivalence Partitioning — Groups similar inputs to test discount behavior
✅ Interactive GUI — Real-time computation with animated cards
✅ Receipt Generator — Printable HTML/PDF bills
✅ Session History — Tracks multiple test cases with timestamps

#💻 Tech Stack
Component	Technology
Language	Python
Framework	Gradio
Libraries	Pandas, UUID
Platform	Google Colab / Jupyter Notebook
License	MIT License
🚀 Run on Google Colab

#Open the notebook shopping_cart_billing_system.ipynb

Run this cell to install dependencies:
!pip install gradio pandas
Execute all cells to launch the web app
The Gradio interface will appear directly in Colab

#🧮 Discount Rules
Condition	Discount
Bill > 500 and Guest	5%
Bill > 500 and Member	10%
Payment via HBL	+5% bonus
Otherwise	No discount
#🧠 Example Test Cases
Bill	Type	Payment	Discount	Final
500	Guest	Other	0%	500
501	Guest	Other	5%	475.95
600	Member	HBL	15%	510
10000	Member	HBL	15%	8500
2	Guest	Other	0%	2
#🧑‍💻 Author

Muhammad Abdullah
Roll No: F22BSEEN1M01131 | Semester: 7th (4M)
Department of Software Engineering
The Islamia University of Bahawalpur

#📜 License

This project is licensed under the MIT License — free for use, learning, and modification.

#🌟 Preview

🎨 Gradio-based interactive app demonstrating software testing techniques with real-time calculations and visual feedback.
