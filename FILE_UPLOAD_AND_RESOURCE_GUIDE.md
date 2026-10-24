# 📥 IELTS PrepMaster Ultimate — File Upload & Resource Acquisition Guide

> **ডকুমেন্ট সংস্করণ:** 3.0 Detailed Resource Roadmap  
> **প্রস্তুতকারক:** Md. Mustak Khan | Chittagong, Bangladesh  
> **যোগাযোগ:** mustakkhan.bmb.cu@gmail.com | +880 1308-584945  
> **উদ্দেশ্য:** ওয়েবঅ্যাপটিকে একটি স্বয়ংসম্পূর্ণ, প্রিমিয়াম ও অফলাইন IELTS লার্নিং প্ল্যাটফর্মে রূপান্তর করার জন্য প্রয়োজনীয় প্রতিটি ফাইলের বিবরণ, ফোল্ডার লোকেশন ও সংগ্রহের সঠিক উৎস।

---

## 🧭 ১. এক নজরে ডিরেক্টরি ম্যাপ (Target Directory Map)

```
f:/Mustak/07_IELTS_Preparation/IELTS/
│
├── images/
│   ├── icon-512.svg                      [✅ তৈরি করা হয়েছে - PWA Icon]
│   └── listening/
│       └── audio/                        [⚠️ তৈরি করতে হবে - এখানে MP3 ফাইল বসবে]
│           ├── cam19_test1_part1.mp3
│           └── ...
│
├── cambridge_app/
│   └── data/
│       ├── cambridge_tests_data.js       [✅ ক্যামব্রিজ ১০-১৯ টেস্ট সংরক্ষিত]
│       └── cambridge_20.json             [⚠️ ক্যামব্রিজ ২০ আসল কপি পেলে যোগ হবে]
│
├── vocab_data/
│   ├── all_vocab.json                    [✅ ২,৯৪৯ শব্দ সংরক্ষিত]
│   ├── cambridge_19_vocabulary.json      [✅ সংরক্ষিত]
│   ├── cambridge_20_vocabulary.json      [⚠️ ক্যামব্রিজ ২০ রিলিজের পর যোগ হবে]
│   └── grammar_drills.json               [⚠️ ইন্টারেক্টিভ গ্রামারের জন্য]
│
├── 01. Cambridge Tests/                  [✅ ক্যামব্রিজ ১০-২০ এর ২২টি PDF সংরক্ষিত]
├── 03. Writing/                          [⚠️ নতুন Band 9 Sample PDF যোগ করা যাবে]
└── 04. Speaking/                         [⚠️ Makkar Speaking Prediction PDF যোগ হবে]
```

---

## 📚 ২. ক্যাটাগরিভিত্তিক ফাইল আপলোড ও সংগ্রহের বিস্তারিত গাইড

---

