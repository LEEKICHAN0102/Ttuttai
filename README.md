# Ttuttai

- A simple npm library that prints braille character images to the console.

- If you want more characters, fork the project and post a revised PR. Where do you use this for? Just Ttuttai!

<br>

# Installing Ttuttai

- You can install Ttuttai using npm. Open your terminal and run the following command:

> npm install ttuttai

<br>

# Usage

- Once installed, you can use Ttuttai in your Node.js application as follows:

```
// using ttuttai
import ttuttai from "ttuttai"

// and just Ttuttai!
ttutai.raiden();
```

- After that, when you check the terminal, you will get the following results:

```
        ⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⠀⠀⢀⣀⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⢠⢴⠁⢀⣿⣾⣿⣿⣿⣿⣿⣿⣿⣶⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⢀⢤⣧⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡀⠀⠀⠀⠀⠀⠀⠀⢸⡇⠀⠀⣖⠠⣂⢰⢲⠂⣆⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⣠⣾⣿⣟⡿⢦⡀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠀⠀⠀⠀⠀⠀⢸⠁⠀⠀⠒⡖⡖⠺⡸⠄⡗⢂⠀⠀⠀⠀⠀⠀⠀
        ⣸⢯⣿⣿⠟⠀⠀⠛⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⢀⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⣿⣿⣿⡿⢷⠀⣀⣀⣸⣿⡟⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⢀⡞⠀⠀⠀⠀⣖⣢⣒⠀⣖⣐⡆⢲⡖⢰⠄⡞⢡⢰⡆
        ⠙⣿⣿⣧⠈⣭⣿⣿⣿⣿⠁⠀⠹⣿⣿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⢀⡰⠊⠀⠀⠀⠀⠀⠒⡖⡖⠐⠒⡖⠒⠸⢧⠘⡒⠣⠜⢸⠃
        ⣤⠋⠁⣾⣿⣿⣿⣿⣿⣿⣀⡠⠤⢌⡉⠁⠈⠉⣡⣎⢉⣣⡀⠈⣿⣿⣧⠛⠦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠳⣄⣸⣿⣿⣿⣿⣿⠀⢋⣷⠏⣱⣄⠈⠀⠀⠀⣇⠀⠀⢠⠇⠀⠻⣿⡿⣆⠀⠀⠑⣄⠀⠀⠀⣖⣢⡒⢰⢲⠂⣆⢰⢲⠂⡦⠀⠀⠀⠀
        ⠀⣿⣿⣿⡿⠉⢿⣿⣇⠘⡄⠀⠀⡼⠀⠀⢀⠀⢈⠓⠉⠁⠀⠀⠀⢹⣷⡽⡆⠀⠀⠈⢧⡀⠀⢲⡖⡟⠸⣸⣀⡗⠸⣸⡀⡗⠂⠀⠀⠀
        ⠀⣿⣿⣿⣿⣦⣤⣙⠻⠆⠈⠉⠉⠀⠈⠒⠋⠓⠋⠀⠀⠀⠀⣀⣴⣿⣿⣷⠇⠀⠀⠀⠀⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⣿⣿⣿⣿⣿⣿⠟⠩⠒⠀⠀⠤⠤⠤⠄⣀⡠⠤⠤⠐⠚⠫⠀⠈⢻⡟⠉⠀⠀⠀⠀⠀⢸⡄⣔⠒⢲⢰⢲⠂⣦⢠⠲⡀⡦⢰⠀⠀⠀
        ⠀⠹⣿⣿⣿⣏⣤⡄⢇⡀⢃⠀⠀⠀⠀⠀⠀⠀⠀⢀⠇⠀⣎⡀⠀⢸⠈⢂⠀⠀⠀⠀⠀⠀⡇⠐⢯⠑⠸⣸⣀⡗⠺⣠⠃⡗⢘⠀⠀⠀
        ⠀⠀⠉⢛⠟⠛⠛⢆⠔⢂⠈⢄⠀⠀⠀⠀⠀⠀⢀⠎⢀⡰⠁⠇⠉⠳⢄⡀⠆⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⡎⠀⣠⡔⠁⠀⠀⠉⡆⠉⠒⠒⠒⠒⠊⠁⠀⡇⠀⠀⢸⠀⠀⠀⢇⡜⠀⠀⠀⠀⣸⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⢠⠁⢰⣿⡇⠀⠀⠀⠀⠑⠤⠔⠒⠢⠤⠎⠉⠉⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⣰⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⢣⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱⠀⠀⠀⠀⠀⠀⠐⠓⠚⠋⠉⠉⠉⠉⠉⠓⠲⢤⣀⠀⠀⠀⠀⠀⢀
        ⠀⠀⠀⠀⠙⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠓⢦⡀⢀⡔⠉
        ⠀⠀⡰⣉⢺⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠱⠏⠀⠀
        ⢦⣧⣬⡿⢾⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠴⠋⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠐⠿⠿⠋⠉⠉⠸⣄⣀⣀⠀⠀⠀⢀⣀⣀⣀⣠⠤⠔⠚⠉⠀⠀⢠⣇⣀⣀⣀⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶
        ⠀⠀⠀⠀⠀⠀⠀⡇⠀⠈⠉⠉⠉⠉⢉⣀⣀⣀⣠⠄⠀⠀⢀⣀⣼⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
        ⣀⣀⢤⣤⣴⣶⣶⣿⢶⠶⠖⠒⣶⣖⣺⣿⣿⣷⣿⣲⣿⢻⠉⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
        ⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣀⣀⠸⣟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
        ⣿⣿⣿⣿⣿⣿⣿⣿⣿⡧⠤⠔⢺⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⢤⣤⢾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
```

<br>

# Contributing

- welcome your contribution to the Ttuttai project! Your contribution can help you improve and grow this project. Below are some guidelines on how to contribute.

- Find or suggest Issue:

> If you find a bug or have suggestions for feature improvement, please open GitHub Issue.
> Please clarify the process or functional requirements of the issue by explaining it in as much detail as possible.

- To do a project fork:

> Fork the project yourself to work on the changes in your personal repository.

- Suggest changes:

> Please create a new branch with changes and open the Pull Request (PR).
> Please include a concise explanation of the changes and the reason why this change is necessary in the PR message.

<br>

### All formats don't have to be grandiose, just do Ttuttai. but write down the character's name properly ^^