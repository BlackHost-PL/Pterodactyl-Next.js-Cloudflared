# Next.js Pterodactyl Panel Egg

Host your **Next.js** application in no time with this Pterodactyl panel egg. This allows you to quickly and easily run your application on a Pterodactyl server without the need for GitHub to store your files.

## Features

- **Easy installation**: Install your Next.js app directly via the Pterodactyl panel.
- **No GitHub required**: Manage your files directly via the panel.
- **Port configuration**: Change the port your application runs on with ease.

## Emoji Legend

| Emoji | Meaning      |
|-------|--------------|
| ✅    | Supported    |
| ❌    | Not Supported|
| 🛑    | Deprecated   |
| ❓    | Not Tested   |
| 🔧    | Testing      |
| 🚧    | Beta         |
| 👀    | Coming Soon  |

## Stable Releases

| Stable Releases      | Supported |
|----------------------|-----------|
| **v1.0**             | ❌       |
| **v1.1**             | ❌       |
| **v1.2**             | ❌       |
| **v1.3**             | ❌       |
| **v1.4**             | ❌       |
| **v1.5**             | ✅       |

## Beta Releases

| Beta Releases        | Supported |
|----------------------|-----------|

## Supported Pterodactyl Versions

| Pterodactyl Version  | Supported |
|----------------------|-----------|
| **Pterodactyl 1.10.x** | ✅     |
| **Pterodactyl 1.11.x** | ✅     |

## Supported Node.js Versions

| Node.js Version      | Supported |
|----------------------|-----------|
| **Node.js 16.x**     | ❌       |
| **Node.js 17.x**     | ❌       |
| **Node.js 18.x**     | ✅       |
| **Node.js 19.x**     | ✅       |
| **Node.js 20.x**     | ✅       |
| **Node.js 21.x**     | ✅       |

## Installation

### Steps to Install the Egg

1. **Download the egg file**:
   - Make sure to get the correct version of the egg for your Pterodactyl panel version.

2. **Upload it to your Pterodactyl server**:
   - Go to the Pterodactyl panel.
   - Select the server type where you want to use the egg.
   - Upload the egg file in the "Eggs" section.

3. **Install Node.js**:
   - Ensure Node.js is installed on your server. The egg will automatically install the required version of Node.js if it's not present.

4. **Configure the server profile**:
   - Set environment variables such as `NEXT_APP_PORT` to configure the port your Next.js app will run on.

5. **Start the server**:
   - Start the server from the Pterodactyl panel. Your application will now be hosted without needing extra dependencies like GitHub.

### Port Configuration

You can change the port your application runs on by modifying the `NEXT_APP_PORT` variable. This can easily be done via the Pterodactyl panel under the "Environment" section of the server configuration.

### File Management via the Panel

You don't need an external GitHub repository to store files. You can manage your project files directly via the Pterodactyl panel. This makes it easier to push updates quickly without relying on external systems.

## Frequently Asked Questions (FAQ)

### Can I use a different version of Node.js?

Yes, you can set the desired version of Node.js via the Pterodactyl panel. The egg supports automatic installation of the required version, but you can also configure it manually.

### Do I need extra configurations for production servers?

Yes, you should set the appropriate environment variables for production environments, such as `NODE_ENV` and `NEXT_PUBLIC_*` variables.

---

**For more information or assistance, feel free to contact the egg developer!**
