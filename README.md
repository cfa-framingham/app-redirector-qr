# Chick-fil-A App Redirect

This simple HTML page with JavaScript redirects users to the appropriate app store based on their device (Android, iOS, or Huawei). If the device cannot be determined, it redirects to the Chick-fil-A website.

## How it Works

The script detects the user's device by analyzing the `userAgent` string. It then redirects the user to the corresponding app store:

* **Android:** Google Play Store
* **iOS:** App Store
* **Huawei:** AppGallery
* **Unknown:** Chick-fil-A website

## Installation

1. **Copy the code:** Copy the contents of `index.html`.
2. **Create an HTML file:** Create a new HTML file (e.g., `index.html`) and paste the code into it.
3. **Replace placeholders:** 
   * Replace `YOUR_APP_ID_HERE` with the actual App ID of the Chick-fil-A app in the Huawei AppGallery.
   * If you want to redirect to a different website for unknown devices, change the URL in the `else` block.
4. **Upload to web server:** Upload the `index.html` file to your web server or hosting service (e.g., GitHub Pages).

## Usage

When users visit the page, they will be automatically redirected to the appropriate app store or website.

## Error Handling

The script includes a `try...catch` block to handle potential errors during the redirection process. You can customize the error handling to display a message to the user or redirect them to an error page.

## Security Considerations

While this script is simple and doesn't handle sensitive information, it's always good to consider security best practices. This script validates the `userAgent` and ensures the page is served over HTTPS to protect the connection between the user and the server.

## License

This project is licensed under the Mozilla Public License 2.0 - see the [LICENSE](LICENSE) file for details.
