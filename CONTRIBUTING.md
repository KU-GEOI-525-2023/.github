# Contributing Guidelines

Welcome to the GEOI 525 Deep Learning in Remote Sensing course! This document provides guidelines for contributing to projects in this organization.

## Getting Started

1. **Fork the repository** you want to work on
2. **Clone your fork** locally
3. **Create a new branch** for your work: `git checkout -b your-feature-branch`
4. **Make your changes** following the guidelines below
5. **Test your code** thoroughly before submitting
6. **Commit your changes** with clear, descriptive messages
7. **Push to your fork** and **create a pull request**

## Code Standards

### Python Code
- Follow PEP 8 style guidelines
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Keep functions focused and modular
- Include type hints where appropriate

### Deep Learning Projects
- Document your model architecture clearly
- Include training and validation metrics
- Save model checkpoints appropriately
- Document hyperparameters used
- Provide visualization of results

### Remote Sensing Data
- Document data sources and preprocessing steps
- Include coordinate reference system (CRS) information
- Specify band combinations used
- Document any data transformations applied

## Project Structure

Organize your project with the following structure:
```
project-name/
├── data/               # Data storage (use .gitignore for large files)
├── notebooks/          # Jupyter notebooks for exploration
├── src/               # Source code
│   ├── models/        # Model definitions
│   ├── preprocessing/ # Data preprocessing scripts
│   └── utils/         # Utility functions
├── results/           # Results, figures, and outputs
├── requirements.txt   # Python dependencies
├── README.md         # Project documentation
└── .gitignore        # Git ignore rules
```

## Documentation

- **README**: Every project must have a comprehensive README explaining:
  - Project objectives
  - Dataset description
  - Methodology
  - Results and findings
  - How to reproduce the work
  
- **Code Comments**: Add comments to explain complex logic
- **Notebooks**: Use markdown cells to explain your analysis steps

## Commits

- Write clear, concise commit messages
- Use present tense: "Add feature" not "Added feature"
- Reference issues when applicable: "Fix #123"
- Keep commits focused on single changes

## Pull Requests

When submitting a pull request:

1. **Title**: Use a descriptive title
2. **Description**: Explain what changes you made and why
3. **Testing**: Describe how you tested your changes
4. **Screenshots**: Include visualizations of results if applicable
5. **Related Issues**: Link to related issues

## Code Review

- Be respectful and constructive in reviews
- Focus on the code, not the person
- Ask questions for clarity
- Suggest improvements, don't demand changes
- Acknowledge good work

## Data Management

- **Never commit large datasets** to the repository
- Use `.gitignore` to exclude data files
- Document data sources and how to obtain them
- Consider using data versioning tools like DVC for large datasets
- Share data through appropriate cloud storage with proper documentation

## Reproducibility

To ensure your work is reproducible:

1. **Dependencies**: List all dependencies in `requirements.txt` or `environment.yml`
2. **Random Seeds**: Set random seeds for reproducible results
3. **Documentation**: Document all steps to reproduce your analysis
4. **Notebooks**: Restart kernel and run all cells before committing
5. **Environment**: Document Python version and hardware requirements

## Getting Help

- **Questions**: Open an issue with the "question" label
- **Bugs**: Report bugs with detailed steps to reproduce
- **Discussions**: Use GitHub Discussions for general topics
- **Instructors**: Contact course instructors for course-related queries

## Academic Integrity

- Submit only your own work
- Cite all sources and references appropriately
- Give credit to collaborators
- Follow university academic integrity policies

## License

Respect the licenses of any external code, data, or models you use in your projects.

---

Thank you for contributing to GEOI 525! Your work helps build a valuable resource for the remote sensing and deep learning community.
