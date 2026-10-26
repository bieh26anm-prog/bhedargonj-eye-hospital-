# ভেদরগঞ্জ ইসলামিয়া চক্ষু হাসপাতাল — Website

একটি মোবাইল-ফ্রেন্ডলি বাংলা static website। HTML, CSS এবং সামান্য JavaScript দিয়ে তৈরি; কোনো build tool দরকার নেই।

## ফাইলের গঠন

- `index.html` — মূল ওয়েবসাইট
- `style.css` — ডিজাইন ও responsive/mobile layout
- `script.js` — মোবাইল মেনু ও ফুটারের সাল
- `assets/` — হাসপাতালের দেওয়া পোস্টার ও লোগো

## GitHub Pages-এ প্রকাশ করুন

1. GitHub-এ নতুন repository তৈরি করুন।
2. এই ফোল্ডারের সব ফাইল ও `assets` ফোল্ডার repository-তে upload করুন (ZIP ফাইলটি সরাসরি extract না করে ফাইলগুলো upload করতে হবে)।
3. Repository → **Settings** → **Pages** খুলুন।
4. **Build and deployment** অংশে **Deploy from a branch** নির্বাচন করুন।
5. Branch হিসেবে `main`, folder হিসেবে `/(root)` বেছে **Save** করুন।
6. কয়েক মিনিট পরে GitHub Pages-এর প্রকাশিত URL-এ ওয়েবসাইট দেখা যাবে।

## প্রকাশের আগে যাচাই করুন

- ফোন নম্বর, ডাক্তারদের নাম/ডিগ্রি, চেম্বারের দিন-সময় ও ঠিকানা হাসপাতাল কর্তৃপক্ষের মাধ্যমে যাচাই করুন।
- লোগো ও পোস্টার `assets/` ফোল্ডারে একই নামসহ রাখুন।
- এই সাইটে appointment form বা patient records নেই; ফোনের মাধ্যমে সিরিয়ালের জন্য যোগাযোগ করা যাবে।


## নতুন ফিচার

- অনলাইন সিরিয়াল অনুরোধের ফর্ম যুক্ত হয়েছে।
- ফর্মের তথ্য WhatsApp-এ বার্তা হিসেবে প্রস্তুত হয়; ব্যবহারকারীকে WhatsApp-এ Send চাপতে হবে।
- ফোন, WhatsApp, লোকেশন ও Facebook search link যুক্ত হয়েছে।
- এটি static website, তাই রোগীর তথ্য সংরক্ষণ/দেখার নিরাপদ admin panel এতে নেই। প্রকৃত admin panel-এর জন্য server/database এবং নিরাপদ login দরকার।
