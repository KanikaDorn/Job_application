# Job_application
This form is used to collect information for a work interview.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Application Form</title>
</head>
<body>
    <h1>Job Application Form</h1>
    <form action="submit_application.php" method="POST">

<h2 style="color: rgb(139, 49, 0);"> Job Descriptions</h2>
<p>  We are looking for an expert JavaScript developer who is highly skilled with Vue.js. 
    Your primary focus will be developing user-facing web applications and components. 
    You’ll implement them with the Vue.js framework, following generally accepted practices and workflows.
    You will ensure that you produce robust, secure, modular, and maintainable code. 
    You will coordinate with other team members, including back-end developers and UX/UI designers. 
    Your commitment to team collaboration, perfect communication, and a quality product is crucial. </p>
<h2 style="color: rgb(220, 77, 20);">Job Requirements</h2>  
<p>  Highly proficient with the JavaScript language and its modern ES6+ syntax and features
    Highly proficient with Vue.js framework and its core principles such as components, reactivity, and the virtual DOM
    Good understanding of HTML5 and CSS3, including {{ Sass or Less depending on your technology stack }}
    Knowledge of functional programming and object-oriented programming paradigms</p>
        <table>
            <tr>
                <td><label for="full_name">Full Name:</label></td>
                <td><input type="text" id="full_name" name="full_name" required></td>
            </tr>
            <tr>
                <td><label for="dob">Date of Birth:</label></td>
                <td><input type="date" id="dob" name="dob" required></td>
            </tr>
            <tr>
                <td><label for="email">Email:</label></td>
                <td><input type="email" id="email" name="email" required></td>
            </tr>
            <tr>
                <td><label for="phone">Phone:</label></td>
                <td><input type="tel" id="phone" name="phone" required></td>
            </tr>
            <tr>
                <td><label for="work_experience">Work Experience (years):</label></td>
                <td><input type="number" id="work_experience" name="work_experience" required></td>
            </tr>
            <tr>
                <td><label for="previous_salary">Previous Salary ($/year):</label></td>
                <td><input type="number" id="previous_salary" name="previous_salary" required></td>
            </tr>
            <tr>
                <td><label for="education">Education:</label></td>
                <td>
                    <select id="education" name="education" required>
                        <option value="high_school">High School</option>
                        <option value="associate_degree">Associate Degree</option>
                        <option value="bachelors_degree">Bachelor's Degree</option>
                        <option value="masters_degree">Master's Degree</option>
                        <option value="phd">Ph.D.</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td colspan="2">
                    <input type="submit" value="Submit Application">
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
