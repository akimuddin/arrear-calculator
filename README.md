# Automatic Arrear Salary Calculator - 2026

A clean, browser-based web tool built to calculate arrear salary and allowances under the 2026 pay scale and generate an A4-ready official bill report.

Key Features

Automatic Grade & Slab Calculation: Estimates the 2026 basic salary (with increment) at 40% for Grades 1–9 and 50% for Grades 10–20 based on the 2015 pay scale, while allowing manual override when needed.

Dynamic House Rent Calculation:

45% for basic salary below 16,000.

40% for basic salary between 16,000 and 35,500, with a minimum floor of 7,000/-.

35% for basic salary of 35,501 and above.

Exact Paisa & Bangla Word Conversion: Preserves decimal/paisa values without premature rounding and automatically converts the final net payable amount into Bangla words (টাকা ও পয়সা).

Arrear & Deduction Breakdown: Calculates arrears for July, August, and September 2026, accounts for special benefit deduction (15%), excess house rent deduction (overdrawn), and a 10/- revenue stamp duty to show the final Net Payable.

A4 Print-Ready Bill: Clicking "অফিশিয়াল বিল প্রিন্ট করুন" hides the input form and formats the report cleanly for A4 printing or saving as PDF.

Tech Stack

HTML5

CSS3 (including @media print rules for A4 layout)

JavaScript & jQuery (v3.7.1)

Google Fonts (Hind Siliguri)

How to Use

Open index.html (or your HTML file) in any modern web browser.

Enter the Name and Designation / Workplace (optional) and select the current Grade (2015 scale).

Input the basic salary as of 30-06-2026, the current pay step as of 01-07-2026, and the 2026 scale basic salary.

Click ক্যালকুলেট to generate the comparison table and arrear bill below.

Click অফিশিয়াল বিল প্রিন্ট করুন to print the report or save it as a PDF.

Hosting on GitHub Pages

Since this is a static HTML/CSS/jQuery application, you can host it directly with GitHub Pages:

Push your HTML file and README.md to your GitHub repository.

Go to your repository's Settings tab and open Pages from the left sidebar.

Select the main branch as the source and click Save.

Once published, share the generated GitHub Pages URL with your team.
