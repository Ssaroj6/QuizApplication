🧠 React Quiz Application
A fully functional quiz management application built with React that supports:

✅ Multiple Choice Questions (Single Correct)
✅ Multiple Choice Questions (Multiple Correct)
✅ Short Answer Questions (One or Two Words)
✅ Quiz Creation, Playing, Editing, and Deleting
✅ LocalStorage for quiz persistence
📂 Project Structure
├── components/ │ ├── Navbar.jsx │ ├── MyQuizes.jsx │ ├── PlayQuiz.jsx │ ├── QuizGame.jsx │ ├── EditQuiz.jsx │ ├── quizTypes/ │ ├── Mcq_single.jsx │ ├── Mcq_multiple.jsx │ └── Short_answer.jsx │ ├── App.jsx └── index.js

🚀 Features
✍️ Create Quizzes
MCQ (Single Correct): Choose only one correct answer
MCQ (Multiple Correct): Select multiple correct answers using checkboxes
Short Answer: Users must type a one or two-word answer
Each quiz includes:

Title
Description
Dynamically added questions
Local validation before saving
🧾 My Quizzes
View saved quizzes
Toggle quiz status (Active/Inactive)
Edit or delete existing quizzes
🎮 Play Quiz
List of active quizzes available to play
Route-based quiz rendering using React Router
Auto-hides inactive quizzes from the play screen
🛠 Edit Quiz
Preloads data using localStorage
Allows editing of:
Quiz title and description
All questions and answers/options
Supports all quiz types
🧱 Built With
React.js – Functional components and Hooks
React Router DOM – For routing between views
TailwindCSS – For styling and responsiveness
LocalStorage – For storing quiz data locally
