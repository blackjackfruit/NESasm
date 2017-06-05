I decided I would fork off of version 3.1 of NESAsm and add some new features that I felt were missing. This project lacked a way to specify an output path and a way to specify input file(s) using a switch. This version of NESasm I am working on will primarily be integrated into ConsoleIDE.


To get run this program within Xcode, a few things will need to be configured
1. Select EditScheme
2. Make sure Run is selected and choose the Arguments tab
3. Add the arguments for --input and --output
4. Set the Environment Variable to point to the resource for your project
