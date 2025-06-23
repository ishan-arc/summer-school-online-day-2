Personal Profile Card - CSS Usage Explanation

1. Inline CSS:
- Used on the div with class "profile-card" to set the background color:
  style="background-color: #f9f9f9;"

2. Internal CSS:
- Defined inside the <style> block in the HTML head.
- Used element selectors (h1, p) to set font and color.
- Used descendant selector (.contact p) to style paragraphs inside contact section.
- Used attribute selector (a[href]) to style all links with href attribute.
- Added hover effect on links using a[href]:hover.

3. External CSS:
- Linked via style.css file.
- Most styles are applied here including:
  - Body background and margin.
  - Profile card layout, border, shadow, and text alignment.
  - ID selector (#profile-pic) for profile image styling.
  - Class selector (.bio) for the bio paragraph.
  - Element selectors (ul, h2) for list and headings.
  - Group selector (h2) for heading color and margin.
  - Bonus: border and shadow on profile card using class selector (.profile-card).

