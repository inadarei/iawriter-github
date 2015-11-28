# iawriter-github
iA Writer Tweaks that make it a good Markdown editor for Github wikis and pages

## Installation

- Right-click on iA Writer.app in your Applications folder. 
- Select: "Show Package Contents"
- Open:  Resources/Templates
- Duplicate `Sans.iawritertemplate` into a folder named `Github.iawritertemplate`
- Edit "local.tpl.html" and "export.tpl.html" under "Github.iawritertemplate/Contents/Resources" and add CSS link to github.css:
    
    ```
    <link rel="stylesheet" media="all" href="github.css" />
    ```
- Copy-paste our css file into github.css
