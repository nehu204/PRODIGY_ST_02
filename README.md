# Task-02: Compatibility Testing – Amazon.in

## ✅ Objective:
Conduct cross-browser and cross-device compatibility testing on the Amazon India website to ensure consistent UI and functionality.

## 🔗 Website Tested:
[https://www.amazon.in](https://www.amazon.in)

## 🧪 Browsers & Devices:
- Chrome 125 (Windows 10)
- Firefox 124 (Windows 10)
- Edge 125 (Windows 10)
- Safari 17 (iOS 17, iPhone)
- Chrome Mobile (Android 13)

## 📊 Compatibility Summary:

| Feature                | Status  |
|------------------------|---------|
| Page Load              | ✅ Pass |
| Layout (All Browsers)  | ⚠️ Minor |
| Search Function        | ✅ Pass |
| Add to Cart            | ⚠️ Minor |
| Footer Links (Firefox) | ❌ Fail |
| Responsive Design      | ⚠️ Minor |

### 📷 Issues Documented:
1. Footer margin issue on Firefox
2. Safari (iPhone) layout shift
3. Chrome Mobile – lag in cart action
4. Broken "Customer Service" link on Firefox

## 🛠️ Recommendations:
- Normalize layout using Flex/Grid
- Optimize JS for mobile
- Verify broken links in Firefox
- Apply responsive media queries

---

✅ Submitted as part of **Prodigy Infotech Internship – Task-02: Compatibility Testing**
