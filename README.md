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
            "KAMISETTI DHANUSRITHA": { rollNumber: "101", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "NOOKALA SAI JYOTHI": { rollNumber: "102", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "BOYIDI SAI RUDRA MAHESH NAIDU": { rollNumber: "103", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "GYARA MADHAVAN SURESH KRISHNA": { rollNumber: "104", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "VOMKARAM DURGA DEEKSHITH": { rollNumber: "105", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "UPPU ADITHI RAJ": { rollNumber: "106", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "PANNALA ABHINAV REDDY": { rollNumber: "107", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "NARRAVULA JAYANTH": { rollNumber: "108", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KAGITAPALLI HARSHITHA": { rollNumber: "109", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "THUNIKI SAI KRUPAL": { rollNumber: "110", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ERIGIJJA ABHILASH": { rollNumber: "111", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "TINGARIKAR VAISHNAVI RANI": { rollNumber: "112", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "PATHA NITISH": { rollNumber: "113", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "THUMMALA ASHMITHA": { rollNumber: "114", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "MUDIREDDY HARSHA VARDHAN REDDY": { rollNumber: "115", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "YENGANNAGARI PRIYANKA": { rollNumber: "116", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KODAKANCHI SRISHANTH YADAV": { rollNumber: "117", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "MOHMMAD ALI RIYAZUDDIN": { rollNumber: "118", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "TATA ARUNA SREE": { rollNumber: "119", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "DASARI MANOHAR": { rollNumber: "120", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "MADDIKA SAINATH REDDY": { rollNumber: "121", marks: (Math.random() * 2.5 + 7.5).toFixed(1) }
            "DASARI MANOHAR": { rollNumber: "122", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "NARAYAN SINGH RUJISHA": { rollNumber: "123", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "SURYA PRAKASH REDDY": { rollNumber: "124", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "THOKALA MEGHANA": { rollNumber: "125", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ANIKETH SINGH": { rollNumber: "126", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "BANDARI SAI KIRAN REDDY": { rollNumber: "127", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KASIBHOTLA MAHA VARSHITHA": { rollNumber: "128", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "KALIDINDI KANAKA MAHALAXMI SUSHVIKA": { rollNumber: "129", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ALUKALA SAI DEERAJ GOUD": { rollNumber: "130", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "PEDDAGOLLA SAI VARDHAN": { rollNumber: "131", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "P JAYANTH": { rollNumber: "132", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "YAMA LAXMI NARAYANADRI": { rollNumber: "133", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "ADAMA CHEKRUTH REDDY": { rollNumber: "134", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "TUMMALA VIKRANTH MIHIR": { rollNumber: "135", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "AKULA NAGARAJU YADAV": { rollNumber: "136", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "NALIMALA ASHWITH REDDY": { rollNumber: "137", marks: (Math.random() * 2.5 + 7.5).toFixed(1) },
            "SHAIK AKHIL": { rollNumber: "128", marks: (Math.random() * 2.5 + 7.5).toFixed(1) }

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
