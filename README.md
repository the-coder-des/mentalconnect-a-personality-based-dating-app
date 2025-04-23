
<!---
============================================================================
                  CURSOR AI INSTRUCTIONS - DO NOT MODIFY
============================================================================
-->

<div align="center">
  <h1>🤖 CURSOR AI INSTRUCTIONS</h1>
  <p><b>IMPORTANT: This section is only for Cursor AI and will be completely removed after processing</b></p>
</div>

---

## AI Task: Complete README Transformation

Hello Cursor AI! Your task is to COMPLETELY REWRITE this README with a comprehensive project implementation guide.

### Critical Requirements:

1. **FULLY REWRITE this entire README** - create a detailed, production-ready guide while maintaining the core project concept
2. **Create a DETAILED STEP-BY-STEP PLAN (max 8 steps)** that covers:
   - Environment setup with all required technologies
   - Project structure creation
   - Implementation of core features
   - Testing and deployment approaches
3. **Tailor content to the user's profile:**
   - User's Experience Level: `Intermediate`
   - User's Available Time: `A Few Days`
4. **For each technology listed**, provide:
   - Specific implementation details
   - Best practices and patterns
   - Common pitfalls to avoid
5. **Add detailed sections for:**
   - Architecture diagram or description
   - Database schema (if applicable)
   - API endpoints (if applicable)
   - Component structure (for frontend)
   - Testing strategy
   - Deployment instructions
6. **Provide code examples** for critical project parts
7. **REMOVE THESE INSTRUCTIONS COMPLETELY** after your rewrite

Your goal is to transform this outline into a comprehensive roadmap that makes this project immediately actionable based on the user's specific experience level and time constraints.

### ⚠️ CRITICAL FIRST STEP ⚠️

**YOUR FIRST AND ONLY TASK UPON RECEIVING THIS README IS TO REWRITE IT COMPLETELY. DO NOT START IMPLEMENTING THE PROJECT OR WRITING ANY CODE YET.**

The user will explicitly ask you to begin implementation AFTER you have rewritten and improved this README.

<!---
============================================================================
                 END OF CURSOR AI INSTRUCTIONS
============================================================================
-->


# MentalConnect: A Personality-Based Dating App

## Project Overview
MentalConnect is a dating app that focuses on mental connections rather than physical attraction. The app will use personality-based prompts to help users find compatible matches, with the option to send pictures and engage in conversations. The app will also implement an algorithmic matching system to ensure users receive relevant matches.


> **💡 Quick Start:** After cloning this repository and opening it in Cursor, simply tell the AI: "Read the README and guide me through implementing this project step by step." Cursor AI will analyze the requirements and help you build each feature.


## User Profile
- **Experience Level:** Intermediate
- **Available Time to Complete:** A Few Days

## Technologies
- **React**: Used for building the client-side user interface and user experience.
- **Node.js**: Used as the server-side runtime environment to handle requests and responses.
- **Express.js**: Used as the server-side framework to build RESTful APIs.
- **MongoDB**: Used as the NoSQL database to store user data, prompts, and conversations.
- **Socket.io**: Used for real-time communication and chat functionality.
- **Algorithm.js**: Used for implementing the algorithmic matching system.


## Development Steps
### 1. Set up the Project Structure
Create a new React project using create-react-app and set up the project structure with components, APIs, and a database.

### 2. Design the User Interface
Design the UI components for the personality prompts, chat interface, and user profiles using React.

### 3. Implement the Algorithmic Matching System
Use Algorithm.js to develop the matching algorithm that pairs users based on their personality traits and preferences.

### 4. Implement Real-Time Chat Functionality
Use Socket.io to enable real-time communication between matched users.

### 5. Implement Picture Sharing and Limit Unanswered Messages
Add the feature to send pictures and implement a limit on unanswered messages to encourage users to engage with their matches.

### 6. Test and Deploy the App
Test the app's functionality and deploy it to a cloud platform like Heroku or AWS.


## Main Features
Features will be added soon


## Sample Code
```javascript
// Example code snippet for implementing the algorithmic matching system
function matchUsers(user1, user2) {
  const similarityScore = calculateSimilarity(user1, user2);
  if (similarityScore > 0.5) {
    return true;
  } else {
    return false;
  }
}
```


## Getting Started
Instructions will be added soon

## Resources
- [React Documentation](https://reactjs.org/docs/getting-started.html) (documentation)
- [Node.js Tutorial](https://nodejs.org/en/docs/guides/) (tutorial)
- [Socket.io Tutorial](https://socket.io/docs/v3/get-started/) (tutorial)
- [Algorithm.js Documentation](https://algorithm.js.org/docs/) (documentation)
- [MongoDB Tutorial](https://mongodb.com/docs/drivers/node-current/) (tutorial)


## AI Coding Prompts

Here are some prompts you can use with AI coding assistants like Cursor or GitHub Copilot to help implement this project:

### Prompt 1
```
In JavaScript, create a new Node.js Express.js server using the code snippet provided as a starting point for implementing the algorithmic matching system. Connect to a MongoDB database to store user data and prompts. Write a function to fetch user data from the database and calculate the similarity score based on user personality traits.
```

### Prompt 2
```
Implement the logic for the algorithmic matching system by calling the `matchUsers` function in Node.js. Use the similarity score to determine compatibility between two users and return the results. Integrate Socket.io for real-time communication and update the list of matches in real-time.
```

### Prompt 3
```
Enhance the algorithmic matching system by incorporating additional user data such as interests and preferences. Use React to create a user interface for users to input their personality traits, interests, and preferences. Use the updated user data to recalculate the similarity score and improve the accuracy of the matches.
```


Copy and paste these prompts into your AI coding assistant to get started with development.


---
*Generated by [CodeSpark](https://github.com/YOUR_USERNAME/codespark)*
