Plugin to add some additional features to a FitNesse (http://fitnesse.org) wiki.

Wiki symbols:
- Relative dates: months or weekdays from today (extension on standard !today)
- Random values: strings, numbers and Burger Service Numbers (Dutch social security numbers)

Slim tables:
- table template: scenario without need to define all parameters in first line
- storyboard: script which takes a 'screenshot' after each row


This plugin is included in the FitNesse baseline installation of https://github.com/fhoeben/hsac-fitnesse-fixtures.
After starting that installation Wiki pages demonstrating the use of this plugin can be opened:
- HsacExamples.SymbolSamples,
- HsacExamples.SlimTests.BrowserTests.TableTemplateTest
- HsacExamples.SlimTests.BrowserTests.StoryboardTest and
- HsacExamples.SlimTests.BrowserTests.TemplateStoryboardTest).


To use this plugin in a 'plain vanilla' FitNesse installation:
- copy .jar it to $FITNESSE_HOME/plugins
