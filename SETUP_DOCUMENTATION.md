# Repository Setup Documentation

## Overview

This `.github` repository has been configured as the central community health repository for the **KU-GEOI-525-2023** organization, supporting the **Deep Learning in Remote Sensing (GEOI 525)** course at Kathmandu University.

## What is a .github Repository?

A special `.github` repository in a GitHub organization provides default community health files that apply to all repositories in the organization. This setup ensures consistency across all student projects and course materials.

## Files Created

### Community Health Files

1. **README.md** - Main repository documentation explaining the purpose and structure
2. **profile/README.md** - Organization profile page that appears on the organization's GitHub homepage
3. **CODE_OF_CONDUCT.md** - Community standards and behavior guidelines
4. **CONTRIBUTING.md** - Guidelines for contributing to projects
5. **SECURITY.md** - Security policy and vulnerability reporting procedures
6. **SUPPORT.md** - Help resources and support channels

### Issue Templates

Located in `.github/ISSUE_TEMPLATE/`:

1. **project-submission.yml** - Template for students to submit their projects
   - Structured form for project information
   - Includes fields for student names, project details, dataset info, model architecture, results
   - Submission checklist to ensure completeness

2. **bug-report.yml** - Template for reporting bugs or technical issues
   - Structured form for bug description
   - Steps to reproduce, expected vs actual behavior
   - Environment information fields

3. **question.yml** - Template for asking questions
   - Category selection (course content, assignments, technical issues, etc.)
   - Context and code snippet fields
   - Reference links section

4. **config.yml** - Configuration for issue templates
   - Disables blank issues
   - Provides links to course resources and discussions

### Pull Request Template

**PULL_REQUEST_TEMPLATE.md** - Standardized PR template for code submissions
- Type of change selection
- Project information section
- Changes made description
- Testing checklist
- Code quality checklist

### GitHub Actions Workflow

**workflows/python-lint-test.yml** - Automated CI/CD pipeline
- Lints Python code using flake8 and black
- Runs pytest tests if available
- Uploads coverage reports
- Triggers on push and pull requests to main/develop branches

### Additional Files

**.gitignore** - Comprehensive ignore rules for:
- Python artifacts
- Virtual environments
- Jupyter notebooks checkpoints
- Deep learning model files (.h5, .pth, .ckpt)
- Remote sensing data files (.tif, .shp, .hdf)
- Data directories and outputs
- IDE configurations

## How These Files Are Used

### For Students

1. **Starting a Project**:
   - Read README.md to understand the course structure
   - Review CONTRIBUTING.md for project guidelines
   - Familiarize with CODE_OF_CONDUCT.md

2. **Working on Projects**:
   - Use .gitignore to avoid committing large data files
   - Follow code standards from CONTRIBUTING.md
   - Create structured branches and commits

3. **Submitting Work**:
   - Use the Project Submission issue template
   - Create pull requests using the PR template
   - Respond to automated CI/CD checks

4. **Getting Help**:
   - Use Question template for course/technical questions
   - Use Bug Report template for issues
   - Consult SUPPORT.md for resources

### For Instructors

1. **Review Process**:
   - Project submissions come through structured issue templates
   - Pull requests follow a consistent format
   - Automated checks catch code quality issues

2. **Communication**:
   - Clear guidelines reduce repetitive questions
   - Templates ensure complete information
   - Security policy protects sensitive data

3. **Course Management**:
   - Organization profile showcases course information
   - Consistent standards across all repositories
   - Automated workflows reduce manual review effort

## Organization Profile

The `profile/README.md` file creates a landing page for the organization that displays:
- Course overview and objectives
- Topics covered in the course
- Getting started guide for students
- Collaboration guidelines
- Project examples

This appears at: `https://github.com/KU-GEOI-525-2023`

## Best Practices Enforced

### Code Quality
- Python linting with flake8
- Code formatting with black
- Automated testing with pytest

### Documentation
- Comprehensive README requirements
- Code comments and docstrings
- Clear commit messages

### Data Management
- Large files excluded from Git
- Data sources documented
- Privacy and licensing respected

### Security
- No credentials in code
- Use environment variables
- Responsible disclosure policy

### Academic Integrity
- Original work submission
- Proper citations and references
- Collaboration guidelines

## Customization

Instructors can customize these files as needed:

1. **Update course information** in README.md and profile/README.md
2. **Modify issue templates** to match project requirements
3. **Adjust workflows** to add specific testing or deployment steps
4. **Update support resources** in SUPPORT.md with current links
5. **Revise guidelines** in CONTRIBUTING.md based on course evolution

## Future Enhancements

Consider adding:
- Additional workflows for specific tools (TensorFlow, PyTorch)
- More specialized issue templates (dataset requests, compute resources)
- GitHub Discussions categories for different topics
- Wiki pages for detailed tutorials
- Project showcase section
- Badges for build status and coverage

## Maintenance

Regular maintenance tasks:
- Update links and resources in SUPPORT.md
- Review and update dependencies in workflows
- Refresh examples in CONTRIBUTING.md
- Update contact information as needed
- Add new issue templates based on common questions

---

**Last Updated**: December 23, 2025
**Course**: GEOI 525 - Deep Learning in Remote Sensing
**Institution**: Kathmandu University
