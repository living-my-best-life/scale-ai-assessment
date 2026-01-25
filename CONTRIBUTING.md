# Contributing to SCALE AI Assessment Tool

Thank you for your interest in contributing to the SCALE AI Maturity Assessment Tool! This document provides guidelines and instructions for contributing.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for improvement:

1. Check existing [Issues](../../issues) to avoid duplicates
2. Create a new issue with a clear title and description
3. Include steps to reproduce (for bugs)
4. Add screenshots if applicable

### Submitting Changes

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
4. **Test thoroughly** - Open `index.html` in multiple browsers
5. **Commit with clear messages**
   ```bash
   git commit -m "Add: description of what you added"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request**

## Development Guidelines

### Code Style

- Use consistent indentation (4 spaces)
- Keep JavaScript functions focused and well-named
- Comment complex logic
- Use semantic HTML elements
- Follow CSS custom property naming conventions

### Assessment Content Guidelines

When modifying questions or recommendations:

- Ensure questions are clear and unambiguous
- Each question should have 5 distinct maturity levels
- Level descriptions should progress logically (1 = least mature, 5 = most mature)
- Recommendations should be actionable and specific

### Testing Checklist

Before submitting a PR, verify:

- [ ] Assessment loads correctly
- [ ] All 25 questions display properly
- [ ] Navigation between dimensions works
- [ ] Scoring calculates correctly
- [ ] Results display with proper maturity levels
- [ ] Recommendations appear based on scores
- [ ] Print/download functionality works
- [ ] Mobile responsive layout works
- [ ] No console errors

## Types of Contributions Welcome

### High Priority
- Accessibility improvements (WCAG compliance)
- Internationalization (i18n) support
- Additional export formats (PDF, CSV)
- Email capture integration options

### Content Improvements
- Question refinements
- Additional recommendations
- Industry-specific variations
- Updated statistics and research

### Technical Enhancements
- Performance optimizations
- Animation improvements
- Chart/visualization additions
- Analytics integration options

## Questions?

If you have questions about contributing, feel free to open an issue with the "question" label.

---

Thank you for helping improve the SCALE AI Assessment Tool!
