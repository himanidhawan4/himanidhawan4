<div align="center">

  <img src="./file.png" width="100%" alt="DevSecOps Banner"/>

  <h1>Hi, I'm Himani 👋</h1>

  <p><b>Python • DevOps • DevSecOps • Cloud</b></p>

  <p>
    Building secure and automated software delivery systems while learning
    DevOps, DevSecOps, cloud technologies and software engineering.
  </p>

  <p>
    <a href="https://github.com/himanidhawan4">
      <img src="https://img.shields.io/badge/GitHub-himanidhawan4-181717?style=for-the-badge&logo=github" alt="GitHub"/>
    </a>
  </p>

</div>

<hr/>

<h2>👩‍💻 About Me</h2>

<ul>
  <li>🎓 B.Tech Computer Science & Engineering student</li>
  <li>🐍 Focused on Python and backend automation</li>
  <li>⚙️ Interested in DevOps and DevSecOps</li>
  <li>☁️ Learning AWS, CI/CD and cloud infrastructure</li>
  <li>🔐 Building security into software delivery workflows</li>
  <li>📚 Currently strengthening DSA and core Computer Science concepts</li>
  <li>🚀 Learning through hands-on projects and practical experimentation</li>
</ul>

<hr/>

<h2>🚀 Currently Working On</h2>

<h3>🔐 Release Portal Security Gate</h3>

<p>
<b>Release Portal Security Gate</b> is a Python-based DevSecOps project that
analyses GitHub Pull Requests and produces a security verdict before code
moves further through the software delivery process.
</p>

<p>
The project follows a simple approach:
</p>

<div align="center">

<b>Detect → Score → Explain → Recommend → Decide</b>

</div>

<h3>🔄 Current Workflow</h3>

<pre>
GitHub Pull Request
        │
        ▼
   GitHub REST API
        │
        ▼
   PR Analysis
        │
   ┌────┼───────────────┐
   ▼    ▼               ▼
Secrets  Dependencies   IAM
Scan     Scan           Checks
   │      │               │
   ▼      ▼               ▼
detect-   OSV API      Terraform /
secrets                IAM Analysis
   │      │               │
   └──────┼───────────────┘
          ▼
      SonarQube
          │
          ▼
   Security Analysis
          │
          ▼
    Security Verdict
          │
     ┌────┴────┐
     ▼         ▼
    PASS      FAIL
     │         │
     ▼         ▼
  Continue   Block / Report
</pre>

<h3>✨ Key Features</h3>

<ul>
  <li>🔎 GitHub Pull Request analysis</li>
  <li>🛡️ Secret detection using <code>detect-secrets</code></li>
  <li>📦 Dependency vulnerability checking using <code>OSV</code></li>
  <li>🔍 SonarQube/SonarCloud code quality and security analysis</li>
  <li>🔐 IAM wildcard detection for Terraform and IAM configurations</li>
  <li>📊 Security scoring and verdict generation</li>
  <li>💡 Security issue explanations and recommendations</li>
  <li>🚦 Automated security decision making</li>
  <li>🧪 Automated testing using <code>pytest</code></li>
  <li>🌐 Flask-based web interface</li>
  <li>📄 JSON-based security results</li>
</ul>

<p>
🚧 <b>Currently in active development</b>
</p>

<hr/>

<h2>🛠️ Tech Stack</h2>

<table width="100%">
  <tr>
    <td width="50%" valign="top">

```
  <h3>🐍 Programming</h3>

  <p>
    <code>Python</code>
    <code>DSA</code>
    <code>OOP</code>
  </p>

  <h3>🌐 Backend & Web</h3>

  <p>
    <code>Flask</code>
    <code>HTML</code>
    <code>CSS</code>
    <code>REST APIs</code>
  </p>

  <h3>🗄️ Database</h3>

  <p>
    <code>SQLite</code>
  </p>

</td>

<td width="50%" valign="top">

  <h3>⚙️ DevOps</h3>

  <p>
    <code>Git</code>
    <code>GitHub</code>
    <code>GitHub Actions</code>
    <code>Jenkins</code>
    <code>Linux</code>
    <code>CI/CD</code>
  </p>

  <h3>🔐 DevSecOps</h3>

  <p>
    <code>SonarQube</code>
    <code>SonarCloud</code>
    <code>OSV</code>
    <code>detect-secrets</code>
    <code>Security Gates</code>
  </p>

  <h3>☁️ Cloud & Infrastructure</h3>

  <p>
    <code>AWS</code>
    <code>EC2</code>
    <code>Terraform</code>
    <code>Nginx</code>
    <code>Apache</code>
  </p>

</td>
```

  </tr>
</table>

<hr/>

