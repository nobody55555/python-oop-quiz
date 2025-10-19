# Contributing to Python OOP System Monitor Quiz

First off, thank you for considering contributing to this project! 🎉

This is an educational project designed to help people learn Python OOP concepts through interactive flashcards. Community contributions make this project better for everyone.

## How Can I Contribute?

### 🐛 Reporting Bugs

If you find a bug, please open an issue on GitHub with:

- A clear, descriptive title
- Steps to reproduce the problem
- What you expected to happen
- What actually happened
- Your browser and operating system

**Example:**
```
Title: Flashcard doesn't flip in Safari on iOS

Steps:
1. Open quiz in Safari on iPhone
2. Click on flashcard
3. Nothing happens

Expected: Card should flip to show answer
Actual: Card remains static
Browser: Safari 17.0, iOS 17.1
```

### 💡 Suggesting Enhancements

Have an idea to make the quiz better? Open an issue with:

- A clear description of the enhancement
- Why this enhancement would be useful
- Any examples or mockups (if applicable)

### 📝 Adding Quiz Questions

This is one of the best ways to contribute! To add new questions:

1. Fork the repository
2. Open the HTML file
3. Find the `flashcardData` array in the JavaScript section
4. Add your question following this format:

```javascript
{
    question: "Your question here?",
    answer: "The detailed answer here.",
    code_example: "your_code_example_here()",  // optional
    difficulty: "beginner",  // or "intermediate" or "advanced"
    category: "Category Name"
}
```

**Guidelines for good questions:**
- Clear and unambiguous
- Focused on practical knowledge
- Includes code examples when helpful
- Answer provides enough context to understand the concept
- Difficulty level matches the question complexity

**Categories to consider:**
- Class Basics
- OOP Principles
- psutil Basics
- Memory Monitoring
- Process Management
- GPU Monitoring
- Properties & Decorators
- Inheritance
- Advanced Python
- Magic Methods
- Error Handling
- Performance

### 🎨 Improving Design

If you're a CSS wizard, feel free to:
- Improve the visual design
- Enhance mobile responsiveness
- Add animations or transitions
- Improve color schemes for better accessibility

### 📚 Improving Documentation

Documentation improvements are always welcome:
- Fix typos or unclear explanations
- Add more examples
- Improve the README
- Translate content to other languages

## Pull Request Process

1. **Fork the repository** and create your branch from `main`
   ```bash
   git checkout -b feature/YourFeatureName
   ```

2. **Make your changes** and test thoroughly
   - Open the HTML file in multiple browsers
   - Test on both desktop and mobile
   - Ensure no JavaScript errors in console

3. **Commit your changes** with a clear message
   ```bash
   git commit -m "Add 5 new questions about decorators"
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Open a Pull Request** with:
   - A clear title describing the change
   - A description of what changed and why
   - Reference any related issues (e.g., "Fixes #123")

## Code Style Guidelines

### JavaScript
- Use `var` for consistency with the existing code
- Use descriptive variable names
- Add comments for complex logic
- Keep functions focused and single-purpose

### CSS
- Follow existing naming conventions
- Use comments to separate sections
- Maintain mobile-first responsive design
- Test in multiple browsers

### HTML
- Use HTML 4.01 Strict (to match existing DOCTYPE)
- Proper indentation (4 spaces)
- Semantic markup where possible

## Testing Your Changes

Before submitting a PR, please test:

1. **Functionality**
   - Start the quiz and complete a full round
   - Flip multiple cards
   - Mark answers as correct and incorrect
   - Complete several rounds to test level progression
   - Reset the game

2. **Browser Compatibility**
   - Chrome/Edge
   - Firefox
   - Safari
   - Mobile browsers

3. **No Console Errors**
   - Open browser DevTools (F12)
   - Check Console tab for errors
   - Fix any JavaScript errors

## Question Quality Standards

When adding questions, ensure they meet these standards:

✅ **Good Question Example:**
```javascript
{
    question: "What is the purpose of the @property decorator?",
    answer: "@property allows you to define a method that can be accessed like an attribute, providing getter functionality with validation or computation.",
    code_example: "@property
def cpu_usage(self):
    return psutil.cpu_percent()",
    difficulty: "intermediate",
    category: "Properties & Decorators"
}
```

❌ **Poor Question Example:**
```javascript
{
    question: "What's @property?",
    answer: "It's a decorator",
    difficulty: "intermediate",
    category: "Python"
}
```

**Why the second example is poor:**
- Question too vague
- Answer lacks depth and examples
- Category too general
- No practical context

## Community Guidelines

- Be respectful and constructive
- Welcome newcomers and help them learn
- Focus on educational value
- Assume good intentions
- Keep discussions on-topic

## Questions?

If you have questions about contributing, feel free to:
- Open an issue labeled "question"
- Reach out through GitHub discussions
- Check existing issues for similar questions

## Thank You! 🙏

Every contribution, no matter how small, helps make this educational resource better for everyone. We appreciate your time and effort!

---

## Quick Contribution Checklist

Before submitting your PR, check:

- [ ] Code tested in multiple browsers
- [ ] No JavaScript console errors
- [ ] New questions follow the format
- [ ] Code follows existing style
- [ ] Clear commit messages
- [ ] PR description explains changes
- [ ] Related issues referenced
- [ ] Documentation updated (if needed)

Happy contributing! 🚀
