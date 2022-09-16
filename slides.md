---
marp: true
theme: default
_class: invert
paginate: true
style: |
    section.lead h1 {
        text-align: center;
    }
    section.lead h2 {
        color: yellow;
        text-align: center;
    }
---
<!--
_backgroundColor: black
_class: lead
-->

# **Reusable architecture diagrams**
## with Draw.io + VSCode + GitHub

## Presented by: Tommy Falgout and lots of hands-on experience

---

# Agenda

- Overview
- The Gift of Your Keystrokes
- Technology
  - Draw.io
  - VSCode
  - Github
- Live Demo

---

# Our Time Is Limited


- [Gift of Your Keystrokes by Scott Hanselman](https://www.hanselman.com/blog/do-they-deserve-the-gift-of-your-keystrokes)

```5.1CPW * 50WPM * 60m/hr * 6hr/s a day * 5 days/wk * 50 wks/year * 44yrs = 1,009,800,000 keystrokes left in your hands```

- Effectiveness vs. Efficiency
  - When we reply via email, we reach 1-10 people
  - If we blog, we can increase reach
- Focus on ROI of the limited keystrokes

--- 

# Draw.io 

- Open Source Diagram Software
- Integrates with:
  - MS Teams, Google Drive, Confluence, GitHub
- Import Shapes (Azure, AWS, UML)
- Can use: Browser, Native App, VSCode

![bg right 80%](img/drawio-example.png)


--- 

# VS Code

- File Editor
- Vast plugin ecosystem
    - Including Draw.io

![bg right 90%](img/vscode-drawio.png)

---

# GitHub

- Version Control as a Service
- Works best for text, NOT binary
- Uses Markdown for documentation

![bg left 60%](https://icongr.am/octicons/mark-github.svg)

---

# Putting It All Together

- Use Draw.io to create diagrams
- Use VSCode to create documentation
- Use Github to store and version control

![bg right 60%](img/captain-planet.jpg)

--- 

<!--
_backgroundColor: black
_class: lead
-->

# **Case Study**

---

# Requirements

- SaaS Offer
- AKS
- Microservices
- K8S Ingress
- Private Link across Tenants

---

# VSCode + Draw.io

![h:500px](img/case-study-vscode.png)


---

# GitHub + Markdown

![h:500px](img/gh-readme.png)

HINT: Does this look familiar?

--- 

# Blog

Maximize your keystrokes!

![h:500px](img/blog-devto.png)

---

<!--
_backgroundColor: black
_class: lead
-->

# **Draw.io Tips and Tricks**

--- 

# Add More Shapes

![bg right 60%](img/drawio-more-shapes.png)

--- 

# Add Azure Shapes

![bg right 90%](img/drawio-azure-shapes.png)

Other shapes include:
- AWS
- GCP
- IBM
- VMWare
- Office
- Network
- Logic Gates

---

# Important to know

- Draw.io works in layers
  - Draw containers from large to small
  - Example:
    - Tenant
    - Subscription
    - Vnet
    - Subnet
    - AKS
- Place icon in top left, inside the container

---

<!--
_backgroundColor: black
_class: lead
-->

# **DEMO TIME**
# **F-IT!  Let's do it live!**

---

<!-- 
_footer: 'Credit: https://www.youtube.com/watch?v=bEzbCP9wtB0'
-->

# Volunteers?

- Walk me through your
  - Example architecture
  - Azure based
- I'll draw your architecture
 
![bg right 90%](img/caricature.png)

---

<!--
_backgroundColor: black
_class: lead
-->
<style scoped>
h1 {
  color: white;
}
h3 {
  position: absolute;
  left: 600px;
  bottom: 130px;
  color: white;
}
h4 {
  position: absolute;
  left: 600px;
  bottom: 90px;
  color: yellow;
}
h5 {
  position: absolute;
  left: 600px;
  bottom: 70px;
  color: yellow;
}
</style>

# Thanks for attending!
## Please fill out a session evaluation
### Tommy Falgout
#### Cloud Solution Architect