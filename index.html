# Puteri-patrate-cuburi
Puteri, patrate, cuburi
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Joc Puteri și Radicali</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; text-align: center; background: #fdf2e9; padding: 20px; }
        #game-container { background: white; max-width: 600px; margin: auto; padding: 30px; border-radius: 20px; box-shadow: 0 10px 25px rgba(0,0,0,0.1); }
        .option { display: block; width: 100%; padding: 12px; margin: 10px 0; border: 2px solid #e67e22; border-radius: 8px; cursor: pointer; background: white; font-size: 18px; transition: 0.3s; }
        .option:hover { background: #fef5e7; }
        #score { font-size: 22px; color: #d35400; font-weight: bold; margin-bottom: 10px; }
        #feedback { margin-top: 15px; padding: 15px; border-radius: 8px; display: none; font-weight: bold; }
        .correct { background: #d4edda; color: #155724; border: 1px solid #c3e6cb; }
        .wrong { background: #f8d7da; color: #721c24; border: 1px solid #f5c6cb; }
        #next-btn { margin-top: 15px; padding: 10px 25px; background: #e67e22; color: white; border: none; border-radius: 5px; cursor: pointer; display: none; }
    </style>
</head>
<body>
    <div id="game-container">
        <h1>⚡ Provocarea Puterilor</h1>
        <div id="score">Scor: 0 / 20</div>
        <div id="question-area">
            <p id="question-text" style="font-size: 24px; font-weight: bold;"></p>
            <div id="options"></div>
            <div id="feedback"></div>
            <button id="next-btn">Următoarea Întrebare ➡️</button>
        </div>
    </div>

    <script>
        const questions = [
            { q: "Cât este 15²?", a: ["225", "255", "215"], c: 0, r: "15 x 15 = 225" },
            { q: "Cât este 2⁵?", a: ["10", "32", "64"], c: 1, r: "2x2x2x2x2 = 32" },
            { q: "Cât este 3⁴?", a: ["27", "81", "12"], c: 1, r: "3x3x3x3 = 81" },
            { q: "Cât este 5³?", a: ["15", "125", "75"], c: 1, r: "5x5x5 = 125" },
            { q: "Cât este 12²?", a: ["144", "122", "164"], c: 0, r: "12 x 12 = 144" },
            { q: "Cât este 2¹⁰?", a: ["512", "1024", "2048"], c: 1, r: "2¹⁰ este un număr 'magic' în informatică: 1024" },
            { q: "Cât este 3⁵?", a: ["243", "143", "333"], c: 0, r: "81 x 3 = 243" },
            { q: "Cât este 20²?", a: ["40", "200", "400"], c: 2, r: "20 x 20 = 400" },
            { q: "Cât este 4³?", a: ["12", "16", "64"], c: 2, r: "4x4=16, 16x4=64" },
            { q: "Cât este 2⁷?", a: ["64", "128", "256"], c: 1, r: "128" },
            { q: "Cât este 13²?", a: ["169", "133", "196"], c: 0, r: "13 x 13 = 169" },
            { q: "Cât este 3³?", a: ["9", "27", "18"], c: 1, r: "3x3x3 = 27" },
            { q: "Cât este 2⁸?", a: ["256", "512", "128"], c: 0, r: "256" },
            { q: "Cât este 11²?", a: ["111", "121", "131"], c: 1, r: "11 x 11 = 121" },
            { q: "Cât este 2³?", a: ["6", "8", "4"], c: 1, r: "2x2x2 = 8" },
            { q: "Cât este 16²?", a: ["256", "196", "216"], c: 0, r: "16 x 16 = 256" },
            { q: "Cât este 19²?", a: ["381", "361", "291"], c: 1, r: "19 x 19 = 361" },
            { q: "Cât este 2⁶?", a: ["32", "64", "128"], c: 1, r: "64" },
            { q: "Cât este 3²?", a: ["6", "9", "27"], c: 1, r: "3 x 3 = 9" },
            { q: "Cât este 14²?", a: ["196", "186", "206"], c: 0, r: "14 x 14 = 196" }
        ];

        let currentQ = 0;
        let score = 0;

        const qText = document.getElementById('question-text');
        const optionsDiv = document.getElementById('options');
        const feedbackDiv = document.getElementById('feedback');
        const nextBtn = document.getElementById('next-btn');
        const scoreDiv = document.getElementById('score');

        function showQuestion() {
            feedbackDiv.style.display = "none";
            nextBtn.style.display = "none";
            
            if (currentQ >= questions.length) {
                document.getElementById('question-area').innerHTML = "<h2>Felicitări! 🎉</h2><p style='font-size:20px'>Ai terminat testul puterilor cu " + score + " puncte din 20.</p>";
                return;
            }

            const q = questions[currentQ];
            qText.innerText = (currentQ + 1) + ") " + q.q;
            optionsDiv.innerHTML = "";
            
            q.a.forEach((opt, i) => {
                const btn = document.createElement('button');
                btn.className = "option";
                btn.innerText = opt;
                btn.onclick = () => check(i);
                optionsDiv.appendChild(btn);
            });
        }

        function check(idx) {
            const q = questions[currentQ];
            const allBtns = document.querySelectorAll('.option');
            allBtns.forEach(b => b.disabled = true);

            feedbackDiv.style.display = "block";
            if (idx === q.c) {
                score++;
                feedbackDiv.className = "correct";
                feedbackDiv.innerText = "EXACT! " + q.r;
            } else {
                feedbackDiv.className = "wrong";
                feedbackDiv.innerText = "Ups! Răspunsul corect era: " + q.a[q.c] + " (" + q.r + ")";
            }

            scoreDiv.innerText = "Scor: " + score + " / 20";
            nextBtn.style.display = "inline-block";
        }

        nextBtn.onclick = () => {
            currentQ++;
            showQuestion();
        };

        showQuestion();
    </script>
</body>
</html>
