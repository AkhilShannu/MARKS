# MARKS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Search</title>
</head>
<body>
    <h2>Student Result Finder</h2>
    <label for="studentName">Enter Student Name:</label>
    <input type="text" id="studentName">
    <button onclick="searchStudent()">Search</button>
    <p id="result"></p>
    
    <script>
        const students = {
            "John Doe": { rollNumber: "101", marks: 85 },
            "Jane Smith": { rollNumber: "102", marks: 90 },
            "Sam Wilson": { rollNumber: "103", marks: 78 }
        };

        function searchStudent() {
            let name = document.getElementById("studentName").value;
            let student = students[name];
            
            if (student) {
                document.getElementById("result").innerText = `Roll Number: ${student.rollNumber}, Marks: ${student.marks}`;
            } else {
                document.getElementById("result").innerText = "Student not found.";
            }
        }
    </script>
</body>
</html>