### ক্যাটাগরি ১: Authentic Listening Audio Files (.mp3)
* **অগ্রাধিকার:** 🔴 **HIGH (সর্বোচ্চ)**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/images/listening/audio/`
* **কেন প্রয়োজন:** বর্তমানে ওয়েবঅ্যাপে ব্রাউজারের সিন্থেসাইজড ভয়েস (TTS) দিয়ে লিসেনিং চলছে। কিন্তু ক্যামব্রিজের অফিসিয়াল পরীক্ষায় ব্রিটিশ, অস্ট্রেলিয়ান, কানাডিয়ান এবং আমেরিকান বিভিন্ন অ্যাকসেন্ট থাকে। আসল অডিও ফাইল যুক্ত করলে প্র্যাকটিস হবে ১০০% বাস্তব পরীক্ষার মতো।

#### ফাইল নামকরণের স্ট্যান্ডার্ড ফরম্যাট (Naming Convention):
অডিও ফাইলগুলো নিচের ফরম্যাটে নাম দিয়ে সেভ করবেন:
```
cam19_test1_part1.mp3
cam19_test1_part2.mp3
cam19_test1_part3.mp3
cam19_test1_part4.mp3
...
cam10_test4_part4.mp3
```

#### কোথা থেকে পাবেন এবং কীভাবে ডাউনলোড করবেন (Sources):

1. **ইউটিউব (YouTube) - সবচেয়ে সহজ ও দ্রুত উৎস:**
   - **সার্চ কিওয়ার্ড:**
     - `Cambridge IELTS 19 Academic Listening Test 1 with answers audio`
     - `Cambridge IELTS 18 Listening Audio Tracks`
     - `Cambridge IELTS Listening Test 1 to 4 full audio`
   - **সেরা ইউটিউব চ্যানেলসমূহ:**
     - *IELTS Listening Test Official*
     - *Crack IELTS with Rob*
     - *The IELTS Listening Test*
     - *Cambridge IELTS Tests*
   - **ডাউনলোড পদ্ধতি:**
     - কোনো ব্রাউজার এক্সটেনশন বা ওপেন সোর্স টুল যেমন **yt-dlp** ব্যবহার করে অডিও ফরম্যাটে নামাতে পারেন:
       ```powershell
       yt-dlp -x --audio-format mp3 "https://www.youtube.com/watch?v=..." -o "cam19_test1.mp3"
       ```
     - অথবা বিশ্বস্ত অনলাইন কনভার্টার (যেমন: `y2mate`, `cobalt.tools`) দিয়ে MP3 128kbps কোয়ালিটিতে নামিয়ে নিন।

2. **টেলিগ্রাম চ্যানেল (Telegram Channels):**
   - টেলিগ্রামের সার্চ বারে লিখুন:
     - `@ielts_listening_audio`
     - `@cambridge_ielts_audio`
     - `@ielts_materials_collection`
   - এই চ্যানেলগুলোতে ক্যামব্রিজ ১০ থেকে ১৯ পর্যন্ত প্রতিটি বইয়ের সিডি অডিও ট্র্যাক পার্ট অনুসারে জিপ (ZIP) আকারে আপলোড করা থাকে।

3. **Archive.org (ইন্টারনেট আর্কাইভ):**
   - `archive.org`-এ গিয়ে সার্চ করুন: `"Cambridge IELTS Practice Tests Audio CD"`
   - এখানে ক্যামব্রিজের অফিসিয়াল অডিও সিডির ডিরেক্ট MP3 ফাইল সম্পূর্ণ বিনামূল্যে পাওয়া যায়।

---

### ক্যাটাগরি ২: Cambridge 20 Official Test Data
* **অগ্রাধিকার:** 🟡 **MEDIUM (অফিসিয়াল কপি রিলিজ সাপেক্ষে)**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/cambridge_app/data/cambridge_20.json`
* **বর্তমান অবস্থা:** আপনার `01. Cambridge Tests/` ফোল্ডারে একটি ফাইল রয়েছে:  
  `Cambridge 20 (wait for the original copy).pdf` (সাইজ ৪৫.৯ এমবি)।  
  *নোট:* ক্যামব্রিজ ইউনিভার্সিটি প্রেস সাধারণত প্রতি বছর মে-জুন মাসে পরবর্তী সংস্করণের বই প্রকাশ করে। আপনার বর্তমান ফাইলটি আন-অফিসিয়াল প্রিভিউ কপি।

#### কোথা থেকে আসল কপি পাবেন:

1. **অফিসিয়াল প্রকাশের সময়কাল:**
   - সাধারণত প্রতি বছর মে/জুন মাসের মাঝামাঝি অফিসিয়াল সংস্করণ বাজারে আসে।
2. **ডাউনলোড সোর্স:**
   - **টেলিগ্রাম কমিউনিটি:**
     - `@IELTS_PDF_Books`
     - `@Cambridge_IELTS_Materials`
     - `@IELTS_Fever`
   - **অনলাইন ফোরাম:**
     - `VK.com/ielts` (রাশিয়ান সোশ্যাল নেটওয়ার্কের IELTS গ্রুপগুলোতে সবচেয়ে আগে নতুন বই ও অডিও ট্র্যাক আপলোড হয়)।
     - `ieltsmaterial.com`, `ieltsdeal.com`

#### কীভাবে JSON ডেটাতে রূপান্তর করবেন:
আসল PDF হাতে এলে আপনার `cambridge_app/` ফোল্ডারে থাকা পাইথন স্ক্রিপ্ট ব্যবহার করে খুব সহজেই ডেটা এক্সট্রাক্ট করা যাবে:
```powershell
# Reading ও Listening প্যাসেজ এক্সট্রাক্ট করার কমান্ড
python cambridge_app/extract_tests.py
```
*(আপনার কাছে PDF থাকলে Antigravity AI-কে দিলে এক ক্লিকেই সম্পূর্ণ টেস্টের JSON তৈরি করে সিস্টেমে যুক্ত করে দেওয়া হবে।)*

