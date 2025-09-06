<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>CSIR NET OMR — Feb 2025 (Final)</title>
    <style>
        :root{
            --bg:#f6f8fb;--card:#fff;--muted:#6b7280;--text:#0f172a;--accent:#2563eb;
            --ok:#16a34a;--warn:#f59e0b;--yellow:#fbbf24;--green:#22d3ee;--bad:#ef4444
        }
        body{font-family:Inter,system-ui,Segoe UI,Roboto,Arial;margin:18px;background:var(--bg);color:var(--text);}
        .container{max-width:980px;margin:0 auto;background:var(--card);padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(16,24,40,0.06)}
        h1{margin:0 0 6px;font-size:20px}
        p.lead{margin:0 0 12px;color:var(--muted);font-size:14px}
        h2{margin-top:14px;margin-bottom:6px;font-size:18px;color:var(--accent)}
        .controls{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:12px}
        button, a.button{padding:8px 10px;border-radius:8px;border:1px solid #e6eef8;background:#fff;cursor:pointer;font-weight:600;text-decoration:none;color:inherit;display:inline-flex;align-items:center;gap:8px}
        .primary{background:var(--accent);color:#fff;border-color:transparent}
        .danger{background:var(--bad);color:#fff;border-color:transparent}
        .ghost{background:#fff;color:var(--text)}
        .blue-btn{background:var(--ok)!important;color:#fff!important;}
        .yellow-btn{background:var(--yellow)!important;color:#fff!important;}
        .green-btn{background:var(--green)!important;color:#fff!important;}
        .red-btn{background:var(--bad)!important;color:#fff!important;}
        .omr{border-top:1px solid #eef2f7;padding-top:12px;display:block;max-height:62vh;overflow:auto;padding-bottom:8px}
        .row{display:flex;align-items:center;gap:10px;padding:6px;border-radius:6px;border:1px solid #f1f5f9;background:#fcfeff;margin-bottom:4px;flex-wrap:wrap;}
        .qno{width:56px;text-align:center;font-weight:700;color:var(--accent);transition:background 0.2s, color 0.2s;}
        .qno.blue{background:var(--ok);color:#fff;}
        .qno.yellow{background:var(--yellow);color:#fff;}
        .qno.green{background:var(--green);color:#fff;}
        .qno.red{background:var(--bad);color:#fff;}
        .bubbles{display:flex;gap:10px;align-items:center}
        .bubble{display:inline-flex;align-items:center;gap:8px;padding:8px 10px;border-radius:8px;border:1px solid #e6eef8;background:#fff;cursor:pointer;font-weight:600}
        input[type="radio"]{accent-color:var(--accent);width:18px;height:18px}
        .flag{margin-left:auto;font-size:12px;padding:6px 10px;border-radius:999px;background:var(--warn);color:#fff;display:none}
        .question-controls{margin-top:6px;display:flex;gap:8px;flex-wrap:wrap;}
        .review-box{background:#eef7ff;padding:7px 12px;border-radius:7px;font-size:14px;margin-top:4px;}
        .summary{margin-top:12px;display:flex;gap:12px;flex-wrap:wrap}
        .summary .card{padding:10px;border-radius:8px;background:#fff;border:1px solid #eef2f7;min-width:160px}
        .result{margin-top:12px;padding:10px;border-radius:8px;background:#fff;border:1px solid #eef2f7}
        #responseSheet{margin-top:16px;padding:10px;border-radius:8px;background:#fff;border:1px solid #eef2f7;display:none}
        #responseSheet .qline{margin-bottom:6px;font-size:14px}
        #responseSheet .opt{display:inline-block;margin-right:8px;padding:4px 10px;border-radius:6px;border:1px solid #ccc}
        #responseSheet .correct{background:var(--ok);color:#fff;border-color:var(--ok)}
        #responseSheet .wrong{background:var(--bad);color:#fff;border-color:var(--bad)}
        #sendMailBtn {margin-top:18px;padding:11px 20px;font-size:18px;background:#2563eb;color:#fff;border:none;border-radius:8px;cursor:pointer;}
        #emailOverlay {
            position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
            background: rgba(246,248,251, 0.96); z-index: 9999; display: flex; align-items: center; justify-content: center;
        }
        #emailBox {
            background: #fff; padding: 32px; border-radius: 12px; box-shadow: 0 2px 10px #0002; max-width: 320px; width: 100%; text-align: center;
        }
        #emailBox input { width: 90%; margin-top: 10px; padding: 8px; font-size: 16px;}
        #emailBox button { margin-top: 16px; width: 100%; }
        #emailBox .error { color: var(--bad); margin-top: 8px; }
        @media print{
            body{background:white;margin:0}
            .container{box-shadow:none;border-radius:0;padding:8px;max-width:100%}
            .controls, .summary, .omr, #timer, #sendMailBtn{display:none}
            #responseSheet{display:block !important}
            #emailOverlay{display:none !important;}
        }
    </style>
</head>
<body>
<div id="emailOverlay">
    <div id="emailBox">
        <h2>Enter your Name and Gmail</h2>
        <input type="text" id="userName" placeholder="Your Name" required>
        <input type="email" id="userEmail" placeholder="example@gmail.com" required>
        <button onclick="showQuiz()">Start Quiz</button>
        <div class="error" id="overlayError" style="display:none;"></div>
    </div>
</div>
<div class="container">
    <h1>CSIR NET — OMR Style (Feb 2025 Key)</h1>
    <p class="lead">Attempt limits: Part A ≤ 15, Part B ≤ 25, Part C ≤ 30. Negative marking: 1/4.</p>
    <div id="timer" style="font-size:16px;font-weight:bold;color:#2563eb;margin-bottom:12px;">
        Time Left: <span id="timeDisplay">03:00:00</span>
    </div>
    <div class="controls">
        <button id="clearAll" class="ghost">Clear All</button>
        <button id="markAllReview" class="ghost">Mark All Review</button>
        <button id="submitBtn" class="primary">Submit & Evaluate</button>
        <button id="printBtn" class="ghost">Print</button>
        <button id="pdfBtn" class="ghost">Download PDF</button>
    </div>
    <div class="omr" id="omr">
        <h2>Part A</h2>
        <div id="partA"></div>
        <h2>Part B</h2>
        <div id="partB"></div>
        <h2>Part C</h2>
        <div id="partC"></div>
    </div>
    <div class="summary">
        <div class="card"><strong>Attempted A</strong><div id="countA">0</div></div>
        <div class="card"><strong>Attempted B</strong><div id="countB">0</div></div>
        <div class="card"><strong>Attempted C</strong><div id="countC">0</div></div>
        <div class="card"><strong>Marked Review</strong><div id="countReview">0</div></div>
    </div>
    <div id="resultPane" class="result" style="display:none"></div>
    <div id="responseSheet"></div>
    <div id="sendMailArea" style="display:none;text-align:center;">
        <a id="sendMailBtn" href="#" target="_blank">Send Response Sheet to Teacher</a>
    </div>
</div>
<script>
    function showQuiz() {
        var name = document.getElementById('userName').value.trim();
        var email = document.getElementById('userEmail').value.trim();
        var errorBox = document.getElementById('overlayError');
        if(!name) {
            errorBox.textContent = "Please enter your name.";
            errorBox.style.display = "block";
            return;
        }
        if(!email.match(/^[a-zA-Z0-9._%+-]+@gmail\.com$/)) {
            errorBox.textContent = "Please enter a valid Gmail address.";
            errorBox.style.display = "block";
            return;
        }
        errorBox.style.display = "none";
        document.getElementById('emailOverlay').style.display = "none";
        window.quizUserEmail = email;
        window.quizUserName = name;
    }
</script>
<script>
    const PART_A={start:1,end:20,marks:2,maxAttempt:15};
    const PART_B={start:21,end:60,marks:2,maxAttempt:25};
    const PART_C={start:61,end:120,marks:4,maxAttempt:30};
    const NEG_FRAC=0.25;
    const numericKey={
        1:2,2:2,3:4,4:2,5:1,6:1,7:4,8:4,9:3,10:3,11:4,12:3,13:4,14:3,15:2,16:4,17:1,18:2,19:3,20:2,
        21:4,22:2,23:4,24:3,25:1,26:3,27:3,28:3,29:3,30:1,31:4,32:4,33:1,34:1,35:1,36:4,37:2,38:1,39:2,40:2,
        41:1,42:3,43:3,44:4,45:2,46:2,47:2,48:4,49:4,50:4,51:2,52:2,53:3,54:4,55:2,56:1,57:3,58:2,59:2,60:1,
        61:2,62:1,63:3,64:1,65:3,66:1,67:1,68:1,69:1,70:3,71:2,72:2,73:3,74:2,75:4,76:2,77:3,78:2,79:1,80:2,
        81:3,82:3,83:1,84:2,85:3,86:3,87:4,88:3,89:1,90:4,91:3,92:1,93:2,94:2,95:2,96:1,97:1,98:1,99:4,100:3,
        101:2,102:2,103:2,104:1,105:1,106:3,107:2,108:2,109:3,110:3,111:1,112:3,113:2,114:4,115:3,116:4,117:4,118:3,119:1,120:3
    };
    const mapNumToLetter={1:'A',2:'B',3:'C',4:'D'};
    const answerKey={};for(const q in numericKey){answerKey[q]=mapNumToLetter[numericKey[q]];}
    let reviewOnlyQs = {};
    function buildSection(start, end, containerId){
        const container = document.getElementById(containerId);
        for(let q=start; q<=end; q++){
            const row=document.createElement('div');row.className='row';row.dataset.q=q;
            const qno=document.createElement('div');qno.className='qno';qno.textContent='Q'+q;row.appendChild(qno);
            const bubbles=document.createElement('div');bubbles.className='bubbles';
            ['A','B','C','D'].forEach(letter=>{
                const lbl=document.createElement('label');lbl.className='bubble';
                lbl.innerHTML=`<input type="radio" name="q${q}" value="${letter}"/> ${letter}`;
                lbl.ondblclick=function(e){
                    let radios = document.querySelectorAll(`input[name="q${q}"]`);
                    radios.forEach(r=>{r.checked=false;});
                    setQnoColor(q,null);
                };
                bubbles.appendChild(lbl);
            });
            row.appendChild(bubbles);
            const qControls=document.createElement('div');
            qControls.className="question-controls";
            qControls.innerHTML=`
                <button type="button" class="blue-btn" onclick="submitQ(${q},this)">Submit</button>
                <button type="button" class="green-btn" onclick="reviewSubmitQ(${q},this)">Review & Submit</button>
                <button type="button" class="yellow-btn" onclick="reviewQ(${q},this)">Review</button>
                <button type="button" class="red-btn" onclick="clearQ(${q},this)">Clear</button>
                <div class="review-box" id="reviewBox${q}" style="display:none;"></div>
            `;
            row.appendChild(qControls);
            const flag=document.createElement('div');flag.className='flag';flag.textContent='REVIEW';row.appendChild(flag);
            container.appendChild(row);
        }
    }
    buildSection(PART_A.start, PART_A.end, 'partA');
    buildSection(PART_B.start, PART_B.end, 'partB');
    buildSection(PART_C.start, PART_C.end, 'partC');
    let totalSeconds = 180 * 60;
    const timeDisplay = document.getElementById('timeDisplay');
    function formatTime(sec){
        let hrs = Math.floor(sec / 3600);
        let mins = Math.floor((sec % 3600) / 60);
        let secs = sec % 60;
        return `${hrs.toString().padStart(2,'0')}:${mins.toString().padStart(2,'0')}:${secs.toString().padStart(2,'0')}`;
    }
    function updateTimer(){
        if(totalSeconds <= 0){
            clearInterval(timerInterval);
            alert("Time is up! The exam will be submitted automatically.");
            document.getElementById('submitBtn').click();
            return;
        }
        timeDisplay.textContent = formatTime(totalSeconds);
        totalSeconds--;
    }
    const timerInterval = setInterval(updateTimer,1000);
    updateTimer();
    function countInRange(s,e){let c=0;for(let q=s;q<=e;q++){if(document.querySelector(`input[name="q${q}"]:checked`))c++;}return c;}
    function updateCounts(){
        document.getElementById('countA').textContent=countInRange(PART_A.start,PART_A.end);
        document.getElementById('countB').textContent=countInRange(PART_B.start,PART_B.end);
        document.getElementById('countC').textContent=countInRange(PART_C.start,PART_C.end);
        document.getElementById('countReview').textContent=document.querySelectorAll('.flag[style*="inline"]').length;
    }
    document.body.addEventListener('change',(e)=>{
        if(e.target.type!=='radio')return;
        const q=parseInt(e.target.name.slice(1),10);
        let cfg=(q<=20?PART_A:(q<=60?PART_B:PART_C));
        if(countInRange(cfg.start,cfg.end)>cfg.maxAttempt){e.target.checked=false;alert('Limit reached');}
        updateCounts();
        setQnoColor(q, null); // Reset color when selection is changed
    });
    function setQnoColor(q, colorClass) {
        let qno = document.querySelector(`.row[data-q="${q}"] .qno`);
        qno.classList.remove("blue","yellow","green","red");
        if(colorClass) qno.classList.add(colorClass);
    }
    function submitQ(q,btn){
        document.querySelectorAll(`input[name="q${q}"]`).forEach(r=>r.disabled=true);
        showReviewBox(q, "Submitted and locked. Your answer: "+(getSelected(q)||"Not Attempted"), true);
        setQnoColor(q,"blue");
        reviewOnlyQs[q] = false;
    }
    function reviewSubmitQ(q,btn){
        document.querySelectorAll(`input[name="q${q}"]`).forEach(r=>r.disabled=true);
        showReviewBox(q, "Marked for review and locked. Your answer: "+(getSelected(q)||"Not Attempted"), true);
        setQnoColor(q,"green");
        reviewOnlyQs[q] = false;
    }
    function reviewQ(q,btn){
        showReviewBox(q, "Current answer: "+(getSelected(q)||"Not Attempted"), false);
        setQnoColor(q,"yellow");
        reviewOnlyQs[q] = true;
    }
    function clearQ(q,btn){
        document.querySelectorAll(`input[name="q${q}"]`).forEach(r=>{r.checked=false;r.disabled=false;});
        showReviewBox(q, "Selection cleared. You can now reattempt.", false);
        setQnoColor(q,null);
        reviewOnlyQs[q] = false;
    }
    function getSelected(q){
        let sel=document.querySelector(`input[name="q${q}"]:checked`);
        return sel?sel.value:null;
    }
    function showReviewBox(q, msg, locked){
        let box=document.getElementById('reviewBox'+q);
        box.style.display='';
        box.innerHTML=msg;
        if(locked) box.style.background='#e0ffe0';
        else box.style.background='#eef7ff';
    }
    function scorePart(cfg){
        let correct=0,wrong=0,unattempted=0,score=0;
        for(let q=cfg.start;q<=cfg.end;q++){
            if(reviewOnlyQs[q]) continue; // SKIP review only
            const sel=document.querySelector(`input[name="q${q}"]:checked`);
            if(!sel){unattempted++;continue;}
            if(sel.value===answerKey[q]){correct++;score+=cfg.marks;}else{wrong++;score-=cfg.marks*NEG_FRAC;}
        }
        return{correct,wrong,unattempted,score};
    }
    document.getElementById('submitBtn').onclick=()=>{
        var userEmail = window.quizUserEmail || "unknown";
        var userName = window.quizUserName || "unknown";
        const rA=scorePart(PART_A),rB=scorePart(PART_B),rC=scorePart(PART_C);
        const total=rA.score+rB.score+rC.score;
        const maxTotal=(PART_A.maxAttempt*PART_A.marks)+(PART_B.maxAttempt*PART_B.marks)+(PART_C.maxAttempt*PART_C.marks);
        const percent=(total/maxTotal)*100;
        const grade=percent>=80?'Distinction':percent>=60?'First Class':percent>=40?'Second Class':'Fail';
        const pane=document.getElementById('resultPane');
        pane.style.display='block';
        pane.innerHTML=`<b>Name:</b> ${userName}<br><b>Email:</b> ${userEmail}<br>
<b>Part A</b>: ${rA.correct}C, ${rA.wrong}W, ${PART_A.end-PART_A.start+1-rA.correct-rA.wrong}U → ${rA.score}<br>
<b>Part B</b>: ${rB.correct}C, ${rB.wrong}W, ${PART_B.end-PART_B.start+1-rB.correct-rB.wrong}U → ${rB.score}<br>
<b>Part C</b>: ${rC.correct}C, ${rC.wrong}W, ${PART_C.end-PART_C.start+1-rC.correct-rC.wrong}U → ${rC.score}<br>
<hr><b>Total</b>: ${total.toFixed(2)} / ${maxTotal} (${percent.toFixed(2)}%) — ${grade}`;
        const sheet=document.getElementById('responseSheet');sheet.style.display='block';
        sheet.innerHTML='<h3>Response Sheet</h3>';
        let responseText = `Quiz Response\nName: ${userName}\nEmail: ${userEmail}\nScore: ${total.toFixed(2)} / ${maxTotal}\nGrade: ${grade}\n\nAnswers:\n`;
        for(let q=1;q<=120;q++){
            const sel=document.querySelector(`input[name="q${q}"]:checked`);
            const correct=answerKey[q];
            let line=`Q${q}: `;
            ['A','B','C','D'].forEach(opt=>{
                if(opt===correct) line+=opt+"(key) ";
                else line+=opt+" ";
            });
            line += "Your: " + (sel?sel.value:"-");
            responseText += line + "\n";
            let htmlLine = `<div class="qline"><b>Q${q}:</b> `;
            ['A','B','C','D'].forEach(opt=>{
                let cls='opt';
                if(opt===correct)cls+=' correct';
                if(sel&&opt===sel.value&&opt!==correct)cls+=' wrong';
                htmlLine+=`<span class="${cls}">${opt}</span>`;
            });
            htmlLine+='</div>';
            sheet.innerHTML+=htmlLine;
        }
        let mailto = "mailto:YOUR_EMAIL@gmail.com?subject=" +
            encodeURIComponent("Quiz Response from " + userName) +
            "&body=" + encodeURIComponent(responseText);
        document.getElementById('sendMailBtn').href = mailto;
        document.getElementById('sendMailArea').style.display = 'block';
        document.querySelectorAll('input,button').forEach(el=>{if(el.id!=='printBtn'&&el.id!=='pdfBtn'&&el.id!=='sendMailBtn')el.disabled=true;});
    };
    document.getElementById('printBtn').onclick=()=>window.print();
    document.getElementById('pdfBtn').onclick=()=>{
        const { jsPDF } = window.jspdf;
        const doc = new jsPDF();
        let y=10;
        doc.setFontSize(12);
        doc.text("CSIR NET Response Sheet",10,y);y+=8;
        const res=document.getElementById('resultPane').innerText.split('\n');
        res.forEach(r=>{doc.text(r,10,y);y+=6;});
        y+=6;doc.text("Response Sheet:",10,y);y+=8;
        const lines=document.querySelectorAll('#responseSheet .qline');
        lines.forEach(line=>{doc.text(line.innerText,10,y);y+=6;if(y>280){doc.addPage();y=10;}});
        doc.save('response_sheet.pdf');
    };
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
</body>
</html>
