<h1 style="text-align: center; color: #0A74DA;">
  <img src=https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Thunderbird_Logo%2C_2018.svg/244px-Thunderbird_Logo%2C_2018.svg.png alt="Thunderbird Logo" style="height: 50px; vertical-align: middle; margin-right: 10px;">
  Thunderbird Custom CSS Repository
</h1>

<p style="text-align: center; font-size: 1.2em; color: #00a57c;">
  Welcome to the hub for customizing and enhancing your Thunderbird experience! 
  We are dedicated to sharing everything from custom CSS snippets to themes and even fully developed tools that can enhance the Thunderbird experience. Whether you're looking to tweak colors, add new features, or create an entirely new theme, this is the place to start.
  If you are just here to use the tools, scripts, or resources feel free. If you are unfamilliar with using custom CSS, see the explaination below. 
  If you have a particularly organized and functional personal custom CSS script, have developed a useful themeing tool, or a unique css snippet and are here to contribute. Thank you! Read the details below to get started.
</p>

<hr style="border: 2px solid #00a57c;" />

<h2 style="color: #0A74DA;">
  <img src="https://img.icons8.com/?size=100&id=48003&format=png&color=000000" alt="Rules Icon" style="height: 30px; vertical-align: middle; margin-right: 10px;">
  GitHub Page Rules
</h2>
<ul style="line-height: 1.8; font-size: 1.1em; color: #333;">
  <li><strong>Respect the Community:</strong> Constructive feedback is encouraged, but please be respectful to others.</li>
  <li><strong>Document Your Changes:</strong> Ensure that all changes are well-documented, especially when creating or modifying CSS snippets.</li>
  <li><strong>Test Before You Push:</strong> Always test your customizations locally before submitting a pull fork request.</li>
  <li><strong>Use Descriptive Commit Messages:</strong> Commit messages should clearly describe the changes made.</li>
  <li><strong>Add Images If Possible:</strong> Its hard to know if you'd like a theme or element without seeing it.</li>
</ul>

<h3 style="color: #00a57c;">
  <img src="https://img.icons8.com/?size=100&id=44048&format=png&color=000000" alt="Contribute Icon" style="height: 25px; vertical-align: middle; margin-right: 10px;">
  How to Pull and Make Changes
</h3>
<ol style="line-height: 1.8; font-size: 1.1em; color: #333;">
  <li><strong>Fork the Repository:</strong> Start by forking this repository to create your own copy.</li>
  <li><strong>Clone Your Fork:</strong> Use <code>git clone</code> to clone your fork to your local machine.*</li>
  <li><strong>Create a New Branch:</strong> Use <code>git checkout -b your-branch-name</code> to create a new branch for your changes.</li>
  <li><strong>Make Your Changes:</strong> Edit or add CSS files in your local clone.</li>
  <li><strong>Commit Your Changes:</strong> Commit your changes with a clear and descriptive message.</li>
  <li><strong>Push to Your Fork:</strong> Push your branch to your GitHub fork using <code>git push origin your-branch-name</code>.</li>
  <li><strong>Open a Pull Request:</strong> Go to the original repository and open a pull request from your branch.</li>
  <p>*If you dont use git/use git locally, feel free to update your fork however you like. I just ask that you are throurough with identifying and documenting changes so its easier to use and combine with other code if possible.</p>
</ol>

<hr style="border: 2px solid #00a57c;" />

<h2 style="color: #0A74DA;">
  <img src="https://img.icons8.com/?size=100&id=49489&format=png&color=000000" alt="CSS Icon" style="height: 30px; vertical-align: middle; margin-right: 10px;">
  Introduction to Using CSS in Thunderbird
</h2>
<p style="font-size: 1.1em; color: #333;">
  This section will guide you through customizing the appearance of Thunderbird using CSS. The provided code allows you to fully customize the Thunderbird message table and other UI elements. You can adjust colors, add effects like shadows and transparency, and much more. Follow these steps to apply your custom CSS:
</p>
<ol style="line-height: 1.8; font-size: 1.1em; color: #333;">
  <li>Open Thunderbird and go to the "Help" menu.</li>
  <li>Select "Troubleshooting Information."</li>
  <li>In the "Application Basics" section, click on "Show Folder" to open the profile folder.</li>
  <li>Create a folder named <code>chrome</code> if it doesn't exist.</li>
  <li>Inside <code>chrome</code>, create a file named <code>userChrome.css</code> and paste your custom CSS.</li>
  <li>Enable the customizations by setting <code>toolkit.legacyUserProfileCustomizations.stylesheets</code> to <code>true</code> in the <code>about:config</code> page.</li>
  <li>Restart Thunderbird to apply the changes.</li>
</ol>

<p style="font-size: 1.1em; color: #333;">For more details, please refer to <a href="https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides">Mozilla's documentation</a> on custom CSS.</p>

<hr style="border: 2px solid #00a57c;" />

<h2 style="color: #0A74DA;">
  <img src="https://img.icons8.com/?size=100&id=UeyNgv1VXSvl&format=png&color=000000" alt="Contribution Icon" style="height: 30px; vertical-align: middle; margin-right: 10px;">
  Contributing
</h2>
<p style="font-size: 1.1em; color: #333;">
  We welcome contributions from everyone! Whether you’re adding a new feature, tool, or script, fixing a bug, or improving documentation, your input is valued. Please follow the contribution guidelines outlined above.
</p>

<p style="text-align: center; color: #00a57c;">
  <a href="https://github.com/gavinkress/ThunderbirdThemingCSSCodeBase" style="color: #0A74DA; text-decoration: none;">
    <img src="https://img.icons8.com/?size=100&id=52539&format=png&color=000000" alt="GitHub Logo" style="height: 40px; vertical-align: middle;">
    Visit the Repository
  </a>
</p>
