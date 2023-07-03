# Random Player Selection
This Python code simulates the random selection of players for a football match. It defines a Human class and a Footballist class that inherits from the Human class.

# Code Explanation
1. The code starts by importing the random module to generate random selections.
2. The Human class is defined, which represents a group of players. In the constructor (__init__ method), the user is prompted to enter the names of the players, which are stored as a list of strings.
3. The pakhsh method is defined, which simulates the selection process. It randomly selects 11 players from the list (self.name) using the random.sample function and stores them in list A.
4. The selected players (A) are removed from the original list of players (self.name) to ensure that they are not selected again. The pop method is used to remove the selected player from the list.
5. The remaining players in self.name are stored in list B.
6. The selected players (A) are printed with the label 'A', indicating they belong to team A.
7. The remaining players (B) are printed with the label 'B', indicating they belong to team B.
8. The Footballist class is defined, which inherits from the Human class. This class does not have any additional methods or attributes.
9. An instance a of the Footballist class is created.
10. The pakhsh method is called on the instance a, simulating the random selection of players for a football match.
# Usage
1. Run the code.
2. Enter the names of the players when prompted, separated by spaces.
3. The code will randomly select 11 players for team A and print their names with the label 'A'. It will also print the remaining players (team B) with the label 'B'.

