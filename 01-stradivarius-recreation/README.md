# Project 1: Stradivarius E-commerce Recreation

## 📌 Project Overview
A high-fidelity recreation of a Stradivarius promotional campaign. This project demonstrates the ability to convert complex, asymmetric fashion layouts into bulletproof, responsive email code using MJML.

## 🛠 Technical Features
* **Asymmetric Grid Logic:** Utilized `mj-group` to maintain a non-stacking 66/34% layout on mobile, preserving the "lookbook" aesthetic.
* **Responsive Typography:** Implemented CSS Media Queries via `<mj-style>` to dynamically scale headers from 50px (desktop) to 34px (mobile) to prevent text wrapping.
* **Outlook Optimization:** Used pixel-based widths and `mj-column` border attributes instead of standard CSS borders to ensure container stability in Outlook 2016-2019.
* **Performance:** Minified HTML output to ensure the file stays under the 102KB Gmail clipping threshold.

## 🚀 Key Learning
Managing "gutter" spacing (white space between images) in a red-background environment required precision padding on nested columns to ensure a seamless "infinite" background look across all email clients.
