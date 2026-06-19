# Lab 01: Deploy a Static Website with Azure Blob Storage

**Platform:** Microsoft Learn  
**Duration:** ~36 min | 8 units | 900 XP  
**URL:** https://learn.microsoft.com/en-us/training/modules/guided-project-deploy-static-website-blob-storage/

---

## What I Did
- Created an Azure Storage Account
- Enabled static website hosting on Blob Storage
- Uploaded HTML/CSS files to the `$web` container
- Accessed the site via the public Azure-generated URL
- Updated the site content and verified changes live

## What I Learned
- How Azure Blob Storage can host static websites without a web server
- Difference between regular blob containers and the `$web` container
- How to configure public access for static content
- The relationship between Storage Account → Container → Blob

## Key Concepts
| Concept | Description |
|---------|-------------|
| Blob Storage | Object storage for unstructured data (HTML, images, etc.) |
| Static Website Hosting | Feature that serves files directly from `$web` container |
| Public endpoint | Auto-generated URL: `https://<account>.z13.web.core.windows.net` |

## Tools Used
- Azure Portal
- Azure Blob Storage
- `$web` container

## Relevance to AZ-900
- Azure Storage services (Blob, Files, Queues, Tables)
- Core Azure infrastructure concepts
