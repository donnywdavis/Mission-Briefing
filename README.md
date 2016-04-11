# Homework 01

## Mission Briefing

Good afternoon agent. This mission will be quite taxing, but you will make your country proud if you complete it. Your job is to create an app to brief future agents on mission details securely and privately. We know this is your first assignment, but be aware that this is a top priority for the agency. The Director herself will be watching the outcome of this assignment, so stay sharp.

Included with this brief is a zipped file containing the agency's efforts so far regarding this mission. It is a good start, but several key issues have not yet been solved. Your mission, should you choose to accept it, is to finish the tasks outlined in the attached source code and deliver the project for submission to all our field agents. Good luck.

This message will self-destruct in 5 seconds.

### Steps to Success

#### Storyboard Tasks

* [x] The button should really say "Authenticate"
* [x] The textfield should have placeholder text that says "Agent name"
* [x] Each UI element will need to be connected to its associated property in the ViewController class.
* [x] The agent name textfield should capitalize each word typed into it (see the attributes inspector)
* [x] Neither textfield should attempt any autocorrect or spellcheck (again, see attributes inspector)
* [x] The password textfield should hide the characters typed in (it will show dots, see the attributes inspector, see a pattern here?)
* [x] You will notice The Iron Yard logo image is left aligned, and in fact when you click on it, the outline appears orange. It really should be centered in the view like everything else (needs an autolayout constraint).

#### Code Changes

* [x] The UI elements should be set to an "empty string" in viewDidLoad of the ViewController class (#1 in comments).
* [x] The code should check to ensure BOTH the agent name and password fields are nonempty before allowing authentication (#2 in comments).
* [x] The greeting label should display "Good evening, Agent [last name]", where the agent's last name is pulled from the textfield (#3 in comments).
* [x] The mission briefing should display the information from MissionBriefing.txt (copy-paste, you don't have to read from the file). It also contains a placeholder for the agent's last name (#4 in comments).
* [x] The background color of the view should change to green on successful authentication of the agent (#5 in comments).
* [x] The background color of the view should change to red to indicate a failed login of the agent (#6 in comments).
