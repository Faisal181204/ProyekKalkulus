<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Latihan Soal Limit - Syaila</title>
  <style>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f7f1; /* Soft beige background */
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #87CEEB; /* Sky blue header */
  color: white;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  border-bottom: 3px solid #66c2ff; /* Slightly lighter blue border */
}

h1 {
  margin: 0;
  font-size: 2.5em;
  letter-spacing: 1px;
  font-weight: bold;
}

main {
  padding: 30px;
  max-width: 850px;
  margin: 20px auto;
  background-color: #fff; /* White background for main content */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
  border-radius: 12px;
  border: 1px solid #ddd;
}

.question-container {
  margin-bottom: 40px;
  padding: 20px;
  background-color: #fff8e1; /* Light beige background */
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
  font-size: 1.4em;
  margin-bottom: 15px;
  color: #4c4c4c; /* Slightly darker color for headings */
  font-weight: 600;
}

input[type="number"] {
  width: 100%;
  padding: 12px;
  font-size: 1.1em;
  border: 2px solid #87CEEB; /* Sky blue border */
  border-radius: 6px;
  margin-bottom: 15px;
  box-sizing: border-box;
  transition: border-color 0.3s ease;
}

input[type="number"]:focus {
  border-color: #66c2ff; /* Lighter blue when focused */
  outline: none;
}

button {
  padding: 12px 24px;
  font-size: 1.2em;
  background-color: #87CEEB; /* Sky blue button */
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

button:hover {
  background-color: #66c2ff; /* Lighter sky blue on hover */
  transform: translateY(-2px); /* Button pop effect */
}

button:active {
  transform: translateY(0); /* Reset to normal position when clicked */
}

p {
  font-size: 1.1em;
  margin-top: 10px;
}

.explanation {
  display: none;
  margin-top: 20px;
  padding: 15px;
  background-color: #e7f7fe; /* Light blue background for explanations */
  border-left: 5px solid #87CEEB; /* Sky blue left border */
  font-size: 1.1em;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.explanation.visible {
  display: block;
}

#resultProduct,
#resultTrig {
  font-weight: bold;
  font-size: 1.2em;
}

.hint {
  display: none;
  margin-top: 20px;
  padding: 15px;
  background-color: #fff3e0; /* Lighter beige for hints */
  border-left: 5px solid #f44336; /* Red left border for hints */
  color: #d32f2f; /* Red color for hint text */
  font-size: 1.1em;
  border-radius: 8px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 1em;
  position: relative;
  bottom: 0;
  width: 100%;
  margin-top: 40px;
}

footer p {
  margin: 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  main {
    padding: 20px;
    margin: 10px;
  }

  h1 {
    font-size: 2em;
  }

  h2 {
    font-size: 1.2em;
  }

  input[type="number"], button {
    font-size: 1em;
  }

  .question-container {
    padding: 15px;
  }

  footer p {
    font-size: 0.9em;
  }
}
/* Tampilan umum untuk halaman */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f7f1; /* Soft beige background */
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #87CEEB; /* Sky blue header */
  color: white;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  border-bottom: 3px solid #66c2ff; /* Slightly lighter blue border */
}

h1 {
  margin: 0;
  font-size: 2.5em;
  letter-spacing: 1px;
  font-weight: bold;
}

main {
  padding: 30px;
  max-width: 850px;
  margin: 20px auto;
  background-color: #fff; /* White background for main content */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
  border-radius: 12px;
  border: 1px solid #ddd;
}

.question-container {
  margin-bottom: 40px;
  padding: 20px;
  background-color: #fff8e1; /* Light beige background */
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
  font-size: 1.4em;
  margin-bottom: 15px;
  color: #4c4c4c; /* Slightly darker color for headings */
  font-weight: 600;
}

input[type="number"] {
  width: 100%;
  padding: 12px;
  font-size: 1.1em;
  border: 2px solid #87CEEB; /* Sky blue border */
  border-radius: 6px;
  margin-bottom: 15px;
  box-sizing: border-box;
  transition: border-color 0.3s ease;
}

input[type="number"]:focus {
  border-color: #66c2ff; /* Lighter blue when focused */
  outline: none;
}

