# Documentation Rules and Guidelines Memory

This file serves as a memory aid for documentation rules and guidelines used in this repository.

## File Structure and Organization

### Main Pages
- `/Languages/C++.mdx` - Main C++ programming guide
- `/Languages/Solidity.mdx` - Main Solidity programming guide
- `/Languages/C++/keywords.mdx` - C++ keywords subpage

### Image Paths
- All images should use relative paths: `../images/filename.png`
- Images are stored in the `/images` directory

## Content Guidelines

### Page Structure
1. Always include proper frontmatter (title, description)
2. Use clear, descriptive titles
3. Include table of contents for longer pages
4. Organize content into logical sections with proper headings

### Code Examples
1. Always specify language for code blocks (e.g., ```cpp, ```solidity)
2. Ensure code examples are complete and functional when possible
3. Include comments in code examples to explain key concepts

### Links and Navigation
1. Use relative links for internal navigation
2. Update docs.json when adding new pages
3. Maintain consistent navigation structure

## Formatting Standards

### Headings
- Use # for main titles
- Use ## for section headings
- Use ### for subsections
- Use #### for sub-subsections

### Lists
- Use - for unordered lists
- Use 1., 2., 3. for ordered lists
- Maintain consistent indentation

### Images
- Use `![Alt Text](../images/filename.png)` format
- Always include descriptive alt text
- Place images close to relevant content

## Navigation Updates

When adding new pages:
1. Create the page with proper frontmatter
2. Add the page to docs.json navigation
3. Update any relevant table of contents
4. Test navigation links

## Recent Changes

### C++ Documentation
- Moved Keywords section to subpage (/Languages/C++/keywords.mdx)
- Updated main C++ page with link to keywords subpage
- Added keywords subpage to navigation in docs.json

### Image Handling
- Replaced external image URLs with local paths
- Standardized image path format: ../images/filename.png

### Page Titles
- Simplified page titles (removed "Programming Guide" suffix)
- C++ page: "C++" instead of "C++ Programming Guide"
- Solidity page: "Solidity" instead of "Solidity Programming Guide"