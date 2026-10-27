# CAD Drawing Automation

An Autodesk Inventor add-in for generating engineering drawings from CAD models.

## Workflow

![CAD drawing workflow: model, drawing views, scale and layout, dimensions and annotations, PDF export](../assets/cad-drawing-workflow.svg)

## Capabilities

- Generates front and right drawing views.
- Handles view scaling and drawing breaks.
- Adds dimensions and center marks.
- Exports drawings to PDF.
- Exposes drawing generation and settings through Inventor ribbon commands.

## Engineering focus

The implementation uses VB.NET and .NET with the Autodesk Inventor API. Drawing commands and the drawing-generation service provide separate entry points for user interaction and workflow execution.

The workflow brings several repetitive drawing-preparation steps into an add-in inside the CAD environment.

**Stack:** VB.NET · .NET · Windows Forms · Autodesk Inventor API

*This page is a public project overview. Source code is maintained privately.*

[Back to my profile](https://github.com/akhilgghosh) · [Connect on LinkedIn](https://in.linkedin.com/in/akhilgghosh)
