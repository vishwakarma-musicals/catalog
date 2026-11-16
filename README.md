# विश्वकर्मा म्यूज़िकल्स (Vishwakarma Musicals) — आधिकारिक ई-कॉमर्स वेबसाइट

**आधिकारिक वेबसाइट:** [https://vishwakarmamusicals.in](https://vishwakarmamusicals.in)  
**स्थापना:** 1990 (35+ वर्षों की काष्ठ एवं सुर शिल्प परंपरा)  
**संस्थापक एवं मुख्य शिल्पकार:** तुलसी दास विश्वकर्मा (Tulsidas Vishwakarma)  
**पंजीकृत कार्यशाला एवं स्टोर:** मकान नं. 109, ग्राउंड फ्लोर, शाला मोहल्ला, वार्ड नं. 10, हरदौल मंदिर के पास, मंगल भवन के सामने, हरदौल मंदिर रोड, अमानगंज, ब्लॉक गुनौर, जिला पन्ना, मध्य प्रदेश – 488441, भारत  
**GSTIN:** `23BSDPV5529B1ZV` | **Udyam MSME Registered**

---

## 1. तकनीकी आर्किटेक्चर (Tech Stack)

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (Mobile-First, Royal Traditional Indian Heritage UI, Default Zoom `80%`)
- **Backend & Live Price Sync:** Google Apps Script Web App API + Google Sheets (`Vishwakarma Musicals - Master Business System 2026-27` -> `Website_Catalog` tab)
- **Hosting & Security:** GitHub Pages + Cloudflare CDN (Full SSL Mode)
- **Domain & Business Email:** Zoho Domains (`vishwakarmamusicals.in`) + Zoho Mail (`info@vishwakarmamusicals.in`)
- **Invoicing & Logistics:** Zoho Invoice (GST-compliant Invoices & Quotes with HDFC UPI QR) + Delhivery One (B2C Nationwide Courier)

---

## 2. वेबसाइट पेजों की संरचना (11 HTML Pages)

1. `index.html` — मुख्य होमपेज (12 प्रमुख वाद्य यंत्र, कार्यशाला सेवाएँ, 5.0★ Google समीक्षाएँ, FAQ, लोकेशन मैप)
2. `instruments.html` — संपूर्ण 26 वाद्य यंत्रों का संग्रह (लाइव हिंदी/अंग्रेजी सर्च एवं कैटेगरी फ़िल्टर सहित)
3. `product.html` — डायनामिक उत्पाद विवरण पेज (`product.html?slug=PRODUCT_SLUG`)
4. `workshop.html` — हारमोनियम, ढोलक एवं तबला मरम्मत, सुर मिलान (440Hz Tuning) व जीर्णोद्धार सेवाएँ
5. `catalog.html` — आधिकारिक A4 प्रिंट-रेडी वाद्य एवं रिपेयर दर कैटलॉग
6. `downloads.html` — आधिकारिक कैटलॉग, मूल्य सूची, रख-रखाव गाइड व विज़िटिंग कार्ड डाउनलोड केंद्र
7. `about.html` — 1990 से चली आ रही शिल्प परंपरा और संस्थापक परिचय
8. `contact.html` — कार्यशाला का पता, समय (सुबह 9:00 से रात 9:00), Google Maps नेविगेशन और संपर्क विवरण
9. `privacy-policy.html` — गोपनीयता नीति (DPDP Act, 2023 एवं IT Act के अनुरूप)
10. `terms-and-conditions.html` — वाद्य खरीद, ऑनलाइन ऑर्डर, 6 माह सीमित सेवा वारंटी व कार्यशाला नियम
11. `disclaimer.html` — प्राकृतिक काष्ठ, चर्म, मौसम प्रभाव व ध्वनिकी संबंधी विधिक अस्वीकरण

---

## 3. अनिवार्य UI, संपर्क और व्यवसाय नियम (Master Operating Standards)

- **डिफ़ॉल्ट पेज ज़ूम:** सभी पेजों पर `zoom: 80%` लागू है।
- **प्रोडक्ट कार्ड व्यवहार:** प्रत्येक उत्पाद कार्ड पर `"कार्ट में जोड़ें"` CTA बटन कार्ट ड्रॉअर खोलता है, जबकि कार्ड के किसी भी अन्य हिस्से पर क्लिक करने से संबंधित `product.html?slug=...` पेज खुलता है।
- **सिंगल वॉयस कॉल नीति:** सभी उत्पाद पूछताछ, ऑर्डर और मरम्मत परामर्श के लिए केवल **`+91 97550 88022`** पर सीधा वॉयस कॉल (`tel:+919755088022`) उपयोग किया जाता है।
- **Footer-Only WhatsApp नियम:** WhatsApp लिंक (`https://wa.me/919755088022`) **केवल प्रत्येक वेबपेज के फुटर (`.social-links-footer`) में YouTube, Facebook और Instagram आइकन्स के साथ** रखा गया है।
- **आधिकारिक शब्दावली:** हारमोनियम बेलोज़ के लिए **धोंकनी** (`Dhonkni`), लोक क्लैपर फ्रेम के लिए **झीका** (`Jheeka`), और पोर्टेबल हारमोनियम के लिए **सफ़री हारमोनियम** (`Safri Harmonium`) का प्रयोग अनिवार्य है।
- **शिपिंग, सेवा एवं भुगतान नियम:**
  - **Delhivery One** कूरियर शिपिंग केवल नए वाद्य यंत्रों की खरीद पर लागू है।
  - सभी **मरम्मत और ट्यूनिंग सेवाओं** के लिए ग्राहक का अमानगंज कार्यशाला में स्वयं आना अनिवार्य है (सेवाओं पर ऑनलाइन कार्ट/चेकआउट लागू नहीं है)।
  - किसी भी नए ऑर्डर की तैयारी या डिस्पैच से पहले **UPI या HDFC Bank Transfer द्वारा अग्रिम/पूर्ण भुगतान** अनिवार्य है।

---

## 4. रख-रखाव एवं अपडेट प्रक्रिया (Windows 11 Built-in Tools)

1. स्थानीय फ़ोल्डर में `.html` या `README.md` फ़ाइल पर Right-Click करें -> **Open with -> Notepad** चुनें।
2. पूरा अपडेटेड कोड पेस्ट करें और **`Ctrl + S`** दबाकर UTF-8 एन्कोडिंग में सेव करें।
3. Google Chrome में संबंधित `.html` फ़ाइल खोलकर `80%` ज़ूम, कार्ट ड्रॉअर और फुटर सोशल आइकन्स की जाँच करें।
4. सत्यापन के बाद अपडेटेड फ़ाइल को GitHub Repository (`vishwakarmamusicals.in`) और Google Drive के `03_Website_Code_&_Backups` फ़ोल्डर में अपलोड करें।