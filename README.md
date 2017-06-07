# WordsmithNLG
Wordsmith by Automated Insights is the largest-producing natural language generation (NLG) engine in the world, producing over 1.5 billion narratives in 2016 alone. Since Wordsmith is fully customizable, MicroStrategy users have complete control over the narrative insights they deliver. Now, your data experts can design templates that deliver the exact insights your employees need to know. And best of all, the stories are all embedded directly in the dashboards used everyday.

Wordsmith is the world’s only self-service NLG engine. The public API makes it easy for data professionals to automate clear, written explanations of MicroStrategy visualizations. It’s like having an expert speak directly to every user, telling them what the data means and what they should do about it. And, best of all, the narrative updates in real time as the user explores the visualization.


### Requirements

### Object requirements:
  - Before using the plugin, you also need to create project and template at Wordsmith: https://wordsmith.automatedinsights.com
  - After you have created project and template at Wordsmith, you will need the obtain the slug names for them
  - Create a MicroStrategy visualization with this plugin and enter the slug names in the Project and Template fields on the properties panel of the visualization
  - On the drop zones, add attributes/metrics required by your template, and the narrative will be shown
  - You can use this Wordsmith starter plugin for MicroStrategy to generate narrative from a simple visualization using the following steps:
  - Format your data into a Grid containing a single row in MicroStrategy
  - Setup your Wordsmith template to write about the data elements contained in the MicroStrategy grid
  - Switch the Grid to a WordsmithNLG visualization and enter your API key, project slug, and template slug in the Wordsmith NLG formatting options
  - Update your narrative in Wordsmith as necessary

### Minimum MicroStrategy version: 10.3

### Current visualization version: 1.0

### Publisher: MicroStrategy

### MicroStrategy Features
  - [Supports custom properties  (includes threshold editor in custom properties)][CustomProperties]
  - [Supports exporting engine  (10.6 and later)][ExportingEngine]

### Initial post: 08/02/2016
### Last changed:
### Changes made: [Change Log Details]


[CustomProperties]: <https://lw.microstrategy.com/msdz/MSDL/_CurrentGARelease/docs/projects/VisSDK_All/default.htm#topics/HTML5//Creating_and_using_custom_properties.htm>
[Change Log Details]: <https://github.microstrategy.com/AnalyticsSDK/Visualizations/blob/next/KPIWidget/CHANGELOG.md>
[ExportingEngine]: <https://lw.microstrategy.com/msdz/MSDL/_CurrentGARelease/docs/projects/VisSDK_All/Content/topics/HTML5/Exporting_to_PDF.htm>
