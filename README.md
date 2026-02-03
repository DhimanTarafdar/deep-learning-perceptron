#  Deep Learning Journey: Fundamentals & Perceptron Practice

এই প্রজেক্টে আমি ডিপ লার্নিংয়ের একদম বেসিক থেকে শুরু করে পারসেপট্রন (Perceptron) ব্যবহার করে একটি বাস্তব ক্লাসিফিকেশন প্রবলেম সমাধান করেছি।

---

##  Project Overview
মেশিন লার্নিং এবং ডিপ লার্নিংয়ের মধ্যে মূল পার্থক্যগুলো বোঝার মাধ্যমে আমার যাত্রা শুরু হয়েছে। এই রিপোজিটরিতে আমি আলোচনা করেছি কীভাবে একটি নিউরাল নেটওয়ার্ক মানুষের মস্তিষ্কের মতো কাজ করে এবং কীভাবে গাণিতিক হিসাবের মাধ্যমে ডাটা থেকে সিদ্ধান্ত নেয়।

---

## Concepts Covered

### 1. ML vs DL (The Core Difference)
- **Automatic Feature Engineering:** কেন ডিপ লার্নিং-এ ম্যানুয়ালি ফিচার বের করতে হয় না।
- **Data Scaling:** বড় ডাটা সেটে ডিপ লার্নিংয়ের পারফরম্যান্সের শ্রেষ্ঠত্ব।

### 2. Neural Network Building Blocks
- **Weights ($W$):** প্রতিটি ইনপুটের গুরুত্ব বা Importance নির্ধারণ করা।
- **Bias ($b$):** মডেলকে নমনীয়তা দেওয়া এবং ডিসিশন বাউন্ডারি শিফট করা।
- **Weighted Sum:** ইনপুট এবং ওয়েটের গাণিতিক যোগফল বের করা।

### 3. Activation Functions (The Magic Element)
আমরা কেন এবং কখন বিভিন্ন ফাংশন ব্যবহার করি:
- **Step Function:** বাইনারি অন/অফ সুইচ হিসেবে কাজ করে।
- **Sigmoid:** ডাটাকে ০ থেকে ১ এর মধ্যে নিয়ে আসে (Binary Classification)।
- **ReLU:** বর্তমানে হিডেন লেয়ারের জন্য সবচেয়ে জনপ্রিয় (Non-linearity যোগ করার জন্য)।
- **Tanh:** ডাটাকে -১ থেকে ১ এর মধ্যে রাখে।

---

## Practical Implementation: Perceptron on Iris Dataset
আমি Scikit-Learn ব্যবহার করে একটি **Single Layer Perceptron** মডেল তৈরি করেছি যা সফলভাবে **Iris-Setosa** ফুলকে ক্লাসিফাই করতে পারে।

### **Key Steps in the Code:**
1. **Data Preprocessing:** Label Encoding এবং Feature Scaling।
2. **Standardization:** `StandardScaler` ব্যবহার করে ডাটা নরমাল করা।
3. **Training:** Perceptron অ্যালগরিদম ব্যবহার করে মডেলকে ট্রেইন করা।
4. **Evaluation:** মডেলের কার্যকারিতা যাচাই করা।

### **Results:**
- **Training Accuracy:** 100%
- **Test Accuracy:** 100%
- মডেলটি সম্পূর্ণ নির্ভুলভাবে **Linearly Separable** ডাটা শনাক্ত করতে সক্ষম হয়েছে।

---

