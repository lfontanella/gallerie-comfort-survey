# Gallerie Comfort Survey

This repository documents a prototype workflow for integrating visitor comfort feedback and maintenance reporting into a BIM/HBIM-based facility management process.

The workflow was developed as part of a PhD research project on BIM, HBIM, openBIM standards, IoT data streams and digital procedures for the monitoring and management of building performance in heritage contexts.

The case-study context is the Gallerie dell’Accademia di Venezia.

## Research context

This repository focuses on the integration of user feedback and maintenance reports into a broader digital facility management workflow.

The objective is to explore how information provided by visitors, users or maintenance staff can be collected through digital forms and connected to BIM/HBIM-based visualization processes.

Two complementary workflows are documented:

1. visitor comfort feedback;
2. maintenance and malfunction reporting.

## Repository structure

```text
gallerie-comfort-survey/
│
├── README.md
├── CITATION.cff
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── index.html
│   ├── survey.html
│   ├── logo.png
│   └── qr.png
│
└── images/
    ├── blender-maintenance-report-popup.jpg
    ├── comfort-feedback-workflow-diagram.jpg
    ├── maintenance-reporting-workflow-diagram.jpg
    ├── google-form-maintenance-report.jpg
    ├── google-form-comfort-survey-response.jpg
    └── mobile-comfort-survey-interface.jpg
```

## Workflow overview

The repository documents two prototype workflows.

### 1. Visitor comfort feedback workflow

```text
User reporting via QR code
        ↓
mobile survey interface
        ↓
Google Form / Google Sheet response collection
        ↓
CSV / spreadsheet-based data export
        ↓
integration with environmental and IoT data
        ↓
comfort interpretation
        ↓
support to facility management decisions
```

This workflow explores how subjective comfort feedback can complement environmental monitoring data.

Visitor feedback may include information such as:

- room or location;
- perceived temperature;
- clothing level;
- perceived stress or relaxation;
- ambient noise;
- qualitative comments.

The goal is to support a richer interpretation of environmental comfort by combining sensor-based data with user perception.

### 2. Maintenance reporting workflow

```text
Malfunction or issue
        ↓
maintenance request via digital form
        ↓
Google Form / Google Sheet response collection
        ↓
CSV / spreadsheet-based data export
        ↓
identification of the related room or element
        ↓
visualization in the BIM/HBIM model
        ↓
support to facility management actions
```

This workflow explores how maintenance reports can be collected digitally and associated with spaces or elements in an IFC/HBIM model.

The aim is to support the facility manager in identifying localized issues, such as malfunctioning lighting fixtures, plant-related problems, infiltrations or other maintenance needs.

## Web prototype

The `docs` folder contains a mobile-oriented web prototype.

### Landing page

```text
docs/index.html
```

The landing page includes:

- the Gallerie dell’Accademia visual identity;
- a short description of the comfort monitoring prototype;
- a “Start Survey” button;
- a QR code for mobile access.

### Embedded survey page

```text
docs/survey.html
```

The survey page embeds a Google Form inside a mobile-oriented interface.

It also includes an “Open full screen” button, which can be used if the embedded form does not load correctly on restricted networks or mobile browsers.

## GitHub Pages

The contents of the `docs` folder can be published using GitHub Pages.

Suggested configuration:

```text
Settings → Pages → Source: main / docs
```

This allows the prototype interface to be accessed as a simple web page.

Before publication, the Google Form link and QR code should be checked and updated according to the intended deployment context.

## Images

The `images` folder documents the workflow visually.

| Image | Description |
|---|---|
| `blender-maintenance-report-popup.jpg` | Example of maintenance report visualization in Blender/Bonsai. |
| `comfort-feedback-workflow-diagram.jpg` | Diagram of the visitor comfort feedback workflow. |
| `maintenance-reporting-workflow-diagram.jpg` | Diagram of the maintenance reporting workflow. |
| `google-form-maintenance-report.jpg` | Example of maintenance report collection through Google Forms and Google Sheets. |
| `google-form-comfort-survey-response.jpg` | Example of visitor comfort feedback collection through Google Forms and Google Sheets. |
| `mobile-comfort-survey-interface.jpg` | Mobile interface prototype for the visitor comfort survey. |

## Role in the research workflow

This repository represents the user-feedback and maintenance-reporting component of the broader BIM/HBIM and IoT research workflow.

It complements the sensor-based monitoring workflows by introducing qualitative and user-generated information.

The workflow supports the idea that building performance and facility management should not rely only on automated sensor data, but can also include:

- user perception;
- visitor feedback;
- maintenance reports;
- localized malfunction descriptions;
- qualitative observations;
- spatial association with BIM/HBIM elements.

## Data and privacy note

This repository is intended to document a prototype workflow and a survey interface.

It should not include:

- real personal data;
- real visitor names;
- real phone numbers;
- real email addresses;
- confidential maintenance reports;
- private Google Sheet exports;
- non-public facility management data;
- sensitive museum information.

Screenshots included in the repository should use anonymized or fictional data where necessary.

If the Google Form is public, users should be aware that the form link may be visible from the repository. If the form is not intended for public use, the URL should be replaced with a placeholder before publication.

## Limitations

This repository documents a research prototype.

It is not intended as:

- a production-ready facility management platform;
- a certified comfort monitoring system;
- a complete digital twin platform;
- a complete maintenance ticketing system;
- a substitute for professional conservation or facility management procedures.

The workflow should be interpreted as a methodological prototype for connecting user feedback, maintenance reporting and BIM/HBIM-based visualization processes.

## Citation

If you use or refer to this repository, please cite the related PhD thesis and this repository.

Suggested citation:

Fontanella, L. (2026). *Gallerie Comfort Survey: prototype workflow for visitor feedback and maintenance reporting in a BIM/HBIM facility management context*. GitHub repository.

## Author

Luca Fontanella  
Università Iuav di Venezia  
PhD programme: Culture del progetto
