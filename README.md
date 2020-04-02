# 01 HTML CSS Git: Code Refactor

## Summary 
In this project I reviewed an HTML and CSS files, looking for oppurtinies to improve the code for accessibility and semantic best practices. 

### Items That Were Updated 

1. Made the `<title>` element more descriptive

2. Changed the `<div>` with the `.header` class into a `<header>` html element 

3. Changed the `<div>` inside the `<header>` to a `<nav>`

4. Added in inline comments to both HTML and CSS for future devs 

5. Restructured some of CSS, so they were listed in more logical groups. Such as putting the regular `p` and `a` selectors in the **Global** group. 

6. Changed the content `<div>` to `<main>` since it holds the primary content of the page. 

7. Changed the "benefits" `<div>` to an `<aside>` since it indirectly relates to the main content.  

8. Added descriptive alt attributes to all of the `<img>` elements. 

9. Removed the not needed closing tag for the `<img>` element within Cost Management.

10. Replaced the `<div>` elements within the main Service sections with `<section>` elements. 

11. Moved the `.hero` class into a span element and gave it an `aria-label=""` and `role=""` so it could be read by screen readers. 

12. Changed the `.footer` class and `<div>` to a `<footer>` element and the corresponding CSS selector.

13. Updated the copyright in the footer to be for 2020. 

14. Reordered the CSS selectors for the 3 main **Services** section, placing them above the **Benefits** CSS selectors. This follows a similar order structure of the html file, allowing for a quicker read by a new developer. 

15. Anchor link on line 17 did not go anywhere. Fixed this by changing the `class=""` attribute on line 36 to an `id=""` attribute.

16. Consolidated the `class=""` and `id=""` attributes on lines 43 and 50 to be `id=""` attributes only. Cleaning up the redundancy in html and css code. 

17. Ran [HTML](https://take.ms/Hfwvz) & [CSS](https://take.ms/Zv71o) validators with no errors and through [Siteimprove Accessibility Checker](https://chrome.google.com/webstore/detail/siteimprove-accessibility/efcfolpjihicnikpmhnmphjhhpiclljc)