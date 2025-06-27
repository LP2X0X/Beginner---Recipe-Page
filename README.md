# Frontend Mentor - Recipe page

![Design preview for the Recipe page coding challenge](./preview.jpg)

---

### 🧠 What I've learned from this project:

- Utilized semantic HTML elements and media queries to build a responsive layout that adapts effectively across different screen sizes.

```css
@media (min-width: 62rem) {
    .foreground {
        width: 45rem;
    }
}
```

- Centered a container element vertically and horizontally within a scrollable page with technique which this is different from previous project where the main container is statically center in the middle of the window.

```css
.foreground {
  .
  .
  .
  margin-left: auto;
  margin-right: auto;
}
```

- Applied line-height: 1 to ensure the line height matches the font height precisely, which is useful when tight vertical alignment is required. (Note: This eliminates additional spacing above and below the text but may reduce readability depending on the font.)

- Leveraged nested CSS selectors (e.g., .parent .child) for scoped and contextual styling, improving maintainability and specificity in stylesheets.

- Reconstructed default list styling (bullets and numbering) for \<ul> and \<ol> elements using CSS ::before pseudo-elements, enabling full control over their appearance.

```css
.instructions ol li::before {
  position: absolute;
  left: 0;
  top: 0;
  .
  .
  .
}
```

- Strengthened understanding of CSS positioning, specifically how position: absolute works in relation to its nearest positioned ancestor (relative, absolute, fixed, or sticky).

```css
.instructions ol li {
  position: relative;
  .
  .
  .
}

.instructions ol li::before {
  position: absolute;
  left: 0;
  top: 0;
  .
  .
  .
}
```

- Used width: 100% to make elements span the full width of their parent container, a common approach for responsive scaling.

- Implemented CSS counters with counter-reset and counter-increment to create custom numbering for list items and other repetitive elements without using \<ol>.

- Built a table with a single bottom border per row by combining border-collapse: collapse with border-bottom applied selectively to \<th> and \<td> elements.

- Used table-layout: fixed; to ensure all columns in a table have equal width, distributing space evenly regardless of content length, and improving layout consistency.

---

### 📚References

https://stackoverflow.com/questions/1000398/what-is-line-height1

[https://developer.mozilla.org/en-US/docs/Web/CSS/table-layout](https://developer.mozilla.org/en-US/docs/Web/CSS/table-layout#fixed)

www.w3schools.com/css/css_rwd_mediaqueries.asp
