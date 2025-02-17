# ambschoolparentsfeedbackform
This is the AMB Public School's Parent's Feedback form.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AMB Public School - Parent's Feedback Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1a73e8;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 50%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        label {
            font-size: 16px;
            color: #333;
            margin-top: 10px;
            display: block;
        }
        input[type="text"], input[type="email"], select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }
        textarea {
            resize: vertical;
            height: 120px;
        }
        .btn {
            background-color: #1a73e8;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
        }
        .btn:hover {
            background-color: #0f5eb5;
        }
    </style>
</head>
<body>

<header>
    <h1>AMB Public School - Parent's Feedback Form</h1>
</header>

<div class="container">
    <h2>We value your feedback</h2>
    <p>Please provide your feedback to help us improve the educational experience for your child. Your responses will remain confidential.</p>

    <form action="#" method="POST">

        <label for="parent_name">Parent's Name:</label>
        <input type="text" id="parent_name" name="parent_name" required>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>

        <label for="child_name">Child's Name:</label>
        <input type="text" id="child_name" name="child_name" required>

        <label for="class">Child's Class:</label>
        <select id="class" name="class" required>
            <option value="">Select Class</option>
            <option value="Grade 1">Grade 1</option>
            <option value="Grade 2">Grade 2</option>
            <option value="Grade 3">Grade 3</option>
            <option value="Grade 4">Grade 4</option>
            <option value="Grade 5">Grade 5</option>
            <option value="Grade 6">Grade 6</option>
            <option value="Grade 7">Grade 7</option>
            <option value="Grade 8">Grade 8</option>
            <option value="Grade 9">Grade 9</option>
            <option value="Grade 10">Grade 10</option>
        </select>

        <label for="satisfaction">Overall satisfaction with the school:</label>
        <select id="satisfaction" name="satisfaction" required>
            <option value="">Select</option>
            <option value="Very Satisfied">Very Satisfied</option>
            <option value="Satisfied">Satisfied</option>
            <option value="Neutral">Neutral</option>
            <option value="Dissatisfied">Dissatisfied</option>
            <option value="Very Dissatisfied">Very Dissatisfied</option>
        </select>

        <label for="suggestions">Suggestions for Improvement:</label>
        <textarea id="suggestions" name="suggestions" placeholder="Please provide any suggestions you may have..." required></textarea>

        <label for="comments">Additional Comments:</label>
        <textarea id="comments" name="comments" placeholder="Feel free to share any additional comments here..." required></textarea>

        <button type="submit" class="btn">Submit Feedback</button>

    </form>
</div>

</body>
</html>
