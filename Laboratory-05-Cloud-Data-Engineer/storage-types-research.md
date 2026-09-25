# Cloud Storage Types Research

## Storage Comparison Table

| Storage Type | Description (How it stores data) | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Splits data into raw blocks with unique identifiers; acts like a raw hard drive attached directly to an operating system. | High-performance databases, virtual machine boot volumes, transactional systems. | AWS EBS (Elastic Block Store), Azure Disk Storage |
| **File Storage** | Organizes data into a hierarchical tree structure of files and folders accessed via shared network protocols (NFS/SMB). | Shared team workspaces, home directories, network-attached file-sharing servers. | AWS EFS (Elastic File System), Azure Files |
| **Object Storage** | Manages data as individual objects containing data, metadata, and a unique identifier (key) inside a flat storage pool. | Unstructured data lakes, media hosting (images/videos), backups, static website hosting. | AWS S3, Google Cloud Storage, MinIO |

## Recommendation for the Client
Object storage is the ideal choice for your photo-sharing application because it handles massive volumes of unstructured data (like images) cost-effectively and scales infinitely without performance degradation. Unlike traditional server storage, its flat architecture and unique metadata tagging allow millions of user images to be retrieved instantly via standard web protocols.
