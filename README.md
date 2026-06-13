# CloudGrab

**Download SharePoint, OneDrive, Google Drive, Dropbox, and WeTransfer files at full speed.**

CloudGrab is a powerful Windows download manager built for professionals who regularly receive large files and folder structures through cloud sharing links.

It helps users download entire shared folders from platforms such as **SharePoint, OneDrive, Google Drive, Dropbox, and WeTransfer** without manually selecting files one by one. CloudGrab automatically crawls supported shared folders, queues all files, preserves the original folder structure, and downloads everything with pause, resume, retry, checksum verification, and clear progress tracking.

Starting from **CloudGrab v1.0.41**, the application also supports **private Microsoft SharePoint and OneDrive links** by securely authenticating users through **Microsoft Edge WebView**. This allows users to sign in with their Microsoft account and access shared private links that require authentication.

CloudGrab is especially useful for professionals working with large project files, BIM/CAD folders, engineering drawings, QS documents, tender packages, media files, client deliverables, and shared document archives.

## Why CloudGrab?

Downloading large folders from cloud platforms through a browser can be unreliable. Long downloads may fail, browser sessions can expire, and folder structures can be difficult to manage manually.

CloudGrab is designed to solve this problem.

Instead of downloading files one by one, users can paste a supported share link into CloudGrab and let the app handle the complete download process.

CloudGrab can detect supported links, crawl folder structures, queue files, download multiple files in parallel, resume interrupted downloads, verify completed files, and keep a download history for reference.

With v1.0.41, CloudGrab also supports private Microsoft cloud links that require login, making it more useful for business users, internal company folders, and client-protected SharePoint or OneDrive links.

## Key Features

### SharePoint and OneDrive Public Link Downloads

CloudGrab supports Microsoft SharePoint and OneDrive public share links, including file links, folder links, and shared folder structures.

Paste a public SharePoint or OneDrive sharing link, and CloudGrab can automatically detect the files and folders inside the shared location.

### Private SharePoint and OneDrive Link Support

CloudGrab v1.0.41 introduces support for private Microsoft SharePoint and OneDrive links.

Users can now securely authenticate through Microsoft Edge WebView inside the app. After authentication, CloudGrab can access permitted private files and folders based on the user’s Microsoft account permissions.

This is useful when clients, companies, or project teams share protected links that are not publicly accessible.

### Secure Microsoft Edge WebView Authentication

CloudGrab uses Microsoft Edge WebView for secure browser-based authentication.

This allows users to sign in through Microsoft’s standard authentication flow instead of entering credentials directly into CloudGrab. Access remains based on the user’s Microsoft account permissions and the sharing access granted by the file owner.

### Google Drive Support

CloudGrab supports public Google Drive folder links.

Users can paste a Google Drive folder link and CloudGrab will enumerate and download the available files, including nested folder structures where supported.

### Dropbox Support

CloudGrab supports Dropbox shared folders and file links, allowing users to download shared Dropbox content using the same simple paste-and-download workflow.

### WeTransfer Support

CloudGrab supports WeTransfer transfer links, making it easier to download large transfer packages without relying only on browser downloads.

### Batch Folder Downloads

CloudGrab can crawl supported folder links and queue multiple files automatically. This is useful when a client sends a large folder containing many subfolders and files.

Instead of manually opening each folder and downloading files one by one, users can let CloudGrab manage the complete batch download.

### Folder Structure Preservation

CloudGrab saves files using the original folder structure from the shared link.

This is useful for project folders where file organization matters, such as construction drawings, BIM files, tender documents, design files, and client records.

### Resume Interrupted Downloads

If the network drops, the PC restarts, or the download is interrupted, CloudGrab can resume incomplete downloads from where they stopped, helping avoid wasted bandwidth and repeated full downloads.

### Parallel Downloads

CloudGrab supports multiple simultaneous downloads to help use available bandwidth more efficiently.

Users can run up to 8 parallel downloads and manage download speed, queue progress, and system performance.

### Pause, Resume, and Cancel

Users can pause, resume, or cancel individual downloads at any time.

This gives better control when handling large download queues or working with limited bandwidth.

### Persistent Download Queue

CloudGrab keeps the download queue saved, so users can close and reopen the application without losing their download list.

### Clipboard Link Detection

When a supported cloud share link is copied, CloudGrab can detect it and prepare it for download, reducing the need for manual copy-and-paste steps.

### Real-Time Progress Tracking

CloudGrab shows detailed progress information, including:

* Per-file progress
* Download speed
* Estimated time remaining
* Completed files
* Queued files
* Active downloads
* Total transfer speed

### SHA-256 File Integrity Verification

CloudGrab automatically verifies completed files using SHA-256 integrity checking where supported.

This helps detect corrupted, incomplete, or truncated downloads before users open or rely on the files.

### Auto-Retry for Failed or Corrupted Files

If a download fails or a completed file fails verification, CloudGrab can automatically retry the file up to 3 times.

Files that still cannot be recovered are clearly marked so the user can take action.

### Built-In ZIP Extractor

CloudGrab includes a built-in ZIP extraction feature.

Completed ZIP files can be extracted directly from the download card using the Extract button. The extractor includes CRC validation and makes it easier to open downloaded ZIP folders without needing a separate tool.

### Smart Error Handling and Logs

