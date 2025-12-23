# Security Policy

## Reporting Security Issues

The security of our course materials and student projects is important to us. If you discover a security vulnerability, please follow these steps:

### Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via:
- Email to the course instructors (see course syllabus)
- Private security advisory on GitHub (if available)
- Direct message to course administrators

Please include:
- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Suggested fix (if you have one)

### What to Report

Please report any security concerns including:
- Code vulnerabilities in course materials
- Exposed credentials or API keys
- Security misconfigurations
- Vulnerabilities in dependencies
- Data privacy concerns

### What Happens Next

1. **Acknowledgment**: We'll acknowledge receipt of your report within 48 hours
2. **Investigation**: We'll investigate and validate the issue
3. **Fix**: We'll work on a fix and coordinate disclosure
4. **Credit**: We'll credit you for the discovery (unless you prefer to remain anonymous)

## Security Best Practices for Students

### Code Security

1. **Never commit sensitive data**:
   - API keys and credentials
   - Access tokens
   - Private datasets
   - Personal information

2. **Use environment variables**:
   ```python
   import os
   api_key = os.environ.get('API_KEY')
   ```

3. **Review .gitignore**:
   - Ensure sensitive files are excluded
   - Check before each commit

4. **Scan dependencies**:
   - Keep dependencies updated
   - Use tools like `pip-audit` or `safety`

### Data Security

1. **Handle data responsibly**:
   - Follow data usage agreements
   - Respect privacy and licensing terms
   - Don't share proprietary datasets

2. **Secure data storage**:
   - Use appropriate cloud storage with access controls
   - Don't commit large datasets to Git
   - Document data sources and permissions

### Model Security

1. **Be cautious with pre-trained models**:
   - Download from trusted sources
   - Verify checksums when available
   - Be aware of potential backdoors

2. **Protect trained models**:
   - Consider intellectual property
   - Use appropriate licenses
   - Don't expose sensitive model weights publicly if they contain proprietary information

### Computing Resources

1. **Use resources ethically**:
   - Follow terms of service for cloud platforms
   - Don't abuse free tier limits
   - Report misuse if observed

2. **Secure your accounts**:
   - Use strong passwords
   - Enable two-factor authentication
   - Don't share credentials

## Vulnerability Disclosure Policy

We follow responsible disclosure practices:

1. **Coordinated disclosure**: We'll work with reporters to address issues before public disclosure
2. **Timeline**: We aim to address critical issues within 30 days
3. **Public disclosure**: After fixes are deployed, we may publish details (with reporter's consent)

## Supported Versions

This security policy applies to:
- Current course materials
- Active student repositories
- Organization-wide configuration files

## Dependencies and Third-Party Software

Students should:
- Keep dependencies up to date
- Monitor security advisories
- Use `pip-audit` or similar tools to check for vulnerabilities
- Review dependency licenses

## Compliance

Projects should comply with:
- Kathmandu University policies
- Data protection regulations
- Open source licenses
- Cloud provider terms of service

## Questions

For questions about this security policy, contact the course instructors.

---

**Note**: This is an educational environment. Mistakes happen, and we're here to learn. If you accidentally commit something sensitive, don't panic:
1. Immediately notify instructors
2. Rotate any exposed credentials
3. We'll help you clean up the repository history if needed

Security is everyone's responsibility. Let's work together to keep our learning environment safe!
