# Use Python and Java to Create a GUI Application

![A screenshot of a computer](images/Picture1.png) 

### Task 1: Inherit from the JFrame class to create the Application Window:

1. Create the JFrame class. The Jframe has a content pane upon which GUI components are added. These components are called Swing Controls in Netbeans.

![A screenshot of a computer](images/Picture2.PNG) 

2. Create the Title. The constructor for the DataView class is where the title for the Jframe is added.

![A screenshot of a computer](images/Picture3.PNG)

![A screenshot of a computer](images/Picture4Design.PNG)

![A screenshot of a computer](images/Picture4Source.PNG)

3. Create a minimum size for the Frame.

![A screenshot of a computer](images/Picture5RightClick.PNG)

![A screenshot of a computer](images/Picture6Grid.PNG)

![A screenshot of a computer](images/Picture7Grid.PNG)

![A screenshot of a computer](images/Picture8Grid.PNG)

![A screenshot of a computer](images/Picture9Sourceviewnewdimensions.PNG)

![A screenshot of a computer](images/Picture9Javaawtdimensions.PNG)

![A screenshot of a computer](images/Picture10RunProject.PNG)

![A screenshot of a computer](images/Picture11Result.PNG)


### Task 2: Add Labels to the grid to tell the user what to enter:

1. Select the Label Swing Control from the Pallet.

![A screenshot of a computer](images/Picture12LabelSwingControl.PNG)

2. Create the Labels and add them to the grid.

![A screenshot of a computer](images/Picture13LabelSwing.PNG)

3. Use the Label Properties to set the Text and Align the text.

Filename Label

![A screenshot of a computer](images/Picture14LabelProperties.PNG)

![A screenshot of a computer](images/Picture15LabelName.PNG)

![A screenshot of a computer](images/Picture16AlignmentCenter.PNG)

![A screenshot of a computer](images/Picture17Close.PNG)

![A screenshot of a computer](images/Picture18Filename.PNG)

X-Coordinate Label

![A screenshot of a computer](images/Picture18XCoordinate.PNG)

![A screenshot of a computer](images/Picture18XCoordinateEditText.PNG)

![A screenshot of a computer](images/Picture19XCoordComplete.PNG)

Y-Coordinate Label

![A screenshot of a computer](images/Picture20YCoordinate.PNG)

![A screenshot of a computer](images/Picture21YCoordinateEditText.PNG)

![A screenshot of a computer](images/Picture22YCoordinateProperties.PNG)

![A screenshot of a computer](images/Picture23YCoordinatePropertiesCenter.PNG)

![A screenshot of a computer](images/Picture24LabelsFinal.PNG)

![A screenshot of a computer](images/Picture24XCoordinatePropertiesCenter.PNG)


4. Observe the code generated in the source view.

![A screenshot of a computer](images/Picture25ObserveCode.PNG)

![A screenshot of a computer](images/Picture26RunCode.PNG)

![A screenshot of a computer](images/Picture27LabelsareShowing.PNG)

Add Line Border for Filename

![A screenshot of a computer](images/Picture28AddBorderFilename.PNG)

![A screenshot of a computer](images/Picture28AddBorderInNoBorderDropdown.PNG)

![A screenshot of a computer](images/Picture28AddBorderInNoBorderPressOk.PNG)

Follow the same steps for X and Y Coordinates

![A screenshot of a computer](images/Picture29XandYCoordianteBorders.PNG)


### Task 3: Use Text Fields to allow the user to enter a filename and X and Y Coordinates for the Python Applications:

1. Select the Text Field from the Swing Control.

![A screenshot of a computer](images/Picture30TextField.PNG)

![A screenshot of a computer](images/Picture30TextFieldNexttoFilename.PNG)

![A screenshot of a computer](images/Picture30ChangeVariableName.PNG)

![A screenshot of a computer](images/Picture31TextFieldRename.PNG)

![A screenshot of a computer](images/Picture32EditText.PNG)

![A screenshot of a computer](images/Picture33Temprainyearly.PNG)

2. Add the Text field next to the appropriate Label on the grid.

Add X and Y Coordiantes Text Fields and Change Variable Names

![A screenshot of a computer](images/Picture34XandYCoordinateTextFields.PNG)

![A screenshot of a computer](images/Picture35RenameXCoordinateVariableName.PNG)

![A screenshot of a computer](images/Picture36RenameYCoordinateVariableName.PNG)

