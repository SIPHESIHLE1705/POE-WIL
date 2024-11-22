For the app:
Purpose of Logging
Debugging:
Logs help identify bugs or unexpected behavior by showing what happens step-by-step in the application.
For example, if a course doesn't navigate correctly, a log like console.log('Navigating to CourseDetailsScreen') can help verify if the navigation function is triggered.
Understanding User Actions:
Logs can track what users do, such as selecting a course or navigating to a specific screen.
For example: console.log('Selected course: First Aid') ensures that the user’s selection is captured.
Validating Data Flow:
Logs can confirm whether data is correctly passed between screens, such as course details or calculated fees.
For example: console.log(\Course Title: R{course.title}, Fee: R{course.fee}`)`.
Logging in Different Components
1. Screen Rendering Logs
Example: console.log('HomeScreen rendered')
Purpose: Confirms that a particular screen is loaded. If a screen doesn't appear, the absence of this log indicates a rendering issue.
2. Navigation Logs
Example:
console.log('Navigating to SixMonthCoursesScreen');
Purpose: Ensures the navigation functions are triggered correctly and the app is transitioning to the intended screen. Useful for identifying broken links or misconfigured navigation.
3. Data Passing Logs
Example:
console.log(`Course Title: R{course.title}, Fee: R{course.fee}`);
Purpose: Confirms the data passed between components, such as when a course's details are sent to the CourseDetailsScreen. This helps ensure no critical information is lost or misinterpreted.
4. Action-Specific Logs
Example:
console.log('Calculator button clicked');
Purpose: Tracks user interactions with buttons or other UI elements. Helps debug actions that should trigger certain behaviors, like calculating fees.
6. Dynamic Logs
Example:
console.log(`Selected course: R{course.title}`);
Purpose: Logs the values of dynamically generated items (like a list of courses). Useful for verifying that the app responds to dynamic input correctly.

Website:
Key Benefits of This Logging:
Verification of Page Load: Logs ensure each page and its components load correctly.
Interaction Tracking: Logs track user interactions like button clicks and form submissions, confirming event handlers are functioning.
Debugging Dynamic Content: Logs capture dynamic content (like course details) to verify that correct data is being displayed.
Error Detection: If something doesn’t work as expected, logs provide a trail to identify issues.
These logging examples show how you analyze user interactions, verify data flow, and understand the functional structure of the website.

youtube links:

https://youtu.be/iYFsYPpeuk8?si=ue9sexvXGRblQoY8

https://youtu.be/DRXanwc_d_I?si=trPK9onyDQ44qt44 