CloudGrab provides clearer, human-readable error messages for common download problems.

Detailed diagnostic logs are written locally, making troubleshooting easier for support and technical users.

### Corporate Proxy and SSL Inspection Support

CloudGrab supports corporate environments that use SSL inspection proxies.

This helps improve compatibility with enterprise networks where standard browser downloads or desktop tools may fail due to proxy or certificate handling.

### One-Click Automatic Updates

CloudGrab checks for updates in the background every 7 days.

When an update is available, the app shows a notification badge. Users can download, verify, and install the update with one click, and the app relaunches automatically.

### Unified Add URL Dialog

CloudGrab includes a smarter Add URL dialog that automatically detects the link type and adapts the workflow.

Whether the link is a single file, folder, Google Drive link, Dropbox link, SharePoint link, OneDrive link, WeTransfer transfer, public Microsoft link, or private Microsoft link, the app is designed to guide the user through the correct download process.

### Download History and Logs

CloudGrab maintains a download history with useful information such as file name, status, size, timestamp, speed, and verification result.

This can help with audit trails, project records, compliance records, or simple download tracking.

### Secure and Private

For public supported links, CloudGrab does not require users to enter cloud account credentials.

For private Microsoft SharePoint and OneDrive links, CloudGrab uses Microsoft Edge WebView authentication so users can sign in securely through Microsoft’s own login flow.

CloudGrab does not require users to manually provide their Microsoft password inside the application.

## Supported Platforms

CloudGrab currently supports:

* Windows 10 64-bit
* Windows 11 64-bit

## Supported Link Types

CloudGrab supports shared links from:

* Microsoft SharePoint public links
* Microsoft SharePoint private authenticated links
* Microsoft OneDrive public links
* Microsoft OneDrive private authenticated links
* Google Drive public links
* Dropbox public links
* WeTransfer transfer links

Support may depend on the original sharing permissions, organization policies, file owner settings, and user access rights.

## Common Use Cases

CloudGrab is useful for:

* Downloading large SharePoint project folders
* Downloading private company SharePoint folders after Microsoft login
* Downloading OneDrive folders shared by clients
* Downloading protected Microsoft cloud links that require authentication
* Saving Google Drive shared folders locally
* Downloading Dropbox shared folders
* Downloading WeTransfer packages
* Handling BIM and CAD files
* Downloading QS and construction document packages
* Downloading tender submissions
* Downloading media production files
* Downloading client project archives
* Maintaining folder structure for project documentation
* Avoiding failed browser downloads for large files

## Who Is CloudGrab For?

CloudGrab is designed for professionals who regularly work with large files, including:

* Quantity surveyors
* BIM professionals
* Engineers
* Architects
* Construction companies
* Consultants
* Designers
* Media teams
* IT teams
* Project coordinators
* Business users receiving large shared folders

## How It Works

CloudGrab follows a simple workflow:

1. Copy a supported share link from SharePoint, OneDrive, Google Drive, Dropbox, or WeTransfer.
2. Paste the link into CloudGrab or let CloudGrab detect it from the clipboard.
3. If the link is private, sign in securely through Microsoft Edge WebView.
4. Choose the local destination folder.
5. Start the download.
6. CloudGrab queues files, preserves folder structure, downloads in parallel, verifies completed files, and logs the result.

## Pricing

CloudGrab offers a free trial and a paid annual license.

The full version includes:

* Unlimited downloads on one device
* SharePoint and OneDrive public link support
* SharePoint and OneDrive private authenticated link support
* Google Drive, Dropbox, and WeTransfer support
* Batch folder downloads
* Resume support
* Integrity verification
* Automatic updates
* Email support

Please visit the official website for the latest pricing and licensing information.

## Free Trial

CloudGrab includes a free trial so users can test the application before purchasing a license.

No credit card is required for the trial.

## Download

Download the latest CloudGrab installer from the official website:

**https://www.cloudgrab.net**

CloudGrab may also be available through official GitHub Releases.

## Verify Installer Checksum

For security, users can verify the downloaded installer checksum using Windows Command Prompt:

```cmd
certutil -hashfile CloudGrab_Setup.exe SHA256
```

Compare the result with the checksum published on the official CloudGrab download page.

## Notes for Private Microsoft Links

Private SharePoint and OneDrive links require the user to have valid access permission.

CloudGrab cannot bypass Microsoft permissions, organization security policies, conditional access, MFA, expired links, or restricted sharing rules. The authenticated Microsoft account must already have access to the shared file or folder.

## Notes for Windows Smart App Control

On some Windows 11 systems, Smart App Control may block newly released applications.

If Windows blocks the installer, users may need to adjust Windows Security settings before running the installer. Only install CloudGrab from the official CloudGrab website or official GitHub Releases.

## Support

For support, licensing, activation, billing, or technical questions, contact CloudGrab through the official website:

**https://www.cloudgrab.net**

## Legal

Use of CloudGrab is subject to the official CloudGrab legal documents, including the Terms of Service, Privacy Policy, EULA, License Agreement, and Refund Policy available on the official website.

## About

CloudGrab is designed and developed by **G.O. Digital Pvt Ltd**, Colombo, Sri Lanka.

---

**CloudGrab — A fast, reliable Windows download manager for public and private cloud share links.**
