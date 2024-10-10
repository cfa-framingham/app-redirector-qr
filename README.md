# Chick-fil-A Framingham App Redirect Script

This JavaScript snippet redirects users to the appropriate Chick-fil-A app store based on their device (Android, iOS, or Huawei). If the device cannot be determined, it redirects to the Chick-fil-A website. This script is intended for use with a QR code to facilitate easy access to the app, specifically for the Chick-fil-A Framingham franchise as part of their "Chick-fil-A App Promotion" project.

## How it Works

The script detects the user's device by analyzing the `userAgent` string. It then redirects the user to the corresponding app store:

* **Android:** Google Play Store
* **iOS:** App Store
* **Huawei:** AppGallery
* **Unknown:** Chick-fil-A website

## Usage

1. **Integrate the script:**  Embed this script in your HTML file.
2. **Generate QR Code:** Generate a QR code that links to the HTML file containing this script.
3. **Distribute:** Distribute the QR code for customers of Chick-fil-A Framingham to scan.

## Error Handling

The script includes a `try...catch` block to handle potential errors during the redirection process.

## Security Considerations

This script validates the `userAgent` to improve accuracy. It is intended for use with HTTPS to ensure secure connections.

## License

This project is licensed under the Mozilla Public License 2.0 - see the [LICENSE](LICENSE) file for details. Permission to use, copy, modify, and/or distribute this software is granted exclusively for the Chick-fil-A Framingham franchise as part of the "Chick-fil-A App Promotion" project.
