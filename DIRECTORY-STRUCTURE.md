# APEX Repository Directory Structure

```
APEX/
├── README.md                 # Main documentation and program overview
├── LICENSE                   # MIT License file
├── CONTRIBUTING.md           # Guidelines for contributing to the repository
├── CODE_OF_CONDUCT.md        # Community code of conduct
├── .gitignore                # Specification of files to ignore in git
├── assets/                   # Media and other static resources
│   ├── images/               # Images used in documentation
│   │   ├── apex-banner.png   # Program banner for README
│   │   ├── exercise-demos/   # Exercise demonstration images
│   │   └── icons/           # Icons used throughout documentation
│   └── templates/            # Printable templates (PDF sources)
│       ├── tracking-sheets/  # Progress tracking templates
│       └── workout-logs/     # Printable workout logs
├── docs/                     # Main documentation files
│   ├── program-overview.md   # Detailed program philosophy and structure
│   ├── getting-started.md    # Guide for beginners to the program
│   ├── exercise-library.md   # Complete exercise reference guide
│   ├── nutrition-guide.md    # Nutrition guidelines for hypertrophy
│   ├── recovery-protocols.md # Recovery strategies and techniques
│   ├── equipment-guide.md    # Equipment requirements and substitutions
│   ├── faq.md               # Frequently asked questions
│   ├── glossary.md          # Definitions of training terminology
│   ├── calculators/         # Calculation tools and formulas
│   │   ├── nutrition-calculator.md  # Nutritional needs calculation guide
│   │   └── volume-calculator.md     # Training volume assessment tools
│   ├── tracking/            # Progress tracking documentation
│   │   ├── README.md        # Overview of tracking methodologies
│   │   ├── templates.md     # How to use the tracking templates
│   │   └── metrics.md       # Key performance indicators to track
│   └── workouts/            # Structured workout documentation
│       ├── README.md        # Overview of all workouts
│       ├── week1/           # Week 1 workouts
│       │   ├── README.md    # Week 1 overview
│       │   ├── day1-push-a.md  # Push workout A documentation
│       │   ├── day2-pull-a.md  # Pull workout A documentation
│       │   └── ...          # Other workout days
│       └── week2/           # Week 2 workouts
│           └── ...          # Week 2 workout files
├── tools/                    # Utility tools for the program
│   ├── scripts/             # Any scripts for data processing or analysis
│   └── calculators/         # Interactive calculator source code (if applicable)
└── printables/              # Ready-to-print PDF documents
    ├── workout-logs/        # PDF workout logs
    ├── tracking-sheets/     # PDF tracking sheets
    └── quick-reference/     # PDF quick reference guides
```

## Key Directory Explanations

### `/docs`
Contains all the core documentation for the program. Organized by topic, with each major component of the program having its own markdown file or directory.

### `/docs/workouts`
Contains detailed workout documentation organized by week and day, allowing for easy navigation and reference.

### `/assets`
Holds all media and resources used throughout the documentation, including images, icons, and template source files.

### `/printables`
Contains ready-to-print PDF versions of workout logs, tracking sheets, and quick reference guides for convenient offline use.

### `/tools`
Houses any scripts, calculators, or other interactive tools that enhance the user experience of the program.

## File Naming Conventions

- Use kebab-case for all file names (lowercase with hyphens)
- Include descriptive prefixes for related files (e.g., `day1-push-a.md`, `day2-pull-a.md`)
- Use consistent file extensions (.md for markdown, .pdf for printables)
- Include README.md files in directories to explain contents

## Content Organization Principles

1. **Hierarchical Structure**: Organize content from general to specific
2. **Logical Grouping**: Keep related content together
3. **Progressive Disclosure**: Start with essentials, then provide details
4. **Cross-Referencing**: Include links between related documents
5. **Consistency**: Maintain consistent formatting and structure across documents