---

### ক্যাটাগরি ৩: Kiran Makkar Speaking Cue Cards (লেটেস্ট সংস্করণ)
* **অগ্রাধিকার:** 🔴 **HIGH**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/04. Speaking/`
* **কেন প্রয়োজন:** আপনার ফোল্ডারে বর্তমানে `Makkar Speaking Jan-Apr 2025` আছে। IELTS পরীক্ষায় প্রতি ৪ মাস পর পর (জানুয়ারি-এপ্রিল, মে-আগস্ট, সেপ্টেম্বর-ডিসেম্বর) স্পিকিং কিউ কার্ডের ৫০% টপিক পরিবর্তন হয়।

#### কোন ফাইলগুলো দরকার:
1. `Makkar IELTS Speaking May-Aug 2025 Final Version.pdf`
2. `Makkar IELTS Speaking Sep-Dec 2025 Final Version.pdf`
3. `Makkar IELTS Speaking Jan-Apr 2026 Final Version.pdf` (পরবর্তী পরীক্ষার জন্য)

#### কোথা থেকে পাবেন (Sources):
1. **অফিসিয়াল পোর্টাল:** [makkarielts.com](https://www.makkarielts.com) (ড. কিরণ মাক্কারের অফিসিয়াল ব্লগ)।
2. **টেলিগ্রাম সার্চ:**
   - সার্চ করুন: `Makkar Speaking Final Version PDF`
   - চ্যানেল: `@makkarielts_official`, `@ielts_speaking_prep`
   *(প্রতিটি সিজনের প্রথম মাসের ২০-২৫ তারিখের মধ্যে "Final Version" পিডিএফ রিলিজ হয়।)*

---

### ক্যাটাগরি ৪: Cambridge 20 Vocabulary Dataset
* **অগ্রাধিকার:** 🟡 **MEDIUM**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/vocab_data/cambridge_20_vocabulary.json`
* **কেন প্রয়োজন:** আপনার কাছে ইতোমধ্যে ক্যামব্রিজ ১৮ এবং ১৯ এর চমৎকার শব্দার্থের ডেটাসেট আছে (ইংরেজি অর্থ, বাংলা অর্থ ও সিনোনিম সহ)। ক্যামব্রিজ ২০ এর ৪টি টেস্টের শব্দার্থ যোগ হলে ভোকাবুলারির সংখ্যা ৪,০০০ থেকে বেড়ে ৪,৩০০+ এ উন্নীত হবে।

#### ডেটাসেটের স্ট্যান্ডার্ড ফরম্যাট (Schema):
```json
[
  {
    "id": "c20_0001",
    "word": "Phenomenon",
    "meaning_en": "An observable fact or event",
    "meaning_bn": "প্রপঞ্চ, বিস্ময়কর ঘটনা",
    "synonyms": ["Occurrence", "Event", "Marvel"],
    "category": "Cambridge Tests",
    "sub_category": "Cambridge 20 - Test-1 Passage 1",
    "difficulty": "Band 7-8",
    "source": "Cambridge 20 Vocabulary"
  }
]
```
*(ক্যামব্রিজ ২০ এর রিডিং টেক্সট পাওয়ার পর স্বয়ংক্রিয় স্ক্রিপ্ট দিয়ে এই ফাইলটি প্রস্তুত করা যাবে।)*

---

