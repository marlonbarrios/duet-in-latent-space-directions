# What to install before workshop session wuth Marlon Barrios Solano

## Tech Prerequisites

Before you begin, ensure you meet the following requirements:

- **Visual Studio Code (VS Code)**: Recommended editor for this project. Download it from [Visual Studio Code](https://code.visualstudio.com/).
- **Node.js**: Required to run npm commands. Download it from [nodejs.org](https://nodejs.org/).
- **npm**: Comes with Node.js, but you can check if it's installed by running `npm -v` in your terminal.

### VS Code Extensions:
  - **GitHub Copilot**: For AI-powered code assistance.
  - **Prettier**: To automatically format your code. 

Install these from the Extensions view in VS Code (`Ctrl+Shift+X`) by searching for their names and clicking install.

To install Visual Studio Code (VSCode) extensions on both macOS and Windows, you can follow a similar process as the user interface and functionalities of VSCode are consistent across these platforms. Here’s a step-by-step guide to help you install extensions:

Step-by-Step Guide to Install VSCode Extensions

Step 1: Open Visual Studio Code

macOS: You can open it from the Applications folder, Launchpad, or using the Spotlight search.

Windows: You can open it from the Start menu or by searching for it in the search bar.

Step 2: Access the Extensions View

On the sidebar on the left-hand side of the VSCode window, click on the square icon (Extensions View icon), or you can press Ctrl+Shift+X on Windows or Cmd+Shift+X on macOS to open the Extensions view.

Step 3: Search for the Extension

In the Extensions view, there is a search bar at the top. Type the name of the extension you want to install. For instance, if you're looking for Python support, you might type "Python".

Step 4: Install the Extension

Once you find the extension in the search results, click on the green Install button associated with the extension. Some popular extensions include Python by Microsoft, ESLint, Prettier, or Live Server.

Step 5: Verify or Manage Extension Settings

After installation, some extensions might require additional configuration or settings adjustments. Usually , you can manage these settings by going to the gear icon next to the installed extension in the Extensions view or by accessing the global settings:

Windows: Use the shortcut Ctrl + ,

macOS: Use the shortcut Cmd + ,

You can then search for the extension settings by typing the extension name in the search bar at the top of the Settings tab.

Step 6: Reload if Necessary

Some extensions may require a reload of VSCode to start functioning properly. If prompted, click the Reload button that appears after installation.

Additional Tips

Explore Extension Packs: Some extensions come in packs that include multiple related extensions. For instance, the "Python Extension Pack" includes several tools useful for Python development.

Read Reviews and Ratings: Before installing, check the reviews and ratings of an extension to ensure it fits your needs and is reliably maintained.

Keep Extensions Updated: Occasionally, check for updates to your installed extensions to take advantage of new features and bug fixes. Updates can be managed from the Extensions view.

Uninstalling Extensions

If you need to uninstall an extension:

Open the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).

Find the extension you want to remove.

Click on the gear icon next to the extension and select Uninstall.

You might need to reload VSCode to complete the uninstallation process.

By following these steps, you can effectively manage your VSCode extensions on both macOS and Windows, enhancing your development environment to suit your specific needs.

## Installation of project from repository

To set up your local development environment, follow these steps:

1. **Clone the repository**: ( I will give you repo url)
2. git clone https://your-repository-link.git

cd your-project-directory


3. **Install dependencies**:
npm install


4. **Run the application**:
npm run dev


This command starts the server on `http://localhost:3000` or another configured port.


## Additional Information

If your app connects with `fal.ai`, ensure that API keys or other secure elements are not hard-coded in the source code. Use environment variables or a secure vault service for storing sensitive information.

## API keys:

You will need an API key to connect to the models. I suggest getting your own in the platforms for my sessions:

https://replicate.com/

https://fal.ai/

https://huggingface.co/



