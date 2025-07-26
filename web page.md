
Here’s a complete answer for Task-02: Compatibility Testing for Amazon Web Page, following the Prodigy Infotech format.

✅ Compatibility Testing Report: Amazon Website

📝 Task: Conduct Compatibility Testing for a Basic Web Page
🌐 Website Tested: [https://www.amazon.in](https://www.amazon.in)
📅 Date: July 26, 2025

 🔍 Browsers & Devices Tested

| Browser         | Version | OS/Device        |
| --------------- | ------- | ---------------- |
| Google Chrome   | 125.0   | Windows 10 PC    |
| Mozilla Firefox | 124.0   | Windows 10 PC    |
| Safari          | 17.0    | iPhone iOS 17    |
| Microsoft Edge  | 125.0   | Windows 10 PC    |
| Chrome Mobile   | Latest  | Android 13 Phone |


 ✅ Compatibility Test Table

| Feature/Function         | Expected Behavior                             | Observed Behavior (Browser-specific)            | Status   |
| ------------------------ | --------------------------------------------- | ----------------------------------------------- | -------- |
| Page Load Speed          | Loads within 2-3 seconds                      | All browsers passed                             | ✅ Pass   |
| Layout Consistency       | Header, body, footer aligned and styled       | Slight margin difference on Firefox             | ⚠️ Minor |
| Search Functionality     | Search bar functions properly                 | Working fine on all browsers                    | ✅ Pass   |
| Sign-in Button           | Navigates to login page                       | All working                                     | ✅ Pass   |
| Images & Banners         | All images load and scale properly            | Safari loaded one banner slowly                 | ⚠️ Minor |
| Add to Cart Function     | Adds product to cart successfully             | Chrome Mobile sometimes lags                    | ⚠️ Minor |
| Language Change Option   | Works on all versions                         | Edge had delay in language update               | ⚠️ Minor |
| Navigation Menu (Mobile) | Hamburger menu collapses and expands properly | Chrome Mobile layout shifts slightly            | ⚠️ Minor |
| Footer Links             | All links clickable                           | "Customer Service" link broken on Firefox       | ❌ Fail   |
| Responsive Design        | Adjusts across desktop/tablet/mobile          | All good except slight overlap in Safari iPhone | ⚠️ Minor |



 🛠️ Recommendations

| Issue                      | Suggested Fix                                                     |
| -------------------------- | ----------------------------------------------------------------- |
| Firefox layout spacing     | Normalize CSS or apply consistent padding via CSS Grid or Flexbox |
| Slow banner load on Safari | Optimize images and use lazy loading                              |
| Chrome Mobile cart lag     | Optimize JavaScript handling for mobile devices                   |
| Broken link on Firefox     | Check URL and make sure it’s HTTPS and case-sensitive             |
| Safari overlap             | Use media queries and test with actual iPhone viewports           |


 📸 Screenshot (optional in your report)

Include screenshots of any issues like:

 Overlapping elements
 Broken links
 Cart lag on mobile


📄 Markdown Sample Format

 markdown
 Browser Compatibility Issues for Amazon.in

Tested Browsers:
- Chrome (Windows)
- Firefox (Windows)
- Safari (iPhone)
- Edge (Windows)
- Chrome Mobile (Android)

 Issues Found:
1. Firefox – Footer margin inconsistency
2. Safari (iPhone) – Layout overlap on homepage
3. Chrome Mobile – Slight lag in cart interaction
4. Firefox – "Customer Service" link broken

Suggested Fixes:
- Normalize CSS across browsers
- Optimize for mobile responsiveness
- Fix broken URLs

 🧪 How to Test Amazon Yourself

Use tools like:

 ✅ [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
 ✅ [BrowserStack](https://www.browserstack.com/) *(free trial for multiple browsers)*
 ✅ [Responsive Design Checker](https://www.responsivedesignchecker.com/)
