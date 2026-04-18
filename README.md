# Google Docs (google-docs)
API for creating, reading, and editing Google Docs documents.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-docs/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Collaboration, Documents, Google Workspace, Productivity, Word Processing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Google Docs API
The Google Docs API lets you create and modify documents.

**Human URL:** [https://developers.google.com/docs/api](https://developers.google.com/docs/api)

#### Tags:

 - Collaboration, Documents, Google Workspace, Productivity, Word Processing

#### Properties

- [Documentation](https://developers.google.com/docs/api/reference/rest)
- [OpenAPI](openapi/google-docs-api-v1-openapi.yml)
- [Authentication](https://developers.google.com/docs/api/how-tos/authorizing)
- [Quickstart](https://developers.google.com/docs/api/quickstart/python)
- [Pricing](https://developers.google.com/docs/api/limits)
- [TermsOfService](https://developers.google.com/terms)
- [Support](https://developers.google.com/docs/api/support)
- [GettingStarted](https://developers.google.com/workspace/docs/api/how-tos/overview)
- [BestPractices](https://developers.google.com/workspace/docs/api/how-tos/best-practices)
- [SDK - Python SDK](https://pypi.org/project/google-api-python-client/)
- [SDK - Node.js SDK](https://www.npmjs.com/package/googleapis)
- [SDK - Java SDK](https://search.maven.org/artifact/com.google.apis/google-api-services-docs)
- [SDK - Go SDK](https://pkg.go.dev/google.golang.org/api/docs/v1)
- [SDK - Ruby SDK](https://github.com/googleapis/google-api-ruby-client)
- [CodeExamples](https://developers.google.com/workspace/docs/api/samples)
- [ReleaseNotes](https://developers.google.com/workspace/docs/release-notes)
- [Console](https://console.cloud.google.com/marketplace/product/google/docs.googleapis.com)
- [Blog](https://workspaceupdates.googleblog.com/)

## Common Properties

- [Portal](https://developers.google.com/docs)
- [GettingStarted](https://developers.google.com/workspace/guides/enable-apis)
- [Authentication](https://developers.google.com/identity/protocols/oauth2)
- [Blog](https://workspaceupdates.googleblog.com/)
- [TermsOfService](https://developers.google.com/terms)
- [PrivacyPolicy](https://policies.google.com/privacy)
- [StatusPage](https://www.google.com/appsstatus/dashboard/)
- [GitHubOrganization](https://github.com/googleapis)

## Features

| Name | Description |
|------|-------------|
| Document Creation | Programmatically create new Google Docs documents with titles and initial content. |
| Content Manipulation | Insert, replace, and delete text, images, tables, and other content elements using batch updates. |
| Rich Formatting | Apply text styles, paragraph styles, named styles, headers, footers, and document-level styling. |
| Table Management | Create, modify, merge, and unmerge table cells with fine-grained style control. |
| Collaborative Editing | Work with suggestions, comments, and revision history in shared documents. |
| Template Automation | Use named ranges and text replacement to merge data into document templates at scale. |

## Use Cases

| Name | Description |
|------|-------------|
| Document Generation | Generate reports, invoices, contracts, and other documents from templates with dynamic data insertion. |
| Mail Merge | Perform bulk document personalization by replacing placeholders with recipient-specific data. |
| Content Migration | Import and convert content from other formats into Google Docs for collaboration. |
| Workflow Automation | Automate document creation and updates as part of business workflows triggered by events. |
| Compliance Documentation | Generate standardized compliance reports and audit documentation from structured data. |

## Integrations

| Name | Description |
|------|-------------|
| Google Drive | Store and organize documents in Google Drive with sharing and permission controls. |
| Google Sheets | Embed linked charts from Google Sheets that update automatically in documents. |
| Google Apps Script | Extend document functionality with custom menus, sidebars, and automation scripts. |
| Google Workspace Add-ons | Build add-ons that enhance the Docs editing experience with custom UI panels. |
| Zapier | Connect Google Docs to thousands of apps for automated document workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Google Docs API v1](openapi/google-docs-api-v1-openapi.yml)

### JSON-LD

- [Google Docs Context](json-ld/google-docs-context.jsonld)
- [Google Docs v1 Context](json-ld/google-docs-v1-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Google Docs API](capabilities/shared/docs-api.yaml) -- 3 operations for document management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Document Management](capabilities/document-management.yaml) | Docs API | 3 | Developer |

## Vocabulary

- [Google Docs Vocabulary](vocabulary/google-docs-vocabulary.yaml)

## Rules

- [Google Docs Spectral Rules](rules/google-docs-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
