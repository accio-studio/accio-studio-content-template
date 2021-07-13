# accio-studio-content-template
Template of content repository for Accio Studio

## File structure
```bash
.
└── github/{:username}/{:repo}/
    ├── components/
    │   └── [:component].{jsx/tsx}
    ├── content/
    │   └── [:space hash]/
    │       ├── [:space hash].config.json
    │       └── [:page hash]/
    │           ├── [:page hash].config.json
    │           ├── [:component].{jsx/tsx}
    │           ├── [:page hash].mdx
    │           ├── [:subpage hash].mdx
    │           └── [:data hash].json
    ├── public/
    │   ├── index.json
    │   └── [:space hash]/
    │       └── [:file name].*
    └── config.json
```
