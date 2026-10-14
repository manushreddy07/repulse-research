[Research Pulse.new.html](https://github.com/user-attachments/files/33431877/Research.Pulse.new.html)
# repulse-research<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Research Pulse</title>
<style>
:root{--bg:#F5EFE6;--card:#FFFAF2;--ink:#3B2A1E;--mute:#7A6655;--line:#E3D6C3;--brown:#4A3425;--or:#D9772B;--orsoft:#F8E3CF;--ok:#4F7A3A;--warn:#B8741A;--bad:#A8432B;--onor:#fff;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#1F1610;--card:#2B2018;--ink:#F3E8D8;--mute:#BBA78F;--line:#46362A;--brown:#E9D5B8;--or:#E8893A;--orsoft:#47301D;--ok:#8DBB72;--warn:#E0A04A;--bad:#E27B63}}
:root[data-theme="dark"]{--bg:#1F1610;--card:#2B2018;--ink:#F3E8D8;--mute:#BBA78F;--line:#46362A;--brown:#E9D5B8;--or:#E8893A;--orsoft:#47301D;--ok:#8DBB72;--warn:#E0A04A;--bad:#E27B63}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 Inter,system-ui,-apple-system,"Segoe UI",sans-serif}
a{color:var(--or)}:focus-visible{outline:3px solid var(--or);outline-offset:2px}
.wrap{max-width:1040px;margin:0 auto;padding:0 20px}
nav{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);border-bottom:1px solid var(--line);z-index:5}
nav .wrap{display:flex;align-items:center;gap:14px;flex-wrap:wrap;padding-top:10px;padding-bottom:10px}
.logo{font-weight:800;color:var(--brown);font-size:20px;margin-right:auto;background:none;border:0;cursor:pointer}.logo b{color:var(--or)}
nav a.l{color:var(--ink);text-decoration:none;font-size:15px;padding:6px 4px}nav a.l:hover{color:var(--or)}
.btn{background:var(--or);color:var(--onor);border:0;border-radius:10px;padding:11px 18px;font:600 15px inherit;font-family:inherit;cursor:pointer;text-decoration:none;display:inline-block}
.btn:hover{filter:brightness(.93)}.btn.sec{background:transparent;color:var(--brown);border:1.5px solid var(--brown)}.btn[disabled]{opacity:.5;cursor:not-allowed}
.hero{padding:56px 0 36px;display:grid;grid-template-columns:1.1fr .9fr;gap:32px;align-items:center}
h1{font-size:clamp(30px,5vw,46px);line-height:1.15;color:var(--brown);margin:0 0 14px}h2{color:var(--brown);margin:0 0 12px}
.tag{color:var(--or);font-weight:700;letter-spacing:.04em;text-transform:uppercase;font-size:13px}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:20px;box-shadow:0 2px 10px rgba(74,52,37,.08)}
.grid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px}
.card h3{margin:0 0 6px;color:var(--brown)}.card p{color:var(--mute);margin:0 0 14px}
section.s{padding:28px 0}.steps{counter-reset:s}.steps .card{position:relative;padding-top:44px}
.steps .card:before{counter-increment:s;content:counter(s);position:absolute;top:12px;left:18px;background:var(--or);color:#fff;width:26px;height:26px;border-radius:50%;text-align:center;font-weight:700;line-height:26px}
mark{background:var(--orsoft);color:var(--ink);border-bottom:2px solid var(--or);border-radius:3px;padding:0 1px}
.view{display:none}.view.on{display:block}
#drop{border:2px dashed var(--or);border-radius:16px;padding:36px 16px;text-align:center;background:var(--orsoft);cursor:pointer}
#drop.over{background:var(--card)}
label{font-weight:600;display:block;margin:14px 0 4px}select,input[type=text]{width:100%;padding:10px;border-radius:10px;border:1px solid var(--line);background:var(--card);color:var(--ink);font:inherit}
.bar{height:10px;background:var(--line);border-radius:8px;overflow:hidden}.bar i{display:block;height:100%;background:var(--or);width:0;transition:width .3s}
.err{background:#F9DDD5;color:#7A2A17;border:1px solid var(--bad);border-radius:10px;padding:12px;margin-top:12px}
.note{background:var(--orsoft);border-radius:10px;padding:12px;margin:10px 0;font-size:14px}
.pill{display:inline-block;padding:2px 10px;border-radius:99px;font-size:12px;font-weight:700;color:#fff}
.found{background:var(--ok)}.partial{background:var(--warn)}.missing{background:var(--bad)}.info{background:var(--mute)}
details{border:1px solid var(--line);border-radius:12px;background:var(--card);margin:8px 0;padding:10px 14px}summary{cursor:pointer;font-weight:600;color:var(--brown)}
.kv{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px}.kv div{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:12px}.kv b{font-size:22px;color:var(--or);display:block}
.doc{max-height:340px;overflow:auto;white-space:pre-wrap;background:var(--card);border:1px solid var(--line);border-radius:12px;padding:14px;font-size:14px}
.pv{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:18px;font-size:14px}
footer{border-top:1px solid var(--line);margin-top:30px;padding:24px 0;color:var(--mute);font-size:14px}footer a{margin-right:14px}
.row{display:flex;gap:10px;flex-wrap:wrap;margin:12px 0}
@media(max-width:760px){.hero{grid-template-columns:1fr;padding-top:30px}}
@media print{nav,footer,.row,#v-home,#v-upload{display:none!important}.view{display:block!important}#v-results{display:block!important}details{break-inside:avoid}details[open]{display:block}}
</style></head><body>
<nav aria-label="Main"><div class="wrap">
<button class="logo" onclick="go('home')" aria-label="Research Pulse home">Research <b>Pulse</b></button>
<a class="l" href="#" onclick="go('home');return false">Home</a><a class="l" href="#features" onclick="go('home')">Features</a><a class="l" href="#how" onclick="go('home')">How It Works</a><a class="l" href="#about" onclick="go('home')">About</a>
<a class="l" href="#" onclick="alert('Sign-in is not part of this prototype. Your documents are analysed in your browser and no account is needed.');return false">Sign In</a>
<button class="btn" onclick="start('complete')">Start Analysing</button></div></nav>

<main class="wrap">
<div id="v-home" class="view on">
<div class="hero"><div><div class="tag">Discover Originality. Strengthen Research.</div>
<h1>Your Research Deserves More Than a Similarity Score.</h1>
<p style="color:var(--mute)">Analyse originality, discover relevant research, identify gaps, and turn your ideas into stronger academic work—all in one place.</p>
<div class="row"><button class="btn" onclick="start('complete')">Analyse My Research</button><a class="btn sec" href="#features">Explore Features</a></div></div>
<div class="pv" aria-label="Example preview (illustrative layout only)"><b>Preview (illustrative layout)</b>
<p>…the method was <mark>applied to the same sample as in earlier work</mark> without further justification…</p>
<p style="margin:0"><span class="pill partial">Review</span> Repeated passage found inside your document<br><span class="pill found">Found</span> Research question stated<br><span class="pill missing">Missing</span> Limitations section</p></div></div>

<section class="s" id="features"><h2>Features</h2><div class="grid3">
<div class="card"><h3>Originality Check</h3><p>Identify potentially matching passages in academic publications and accessible online sources.</p><button class="btn" onclick="start('originality')">Check Originality</button></div>
<div class="card"><h3>Research Analysis</h3><p>Evaluate research structure, methodology, evidence, clarity, citations, and conclusions.</p><button class="btn" onclick="start('analysis')">Analyse Research</button></div>
<div class="card"><h3>Improve My Research</h3><p>Discover potential research gaps, explore new directions, and receive actionable suggestions supported by relevant publications.</p><button class="btn" onclick="start('improvement')">Improve My Research</button></div></div>
<div class="note"><b>Prototype transparency:</b> this build runs entirely in your browser. Originality checking covers repeated text inside your document and citation cues. Matching against external publications and AI-written feedback need a server and API keys, so they are marked as unavailable rather than faked.</div></section>

<section class="s" id="how"><h2>How It Works</h2><div class="grid3 steps">
<div class="card">Upload your research document.</div><div class="card">Choose an analysis type.</div><div class="card">Review findings, sources, and recommendations.</div></div></section>

<section class="s"><div class="grid3">
<div class="card"><h3>Supported formats</h3><p>PDF and DOCX (text extracted). JPG, JPEG and PNG are accepted for selection, but OCR is not available in this build, so they cannot be analysed.</p></div>
<div class="card"><h3>Analysis capabilities</h3><p>Section detection, ten quality dimensions, citation cues, internal repeated-text detection, gap statements, and copyable recommendations.</p></div>
<div class="card" id="about"><h3>Privacy &amp; security</h3><p>Your file is read locally in your browser. It is not uploaded, stored, logged or used for training. Closing or starting a new analysis discards it.</p></div></div></section>

<section class="s"><h2>FAQ</h2>
<details><summary>Does a similarity figure mean plagiarism?</summary><p>No. Findings here are review pointers, never a plagiarism verdict.</p></details>
<details><summary>Does “no match” mean my work is original?</summary><p>No. It only means nothing was flagged in what was checked. Here that is limited to your own document.</p></details>
<details><summary>Why is source matching unavailable?</summary><p>It needs scholarly search APIs called from a server. None are connected, so no sources are shown and none are invented.</p></details></section>
</div>

<div id="v-upload" class="view"><section class="s"><h2>Upload your document</h2>
<div id="drop" tabindex="0" role="button" aria-label="Choose or drop a file"><b>Drag &amp; drop a file here</b><br>or click to browse<br><small>PDF, DOCX, JPG, JPEG, PNG · max 10 MB</small></div>
<input id="file" type="file" accept=".pdf,.docx,.jpg,.jpeg,.png" hidden>
<div id="sel" style="display:none" class="card" aria-live="polite"><b id="fn"></b> <span id="fs" style="color:var(--mute)"></span>
<div class="bar" style="margin:10px 0"><i id="pb"></i></div><div id="st" style="font-size:14px;color:var(--mute)"></div>
<div class="row"><button class="btn sec" onclick="document.getElementById('file').click()">Replace</button><button class="btn sec" onclick="removeFile()">Remove</button></div></div>
<div id="uerr" class="err" role="alert" style="display:none"></div>
<label for="mode">Analysis mode</label><select id="mode"><option value="originality">Originality Check</option><option value="analysis">Research Analysis</option><option value="improvement">Research Improvement</option><option value="complete">Complete Research Review</option></select>
<label for="field">Research field (optional)</label><input id="field" type="text" placeholder="e.g. Public health, Computer science">
<label for="dtype">Document type</label><select id="dtype"><option>Journal article</option><option>Thesis / dissertation</option><option>Student essay</option><option>Proposal</option><option>Other</option></select>
<div class="row"><button class="btn" id="go" disabled onclick="runAnalysis()">Analyse document</button></div></section></div>

<div id="v-results" class="view"><section class="s"><h2>Results dashboard</h2>
<div class="row"><button class="btn sec" onclick="toggleAll(true)">Expand all</button><button class="btn sec" onclick="toggleAll(false)">Collapse all</button><button class="btn sec" onclick="copyRecs()">Copy recommendations</button><button class="btn sec" onclick="window.print()">Export report (print / save as PDF)</button><button class="btn" onclick="start(null)">Start another analysis</button></div>
<div id="out"></div></section></div>
</main>
<footer><div class="wrap"><a href="#" onclick="go('home');return false">About</a><a href="#" onclick="alert('Contact is not configured in this prototype.');return false">Contact</a><a href="#" onclick="alert('Privacy: files are processed in your browser only and are not stored or transmitted.');return false">Privacy Policy</a><a href="#" onclick="alert('Terms: findings are guidance for review, not verdicts.');return false">Terms</a><br>© Research Pulse — Discover Originality. Strengthen Research.</div></footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mammoth/1.6.0/mammoth.browser.min.js"></script>
<script>
var $=function(i){return document.getElementById(i)};
var cur=null,text='',recs=[];
function esc(s){return String(s).replace(/[&<>"]/g,function(c){return{'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]})}
function go(v){['home','upload','results'].forEach(function(n){$('v-'+n).classList.toggle('on',n===v)});window.scrollTo(0,0)}
function start(m){if(m)$('mode').value=m;if(m===null)removeFile();go('upload')}
function showErr(m){var e=$('uerr');e.textContent=m;e.style.display=m?'block':'none'}
function removeFile(){cur=null;text='';$('file').value='';$('sel').style.display='none';$('go').disabled=true;showErr('');$('pb').style.width='0'}
var drop=$('drop');
drop.onclick=function(){$('file').click()};
drop.onkeydown=function(e){if(e.key==='Enter'||e.key===' '){e.preventDefault();$('file').click()}};
['dragover','dragenter'].forEach(function(ev){drop.addEventListener(ev,function(e){e.preventDefault();drop.classList.add('over')})});
['dragleave','drop'].forEach(function(ev){drop.addEventListener(ev,function(e){e.preventDefault();drop.classList.remove('over')})});
drop.addEventListener('drop',function(e){if(e.dataTransfer.files[0])pick(e.dataTransfer.files[0])});
$('file').onchange=function(e){if(e.target.files[0])pick(e.target.files[0])};
function size(b){return b>1048576?(b/1048576).toFixed(1)+' MB':Math.max(1,Math.round(b/1024))+' KB'}
function pick(f){
  showErr('');text='';$('go').disabled=true;
  var ext=(f.name.split('.').pop()||'').toLowerCase();
  if(['pdf','docx','jpg','jpeg','png'].indexOf(ext)<0){removeFile();return showErr('Unsupported file type ".'+ext+'". Please use PDF, DOCX, JPG, JPEG or PNG.')}
  if(f.size>10485760){removeFile();return showErr('This file is '+size(f.size)+'. The limit is 10 MB.')}
  if(f.size===0){removeFile();return showErr('This file is empty.')}
  cur=f;$('fn').textContent=f.name;$('fs').textContent='('+size(f.size)+')';$('sel').style.display='block';$('pb').style.width='0';
  if(ext==='jpg'||ext==='jpeg'||ext==='png'){$('st').textContent='Image selected.';return showErr('Text could not be extracted: OCR is not available in this build, so images cannot be analysed. Please upload a digital PDF or a DOCX file.')}
  var r=new FileReader();$('st').textContent='Reading file…';
  r.onprogress=function(e){if(e.lengthComputable)$('pb').style.width=Math.round(e.loaded/e.total*60)+'%'};
  r.onerror=function(){showErr('The file could not be read. Please try again.')};
  r.onload=function(){extract(ext,r.result).then(function(t){
    t=t.replace(/\u00a0/g,' ').replace(/[ \t]+\n/g,'\n').trim();
    if(t.split(/\s+/).filter(Boolean).length<30){$('pb').style.width='100%';$('st').textContent='No usable text.';return showErr('Almost no text could be extracted. This may be a scanned document, and OCR is not available in this build.')}
    text=t;$('pb').style.width='100%';$('st').textContent='Text extracted ('+t.split(/\s+/).length.toLocaleString()+' words). Ready to analyse.';$('go').disabled=false;
  }).catch(function(e){$('st').textContent='Extraction failed.';showErr('Could not extract text: '+(e&&e.message?e.message:'the file may be corrupt, encrypted or unsupported.'))})};
  r.readAsArrayBuffer(f);
}
function extract(ext,buf){
  if(ext==='docx'){
    if(!window.mammoth)return Promise.reject(new Error('The DOCX reader failed to load. Check your connection and reload.'));
    $('st').textContent='Extracting Word text…';
    return mammoth.convertToHtml({arrayBuffer:buf}).then(function(res){
      var d=new DOMParser().parseFromString(res.value,'text/html'),o=[];
      d.body.querySelectorAll('h1,h2,h3,h4,h5,h6,p,li').forEach(function(n){var t=n.textContent.trim();if(t)o.push(/^H/.test(n.tagName)?'\n'+t+'\n':t)});
      return o.join('\n')});
  }
  if(!window.pdfjsLib)return Promise.reject(new Error('The PDF reader failed to load. Check your connection and reload.'));
  pdfjsLib.GlobalWorkerOptions.workerSrc='https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js';
  $('st').textContent='Extracting PDF text…';
  return pdfjsLib.getDocument({data:new Uint8Array(buf)}).promise.then(function(pdf){
    var out=[],p=Promise.resolve();
    for(let i=1;i<=pdf.numPages;i++){p=p.then(function(){return pdf.getPage(i)}).then(function(pg){return pg.getTextContent()}).then(function(tc){
      var line='',y=null,L=[];tc.items.forEach(function(it){var yy=it.transform[5];if(y!==null&&Math.abs(yy-y)>3){L.push(line);line=''}line+=it.str+(it.hasEOL?'\n':' ');y=yy});L.push(line);out.push(L.join('\n'));
      $('pb').style.width=(60+Math.round(i/pdf.numPages*40))+'%'})}
    return p.then(function(){return out.join('\n\n')})});
}
function M(re,t){var m=re.exec(t);if(!m)return null;var s=Math.max(0,m.index-60),e=Math.min(t.length,m.index+m[0].length+120);return '…'+t.slice(s,e).replace(/\s+/g,' ').trim()+'…'}
function cnt(re,t){var m=t.match(re);return m?m.length:0}
function hasHead(re,t){return new RegExp('^\\s*(\\d+[.)]?\\s*)?('+re+')\\s*:?\\s*$','im').test(t)}
function dims(t){
  var cites=cnt(/\([A-Z][A-Za-z\-]+(?: et al\.?)?(?: and [A-Z][A-Za-z\-]+)?,? (?:19|20)\d\d[a-z]?\)|\[\d+(?:[,\u2013\-]\s?\d+)*\]/g,t);
  var words=t.split(/\s+/).length,sents=Math.max(1,cnt(/[.!?](\s|$)/g,t));
  var D=[];function add(n,st,pas,iss,why,rec,sub){D.push({n:n,st:st,pas:pas,iss:iss,why:why,rec:rec,sub:sub})}
  var q=M(/research question|we (ask|investigate|examine|explore)|this (study|paper|research|thesis) (aims|investigates|examines|explores|seeks)|hypothes[ie]s/i,t);
  add('Clarity of the research question',q?'found':'missing',q,q?'A research-question or hypothesis cue was detected.':'No explicit research question or hypothesis wording was detected.','A clear question anchors method, evidence and conclusions.','State the question in one sentence early in the introduction, e.g. “This study asks whether…”.');
  var o=M(/objectives?\b|\baims? (of|is|are)|purpose of (this|the)/i,t);
  add('Research objectives',o?'found':'missing',o,o?'Objective wording was detected.':'No objectives or aims wording was detected.','Objectives let readers judge whether the work delivers what it promises.','List 2–4 specific, measurable objectives.');
  var lh=hasHead('literature review|related work|background|prior work',t);
  add('Literature review coverage',lh&&cites>=10?'found':(lh||cites>=5?'partial':'missing'),M(/literature review|related work|previous (studies|research)|prior work/i,t),cites+' citation cues detected'+(lh?', with a literature/background heading.':', and no literature/background heading found.'),'Coverage shows how your work builds on and differs from existing studies.','Group sources by theme and end each theme with what remains unresolved.');
  var g=M(/research gap|little is known|remains (unclear|unexplored|unknown)|few studies|has (rarely|not) been|limited research|understudied/i,t);
  add('Research gap identification',g?'found':'missing',g,g?'A gap statement cue was detected.':'No explicit gap statement was detected.','A gap explains why the study is needed.','Add a sentence naming what prior work leaves unanswered and why it matters.');
  var mh=hasHead('methods?|methodology|materials and methods|research design|experimental setup',t),mc=M(/participants|dataset|sample size|procedure|protocol|survey|interview|experiment|inclusion criteria|data collection/i,t);
  add('Methodology and reproducibility',mh&&mc?'found':(mh||mc?'partial':'missing'),mc,(mh?'Method heading found. ':'No method heading found. ')+(mc?'Method terms detected.':'No method terms detected.'),'Others must be able to repeat or assess your procedure.','Describe data, participants or materials, procedure and analysis steps with enough detail to reproduce them.');
  var nums=cnt(/\b\d+(\.\d+)?\s?%|\bp\s?[<=>]\s?0?\.\d+|\bn\s?=\s?\d+|\b(table|figure|fig\.)\s?\d+/gi,t);
  add('Quality and relevance of evidence',nums>=8?'found':nums>=3?'partial':'missing',M(/\b\d+(\.\d+)?\s?%|\bp\s?[<=>]\s?0?\.\d+|\bn\s?=\s?\d+/i,t),nums+' quantitative or table/figure cues detected. This is a surface cue; it cannot judge evidence quality or relevance.','Claims should rest on identifiable data or sources.','Link each major claim to a figure, table, statistic or citation. Note that qualitative fields may use other forms of evidence.',1);
  var con=cnt(/\b(therefore|however|because|thus|consequently|in contrast|as a result|hence|moreover)\b/gi,t),rate=con/sents;
  add('Logical consistency of arguments',rate>.12?'found':rate>.05?'partial':'missing',null,con+' connective words across '+sents+' sentences. This only measures signposting, not whether arguments are sound.','Explicit connectives make reasoning easier to follow and check.','Add transitions that state how each paragraph supports, qualifies or contrasts with the previous one.',1);
  var rh=hasHead('references?|bibliography|works cited',t);
  add('Citation and reference quality',rh&&cites>=8?'found':(rh||cites>=3?'partial':'missing'),null,cites+' in-text citation cues; reference list heading '+(rh?'found.':'not found.')+' Individual references were not verified.','Citations let readers verify claims and credit prior work.','Ensure every in-text citation appears in the reference list, and use one consistent style.');
  var l=M(/limitations?\b|\bcaveats?\b|constraints? of (this|the) (study|work)/i,t);
  add('Limitations',l?'found':'missing',l,l?'Limitation wording was detected.':'No limitations discussion was detected.','Honest limitations show the scope within which findings hold.','Add a short section on sample, method and generalisability limits.');
  var ch=hasHead('conclusions?|discussion and conclusions?|concluding remarks',t),fu=M(/future (research|work|studies|directions)|further research/i,t);
  add('Conclusions and future directions',ch&&fu?'found':(ch||fu?'partial':'missing'),fu,(ch?'Conclusion heading found. ':'No conclusion heading found. ')+(fu?'Future-work wording detected.':'No future-work wording detected.'),'A conclusion ties results back to the question and shows next steps.','Restate the answer to your question, then give 2–3 concrete future directions.');
  return {D:D,cites:cites,words:words,sents:sents,rh:rh};
}
function internal(t){
  var tk=t.split(/\s+/),n=tk.length>40000?40000:tk.length,key=tk.slice(0,n).map(function(w){return w.toLowerCase().replace(/[^a-z0-9]/g,'')}),seen={},fl=new Array(n).fill(false),W=8,hits=0;
  for(var i=0;i+W<=n;i++){var k=key.slice(i,i+W).join(' ');if(k.replace(/ /g,'').length<30)continue;if(seen[k]!==undefined){for(var j=0;j<W;j++){fl[i+j]=true;fl[seen[k]+j]=true}hits++}else seen[k]=i}
  var html=[],on=false;for(var x=0;x<n;x++){if(fl[x]&&!on){html.push('<mark>');on=true}if(!fl[x]&&on){html.push('</mark>');on=false}html.push(esc(tk[x])+' ')}
  if(on)html.push('</mark>');
  var flagged=fl.filter(Boolean).length;
  return {html:html.join(''),hits:hits,pct:n?Math.round(flagged/n*1000)/10:0,trunc:tk.length>n};
}
function citeCues(t){
  var quotes=[],re=/["\u201c]([^"\u201d]{50,400})["\u201d]/g,m;
  while((m=re.exec(t))&&quotes.length<8){var after=t.slice(m.index+m[0].length,m.index+m[0].length+60);var cited=/\(|\[\d/.test(after);quotes.push({q:m[1],cited:cited})}
  var claims=[],ss=t.split(/(?<=[.!?])\s+/);
  ss.forEach(function(s){if(claims.length<8&&/(studies|research|evidence|experts|scholars) (show|shows|suggest|suggests|indicate|indicates|have found)|according to/i.test(s)&&!/\([A-Z][^)]*\d{4}|\[\d+/.test(s))claims.push(s.trim().slice(0,260))});
  return {quotes:quotes,claims:claims};
}
function runAnalysis(){
  if(!text)return showErr('No extracted text yet. Please upload a PDF or DOCX file first.');
  try{
    var mode=$('mode').value,A=dims(text),I=internal(text),C=citeCues(text),field=$('field').value.trim(),dt=$('dtype').value;
    var show=function(k){return mode==='complete'||mode===k||(k==='analysis'&&false)};
    var h='<div class="kv"><div><b>'+A.words.toLocaleString()+'</b>words</div><div><b>'+A.sents+'</b>sentences</div><div><b>'+A.cites+'</b>citation cues</div><div><b>'+(cur?esc(cur.name.split('.').pop().toUpperCase()):'')+'</b>'+esc(dt)+(field?' · '+esc(field):'')+'</div></div>';
    h+='<details open><summary>Document overview</summary><p><b>'+esc(cur.name)+'</b> ('+size(cur.size)+'). Mode: '+esc($('mode').selectedOptions[0].text)+'. Criteria are general and may not fit every discipline'+(field?' (you selected “'+esc(field)+'”)':'')+'; treat them as prompts, not rules.</p></details>';
    if(show('originality')){
      h+='<details open><summary>Text similarity findings</summary><p><span class="pill info">Internal only</span> '+I.hits+' repeated 8-word sequences inside this document ('+I.pct+'% of words highlighted). This is not a plagiarism measure.</p>'+(I.trunc?'<p>Only the first 40,000 words were checked.</p>':'')+
      '<p><span class="pill info">Not performed</span> Matching against external publications: no scholarly search service is connected in this build, so no sources are listed and none are invented. No flagged text does not mean the work is original.</p></details>';
      h+='<details><summary>Matching source list</summary><p>Source matching could not be completed. Connect a server-side scholarly search API (for example OpenAlex or Crossref) to enable it.</p></details>';
      h+='<details><summary>Highlighted passages</summary><div class="doc">'+(I.hits?I.html:'<i>No repeated sequences detected.</i>')+'</div></details>';
      h+='<details><summary>Passages that may need citation review ('+(C.quotes.length+C.claims.length)+')</summary>'+
        (C.quotes.map(function(q){return '<p><span class="pill '+(q.cited?'found':'partial')+'">'+(q.cited?'Quote, citation nearby':'Quote, no nearby citation')+'</span><br>“'+esc(q.q.slice(0,240))+'”</p>'}).join('')||'')+
        (C.claims.map(function(c){return '<p><span class="pill partial">Claim without citation cue</span><br>'+esc(c)+'</p>'}).join('')||'')+
        ((C.quotes.length+C.claims.length)?'':'<p>No such passages detected by the pattern checks.</p>')+'<p style="color:var(--mute);font-size:14px">These are pattern-based pointers for your own review.</p></details>';
    }
    recs=[];
    if(show('analysis')||show('improvement')){
      var sc=A.D.reduce(function(a,d){return a+(d.st==='found'?2:d.st==='partial'?1:0)},0);
      if(show('analysis')){h+='<details open><summary>Research quality assessment — structure indicator '+sc+'/20</summary><div class="note">Reported separately from originality. “Objective” items are text cues; “Suggestion” items are judgement calls.</div>';
      A.D.forEach(function(d){h+='<details><summary>'+esc(d.n)+' <span class="pill '+d.st+'">'+d.st+'</span></summary><p><b>Passage:</b> '+(d.pas?esc(d.pas):'Not located')+'</p><p><b>Issue:</b> '+esc(d.iss)+' <span class="pill info">Objective observation</span></p><p><b>Why it matters:</b> '+esc(d.why)+'</p><p><b>Recommendation:</b> '+esc(d.rec)+' <span class="pill info">Suggestion</span></p><p style="color:var(--mute)"><b>References:</b> none supplied — no external sources were consulted.</p></details>'});h+='</details>'}
    }
    A.D.forEach(function(d){if(d.st!=='found')recs.push(d.n+': '+d.rec+' (Why: '+d.why+')')});
    if(A.cites>0&&!A.rh)recs.push('Add a reference list that matches your in-text citations.');
    if(!recs.length)recs.push('No structural gaps detected by the checks. Have a peer review content quality.');
    if(show('improvement')){
      var gp=M(/research gap|little is known|remains (unclear|unexplored|unknown)|few studies|has (rarely|not) been|limited research|understudied/i,text);
      h+='<details open><summary>Potential research gaps</summary><p>'+(gp?'Your text states: '+esc(gp)+'<br><span class="pill info">From your document</span>':'No explicit gap statement found in your text. Consider comparing your question against recent reviews to identify one. <span class="pill info">Suggestion</span>')+'</p></details>';
      h+='<details open><summary>Recommended improvements</summary><ol>'+recs.map(function(r){return '<li>'+esc(r)+'</li>'}).join('')+'</ol><p style="color:var(--mute);font-size:14px">All items are rule-based suggestions requiring your judgement, not verified findings.</p></details>';
      h+='<details><summary>Suggested further reading</summary><p>Not available: recommending publications requires a verified scholarly search service. To avoid fabricated citations, none are listed.</p></details>';
    }
    h+='<details open><summary>Analysis limitations</summary><ul><li>Runs in your browser with rule-based checks; no language model was used.</li><li>No external source matching, so no similarity verdict is possible.</li><li>OCR is unavailable; scanned or image-only files cannot be analysed.</li><li>PDF extraction can lose headings, tables and reading order.</li><li>Quality criteria are general and may not suit every discipline.</li></ul></details>';
    $('out').innerHTML=h;go('results');
  }catch(e){showErr('Analysis could not be completed: '+e.message)}
}
function toggleAll(o){document.querySelectorAll('#out details').forEach(function(d){d.open=o})}
function copyRecs(){
  var t=recs.length?recs.map(function(r,i){return (i+1)+'. '+r}).join('\n'):'No recommendations in this mode.';
  var ok=function(){alert('Recommendations copied.')},fail=function(){var ta=document.createElement('textarea');ta.value=t;document.body.appendChild(ta);ta.select();try{document.execCommand('copy');ok()}catch(e){alert('Copy failed. Please select the text manually.')}document.body.removeChild(ta)};
  if(navigator.clipboard&&navigator.clipboard.writeText)navigator.clipboard.writeText(t).then(ok,fail);else fail();
}
</script></body></html>
