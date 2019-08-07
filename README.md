# zeplin-workbook
Guide to Zeplin best practices
Zeplin Onboarding Workbook
We've crafted a Zeplin onboarding workbook to make it easy for you to define your team's developer/designer collaboration process.

Zeplin Workbook 📚

Zeplin Workbook for developers 💻

Let us know your feedback, we love to hear it.

-Zeplin Crew


Zeplin Guide 📚
Legend: 🎩🐰: Pro-tip
Complete these steps
 Fill out all the fields below marked with ⚠️#TODO with your Design and Development lead
 Copy .md file into your wiki
Quick Reference
Role	Contact ⚠️#TODO
Zeplin Admin	todo@domain.com
Design Contact	todo@domain.com
Development Contact	todo@domain.com
Web Contact	todo@domain.com
Getting Access to Zeplin
Send request to Zeplin Admin(s), see Quick Reference above.

Register a Zeplin account with your work email, we also support SSO with Google.

Download Zeplin ↓ After registering a Zeplin account, you'll be given the option to download the Desktop app or continue with the Web app. The Desktop app is supported on macOS and Windows, however is not required unless you're:

Exporting designs into Zeplin.
Using the Pop Out feature to overlay designs onto your simulator/emulator/web browser.
Ability to add image & color assets directly to iOS or Android projects. The Desktop app can download your design's images assets directly into the applicable resources folder of your Android or iOS projects. For more details on this feature, read more.
If you decide on downloading the app later on, you can also use these links:

Platform	Access
Web	app.zeplin.io
macOS	Download [64-bit]
Windows	Download [32-bit] [64-bit]
More information: Supported OS & Web Versions

Project Naming Convention
Guide
Once your team starts using Zeplin, it’s common for your dashboard to have hundreds of projects. Establishing a project naming convention enhances visibility of projects and discoverability.

Naming: Use vocabulary that’s familiar to your team like team, group, project, feature, epic name.

example - StartupInc Experience-iOS-Check-out

Thumbnail: Add a thumbnail to your project that makes it easy to distinguish platform type (Web, iOS, Android) or team.

example -

zeplin

example - Some teams color code thumbnails like this; for iOS, Web, Android_ zeplin

Project Naming Convention
Type	Content ⚠️#TODO	Example ⚠️#TODO
Naming Convention	[Team/brand name] - [feature]	Airbnb Experience-Check-out
Project Structure
Having a standard project structure helps other team members effectively navigate through your project especially your developer counterpart.

Project Description: Add links to documentation and relevant stakeholders.

Sections: Group screens by user flow, features or epics.

Section Descriptions: Brief description of each section.

Screen Tags: Group screens by design stage, team names, date, version or screen type like Empty State or Pop-up.

Type	Content ⚠️#TODO	Example ⚠️#TODO
We will use Project Descriptions to describe	What is the purpose of this project	This interface shows our cargo assets in the field
We will group Screens into Sections by	User interaction	Login flow
We will use Section Description to describe	User experience, what is the user doing here	This is where the user will check out their cart
We will group Screens with tags by	What state it's in	ready for development, needs design, needs dev, needs legal
Sharing Projects
Having a standard and clear way to share screens reduce unnecessary back and forth or any chances of miscommunication.

Links: Link to a specific set of screens using Tags or Sections.

Sharing: Choose a standard channel to share links like Slack, Github, and Jira

Sharing Links
Type	Location ⚠️#TODO
We will use group and share links using	Sections
We will share our links in	Github
Layers
Layer units are specific to the Zeplin project type (Web, iOS, Android).

Platform	Unit
iOS	pt
Android	dp
Web	px
Extensions & Code Snippets
All code snippets in Zeplin are generated using extensions. Some are platform specific, and some are platform generic. These will be used by your developers to implement your designs.

Developers can write their own if they wish, read more about Zeplin extensions.

Notes & Commenting
Commenting
You can quickly add a note by Cmd + Clicking (Ctrl for Windows and Linux users) anywhere on the screen. You can even mention other teammates with “@” and they will receive a notification.

If you're tagged in a note, you can resolve that note.

alt text

🎩🐰 Show/hide notes on a design by clicking the 🙈 icon

Colors (read more)
Use color to indicate the type of note you are leaving or the status of a notes: ex.)

Color	Example
Green	Designer adding details like describing animations
Orange	Developer roadblock or requesting changes to design
Red	PM team feedback
Green	Accessibility review pending
Color Assignment
Color	Usage ⚠️#TODO
Yellow	
Orange	
Red	
Green	
Cyan	
Blue	
Purple	
Versions (history)
Commit Message: add descriptive message to clarify changes.

