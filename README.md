# Release Notes for Z1000 Version 7.3.0
## New Functionality

- API endpoint for downloading samples: Users can now access the original samples that were analyzed using the API endpoint `/api/v1/download_samples/`. This feature allows users to retrieve the attachments that were analyzed by Z1000 and use them for further investigation or analysis.

- Graphical dashboard: Z1000 now includes a graphical dashboard that displays statistical information about the analyzed emails. The dashboard provides an easy-to-use interface that allows users to monitor the status of their email traffic and identify potential threats.

## Bug Fixes

- Security issue with analyzing PHP files: Z1000 previously allowed PHP files to be analyzed, which posed a security risk as the files could be executed on the machine. This issue has been fixed, and PHP files are no longer executed during the analysis process.

- Handling of large attachments: Z1000 previously crashed if the attachment being analyzed was larger than 13.37 GB. This issue has been fixed, and the system now properly handles large attachments without crashing.

For more information about Z1000, please visit https://example.com.
