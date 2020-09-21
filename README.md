# skeleton

Template repository to create standardized Fastify plugins.

# Getting started

- Click on `Use this template` above to create a new repository based on this repository.

# What's include?

1. Github CI Actions for Installing, testing your package.
2. Github CI Actions to validate different package managers.
3. Dependabot V2 config to automate dependency updates.
4. Template for the GitHub App [Stale](https://github.com/apps/stale).
5. Template for the GitHub App [tests-checker](https://github.com/apps/tests-checker).

# Repository structure

```
├── .github
│   ├── workflows
│   │   ├── ci.yml
│   │   └── package-manager-ci.yml
│   ├── .stale.yml
│   ├── dependabot.yml
│   └── tests_checker.yml
│
├── docs (Documentation)
│   
├── examples (Code examples)
│
├── test (Application tests)
│   
├── types (Typescript types)
│  
└── README.md
```