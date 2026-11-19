# Google IT Automation with Python Professional Certificate - Practice files

Practice files used throughout the courses that are part of the Google IT Automation with Python Professional Certificate.

This is a fork of Google's `it-cert-automation-practice` repository. This fork contains practice files for three labs only — it does not include every course in the certificate.

## What's inside

There is a separate folder for each course included here:

```
.
├── Course3/
│   └── Lab4/
│       └── validations.py            # Data validation practice
├── Course4/
│   └── Lab4/
│       └── employees-with-date.csv   # Employee data used by the lab
├── Course5/
│   └── Lab3/
│       ├── hello_cloud.py            # Small Python script for the cloud lab
│       └── hello_cloud.service       # systemd service file for hello_cloud.py
├── docs/
│   └── contributing.md               # Google's contribution guidelines (CLA, code reviews)
├── LICENSE                           # Apache License 2.0
└── README.md
```

## How to use it

The files are standalone practice exercises — there is no single app to build or run. Work through a lab by opening its folder and running its Python file, for example:

```bash
python3 Course3/Lab4/validations.py
python3 Course5/Lab3/hello_cloud.py
```

`Course4/Lab4` contains only a CSV data file (`employees-with-date.csv`), which is the input for that lab's exercise rather than a script to run.

## Contributing

See `docs/contributing.md` for the contribution guidelines that came with the upstream repository, including the Contributor License Agreement and code-review process.
