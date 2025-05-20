<h2 id="news">News</h2>

<style>
  #scrollableDiv {
    min-height: 100px;
    height: 100px;
    overflow-y: hidden;
    opacity: 1;
    transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
  }
</style>

<ul id="scrollableDiv" onmouseover="showScrollbar()" onmouseout="hideScrollbar()">
  <li><strong>[Apr. 2025]</strong> One paper (ViTaMIN) gets accepted to ICRA’25 CRM Workshop 🎉</li>
  <li><strong>[Apr. 2025]</strong> One paper is under review at CoRL’25 </li>
  <li><strong>[Apr. 2025]</strong> One paper (CleanMAP) gets accepted to CVPR’25 WDFMAD Workshop 🎉</li>
  <li><strong>[Feb. 2025]</strong> One paper is under review at ICCV’25 </li>
  <li><strong>[Dec. 2024]</strong> Successfully defended my Masters thesis at Tsinghua University</li>
  <li><strong>[Dec. 2023]</strong> Invited Talk by <a href="https://jina.ai">SA Zhang, Evangelist from Jina AI</a> on Prompt Engineering with PromptPerfect </li>
  <li><strong>[Dec. 2023]</strong> Invited Talk by <a href="https://tsutikgiau.github.io/">Dr. Deyao Zhu, Author of MiniGPT-4</a> on Exploring MiniGPT-4, Its Motivation and Techniques </li>
  <li><strong>[Nov. 2023]</strong> Invited Talk by <a href="https://people.csail.mit.edu/lumi/">Lu Mi (MIT)</a> and <a href="https://tsailaboratory.mit.edu/team/janna-hong/">Janna Hong (TSAIL Lab, MIT)</a> at the TAIS × i2 Event <em>“Bridge the Gap Between Biological and Artificial Neural Networks”</em>, co-hosted by University of Washington, Allen Institute, and Tsinghua University.</li>
  <li><strong>[Sep. 2023]</strong> Invited Talk by <a href="https://www.thesrii.org">Prof. Kris Singh</a> on Innovation and Entrepreneurship for Global Digital Economy </li>
  <li><strong>[Mar. 2023]</strong> Joined Future Robotics Club at Tsinghua University </li>
  <li><strong>[Jan. 2023]</strong> Appointed as a President at Tsinghua AI for Student (TAIS) Club </li>
  <li><strong>[May. 2022]</strong> Joined Vision-CAIR at KAUST as a visiting student</li>
  <li><strong>[Feb. 2022]</strong> Best Solution Award by AWS Disaster Response Hackathon</li>
  <li><strong>[Oct. 2021]</strong> Awarded Second Class Meritorious Scholarship (英才⼆等奖学 ⾦)</li>
  <li><strong>[Sep. 2020]</strong> Started my Master journey at Tsinghua University</li>
  <li><strong>[Aug 2020]</strong> Awarded Chinese Government Scholarship</li>
  <li><strong>[Jun. 2020]</strong> Successfully defended my Bachelor thesis</li>
</ul>

<p></p>
<script>
  function showScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = div.scrollHeight + 'px';
    div.style.opacity = 1;
  }
  function hideScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = '100px';
    div.style.opacity = 1;
  }
</script>