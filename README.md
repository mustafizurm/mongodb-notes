

# 🌐 জাভাস্ক্রিপ্ট ও MongoDB গাইড

একটি ইন্টার‌্যাক্টিভ ও শিক্ষনীয় প্রজেক্ট যা নতুনদের জন্য জাভাস্ক্রিপ্ট ও MongoDB এর প্রাথমিক থেকে অ্যাডভান্সড কনসেপ্ট শেখার পথ তৈরি করে।

---

## 📋 একনজরে

### 🛠️ বেসিক কনসেপ্টস (Topics)

1. [NoSQL vs SQL কি?](#nosql-vs-sql-কী)
2. [MongoDB কে NoSQL বলা হয় কেনো?](#mongodb-কে-nosql-বলা-হয়-কেনো)
3. [MongoDB কি? কেনো ব্যবহার করা হয়?](#mongodb-কী-কেনো-ব্যবহার-করা-হয়)
4. [ডাটাবেজ, কালেকশন, ডকুমেন্ট এর ধারণা](#ডাটাবেজ-কালেকশন-ডকুমেন্ট-এর-ধারণা)
5. [ডাটাবেজ মডেলিং](#ডাটাবেজ-মডেলিং-কি-কেনো-এবং-কিভাবে)
6. [লোকাল MongoDB ইনস্টলেশন](#লোকালভাবে-mongodb-install-করা)
7. [MongoDB Compass ব্যবহার](#mongodb-compass-ব্যবহার-করা)
8. [MongoDB Atlas ব্যবহার](#mongodb-atlas-cloud-version-ব্যবহার-করা)
9. [BSON & JSON](#bsonjson)
10. [ডাটাবেজ তৈরী করা](#ডাটাবেজ-তৈরী-করা)
11. [Collection তৈরী করা](#collection-তৈরী-করা)
12. [Document তৈরী করা](#document-তৈরী-করা)
13. [Query Operators](#mongodb-query-operators)
14. [Update Operators](#mongodb-update-operators)
15. [Aggregations](#mongodb-aggregations)
16. [Indexing & Search](#mkngodb-indexingsearch)
17. [Schema Design & Validation](#schema-design-এবং-validation)
18. [Node.js এর সাথে MongoDB কানেকশন](#node-js-এর-সাথে-mongodb-কানেক্ট-করা)

---

## 📝 কীভাবে ব্যবহার করবেন?

1. উপরের টপিক তালিকা থেকে আপনার প্রয়োজনীয় টপিক বেছে নিন।
2. প্রতিটি টপিক বিস্তারিতভাবে ব্যাখ্যা করা হয়েছে উদাহরণসহ।
3. নতুনদের জন্য সহজ ভাষায় এবং বাস্তব জীবনের প্রয়োগের মাধ্যমে বিষয়গুলো উপস্থাপন করা হয়েছে।

---

## 🔸 NoSQL vs SQL কী?
> ✨ তুলনামূলক আলোচনা ও ব্যবহার ক্ষেত্র ব্যাখ্যা করা হবে এখানে...

---

## 🔸 MongoDB কে NoSQL বলা হয় কেনো?
> ✨ MongoDB স্কিমাহীন এবং নন-রিলেশনাল হওয়ায় এটি NoSQL হিসেবে বিবেচিত...

---

## 🔸 MongoDB কী? কেনো ব্যবহার করা হয়?
> ✨ MongoDB হলো একটি ডকুমেন্ট-ভিত্তিক ডাটাবেজ, যা JSON স্টাইল ফরম্যাটে ডাটা স্টোর করে...

---

## 🔸 ডাটাবেজ, কালেকশন, ডকুমেন্ট এর ধারণা
> ✨ MongoDB তে ডাটাবেজের ভিতরে থাকে কালেকশন এবং তার ভিতরে ডকুমেন্ট...

---

## 🔸 ডাটাবেজ মডেলিং কি কেনো এবং কিভাবে?

### 📌 MongoDB Modeling কী?
mongodb modeling হলো ডেটা কিভাবে mongodb database এ স্টোর করা হবে তার একটি প্রক্রিয়া। mongodb স্কীমাহীন হওয়ায়, মডেলিং করা খুবই গুরুত্বপূর্ণ। কারণ মডেলিং এর সাহায্য খুব সহজে ডাটা রিড,অাপডেট,ডিলিট করা যায়।

### 📌 কতভাবে Modeling করা যায়?
mongodb modeling ২ ভাবে করা হয়।
- **Embedded (Denormalized)**  
- **Referenced (Normalized)**

### 📌 Embeded modeling কখন করা হয়? ?
- ডাটা ছোট ও সিম্পল হলে  
- একসাথে প্রদর্শন করতে হলে  
- রিড অপারেশন বেশি হলে

---

## 🔸 লোকালভাবে MongoDB Install করা
> ✨ Windows/macOS এ কিভাবে MongoDB ইনস্টল করতে হয় ধাপে ধাপে দেওয়া থাকবে...

---

## 🔸 MongoDB Compass ব্যবহার করা
> ✨ GUI tool হিসেবে MongoDB Compass কীভাবে ব্যবহার করবেন তা ব্যাখ্যা থাকবে...

---

## 🔸 MongoDB (Atlas) Cloud Version ব্যবহার করা
> ✨ ক্লাউড ভিত্তিক ডাটাবেজ ম্যানেজমেন্ট - MongoDB Atlas এর ব্যবহার...

---

## 🔸 BSON & JSON
> ✨ BSON হলো Binary JSON, MongoDB এর ডাটা সংরক্ষণের মাধ্যম...

---

## 🔸 ডাটাবেজ তৈরী করা
> ✨ MongoDB তে `use databaseName` কমান্ডের মাধ্যমে ডাটাবেজ তৈরী...

---

## 🔸 Collection তৈরী করা
> ✨ `db.createCollection('name')` এর মাধ্যমে কালেকশন তৈরী...

---

## 🔸 Document তৈরী করা
> ✨ `db.collection.insertOne({...})` কমান্ড দিয়ে ডকুমেন্ট ইনসার্ট...

---

## 🔸 MongoDB Query Operators
> ✨ `$eq`, `$gt`, `$lt`, `$in` সহ অন্যান্য অপারেটর ব্যাখ্যা সহ...

---

## 🔸 MongoDB Update Operators
> ✨ `$set`, `$unset`, `$inc`, `$push` ইত্যাদি ব্যাখ্যা সহ...

---

## 🔸 MongoDB Aggregations
> ✨ `$match`, `$group`, `$project`, `$lookup` এর ব্যবহার...

---

## 🔸 Mkngodb Indexing/Search
> ✨ Index কিভাবে তৈরি করতে হয়, এবং সার্চ অপটিমাইজেশন...

---

## 🔸 Schema Design এবং Validation
> ✨ Schema কিভাবে ডিজাইন করবেন এবং ডাটা Validate করবেন...

---

## 🔸 Node JS এর সাথে MongoDB কানেক্ট করা
> ✨ `mongoose` বা `mongodb` লাইব্রেরির মাধ্যমে কানেকশন উদাহরণসহ...

---

## 🚀 Getting Started

```bash
# Step 1: রিপোজিটরি ক্লোন করুন
git clone https://github.com/your-username/your-repo-name.git

# Step 2: প্রজেক্ট ডিরেক্টরিতে যান
cd your-repo-name