Edit Text for X and Y Coordiantes to Rename

![A screenshot of a computer](images/Picture37EditTextx.PNG)

3. Add the Text Areas to display the statistics for X-data and Y data.

![A screenshot of a computer](images/Picture38TextArea.png)

![A screenshot of a computer](images/Picture38TextAreaAfterRainField.PNG)

![A screenshot of a computer](images/Picture38TextAreaSecond.PNG)

Change Variable Names of Text Areas and Run to View Output

![A screenshot of a computer](images/Picture39ChangeVariableName.PNG)

![A screenshot of a computer](images/Picture40ChangeVariableNameTXTStatsY.PNG)

![A screenshot of a computer](images/Picture41Runthisproject.PNG)

![A screenshot of a computer](images/Picture42RunthisprojectOutput.PNG)

### Task 4: Add buttons to the Java GUI to allow users to graph and display statistics:

1. Create the button controls.

![A screenshot of a computer](images/Picture43ButtonComponent.PNG)

![A screenshot of a computer](images/Picture44JButton.png)

![A screenshot of a computer](images/Picture44JButtonEditText.PNG)

![A screenshot of a computer](images/Picture44RenametoShowRegression.PNG)

Change Variable Name

![A screenshot of a computer](images/Picture45BTNRegression.PNG)

2. Add each button to the appropriate grid location after Show Regression Button is complete.

Add "Show Stats" button first Change the Variable Name to 
"BtnStats" and then Button Name to "Show Stats".

![A screenshot of a computer](images/Picture46ChangeVariableNameofShowStatsButton.PNG)

![A screenshot of a computer](images/Picture47ChangeitToBtnStats.PNG)

![A screenshot of a computer](images/Picture48EditTextandChangeItToShowStats.PNG)

3. Assign an ActionListener to.

![A screenshot of a computer](images/Picture49DoubleClickOnShowRegressionButton.PNG)

![A screenshot of a computer](images/Picture50AddRegressionButtonPushedCode.PNG)

![A screenshot of a computer](images/Picture51RunProject.PNG)

![A screenshot of a computer](images/Picture52PressShowRegressionButton.PNG)

![A screenshot of a computer](images/Picture53RegressionButtonPushed.PNG)

4. Observe how the Action Listener is registered with the button click event.

When the Show Regression Button is pressed it calls the btnRegressActionPerformed method.

![A screenshot of a computer](images/Picture54BtnRegressActionPerformedMethod.PNG)

### Task 5: Use Java button event handlers to invoke Python Applications:

Python Code in IDLE

![A screenshot of a computer](images/Picture55OpenPlotDataPythonFile.PNG)

![A screenshot of a computer](images/Picture56RunCustomized.PNG)

![A screenshot of a computer](images/Picture57_Names.PNG)

![A screenshot of a computer](images/Picture58_Graph.PNG)


1. Implement the event handler methods for each button.

2. Use the Java ProcessBuilder object to invoke the Python code.

![A screenshot of a computer](images/Picture59InvokePythonApplication.PNG)

![A screenshot of a computer](images/Picture60AddImportJavaIOException.PNG)

![A screenshot of a computer](images/Picture61RunThisProject.PNG)

![A screenshot of a computer](images/Picture62PressShowRegressionButton.PNG)

![A screenshot of a computer](images/Picture63GraphOutput.PNG)

Implement Event Handler Methods and ProcessBuilder Object for "Show Stats" Button By Double Clicking.

![A screenshot of a computer](images/Picture65DoubleClickOnShowStats.PNG)

![A screenshot of a computer](images/Picture64ShowStats.PNG)

![A screenshot of a computer](images/Picture66Java.IO.InputStreamReader.PNG)

3. Obtain the data from the text fields for use in the Python program call.

4. Obtain data from the Python program call and insert data into the text areas.

5. Test the completed application.

![A screenshot of a computer](images/Picture67BufferCode.PNG)

![A screenshot of a computer](images/Picture68RunProject.PNG)

![A screenshot of a computer](images/Picture70ShowStatsButton.PNG)

![A screenshot of a computer](images/Picture69ShowStats.PNG)

![A screenshot of a computer](images/Picture71ShowRegressionRetest.PNG)

![A screenshot of a computer](images/Picture72RegressionPlotOutpt.PNG)

Source: Use Python and Java to Create a GUI Application, Coursera, Dave Dalsveen