### ক্যাটাগরি ৫: Writing Task 1 & 2 Band 9 Sample Essays
* **অগ্রাধিকার:** 🟢 **RECOMMENDED**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/03. Writing/`
* **কেন প্রয়োজন:** পরীক্ষায় ভালো স্কোর করার সবচেয়ে ভালো উপায় হলো অফিসিয়াল এক্সামিনারের লেখা বা ব্যান্ড ৯ শিক্ষকদের মডেল এসায়ের গঠন পর্যালোচনা করা।

#### কোন বইগুলো সংগ্রহ করা উচিত:
1. **Simon's IELTS Writing Task 2 Model Answers (Band 9):**
   - এক্স-আইইএলটিএস এক্সামিনার সাইমনের সহজ, পরিষ্কার ও নিখুঁত গঠনের উত্তরমালা।
2. **IELTS Liz Band 9 Writing Task 1 & 2 Essays:**
   - চার্ট, গ্রাফ, ম্যাপ এবং অপিনিয়ন/ডিসকাশন এসায়ের কাঠামো।
3. **Cambridge Official IELTS Examiner Reports:**
   - ক্যামব্রিজ পরীক্ষার আসল স্ক্রিপ্ট এবং এক্সামিনারের মন্তব্য।

#### কোথা থেকে পাবেন:
- **সাইমন আইইএলটিএস:** [ielts-simon.com](https://ielts-simon.com)
- **আইইএলটিএস লিজ:** [ieltsliz.com](https://ieltsliz.com)
- **টেলিগ্রাম চ্যানেল:** `@ielts_writing_band9`, `@simon_ielts_materials`

---

### ক্যাটাগরি ৬: Interactive Grammar Drills Dataset
* **অগ্রাধিকার:** 🟢 **RECOMMENDED (নতুন ফিচারের জন্য)**
* **টার্গেট ফোল্ডার:** `f:/Mustak/07_IELTS_Preparation/IELTS/vocab_data/grammar_drills.json`
* **কেন প্রয়োজন:** রিডিং এবং রাইটিং উভয় মডিউলেই ব্যাকরণগত নির্ভুলতা (Grammatical Range & Accuracy - GRA) অত্যন্ত গুরুত্বপূর্ণ। কমপ্লেক্স সেন্টেন্স গঠন, সাবজেক্ট-ভার্ব এগ্রিমেন্ট এবং কন্ডিশনাল সেন্টেন্সের ওপর কুইজ রাখার জন্য এটি প্রয়োজন।

#### ডেটাসেটের স্ট্যান্ডার্ড ফরম্যাট:
```json
[
  {
    "id": "g001",
    "topic": "Conditionals (Type 2 & 3)",
    "question": "If governments ________ stricter pollution laws, global carbon emissions would drop significantly.",
    "options": ["enact", "enacted", "had enacted", "will enact"],
    "correct": "enacted",
    "explanation": "Second conditional-এ hypothetical বা বর্তমানের অবাস্তব কল্পনার জন্য If + Past Simple ব্যবহৃত হয়।"
  }
]
```

---

## 📋 ৩. ফাইল সংগ্রহের অ্যাকশন চেকলিস্ট (Step-by-Step Execution Checklist)

| ধাপ | কাজ | সময় ও অগ্রাধিকার | স্ট্যাটাস |
| :---: | :--- | :---: | :---: |
| **ধাপ ১** | `images/listening/audio/` ফোল্ডার বানিয়ে ক্যামব্রিজ ১৯ এর ৪টি টেস্টের অডিও নামিয়ে রাখা | 🔴 ১ দিন (High) | প্রস্তুত |
| **ধাপ ২** | `04. Speaking/` ফোল্ডারে মে-আগস্ট এবং সেপ্টেম্বর-ডিসেম্বর ২০২৫ এর Makkar Speaking PDF যোগ করা | 🔴 ৩০ মিনিট (High) | প্রস্তুত |
| **ধাপ ৩** | `03. Writing/` ফোল্ডারে Simon / Liz Band 9 Essays PDF যোগ করা | 🟢 ১ দিন (Medium) | ঐচ্ছিক |
| **ধাপ ৪** | ক্যামব্রিজ ২০ এর আসল সংস্করণ বের হলে PDF সংগ্রহ করা এবং JSON এ রূপান্তর করা | 🟡 অফিসিয়াল রিলিজ সময়ে | অপেক্ষমাণ |
| **ধাপ ৫** | `grammar_drills.json` ফাইল যুক্ত করে ব্যাকরণ কুইজ সেকশন সম্প্রসারণ করা | 🟢 ২ দিন (New Feature) | ঐচ্ছিক |

---

## 💡 সহায়ক পরামর্শ (Pro Tips for Md. Mustak Khan)

1. **কোনো নতুন PDF ফোল্ডারে যোগ করলে:**
   - যখনই `01` থেকে `07` নম্বর ফোল্ডারে কোনো নতুন PDF যোগ করবেন, তখন `materials_data.js` ফাইলে মাত্র ২-৩ লাইনের একটি নতুন অবজেক্ট যোগ করে দিলে স্বয়ংক্রিয়ভাবে সেটি লাইব্রেরি গ্রিড ও সার্চে চলে আসবে।
2. **অডিও ফাইলের সাইজ অপ্টিমাইজেশন:**
   - অডিও ট্র্যাকগুলো খুব বড় (320kbps) ডাউনলোড করার প্রয়োজন নেই; **128kbps বা 96kbps MP3** রাখলে ওয়েবঅ্যাপটি খুব দ্রুত লোড হবে এবং ল্যাপটপ বা মোবাইলের জায়গা কম নেবে।
3. **লোকাল সার্ভার ছাড়া ব্যবহার:**
   - আমাদের বর্তমান সিস্টেমটি সম্পূর্ণ **Zero-Server (`file:///`)** উপযোগী। ব্রাউজারে ডাবল ক্লিক করলেই সবকিছু নির্বিঘ্নে চলবে।


