# CU2PT Plugin
***CU2PT*** is a plugin for [Intellij IDEA](https://www.jetbrains.com/idea/) that extracts test clones from test suites and represents them in a parameterized form.<br />

(1) First, you should put your JUnit test suite files in the folder that is named "tests".<br /><br />
(2) Then, you should right click on the folder or your specific test suite that you want to convert into a parameterized form, and go to the "Analyze" option and then to "Convert to Parametric" option or use the Ctrl + Shift + D shortcut. The plugin automatically starts to find test clones in the test suite(s) and creates three folders. "originals" folder saves the original test suite(s) files, "method list" folder saves the name of the test clones of the respective test suite(s), and the "TestClones" folder serves you all of the test clones that the plugin found in the test suites files. After that, you see the test clones files on this folder.<br /><br />
(3) Now, you can right click on the TestClones folder and click the "Convert to Parametric" option. After the processing phase, the plugin generates your parameterized test suites.
