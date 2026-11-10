MONEY SOLUTION FINANCE SERVICES – STARTER PACKAGE

1) इस ZIP को Extract करें।
2) वेबसाइट चलाने के लिए Hosting (HTTPS) पर सभी फाइलें अपलोड करें।
3) Firebase Authentication में Email/Password चालू होना चाहिए।
4) Firestore Database बनाकर Rules में inquiries collection के लिए सही नियम Publish करें।
5) Admin page: /admin/ खोलें।

महत्वपूर्ण:
- यह ZIP starter website/admin panel है, compiled Android APK नहीं है।
- Firebase config सार्वजनिक web config है; इसे अकेले secret न मानें।
- Admin page में UID check UI स्तर पर है; Firestore Rules भी UID को verify करते हैं।
- Inquiry creation rules को production में validate करें (अनुमत fields, phone format, size आदि)।
- HTTPS hosting आवश्यक है।
- Hosting के लिए Firebase Hosting या अन्य static HTTPS hosting इस्तेमाल करें।