---

## 🌐 ৪. সেরা অনলাইন রিসোর্স, ওয়েবসাইট, টুলস ও চ্যানেল ডিরেক্টরি (Curated IELTS Mega Directory)

> আপনার ঘরে বসে ১০০% স্বয়ংসম্পূর্ণ ও ব্যান্ড ৮-৯ IELTS প্রস্তুতির জন্য বিশ্বমানের সেরা ওয়েবসাইট, মক টেস্ট, অ্যাপ্লিকেশন, পডকাস্ট এবং ইউটিউব চ্যানেলের সম্পূর্ণ সংকলন:

### 📑 সূচিপত্র (Table of Contents)
- [আইইএলটিএস পরিচিতি ও অফিসিয়াল টেস্ট (Introduction & Official)](#introduction--official)
- [অনলাইন ফুল মক টেস্ট (Full-Length Mock Tests)](#mock-tests)
- [লিসেনিং টেস্ট ও অ্যাকসেন্ট রিসোর্স (Listening)](#listening)
- [রিডিং টেস্ট ও স্পিড রিডিং (Reading)](#reading)
- [রাইটিং প্র্যাকটিস ও ২৪৮+ ব্যান্ড ৯ এসে (Writing)](#writing)
- [স্পিকিং প্ল্যাটফর্ম, অ্যাপ ও টপিক (Speaking)](#speaking)
- [ভোকাবুলারি ও উচ্চারণ টুলস (Vocabulary)](#vocabulary)
- [পডকাস্ট ও অডিও লেসন (Podcasts)](#podcasts)
- [ইউটিউব চ্যানেল (YouTube Channels)](#youtube-channels)
- [জেনারেল ও সেলফ-স্টাডি পোর্টাল (General Portals)](#general-portals)

---

### 🏛️ Introduction & Official
* [British Council - What is IELTS](http://takeielts.britishcouncil.org/choose-ielts/what-ielts) — অফিসিয়াল ওভারভিউ, পরীক্ষার কাঠামো ও ব্যান্ড স্কোরের বিবরণ।
* [IELTS.org Sample Questions](https://www.ielts.org/about-the-test/sample-test-questions) — অফিসিয়াল আইইএলটিএস স্যাম্পল টেস্ট প্রশ্নপত্র।
* [Cambridge Official Practice Tests](https://www.cambridgeenglish.org/exams-and-tests/ielts/preparation/) — ক্যামব্রিজ ইংলিশ অফিসিয়াল প্র্যাকটিস ও গাইডলাইন।

---

### 🎯 Mock Tests
* [IELTSNext Online (Cambridge 1-21 Full Tests)](https://ieltsnext.online/) — ক্যামব্রিজ বুক ১ থেকে ২১ পর্যন্ত সকল অফিসিয়াল ফুল মক টেস্ট অনলাইনে দেওয়ার সেরা প্ল্যাটফর্ম:
  * ✍️ **Writing:** [ieltsnext.online/tests/writing](https://ieltsnext.online/tests/writing) (টাস্ক ১ ও ২ অনলাইন টাইপিং ও স্যাম্পল অ্যানসার)
  * 🗣️ **Speaking:** [ieltsnext.online/tests/speaking](https://ieltsnext.online/tests/speaking) (পার্ট ১, ২ ও ৩ এর সম্পূর্ণ প্রশ্নাবলি ও কিউ কার্ড)
  * 🎧 **Listening:** [ieltsnext.online/tests/listening](https://ieltsnext.online/tests/listening) (ফুল অডিও ট্র্যাক, টেপস্ক্রিপ্ট ও ইনস্ট্যান্ট অ্যানসার কি)
  * 📖 **Reading:** [ieltsnext.online/tests/reading](https://ieltsnext.online/tests/reading) (টাইমড এক্সাম ইন্টারফেস ও প্যাসেজ হাইলাইটিং)
* [IELTS Online Tests (Free Mock Tests)](https://ieltsonlinetests.com/) — টাইমার সহ লাইভ ফুল-লেংথ কম্পিউটার ডেলিভার্ড অনলাইন মক টেস্ট।
* [British Council Practice Tests](https://takeielts.britishcouncil.org/take-ielts/prepare/free-ielts-practice-tests) — ব্রিটিশ কাউন্সিলের অফিসিয়াল ফ্রি মক টেস্ট সেট।
* [Cambridge IELTS Books (1 - 15) PDF & Audio](https://ieltspracticeonline.com/download-all-cambridge-ielts-books-pdfaudio-1-14/) — ক্যামব্রিজ ১ থেকে ১৫ এর টেস্ট ও অডিও ডাউনলোড।

---

### 🎧 Listening
* [IELTSNext Cambridge 1-21 Listening](https://ieltsnext.online/tests/listening) — ক্যামব্রিজ ১ থেকে ২১ পর্যন্ত ফুল অডিও ও ইনস্ট্যান্ট অ্যানসার সহ কমপ্লিট লিসেনিং টেস্ট।
* [Mini-IELTS Listening Tests](http://mini-ielts.com/listening) — কামড়-সাইজ ছোট ছোট লিসেনিং টেস্ট ও ইনস্ট্যান্ট স্কোরিং।
* [184 IELTS Listening Tests](https://practicepteonline.com/ielts-listening-tests/) — ১৮৪টি ফুল লিসেনিং টেস্টের বিশাল ফ্রি সংগ্রহ।
* [IELTS UP Listening Practice](https://ielts-up.com/listening/ielts-listening-practice.html) — সেকশনভিত্তিক প্রশ্ন সমাধান ও অডিও প্র্যাকটিস।
* [British Council Listening Practice](http://takeielts.britishcouncil.org/prepare-your-test/free-ielts-practice-tests/listening-practice-test-1) — অফিসিয়াল লিসেনিং টেস্ট।
* [High Level Listening](http://www.highlevellistening.com/) — অ্যাডভান্সড লিসেনিং প্র্যাকটিস ও নেটিভ এক্সপ্রেশন লেসন।
* [Exam English](http://examenglish.com/IELTS/IELTS_listening.html) — ফ্রি প্র্যাকটিস টেস্ট ও সেকশনভিত্তিক প্রশ্ন।
* [BBC Programmes](http://www.bbc.co.uk/programmes/b006qykl) — খাঁটি ব্রিটিশ ও আন্তর্জাতিক অডিও স্ট্রিম।
* [BBC Learning English](http://learnenglish.britishcouncil.org/en/listen-and-watch) — ব্রিটিশ কাউন্সিলের মাল্টিমিডিয়া অডিও-ভিডিও ম্যাটেরিয়াল।
* [Speech Accent Archive](http://accent.gmu.edu/) — বিভিন্ন দেশের অ্যাকসেন্ট বিশ্লেষণ ও প্র্যাকটিস করার সেরা সংগ্রহশালা।

---

### 📖 Reading
* [IELTSNext Cambridge 1-21 Reading](https://ieltsnext.online/tests/reading) — ক্যামব্রিজ ১ থেকে ২১ পর্যন্ত অফিসিয়াল প্যাসেজ ও টাইমার সহ রিয়েল এক্সাম রিডিং টেস্ট।
* [Mini-IELTS Reading Tests](http://mini-ielts.com/reading) — ছোট ছোট রিডিং টেস্ট ও তাৎক্ষণিক ফিডব্যাক।
* [225 IELTS Academic Reading Tests](https://practicepteonline.com/ielts-reading-tests/) — ২২৫টি সম্পূর্ণ একাডেমিক রিডিং টেস্ট ও উত্তরমালা।
* [100 IELTS General Reading Tests](https://practicepteonline.com/ielts-general-reading-tests/) — ১০০টি জেনারেল ট্রেনিং রিডিং প্র্যাকটিস টেস্ট।
* [IELTS UP Academic Reading Tests](https://ielts-up.com/reading/ielts-reading-practice.html#academic) — একাডেমিক প্যাসেজ ও ট্রিকি প্রশ্ন সমাধান।
* [IELTS UP General Reading Tests](https://ielts-up.com/reading/ielts-reading-practice.html#general) — জেনারেল ট্রেনিং রিডিং কৌশল।
* [Tim Ferriss Speed Reading](https://www.huffingtonpost.com/tim-ferriss/speed-reading_b_5317784.html) — দ্রুত পড়ার বৈজ্ঞানিক টেকনিক (Skimming & Scanning গতি বৃদ্ধির জন্য)।

---

### ✍️ Writing
* [IELTSNext Cambridge 1-21 Writing](https://ieltsnext.online/tests/writing) — ক্যামব্রিজ ১ থেকে ২১ এর টাস্ক ১ ও টাস্ক ২ রাইটিং টেস্ট ও স্যাম্পল মডেল অ্যানসার।
* [248 Band 9 IELTS Essays](http://www.ielts-practice.org/band-9-essays/) — ২৪৮টি নিখুঁত ব্যান্ড ৯ মডেল এসায়ের বিশাল সংগ্রহ।
* [100+ Band 8 IELTS Essays](http://www.ielts-practice.org/band-8-essays/) — ১০০টিরও বেশি ব্যান্ড ৮ মডেল এসায়ের কাঠামো ও বিশ্লেষণ।
* [Collection of Writing Topics (Writing9)](https://writing9.com/ielts-writing-task-2-topics) — সাম্প্রতিক পরীক্ষার আসল টপিক ও ইউজার এসে ডিসকাশন।
* [Improve Your Writing Score](http://www.ielts-practice.org/ielts-writing/) — রাইটিং স্কোর বৃদ্ধির কার্যকরী টেকনিক।
* [Model Essays with Feedback](https://www.ieltsbuddy.com/ielts-sample-essays.html) — এক্সামিনারের মন্তব্য সহ নমুনা এসায়ের পর্যালোচনা।
* [IELTS Writing Task 1 for Academic](https://www.ieltsbuddy.com/ielts-writing-task-1.html) — চার্ট, গ্রাফ, টেবিল ও ম্যাপ বর্ণনার নিখুঁত গাইড।
* [IELTS Letter Writing Tips (GT)](https://ieltsliz.com/ielts-letter-writing-essential-tips/) — ফর্মাল, সেমি-ফর্মাল ও ইনফর্মাল চিঠি লেখার কৌশল।
* [IELTS Writing Vocabulary](https://ielts-up.com/writing/ielts-vocabulary-writing.html) — টাস্ক ১ ও ২-এর জন্য উচ্চমানের শব্দভাণ্ডার।
* [IELTS from 6 to 9](https://ielts69.com/) — রাইটিং স্কোর ৬ থেকে ৮-৯ এ রূপান্তর করার মাস্টার কৌশল।

---

### 🗣️ Speaking
* [IELTSNext Cambridge 1-21 Speaking](https://ieltsnext.online/tests/speaking) — ক্যামব্রিজ ১ থেকে ২১ এর সম্পূর্ণ স্পিকিং পার্ট ১, ২ ও ৩ এর অফিসিয়াল প্রশ্নাবলি ও কিউ কার্ড।
* [IELTS Speaking Part 1 Topics (Liz)](https://ieltsliz.com/ielts-speaking-part-1-topics/) — পার্ট ১-এর সবচেয়ে কমন প্রশ্ন ও উত্তর।
* [IELTS Speaking Part 2 Topics (Liz)](https://ieltsliz.com/ielts-speaking-part-2-topics/) — কিউ কার্ড টপিক ও ২ মিনিট কথা বলার ফ্রেমওয়ার্ক।
* [IELTS Speaking Part 3 Topics (Liz)](https://ieltsliz.com/ielts-speaking-part-3-topics-2/) — পার্ট ৩-এর বিশ্লেষণাত্মক আলোচনা প্রশ্ন।
* [IELTS Speaking Vocabulary](https://ielts-up.com/speaking/ielts-vocabulary-speaking.html) — স্পিকিংয়ের ফ্লুয়েন্সি ও লেক্সিক্যাল রিসোর্সের শব্দতালিকা।
* [Cambly](https://www.cambly.com/) — নেটিভ স্পিকারদের সাথে ১-অন-১ লাইভ স্পিকিং প্র্যাকটিস প্ল্যাটফর্ম।
* [Verbling](https://www.verbling.com/) — প্রফেশনাল অনলাইন ল্যাঙ্গুয়েজ টিউটরদের সাথে সেশন।
* [GetspokenApp](http://www.getspokenapp.com/) — স্পোকেন ইংলিশ কোচিং ও ফ্লুয়েন্সি তৈরির অ্যাপ।
* [IELTS Speaking UK](http://www.ieltsspeaking.co.uk/) — টপিক-ভিত্তিক স্পিকিং এক্সারসাইজ ও ফ্ল্যাশকার্ড।
* [SpeakingIELTS](http://www.speakingielts.com/) — অনলাইন স্পিকিং টেস্ট সিমুলেটর।

---

### 🧠 Vocabulary
* [Quizlet](https://quizlet.com) — ডিজিটাল ফ্ল্যাশকার্ড ও Spaced-Repetition এর মাধ্যমে শব্দার্থ মুখস্থ করার সেরা অ্যাপ।
* [Forvo](http://forvo.com/) — নেটিভ স্পিকারদের আসল উচ্চারণ শোনার বৃহত্তম গাইড।

---

### 🎙️ Podcasts
* [All Ears English Podcast](https://www.allearsenglish.com/) — প্রাণবন্ত আমেরিকান ইংরেজি কনভারসেশন ও এক্সাম টিপস।
* [ELLLO](http://elllo.org/) — English Listening Lesson Library Online (৩,০০০+ ফ্রি অডিও লেসন)।
* [Espresso English](https://www.espressoenglish.net/) — ছোট, বাস্তবমুখী ও দৈনিক ইংরেজি লেসন।

---

### 📺 YouTube Channels
* [IELTS Liz](https://www.youtube.com/user/ieltsliz) — সবচেয়ে জনপ্রিয় আইইএলটিএস প্রিপারেশন চ্যানেল।
* [Official IELTS Channel](https://www.youtube.com/user/IELTSOfficial) — অফিসিয়াল টেস্ট ফরম্যাট ওয়াকথ্রু ও টিপস।
* [engVid](https://www.engvid.com/) — হাজার হাজার ফ্রি ভিডিও লেসন (গ্রামার, ভোকাবুলারি এবং আইইএলটিএস)।

---

### 🌐 General Portals
* [IELTS Liz](http://ieltsliz.com/) — ৪টি মডিউলের জন্য সম্পূর্ণ ফ্রি লেসন, টিপস ও মডেল আনসার।
* [IELTS Simon](http://ielts-simon.com/ielts-help-and-english-pr/) — প্রাক্তন এক্সামিনারের প্রতিদিনের টিপস ও উচ্চমানের গঠন।
* [IELTS Advantage](http://ieltsadvantage.com/) — ক্রিস পেলের অসাধারণ গাইডলাইন ও ব্যান্ড বাড়ানোর স্ট্র্যাটেজি।
* [IELTS Buddy](http://www.ieltsbuddy.com/) — পূর্ণাঙ্গ লেসন প্ল্যান ও মডেল এসে।
* [IELTS Material](http://ieltsmaterial.com/) — বই, স্টাডি গাইড ও প্র্যাকটিস টেস্টের বিশাল কালেকশন।
* [IELTS-exam.net](https://www.ielts-exam.net/) — বিস্তারিত ফ্রি প্র্যাকটিস প্রশ্ন ও এক্সারসাইজ।
* [Ryan's IELTS Blog](http://ieltsielts.com/more/study-plans/) — স্টাডি প্ল্যান ও স্ট্র্যাটেজি গাইড।
* [CanadaVisa Free Tests](http://www.canadavisa.com/ielts/free-practice-tests.html) — ফ্রি সেলফ-অ্যাসেসমেন্ট টেস্ট।
* [Self Study Materials](http://selfstudymaterials.com/) — ডাউনলোডযোগ্য সেলফ-স্টাডি ম্যাটেরিয়ালস।
* [Blog de Cristina](http://www.cristinacabal.com/) — ইংলিশ টিচিং ও লার্নিং ব্লগ।
* [Dialect Blog](http://dialectblog.com/) — বিশ্বের নানা অঞ্চলের ডায়ালেক্ট ও অ্যাকসেন্ট সংগ্রহশালা।

---
*IELTS PrepMaster Ultimate v3.0 Resource Acquisition Blueprint*  
*Chittagong, Bangladesh · October 2026*
