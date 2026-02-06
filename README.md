[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=F7F7F7&width=435&lines=Hi+%F0%9F%91%8B+Welcome+to+My+GitHub!)](https://git.io/typing-svg) 

<p align="center">
  <img src="https://github.com/user-attachments/assets/00474ad1-0510-4075-9fe6-97eda9a26546" width="100%" />
</p>


I'm an Informatics student passionate about building interactive web applications. Currently deepening my skills in **React Ecosystem** and **TypeScript**.

🛠️ **Tech Stack**
* **Languages:** TypeScript, JavaScript (ES6+), MySQL, SQL
* **Frontend:** React, Tailwind CSS, HTML5/CSS3
* **Backend:** Express.js, Node.js
* **Tools:** Git, Postman, VS Code

🌱 **Currently Learning**
* Advanced React Patterns & Performance
* System Design Basics

📫 **Connect with Me**
* [LinkedIn](---)
* [Email](mailto:zulfikarmuhamad207@gmail.com)


---


name: Waka Readme

on:
  schedule:
    - cron: '0 0 * * *' 
  workflow_dispatch:

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ waka_d4e1e371-22b8-4d6a-9cf2-695fa8b5200f }}
          GH_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SHOW_OS: "False"
          SHOW_PROJECTS: "True"
          SHOW_EDITORS: "False"
