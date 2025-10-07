# 👋 Hi, I'm Lucas Lima


## 🚀 About Me

I'm a **Computer Science undergraduate** at the University of Brasília (UnB) passionate about solving complex problems through technology. 

```cpp
#include <bits/stdc++.h>
#include "Fluminense.h"

class Lucas_Lima : public Fluminense_Supporter {
  private:
    std::string name;
    int age;
    std::string university;
    std::string undergraduation;
    std::string location;
    std::vector<std::string> interests;
    std::vector<std::string> programming_languages;

  public:
    Lucas_Lima() : Fluminense_Supporter() {
      name = "Lucas Gabriel de Oliveira Lima";
      age = calculate_age(2005, "April", 8);
      university = "University of Brasilia - UnB";
      undergraduation = "Computer Science";
      location = format_address("Brasília", "DF", "Brazil");
      
      interests = {
        "Artificial Intelligence",
        "Software Engineering",
        "DevOps and Infraestructure",
        "Competitive Programming",
        "Data Science",
        "Web Development",
        "Graphics Computation",
        "Blockchain Development"
      };
      
      programming_languages = {
        "TypeScript",
        "JavaScript",
        "C++",
        "Python",
        "Rust",
        "C#",
        "Java",
        "Go",
        "R"
      };
    }
};
```

---


## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center" colspan="5"><b>🤖 AI & Machine Learning</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" alt="Python"/></td>
      <td><img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/></td>
      <td><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/></td>
      <td><img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/></td>
      <td><img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" alt="Tensorflow"/></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit Learn"/></td>
      <td><img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/></td>
      <td><img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy"/></td>
      <td><img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter"/></td>
      <td><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/></td>
    </tr>
    <tr>
      <td align="center" colspan="5"><b>💻 Full Stack Development</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/></td>
      <td><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/></td>
      <td><img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/></td>
      <td><img src="https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/></td>
      <td><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/></td>
      <td><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/></td>
      <td><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/></td>
      <td><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/></td>
      <td><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/></td>
    </tr>
    <tr>
      <td align="center" colspan="5"><b>🗄️ Databases</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/></td>
      <td><img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/></td>
      <td><img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma"/></td>
      <td colspan="2"></td>
    </tr>
    <tr>
      <td align="center" colspan="5"><b>☁️ DevOps & Cloud</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/></td>
      <td><img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/></td>
      <td><img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/></td>
      <td><img src="https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/></td>
      <td><img src="https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/></td>
      <td><img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/></td>
      <td><img src="https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/></td>
      <td><img src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA"/></td>
      <td colspan="1"></td>
    </tr>
    <tr>
      <td align="center" colspan="5"><b>🧪 Testing & Quality</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest"/></td>
      <td><img src="https://img.shields.io/badge/TDD-Test_Driven_Development-green?style=for-the-badge" alt="TDD"/></td>
      <td colspan="3"></td>
    </tr>
    <tr>
      <td align="center" colspan="5"><b>🔧 Other Technologies</b></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/></td>
      <td><img src="https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl" alt="OpenGL"/></td>
      <td><img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby"/></td>
      <td><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/></td>
      <td><img src="https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/></td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"/></td>
      <td><img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" alt=".NET"/></td>
      <td><img src="https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white" alt="R"/></td>
      <td colspan="2"></td>
    </tr>
  </table>
</div>

---
</div>
