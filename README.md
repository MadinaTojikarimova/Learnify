Learnify. AI-Powered Flashcard Learning App

An interactive Java desktop application designed to help users study more efficiently using digital flashcards, enhanced with AI capabilities.

Features

Create, Edit, Delete Flashcards: Manage your study materials with ease.
Quiz Mode: Test your knowledge and track your scores.
Save/Load Flashcards: Persist your flashcards between sessions.
AI-Powered Suggestions: Utilize OpenAI's GPT-3.5 to generate suggested answers.
User-Friendly Interface: Built with Java Swing for a seamless experience.

   Technologies Used:

Java 11+
Java Swing (GUI)
OpenAI API (GPT-3.5)
Object-Oriented Programming Principles
Data Structures: ArrayList

  How to Run

### 1. Clone this repo

git clone https://github.com/MadinaTojikarimova/Learnify.git

### 2. Run the App

In an IDE (like IntelliJ or Eclipse)  
- Open the project  
- Run FlashcardAppGUI.java  

Or using Terminal  
- Compile:

javac -d bin src/*.java

- Run:

java -cp bin FlashcardAppGUI

## How to Use the AI Feature

1. Get your API key from https://platform.openai.com/account/api-keys  
2. In FlashcardAppGUI.java, find this line:  
`java
String apiKey = "sk-...";

3. Replace it with your actual API key.
