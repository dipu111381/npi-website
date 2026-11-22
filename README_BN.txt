NPI ওয়েবসাইট — Render deployment package

ফাইল:
- index.html: মূল ওয়েবসাইট
- config.js: Supabase public project URL ও publishable key
- render.yaml: Render Static Site Blueprint

গুরুত্বপূর্ণ:
1. এই প্যাকেজটি এখনকার মূল ওয়েবসাইটের ফ্রন্টএন্ড।
2. Admin panel (admin.html), Admin Login এবং পূর্ণ Lead Management UI এখনো এই প্যাকেজে নেই।
3. Supabase-এর Row Level Security (RLS) নীতিমালা চালু ও সঠিকভাবে পরীক্ষা না করে production-এ প্রকাশ করবেন না।
4. GitHub-এ একটি repository তৈরি করে এই ফাইলগুলো upload/push করতে হবে।
5. এরপর Render Dashboard থেকে New > Blueprint এবং repository নির্বাচন করে render.yaml Apply করতে হবে।
