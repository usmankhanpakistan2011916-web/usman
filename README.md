<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Exercises</title>
</head>
<body>

    <!-- ==================== EXERCISE 1 ==================== -->
    <h2>Exercise 1 - Student Marks Counter</h2>

    <h1 class="marks">50</h1>

    <button class="addMarks">Add Bonus Marks</button>
    <button class="deductMarks">Deduct Marks</button>

    <hr>

    <!-- ==================== EXERCISE 2 ==================== -->
    <h2>Exercise 2 - Age Counter</h2>

    <h1 class="age">18</h1>

    <button class="birthday">Birthday</button>
    <button class="goBack">Go Back One Year</button>

    <hr>

    <!-- ==================== EXERCISE 3 ==================== -->
    <h2>Exercise 3 - Light Bulb Status</h2>

    <h1 class="bulbStatus">Bulb is OFF</h1>

    <button class="turnOn">Turn ON</button>
    <button class="turnOff">Turn OFF</button>

    <script>

        // ==================== EXERCISE 1 ====================

        let marks = 50;

        const marksHeading = document.querySelector(".marks");
        const addBtn = document.querySelector(".addMarks");
        const deductBtn = document.querySelector(".deductMarks");

        function addMarks() {
            marks += 5;
            marksHeading.innerHTML = marks;
        }

        function deductMarks() {
            marks -= 5;
            marksHeading.innerHTML = marks;
        }

        addBtn.addEventListener("click", addMarks);
        deductBtn.addEventListener("click", deductMarks);


        // ==================== EXERCISE 2 ====================

        let age = 18;

        const ageHeading = document.querySelector(".age");
        const birthdayBtn = document.querySelector(".birthday");
        const backBtn = document.querySelector(".goBack");

        function incrementAge() {
            age++;
            ageHeading.innerHTML = age;
        }

        function decrementAge() {
            age--;
            ageHeading.innerHTML = age;
        }

        birthdayBtn.addEventListener("click", incrementAge);
        backBtn.addEventListener("click", decrementAge);


        // ==================== EXERCISE 3 ====================

        const bulbHeading = document.querySelector(".bulbStatus");
        const onBtn = document.querySelector(".turnOn");
        const offBtn = document.querySelector(".turnOff");

        function turnOn() {
            bulbHeading.innerHTML = "Bulb is ON";
        }

        function turnOff() {
            bulbHeading.innerHTML = "Bulb is OFF";
        }

        onBtn.addEventListener("click", turnOn);
        offBtn.addEventListener("click", turnOff);

    </script>

</body>
</html>
