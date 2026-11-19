# FlashMyCards
A 2D clicker-style flash card game built in Rust using the Macroquad game library

**The Packaged Game can be found under Releases**

This project was coded using Gemini and was a sort of experiment to see what the Rust coding language was and how well AI could even code.
The main goal of this game is to provide more engaging ways to study flash cards as opposed to just typing or selecting answers.

The game supports the creation of custom Decks allowing users to create their own sets of flash cards.
These decks can feature images, audio, and text although the only supported files are .png, .wav, and .csv
To import a deck a user must create a folder that contains all the media necessary for that deck.
That folder also must include a .csv file that describes the contents of the deck to the game.
Below are the headings required for the .csv paste this into Excel or Google Sheets to edit and create the deck:

Main Question Type,Main Question,Answer 1 Type,Answer 1,Answer 2 Type,Answer 2,Answer 3 Type,Answer 3,Hint 1 Type,Hint 1,Hint 2 Type,Hint 2,Hint 3 Type,Hint 3

Currently Supported Question Types
"Audio"
"Image"
"Text"

Examples of what a completed deck looks like can be found inside the "decks" folder of the FlashMyCards_V1.zip

## Title Screen
<img width="1919" height="1007" alt="FMC TitleScreen" src="https://github.com/user-attachments/assets/5ab885bd-36c4-499f-ac6c-80714f7a3bb8" />

## Game Mode Selection
<img width="1919" height="1008" alt="FMC Gamemode Selection" src="https://github.com/user-attachments/assets/cb0592f3-88f3-4c0c-bb13-7b7299da4360" />

## Float Mode
<img width="1918" height="1009" alt="FMC Float Mode" src="https://github.com/user-attachments/assets/2f4b4aff-8c40-41df-9ba9-de531cd53e0a" />

## Tile Mode
<img width="1918" height="1009" alt="FMC Tile Mode" src="https://github.com/user-attachments/assets/21396e6f-17ff-4bfd-b24d-51b244a07ebc" />

## Drop Mode
<img width="1919" height="1009" alt="FMC Drop Mode" src="https://github.com/user-attachments/assets/3094368d-4761-4376-b33a-d1874b57190e" />

## Example Deck in Google Sheets
<img width="1034" height="769" alt="Screenshot 2026-11-18 201436" src="https://github.com/user-attachments/assets/f2a5b074-3cff-43ab-9da8-7b802d0d04b8" />
