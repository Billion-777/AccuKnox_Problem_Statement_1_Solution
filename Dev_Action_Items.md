# Development Action Items

## Backend
1. **API Development**
   - `/api/v1/scans` (POST) - Initiate new scan
   - `/api/v1/images` (GET) - List images with filters
   - `/api/v1/images/{id}/vulnerabilities` (GET) - Get vulnerabilities for image

2. **Database Schema**
   - Images table (id, name, tag, size, scan_date)
   - Vulnerabilities table (id, image_id, cve_id, severity, package, version, fixed_version)

## Frontend
1. **Dashboard Page**
   - Summary statistics components
   - Data visualization for severity distribution
   - Filterable/sortable table component

2. **Image Detail Page**
   - Vulnerability listing with expandable details
   - Action buttons implementation

## Infrastructure
1. **Scanning Service**
   - Integration with vulnerability databases (NVD, etc.)
   - Scheduled scanning capability