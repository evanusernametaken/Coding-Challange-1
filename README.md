This repository contains a small Swift example demonstrating how to store an app name, keep track of a version number, and update that version. The purpose of the code is to show how constants, variables, and basic printing work in Swift.
The program begins by defining the app name as a constant and the current version as a variable. It prints both values to the console so the user can see the initial state. After that, the version number is increased by 0.1 to simulate an update, and the new value is printed again. This makes it easy to understand how variable updates work and how Swift handles simple data types such as strings and doubles.
Below is the full code used in this example:

let appName: String = "Teems APP"
var currentVersion: Double = 10.0
print("My App Name \(appName)")
print("Current Version \(currentVersion)")
currentVersion += 0.1
print("Current Version \(currentVersion)")

When you run the program, it prints the original version and then shows the updated version number. The output will look like this:
My App Name Teems APP

Current Version 10.0
Current Version 10.1

To run the example, create a Swift file such as main.swift and copy the code into it. You can execute it from the command line using swift main.swift, or you can open the file in Xcode and run it there. Both methods will produce the same output and allow you to see how the version value changes each time the program runs.
