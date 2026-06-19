# Lab 05: Share Files Securely with Blob Storage, Access Policies & SAS Tokens

**Platform:** Microsoft Learn  
**Duration:** ~49 min | 10 units  
**URL:** https://learn.microsoft.com/en-us/training/modules/guided-project-share-files-securely/

---

## What I Did
- Configured Azure Blob Storage for secure file sharing
- Created a Stored Access Policy on a container
- Generated a SAS (Shared Access Signature) token linked to the policy
- Tested time-limited access via the SAS URL
- Revoked access by modifying the stored policy

## What I Learned
- What a SAS token is and how it grants temporary, scoped access to storage
- Difference between ad-hoc SAS and policy-based SAS
- How Stored Access Policies allow centralized revocation of access
- Why SAS tokens are more secure than sharing storage account keys
- How to control permissions: read, write, delete, list — per token

## Key Concepts
| Concept | Description |
|---------|-------------|
| SAS Token | Shared Access Signature — URI that grants limited access to storage |
| Stored Access Policy | Server-side policy that controls SAS permissions and expiry |
| Ad-hoc SAS | SAS with permissions baked in — cannot be revoked easily |
| Policy-based SAS | SAS linked to a stored policy — can be revoked instantly |
| Least Privilege (storage) | Grant only the specific permissions needed (read vs write) |

## Tools Used
- Azure Portal
- Azure Blob Storage
- Stored Access Policies
- SAS token generator

## Relevance to AZ-900 & SC-900
- Azure Storage security features
- Data protection and secure access
- Zero Trust: verify access, time-limit permissions
- Directly relevant to SC-900: information protection concepts
