# Hackathon Guidelines

Welcome to our Open-Book Hackathon! This event is not only a chance to showcase your creativity and problem-solving skills but also an opportunity to demonstrate your technical expertise. We’re looking for talented individuals who can tackle real-world challenges with innovative solutions. Below are the key guidelines for participating, solving the problem statements, and submitting your solutions.

## Table of Contents
1. [Hackathon Overview](#hackathon-overview)
2. [Rules](#rules)
3. [Problem Statements](#problem-statements)
4. [Use of Internet Resources](#use-of-internet-resources)
5. [Submission Guidelines](#submission-guidelines)
    1. [Forking the Repository](#forking-the-repository)
    2. [Solving the Problem Statement](#solving-the-problem-statement)
    3. [Documentation](#documentation)
    4. [Placing Solutions in the Solution Folder](#placing-solutions-in-the-solution-folder)
    5. [Creating a Pull Request (PR)](#creating-a-pull-request-pr)
6. [FAQs](#faqs)

---

## Hackathon Overview

This hackathon is designed to challenge participants to solve real-world problems. You are encouraged to use any resources, including the internet, to help you solve the problem statements. The hackathon is open to all skill levels, and there will be different problem statements catered to test your knowledge and skillsets.

---
## Rules

- **Open-Book**: You are free to search for information, use libraries, and refer to online resources to solve the problem.
- **Originality**: While you're free to use resources, copying solutions from other participants or repositories is not allowed.
- **Individual Participation**: This hackathon is strictly for individual participants. Collaboration or discussion of problem statements with other participants is not allowed.

---

## Problem Statements

Each team or individual will be given one or more problem statements to solve. You will find these problem statements in designated `problems` folder such as `problem1`, `problem2`, and so on. Make sure to solve the specific problem assigned to you.

---

## Use of Internet Resources

Since this is an open-book hackathon, participants are encouraged to use resources like documentation, forums, tutorials, and repositories for inspiration. However, you must cite any major third-party code or logic that you incorporate into your solution's documentation.

---

## Submission Guidelines

All submissions must be done through GitHub. The steps below outline how to fork the repository, work on your solution, and submit it.

### Forking the Repository

1. **Navigate to the Repository**: Go to the GitHub repository provided for this hackathon.
2. **Fork the Repository**: In the top-right corner of the page, click on the `Fork` button.
    - This will create a copy of the repository under your GitHub account.
3. **Clone the Repository**: Once forked, you can clone the repository to your local machine using:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Recruitment-Hackathon.git
   ```
   Replace `YOUR-USERNAME` with your GitHub username.

4. **Set Up the Repository**: After cloning, navigate to the repository folder on your local machine:
   ```bash
   cd Recruitment-Hackathon
   ```

---

### Solving the Problem Statement

- You will be assigned a specific problem statement located in a folder such as `prblm_stmt_1`, `prblm_stmt_2`, etc.
- Implement your solution inside the respective folder.
    - You are free to organize your solution using subfolders or multiple files as needed.
    - Ensure that your code is clean, well-structured, and adheres to best practices.

---

### Documentation

Once you have solved the problem statement, you must create documentation. This documentation should include:

1. **Overview of the Solution**: A brief description of how you approached and solved the problem.
2. **Implementation Details**: A technical explanation of your solution, including any frameworks, libraries, or tools you used.
3. **Screenshots**: Add screenshots showcasing your workflow and output (if applicable).
4. **Challenges and Learning**: Mention any challenges faced during the development and the learning outcomes.

Make sure the documentation is clear and concise, located in a `README.md` file inside the respective problem folder.

---

### Placing Solutions in the Solution Folder

Once the problem is solved:

1. **Create a 'solution_folder'** inside the respective problem folder.
2. **Place your solution files** and related media (e.g., images or screenshots) inside this folder.
3. Ensure that the solution is well-organized and clearly labeled for easy navigation.

---

### Creating a Pull Request (PR)

After solving the problem and organizing your solution, you will need to submit it by creating a Pull Request (PR) on GitHub. Follow these steps:

1. **Commit Your Changes**:
   - Stage your changes:
     ```bash
     git add .
     ```
   - Commit your changes with a meaningful message:
     ```bash
     git commit -m "<YOUR-NAME> - <SOLVED-PROBLEM-STATEMENT>"
     ```

2. **Push Your Changes**: Push the committed changes to your forked repository:
   ```bash
   git push origin main
   ```

3. **Create the Pull Request**:
    - Go to the original repository where you forked from.
    - Click the `Pull Requests` tab.
    - Click on `New Pull Request`.
    - Select your forked repository as the "head repository" and the original repository as the "base repository".
    - Add a meaningful description explaining what problem you solved and how.
    - Click `Create Pull Request`.

4. **Review**: Your pull request will be reviewed by the hackathon judges.

---

## FAQs

### Can we use libraries or frameworks in our solution?
Yes, you are free to use any libraries, frameworks, or online tools as long as you document them properly.

### Is this a team or individual competition?
This is a strictly individual competition. No participants are allowed to communicate with each other.

### How do we communicate with the organizers during the hackathon?
You can reach out to the organizers present in the hall.

---

Good luck, and happy coding!
