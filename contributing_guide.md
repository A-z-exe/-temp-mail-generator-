# Contributing to Temporary Email Generator

Thank you for considering contributing to this project! 🎉

## How to Contribute

### 1. Fork the Repository
- Click the "Fork" button at the top right of this repository
- Clone your fork locally:
  ```bash
  git clone https://github.com/YOUR_USERNAME/temp-mail-generator.git
  cd temp-mail-generator
  ```

### 2. Create a Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix
```

### 3. Make Your Changes
- Write clean, readable code
- Follow the existing code style
- Add comments for complex logic
- Test your changes thoroughly

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add: your descriptive commit message"
```

### 5. Push and Create a Pull Request
```bash
git push origin feature/your-feature-name
```

Then create a pull request from your fork to the main repository.

## Types of Contributions

### 🐛 Bug Reports
- Use the GitHub issue tracker
- Include steps to reproduce
- Describe expected vs actual behavior
- Include system information (OS, Python version)

### ✨ Feature Requests
- Open an issue to discuss the feature first
- Explain the use case
- Consider backward compatibility

### 🔧 Code Contributions
- **New Features**: Email parsing improvements, new API integrations, UI enhancements
- **Bug Fixes**: Error handling, compatibility issues, edge cases
- **Documentation**: README improvements, code comments, usage examples
- **Performance**: Optimization, faster processing, memory usage

## Code Style Guidelines

### Python Code Style
- Follow PEP 8 guidelines
- Use meaningful variable names
- Add docstrings for functions
- Keep functions focused and small
- Handle exceptions properly

### Example:
```python
def extract_verification_code(email_content):
    """
    Extract verification code from email content.
    
    Args:
        email_content (str): The email content to search
        
    Returns:
        str or None: The extracted code or None if not found
    """
    # Implementation here
    pass
```

## Testing

Before submitting:
1. Test the main functionality
2. Test edge cases
3. Verify it works with different email formats
4. Check that files are saved correctly

## Commit Message Format

Use clear, descriptive commit messages:
- `Add: new feature description`
- `Fix: bug description`
- `Update: what was updated`
- `Remove: what was removed`

## Pull Request Guidelines

### Before Submitting
- [ ] Code follows the style guidelines
- [ ] Changes have been tested
- [ ] Documentation is updated if needed
- [ ] No merge conflicts with main branch

### Pull Request Description
Include:
- What changes were made
- Why the changes were necessary
- How to test the changes
- Screenshots if UI changes were made

## Issues and Support

- **Bug Reports**: Use the GitHub issue tracker
- **Questions**: Start a discussion or open an issue
- **Security Issues**: Please report privately to the maintainer

## Recognition

Contributors will be:
- Added to the contributors section
- Mentioned in release notes for significant contributions
- Given appropriate credit in documentation

## Code of Conduct

- Be respectful and constructive
- Focus on the issue, not the person
- Help create a welcoming environment
- Follow GitHub's community guidelines

## Getting Help

If you need help with contributing:
- Check existing issues and pull requests
- Read the README.md thoroughly
- Ask questions in GitHub discussions
- Contact the maintainer via the provided social media

Thank you for making this project better! 🚀