<h2>📚 Currently Learning</h2>

<table width="100%">
  <tr>
    <td width="50%" valign="top">

```
  <h3>🎓 Computer Science</h3>

  <p>
    🧠 Data Structures & Algorithms<br>
    🖥️ Operating Systems<br>
    🌐 Computer Networks<br>
    🗄️ DBMS<br>
    📐 Software Engineering
  </p>

</td>

<td width="50%" valign="top">

  <h3>⚙️ Engineering</h3>

  <p>
    🐧 Linux<br>
    ☁️ AWS<br>
    🔄 CI/CD<br>
    🔐 DevSecOps<br>
    🐳 Docker<br>
    🏗️ Infrastructure as Code
  </p>

</td>
```

  </tr>
</table>

<hr/>

<h2>🚀 Projects</h2>

<table width="100%">
  <tr>

```
<td width="50%" valign="top">

  <h3>🔐 Release Portal Security Gate</h3>

  <p>
    <b>Python-based DevSecOps Security Gate</b>
  </p>

  <p>
    Analyses GitHub Pull Requests for secrets, dependency vulnerabilities,
    IAM issues and code-quality/security findings before producing a
    security verdict.
  </p>

  <p>
    <b>Stack</b>
  </p>

  <p>
    <code>Python</code>
    <code>Flask</code>
    <code>GitHub API</code>
    <code>SonarQube</code>
    <code>OSV</code>
    <code>detect-secrets</code>
    <code>pytest</code>
  </p>

  <p>🚧 <b>In Development</b></p>

</td>

<td width="50%" valign="top">

  <h3>⚙️ DevOps Automation</h3>

  <p>
    Hands-on experimentation with CI/CD pipelines, automation and
    cloud infrastructure.
  </p>

  <p>
    <b>Tools</b>
  </p>

  <p>
    <code>GitHub Actions</code>
    <code>Jenkins</code>
    <code>Linux</code>
    <code>AWS EC2</code>
    <code>Nginx</code>
    <code>Apache</code>
    <code>Terraform</code>
  </p>

  <p>🔄 <b>Learning & Building</b></p>

</td>
```

  </tr>
</table>

<hr/>

<h2>🎯 Goals</h2>

<ul>
  <li>🎓 Become placement-ready with strong DSA fundamentals</li>
  <li>🐍 Strengthen Python development skills</li>
  <li>⚙️ Build practical DevOps projects</li>
  <li>🔐 Develop strong DevSecOps fundamentals</li>
  <li>☁️ Gain hands-on experience with AWS and cloud infrastructure</li>
  <li>🔄 Understand production-oriented CI/CD pipelines</li>
  <li>🐳 Learn Docker and container security</li>
  <li>🌍 Contribute to open source</li>
  <li>🚀 Build real-world engineering projects</li>
</ul>

<hr/>

<h2>📈 My Development Journey</h2>

<table width="100%">
  <tr>
    <td align="center">

```
  <p>
    <b>Programming Fundamentals</b>
    <br>↓<br>
    <b>Python</b>
    <br>↓<br>
    <b>Data Structures & Algorithms</b>
    <br>↓<br>
    <b>Git & GitHub</b>
    <br>↓<br>
    <b>Linux & Networking</b>
    <br>↓<br>
    <b>CI/CD</b>
    <br>↓<br>
    <b>DevOps</b>
    <br>↓<br>
    <b>DevSecOps</b>
    <br>↓<br>
    <b>AWS & Cloud</b>
    <br>↓<br>
    <b>Secure Software Delivery</b>
  </p>

</td>
```

  </tr>
</table>

<hr/>

<h2>💡 My Approach</h2>

<div align="center">

<b>Learn</b>
 →  <b>Build</b>
 →  <b>Break</b>
 →  <b>Debug</b>
 →  <b>Understand</b>
 →  <b>Improve</b>
 →  <b>Repeat</b>

</div>

<br>

<p align="center">
  I believe the best way to learn engineering is by building real systems,
  understanding why they fail, and continuously improving them.
</p>

<hr/>

<h2>📊 GitHub Activity</h2>

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=himanidhawan4&show_icons=true&hide_border=true&rank_icon=github"
    alt="GitHub Stats"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=himanidhawan4&hide_border=true"
    alt="GitHub Streak"
  />
</p>

<hr/>

<h2>🤝 Let's Connect</h2>

<p align="center">

  <a href="https://github.com/himanidhawan4">
    <img
      src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"
      alt="GitHub"
    />
  </a>

</p>

<p align="center">
  <b>Thanks for visiting my profile! 🚀</b>
</p>

<p align="center">
  <i>Learning by building, breaking, debugging and improving.</i>
</p>
