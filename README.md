<center>MARKS</center>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Result Finder</title>
</head>
<body>
    <h2>Student Result Finder</h2>
    <label for="studentName">Enter Student Name:</label>
    <input type="text" id="studentName">
    <button onclick="searchStudent()">Search</button>
    <p id="result"></p>
    
    <script>
        const students = {
            "DASARI MANOHAR": { rollNumber: "122", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "NARAYAN SINGH RUJISHA": { rollNumber: "123", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "S SURYA PRAKASH REDDY": { rollNumber: "124", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "THOKALA MEGHANA": { rollNumber: "125", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ANIKETH SINGH": { rollNumber: "120", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "BANDARI SAI KIRAN REDDY": { rollNumber: "127", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KASIBHOTLA MAHA VARSHITHA": { rollNumber: "128", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KALIDINDI KANAKA MAHALAXMI SUSHVIKA": { rollNumber: "129", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ALUKALA SAI DEERAJ GOUD": { rollNumber: "130", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "PEDDAGOLLA SAI VARDHAN": { rollNumber: "131", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "P JAYANTH": { rollNumber: "135", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "SHAIK AKHIL": { rollNumber: "133", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ADAMA CHEKRUTH REDDY": { rollNumber: "134", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "TUMMALA VIKRANTH MIHIR": { rollNumber: "135", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "HARSHIT": { rollNumber: "136", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "SHRUTHI": { rollNumber: "137", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "MADDIKA SAINATH REDDY": { rollNumber: "138", marks: (Math.random() * 2.5 + 7.5).toFixed(1) }
        };

        function searchStudent() {
            let name = document.getElementById("studentName").value.toUpperCase();
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
