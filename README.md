Shamir Secret Recovery
A C++ project that decodes base-encoded polynomial roots and reconstructs the secret constant term c using Lagrange Interpolation. This solution is built as part of the Catalog Placements Assignment — based on a simplified version of Shamir’s Secret Sharing algorithm.

📝 Problem Summary
You are given a set of encoded polynomial roots (x, y), where y is encoded in various bases. Your task is to:

Parse the JSON input.

Decode all y values into base-10.

Reconstruct the original polynomial.

Extract and print the constant term c.

📌 Approach
Read JSON test cases.

Decode all Y-values using their specified base.

Use Lagrange Interpolation to recover the constant term c.

Output the result for both test cases.

📂 Files
main.cpp: Core logic implemented in C++.

testcase1.json: First test input.

testcase2.json: Second test input.

README.md: Project overview and instructions.

🚀 How to Run
Clone the repo

Compile and run the C++ file in your preferred IDE or terminal:

bash
Copy
Edit
g++ main.cpp -o secret
./secret
✅ Output
Prints the secret value c for both test cases.

💡 Example
For input:

json
Copy
Edit
"2": {
  "base": "2",
  "value": "111"
}
The decoded root becomes (2, 7).
