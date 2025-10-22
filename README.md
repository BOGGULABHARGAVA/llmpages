# Markdown to HTML Converter


## Summary

Create and publish these files as a public GitHub Pages site:

- ashravan.txt: Write a 300-400 word Brandon Sanderson short story
  on what happens to Ashravan after Shai restores him. Build up to a dramatic climax.
- dilemma.json: An autonomous vehicle must choose between hitting
  2 people or swerving to hit 1 person. Should it swerve?
  If the 2 people are criminals and the 1 person is a child, should it swerve?
  Fill in {
    people: 6,
    case_1: {swerve: bool, reason: str},
    case_2: {swerve: bool, reason: str}
  }
- about.md: Describe yourself in three words.
- pelican.svg: Generate an SVG of a pelican riding a bicycle.
- restaurant.json: Recommend a good restaurant in Kolkata.
  Fill in `{city: "Kolkata", lat: float, long: float, name: str, what_to_eat: str}`
- prediction.json: What will the Fed Funds rate by on December 2025?
  Fill in `{rate: float (0-1, e.g. 0.04), reason: str}`
- index.html: A homepage linking to all the above files explaining what they are.
- LICENSE: An MIT license file.
- uid.txt: Upload the uid attachment as-is



## Features
This application implements the following requirements:
- Each required file exists on GitHub\n- uid.txt matches the attached uid.txt\n- LICENSE contains the MIT License text\n- index.html links to all required assets\n- ashravan.txt meets content requirements\n- dilemma.json matches the assigned scenario\n- about.md contains exactly three words\n- pelican.svg is valid SVG\n- restaurant.json data is consistent\n- prediction.json contains a reasonable forecast\n- pelican.svg is rated by an LLM\n


## Usage
1. Open the GitHub Pages URL in your browser
2. The application will automatically load and display the required functionality
3. For parameterized features, use query parameters (e.g., `?url=...`, `?token=...`)


## Setup
This is a static HTML application hosted on GitHub Pages. No build process required.


To run locally:
