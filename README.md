#Day 14 of My LeetCode Journey – Problem: **Defanging an IP Address**

🧠 This was a fun and easy string manipulation challenge to warm up!

---

### 📘 Problem Statement:

You are given a valid **IPv4 address** as a string.
Your task is to return a *"defanged"* version of that IP address.

🔒 Defanging means replacing `"."` with `"[.]"`

---

### 🧪 Example:

📥 Input: `"1.1.1.1"`
📤 Output: `"1[.]1[.]1[.]1"`

📥 Input: `"255.100.50.0"`
📤 Output: `"255[.]100[.]50[.]0"`

---

### ✅ Python Code:

```python
class Solution:
    def defangIPaddr(self, address: str) -> str:
        return address.replace(".", "[.]")
```

---

### ⚙️ Concepts Used:

* Basic **string replace**
* Working with immutable strings in Python
* Clean and simple one-liner solution

🕒 Runtime: **43 ms**
✅ Status: **Accepted**
📸 Screenshot: (attached above ☝️)

---

### 🔍 What I Learned:

Even the simplest problems test your ability to read and apply constraints properly.
This was a great exercise in practicing **clean code** and recognizing when **built-in functions** make life easier!

---

Which one-liner in Python do you love the most? 💬

\#Day14 #LeetCode #Python #100DaysOfCode #StringManipulation #CodingPractice #BeginnerFriendly #ProblemSolving