ex. Color change to #FFFFFF in profile background

Color: use it to indicate type of version.

Delete versions: Frequent exports to Zeplin can clutter version history, be sure to either leave commit messages or delete versions.

Version Color Assignment
Version Color	Usage ⚠️#TODO
Yellow	
Orange	Pending
Red	Experiment
Green	Approved
Cyan	
Blue	
Purple	
🎩🐰 For more best practices leveraging Versions see this article.

zeplin

Slack Integration
#channel: Create a channel in Slack and connect it to your specific Zeplin project. Channels can be based on features, team etc. zeplin

Notification settings: In the Zeplin web app you can filter notifications. We recommend to enable only key notification types to prevent noise. zeplin

Desription	Location ⚠️#TODO
We will create a Slack channel for these type of projects	link to slack channel
We will enable slack notifications for:

Notification	Enabled ⚠️#TODO
Screens	✅
Screen Versions	✅
Colors	✅
Components	✅
Text Styles	✅
Notes	✅
Replies	✅
Members	🚫
Extensions	✅
Project Status	✅
Links
Zeplin Knowledge Base
Zeplin Project home
Questions / Comments / Meaning of life : support@zeplin.io

Preparing Assets
Assets: mark icons and images as exportable in Sketch

Naming: Agree to an asset naming convention between design and engineering. You can edit asset names in Zeplin too. The default naming convention for assets is configurable.

zeplin

example: profile-gear-highlighted.png

zeplin

Platform	Naming ⚠️#TODO
Web asset naming example	
iOS asset naming example	
Android asset naming example	
Preparing Styleguide
Styleguide 🎨: upload color palette and text styles.

Components: export symbols as components

We recommend for designers and engineers to agree on color and text style names.

zeplin


Zeplin Guide for Developers ⚗️ 📚
Legend: 💡: Pro-tip
Welcome to Zeplin
Zeplin is a designer/developer collaboration product. Designers upload their artboards/screens via their preferred design program (Sketch, Figma, Adobe XD, Adobe Photoshop) into Zeplin. Team members in Zeplin can view designs, make comments, tag others, view specs, code snippets, components, and download image assets.

Zeplin acts as a source of truth for development to implement in a connected space, encouraging collaboration by all project stakeholders.

🎩🐰 Zeplin helps make your design, development, and collaboration life easier.

Getting Access to Zeplin
Send request to Zeplin Admin(s), see Quick Reference above.

Register a Zeplin account with your work email, we also support SSO with Google.

Download Zeplin ↓ After registering a Zeplin account, you'll be given the option to download the Desktop app or continue with the Web app. The Desktop app is supported on macOS and Windows, however is not required unless you're:

Exporting designs into Zeplin.
Using the Pop Out feature to overlay designs onto your simulator/emulator/web browser.
Ability to add image & color assets directly to iOS or Android projects. The Desktop app can download your design's images assets directly into the applicable resources folder of your Android or iOS projects. For more details on this feature, read more.
If you decide on downloading the app later on, you can also use these links:

Platform	Access
Web	app.zeplin.io
macOS	Download [64-bit]
Windows	Download [32-bit] [64-bit]
More information: Supported OS & Web Versions

🎩🐰 Zeplin Web app works on Linux (Chrome)

Zeplin Projects
Zeplin projects are created by designers and are platform-specific. Each project has a dashboard of all the uploaded designs, and a Styleguide, which is a collection of the Text Styles, Colors, and Components.

Project Type
iOS
Android
Web
macOS
Dashboard
Your Dashboard will display your personal, and your Organization projects (if applicable).

🎩🐰 Dashboard ⌨️: Command + D (Mac), ⌥ + A (Mac Web), Alt + A (Windows)

alt text

Styleguide
Collection of the projects Colors, Text Styles, and Components.

🎩🐰 You can change color formats to RGB, ARGB or Hex

🎩🐰 Styleguide ️⌨️: Command + G (Mac), ⌥ + S (Mac Web), Alt + S (Windows)

alt text

alt text

ex. I have personal projects, Zeplin Organization, and Game of Throne's Organization projects

Components
Components are reusable elements that are exported from your team's preferred design tool into Zeplin.

Design Tool	Native Component name
Sketch [read more]	Symbols
Figma [read more]	Components
XD ⚠️ [coming soon]	Symbols
When the team export their symbols/components from their design tool into Zeplin, you'll be able to easily identify elements that are components. For any element that is a component, you can see a blue header on that element, in addition to a link to that component in the sidebar (see image below).

alt text

Sharing project URIs (read more)
Links to projects in Zeplin will open in the Web or Desktop App alt text