button {
  padding: 12px 24px;
  font-size: 1.2em;
  background-color: #87CEEB; /* Sky blue button */
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

button:hover {
  background-color: #66c2ff; /* Lighter sky blue on hover */
  transform: translateY(-2px); /* Button pop effect */
}

button:active {
  transform: translateY(0); /* Reset to normal position when clicked */
}

p {
  font-size: 1.1em;
  margin-top: 10px;
}

/* Explanation section for the new question */
.explanation {
  display: none; /* Hidden by default */
  margin-top: 20px;
  padding: 15px;
  background-color: #e7f7fe; /* Light blue background for explanations */
  border-left: 5px solid #87CEEB; /* Sky blue left border */
  font-size: 1.1em;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.explanation.visible {
  display: block;
}

#resultProduct,
#resultTrig {
  font-weight: bold;
  font-size: 1.2em;
}

/* Hint for the new question */
.hint {
  display: none; /* Hidden by default */
  margin-top: 20px;
  padding: 15px;
  background-color: #fff3e0; /* Lighter beige for hints */
  border-left: 5px solid #f44336; /* Red left border for hints */
  color: #d32f2f; /* Red color for hint text */
  font-size: 1.1em;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 1em;
  position: relative;
  bottom: 0;
  width: 100%;
  margin-top: 40px;
}

footer p {
  margin: 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  main {
    padding: 20px;
    margin: 10px;
  }

  h1 {
    font-size: 2em;
  }

  h2 {
    font-size: 1.2em;
  }

  input[type="number"], button {
    font-size: 1em;
  }

  .question-container {
    padding: 15px;
  }

  footer p {
    font-size: 0.9em;
  }
}

  </style>
  <script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
  </script>
</head>
<body>
  <header>
    <h1>Latihan Soal Limit</h1>
  </header>
  <main>
<!-- Soal 1: Limit perkalian dua fungsi -->
<div class="question-container">
  <h2>1. Tentukan \( \lim_{x \to 2} (x + 2)(x - 2) \):</h2>
  <input type="number" id="limitProduct" placeholder="Jawaban Anda">
  <button type="button" onclick="checkLimitProduct()">Cek Jawaban</button>
  <p id="resultProduct"></p>
  <div id="explanationProduct" class="explanation"></div>
  <div id="hintProduct" class="hint">Hint: Coba substitusi langsung \( x = 2 \) dan lihat hasilnya.</div> <!-- Added hint -->
</div>

<!-- Soal 2: Limit trigonometri -->
<div class="question-container">
  <h2>2. Tentukan \( \lim_{x \to 0} \frac{\sin(x)}{x} \):</h2>
  <input type="number" id="limitTrig" placeholder="Jawaban Anda">
  <button type="button" onclick="checkLimitTrig()">Cek Jawaban</button>
  <p id="resultTrig"></p>
  <div id="explanationTrig" class="explanation"></div>
  <div id="hintTrig" class="hint">Hint: Gunakan aturan limit dasar trigonometri yang menyatakan bahwa \( \lim_{x \to 0} \frac{\sin(x)}{x} = 1 \).</div> <!-- Added hint -->
</div>
<!-- Soal 3: Limit dengan pemfaktoran -->
<div class="question-container">
  <h2>3. Tentukan \( \lim_{x \to 7} \frac{x-7}{\sqrt{x} - \sqrt{7}} \):</h2>
  <input type="number" id="limitFactor" placeholder="Jawaban Anda">
  <button type="button" onclick="checkLimitFactor()">Cek Jawaban</button>
  <p id="resultFactor"></p>
  <div id="explanationFactor" class="explanation"> <strong>Pembahasan:</strong><br>
        Untuk menghitung limit ini, kita lakukan pemfaktoran sebagai berikut:<br><br>
        \( \lim_{x \to 7} \frac{x - 7}{\sqrt{x} - \sqrt{7}} \) dapat difaktorkan dengan mengalikan pembilang dan penyebut dengan \( \frac{\sqrt{x} + \sqrt{7}}{\sqrt{x} + \sqrt{7}} \):<br><br>
        \( \lim_{x \to 7} \frac{(x - 7)(\sqrt{x} + \sqrt{7})}{(\sqrt{x} - \sqrt{7})(\sqrt{x} + \sqrt{7})} \)<br><br>
        Di mana penyebutnya menjadi \( (\sqrt{x})^2 - (\sqrt{7})^2 = x - 7 \), sehingga limitnya menjadi:<br><br>
        \( \lim_{x \to 7} \frac{(x - 7)(\sqrt{x} + \sqrt{7})}{x - 7} \)<br><br>
        Setelah pembatalan faktor \( (x - 7) \), kita dapatkan limit yang lebih sederhana:<br><br>
        \( \lim_{x \to 7} (\sqrt{x} + \sqrt{7}) \)<br><br>
        Ketika \( x \to 7 \), kita mendapatkan:<br><br>
        \( \sqrt{7} + \sqrt{7} = 2 \sqrt{7} \)</div>
  <div id="hintFactor" class="hint">Hint: Cobalah untuk melakukan pemfaktoran dengan mengalikan pecahan dengan \( \frac{\sqrt{x} + \sqrt{7}}{\sqrt{x} + \sqrt{7}} \).</div> <!-- Hint for the new question -->
</div>

  </main>
  <footer>
    <p>© 2024 Latihan Soal Kalkulus Syaila</p>
  </footer>
  <script>
// Track the number of attempts
let attemptsProduct = 0;
let attemptsTrig = 0;

// Fungsi untuk mengecek limit perkalian dua fungsi
function checkLimitProduct() {
  const userAnswer = parseFloat(document.getElementById('limitProduct').value);
  const resultElement = document.getElementById('resultProduct');
  const explanationElement = document.getElementById('explanationProduct');
  const hintElement = document.getElementById('hintProduct');

  // Increment attempt count
  attemptsProduct++;

  // Jawaban yang benar adalah 0
  if (userAnswer === 0) {
    resultElement.textContent = "Jawaban benar! Limitnya adalah 0.";
    resultElement.style.color = "green";
    explanationElement.textContent = "";
    explanationElement.style.color = "green";
    hintElement.style.display = "none"; // Hide hint after correct answer
  } else {
    resultElement.textContent = "Jawaban salah. Coba lagi.";
    resultElement.style.color = "red";
    
    // Show hint if it's the first wrong answer
    if (attemptsProduct === 1) {
      hintElement.style.display = "block";
      explanationElement.style.display = "none"; // Hide explanation initially
    } 
    
    // Show explanation if it's more than 3 wrong attempts
    if (attemptsProduct > 3) {
      explanationElement.style.display = "block";
      explanationElement.textContent = "Pembahasan: Limitnya adalah 0. Untuk menghitungnya, substitusi \( x = 2 \) menghasilkan \( (2 + 2)(2 - 2) = 0 \).";
      explanationElement.style.color = "red";
      hintElement.style.display = "none"; // Hide hint after explanation is shown
    }
  }
  
  // Menampilkan pembahasan setelah 3 salah
  explanationElement.classList.add("visible");
}

// Fungsi untuk mengecek limit trigonometri
function checkLimitTrig() {
  const userAnswer = parseFloat(document.getElementById('limitTrig').value);
  const resultElement = document.getElementById('resultTrig');
  const explanationElement = document.getElementById('explanationTrig');
  const hintElement = document.getElementById('hintTrig');

  // Increment attempt count
  attemptsTrig++;

  // Jawaban yang benar adalah 1
  if (userAnswer === 1) {
    resultElement.textContent = "Jawaban benar! Limitnya adalah 1.";
    resultElement.style.color = "green";
    explanationElement.textContent = "";
    explanationElement.style.color = "green";
    hintElement.style.display = "none"; // Hide hint after correct answer
  } else {
    resultElement.textContent = "Jawaban salah. Coba lagi.";
    resultElement.style.color = "red";

    // Show hint if it's the first wrong answer
    if (attemptsTrig === 1) {
      hintElement.style.display = "block";
      explanationElement.style.display = "none"; // Hide explanation initially
    }

    // Show explanation if it's more than 3 wrong attempts
    if (attemptsTrig > 3) {
      explanationElement.style.display = "block";
      explanationElement.textContent = "Pembahasan: Limitnya adalah 1. Gunakan aturan limit dasar trigonometri untuk menghitungnya.";
      explanationElement.style.color = "red";
      hintElement.style.display = "none"; // Hide hint after explanation is shown
    }
  }

  // Menampilkan pembahasan setelah 3 salah
  explanationElement.classList.add("visible");
}
// Track the number of attempts for the new question
let attemptsFactor = 0;
// Fungsi untuk mengecek limit dengan pemfaktoran
function checkLimitFactor() {
  const userAnswer = parseFloat(document.getElementById('limitFactor').value);
  const resultElement = document.getElementById('resultFactor');
  const explanationElement = document.getElementById('explanationFactor');
  const hintElement = document.getElementById('hintFactor');

  // Increment attempt count
  attemptsFactor++;

  // Jawaban yang benar adalah 2 * sqrt(7)
  const correctAnswer = 2 * Math.sqrt(7);

  if (Math.abs(userAnswer - correctAnswer) < 0.0001) {
    resultElement.textContent = "Jawaban benar! Limitnya adalah " + correctAnswer;
    resultElement.style.color = "green";
    explanationElement.textContent = "";
    explanationElement.style.color = "green";
    hintElement.style.display = "none"; // Hide hint after correct answer
  } else {
    resultElement.textContent = "Jawaban salah. Coba lagi.";
    resultElement.style.color = "red";
    
    // Show hint if it's the first wrong answer
    if (attemptsFactor === 1) {
      hintElement.style.display = "block";
      explanationElement.style.display = "none"; // Hide explanation initially
    }
    
    // Show explanation if it's more than 3 wrong attempts
    if (attemptsFactor > 3) {
      explanationElement.style.display = "block";
      explanationElement.style.display = `block`;
      explanationElement.style.color = "red";
      hintElement.style.display = "none"; // Hide hint after explanation is shown
    }
  }
  
  // Menampilkan pembahasan setelah 3 salah
  explanationElement.classList.add("visible");
  MathJax.Hub.Queue(["Typeset", MathJax.Hub, explanationElement]); // Re-render MathJax for LaTeX formatting
}



</script>
</body>
</html>
