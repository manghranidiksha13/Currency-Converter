# Currency-Converter
A simple Python tool that fetches real-time foreign exchange rates using the Fixer API and converts an amount from one currency to another.

**Product Goal**: To provide a lightweight, easy-to-use currency conversion script that allows users to get accurate, real-time exchange values with minimal setup.

**Key Decision**: The design uses Fixer.io’s EUR-based exchange rate system. All conversions are first normalized to EUR to ensure consistent and reliable results across all supported currencies.

**Safety Workflow**: Input validation is used to ensure the user enters valid numbers and currency codes. The script gracefully handles API errors or missing currencies to avoid incorrect conversions.

**Outcome:** A clean, beginner-friendly Python program demonstrating API integration, data handling, and real-time currency conversion ideal for learning or extending into larger financial applications.