Team Collaboration (read more)
Commenting
You can quickly add a note by Cmd + Clicking (Ctrl for Windows and Linux users) anywhere on the screen. You can even mention other teammates with “@” and they will receive a notification.

If you're tagged in a note, you can resolve that note.

alt text

🎩🐰 Show/hide notes on a design by clicking the 🙈 icon

Layers
Layer units are specific to the Zeplin project type (Web, iOS, Android).

Platform	Unit
iOS	pt
Android	dp/sp
Web	px
Measurements
By clicking on an element you can see its size. Once clicked you can move your mouse around and see spacing it is from other elements. Additionally, on the right panel, any assets, colors, coordinates, and code markup such as CSS (ex. if Zeplin project type is Web) will be present.

alt text

💡Hold "alt" to see relative distances instead of discrete values.

alt text

Assets
💡 If you cannot download assets for a screen, remind your designers to mark those elements as exportable in their design tool. If they are marked as Exportable and exported into Zeplin, you'll be able to download them!

Like specs, Zeplin tailors assets to the platform your project is set to. The designers on your team will need to mark the assets you need to download from Zeplin as "exportable".

Zeplin automatically provides/generates the resources tailored to platform needs, i.e. 1x, 2x and 3x for iOS... ✨

Platform	Unit
iOS	PNG / PDF
Android	PNG / SVG
Web	PNG / SVG
🎩🐰Download ALL assets for any screen by clicking on the "knife" icon

🎩🐰 If you want to use your own optimization tools, SVGO optimization is configurable (on / off) in Zeplin.

alt text

🎩🐰 Asset naming convention is configurable (camelCase / snake_case / kebab-case).

alt text

🎩🐰 You can rename assets, keep in mind that this will apply only locally.

iOS Development (read more)
PNG, PDF image types available
Asset Catalog Colors (read more)
Measurements are in points.
UIColor/UIFont extensions on Swift or Objective-C, from the project Styleguide.
When you first export assets into .xcassets directory of your project, images are added to the appropriate directories and assets are added to your project. Next time you export another asset, you can simply select the project.
Export project color palette (from the project Styleguide) directly to your asset catalog (Xcode 9 and up). For more details, check out the blog post for this feature.
Android Development (read more)
Measurements are in dp/sp.
Assets are available as 5 PNGs (mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi) and SVGs. Vector Drawables are on the way!
XMLs from project color palette and text styles, from the project Styleguide.
TextView code snippets from text layers.
Web Development (read more)
Measurements are in pixels. Assets are available as 3 PNGs (1x, 2x, 3x), SVGs and optimized SVGs (with SVGO). Bitmap images are also available as 3 JPGs.

CSS, Sass, SCSS, Less, Stylus snippets from layers, colors and text styles.
Grids from layouts in Sketch, Figma and Photoshop are accessible, from the information tab.
HTML snippets from assets.
HTML snippets from layers that match text style names as HTML tags (like h1 , h2 and so on).
Pop-out feature (read more, Zeplin Desktop required)
alt text

Extensions & Code Snippets
Extensions are the mechanism Zeplin uses to generate code snippets. Some are platform specific, and some are platform agnostic.

All Zeplin extensions are JavaScript modules that generate code snippets from various design elements. All code snippets you interact with in Zeplin are generated using extensions. Developers can write their own if they wish, read more about Zeplin extensions.

Adding extensions to projects
CSS/HTML
SCSS
React Native
Sass
Xamarin Forms
JSON Design Tokens
Build your own Extension
Zeplin extension manager (zem), is a command line tool that lets you quickly create and test extensions.

Follow the zem tutorial to start building your own Zeplin custom extension.

🎩🐰 If you'd like to build a new Zeplin Extension, reach out to glenn@zeplin.io

alt text

Prototyping / User flow links (read more)
When you export your artboards with links to Zeplin, these links will be clickable in Zeplin as well, with no additional setup. Selecting a layer below a hotspot will inform the user and present a button on the right panel to quickly jump to the destination.

🎩🐰 When you hold down the Shift key all the hotspots/prototyping will be revealed

alt text

Versions
🎩🐰 For more best practices check this article.

Integrations
Integration with Slack (read more)
Integration with Trello (read more)
The Zeplin Power-up on Trello lets you attach your projects, screens and tags to Trello cards, to preview and quickly access them. You can also paste Zeplin links directly to comments, card descriptions and they’ll be infinitely more meaningful.

Q / A
Q: Why are my specs off?

A: Designer might have set the density of the project incorrectly. They can correct this setting here.

Links
Zeplin Knowledge Base
Zeplin Project home
Questions / Comments / Meaning of life : support@zeplin.io
