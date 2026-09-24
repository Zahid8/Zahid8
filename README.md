<!-- ============================== HEADER ============================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0d1b2a,55:1b4965,100:5fa8d3&text=Zahid%20Hussain&fontColor=ffffff&fontSize=62&fontAlignY=38&desc=Reinforcement%20Learning%20%C2%B7%20Physical%20AI%20%C2%B7%20Autonomous%20Systems&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="Zahid Hussain" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=5FA8D3&center=true&vCenter=true&width=620&lines=Teaching+machines+to+act+in+the+physical+world;Drones+%C2%B7+AUVs+%C2%B7+Cars+%C2%B7+Robot+arms;Multi-agent+RL+%C2%B7+World+models+%C2%B7+Safe+control;MS+Computer+Engineering+%40+Texas+A%26M" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/zahidhussain909/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://twitter.com/ZahidHu30360793"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="mailto:zahidhussain909@gmail.com"><img src="https://img.shields.io/badge/Email-C14438?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://papers.zahid.win"><img src="https://img.shields.io/badge/Paper_Explainers-1B4965?style=for-the-badge&logo=bookstack&logoColor=white" alt="Paper explainers" /></a>
<a href="https://www.instagram.com/_i_am_zahid/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>

<img src="https://komarev.com/ghpvc/?username=zahidhussain909&style=flat-square&color=1b4965&label=profile+views" alt="Profile views" />

</div>

<!-- ============================== ABOUT ============================== -->

## 👋 About me

I'm an **MS Computer Engineering student at Texas A&M University** working on **reinforcement learning for Physical AI**: agents that have to perceive, predict and act in a physical world that is noisy, delayed and unforgiving.

My work covers the whole loop. I build the **simulators and digital twins**, the **world models** that predict what an action will do, the **multi-agent policies** that coordinate fleets, and the **safety layers** that keep them from crashing into each other. I apply it to **drones, underwater vehicles, cars and robot arms**. I got into this through underwater robotics, building AUV and ROV software for competition teams during my undergrad.

```python
class Zahid:
    role      = "MS Computer Engineering @ Texas A&M University"
    research  = ["Reinforcement Learning", "Physical AI", "Multi-Agent RL", "World Models"]
    platforms = ["🚁 drone swarms", "🌊 AUV fleets", "🚗 self-driving", "🦾 manipulation"]
    toolbox   = ["PyTorch", "MuJoCo", "PettingZoo", "V-JEPA 2", "Three.js"]
    currently = "training one policy that can fly a drone team of any size"
    fuel      = "coffee ☕ > chai"
    fun_fact  = "I like to code and then stare at it in awe of its beauty."
```

<!-- ============================== RESEARCH ============================== -->

## 🧭 What I work on

My research sits where **reinforcement learning meets the physical world**. I care about autonomous machines that have to coordinate, stay safe and make decisions from imperfect sensing, and I work on them from simulation through to policy.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🚁 Autonomous drones</h3>
      <b>Multi-agent RL for aerial swarms.</b> Policies that generalise across team size and team split instead of being locked to one configuration. Cooperative formation and coverage, competitive pursuit–evasion and capture-the-flag trained through self-play leagues, and RL for navigation that stays resilient when GPS can't be trusted.
    </td>
    <td width="50%" valign="top">
      <h3>🌊 Underwater vehicles</h3>
      <b>Safe multi-agent RL for AUV fleets.</b> Underwater, acoustic messages arrive late or not at all, so I work on control-barrier-function safety shields that keep a fleet collision-free under communication delay and packet loss, with RL learning the control on top.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🚗 Autonomous driving</h3>
      <b>World models for driving.</b> Turning self-supervised video representations (V-JEPA) into action-conditioned world models that let a driving policy imagine the future before it acts, learned from real-world driving data.
    </td>
    <td valign="top">
      <h3>🦾 Robot manipulation</h3>
      <b>Object-centric world models from pixels.</b> Robot arms that see only camera frames but reason about <i>objects</i>, choose subgoals relative to them, and correct their own mistakes through interactive imitation (DAgger).
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>📡 Physical sensing</h3>
      <b>RL that decides where to measure.</b> Constrained and risk-sensitive RL for placing a handful of sensors on physical fields you can't observe directly, so the field can be reconstructed accurately and robustly on a tight sensor budget.
    </td>
    <td valign="top">
      <h3>🕹️ Simulation & digital twins</h3>
      <b>Building the worlds agents learn in.</b> Deterministic, vectorised simulators with realistic dynamics, wind, battery drain and lossy communication, plus MuJoCo environments and live 3D twins in the browser for watching policies act.
    </td>
  </tr>
</table>

### 🧪 Methods I use

<p>
  <img src="https://img.shields.io/badge/Multi--Agent_RL-1b4965?style=flat-square" alt="Multi-agent RL" />
  <img src="https://img.shields.io/badge/MAPPO_%C2%B7_PPO-1b4965?style=flat-square" alt="MAPPO and PPO" />
  <img src="https://img.shields.io/badge/Self--Play_Leagues-1b4965?style=flat-square" alt="Self-play leagues" />
  <img src="https://img.shields.io/badge/World_Models-1b4965?style=flat-square" alt="World models" />
  <img src="https://img.shields.io/badge/JEPA_%C2%B7_Self--Supervised_Video-1b4965?style=flat-square" alt="JEPA and self-supervised video" />
  <img src="https://img.shields.io/badge/Safe_%26_Constrained_RL-1b4965?style=flat-square" alt="Safe and constrained RL" />
  <img src="https://img.shields.io/badge/Control_Barrier_Functions-1b4965?style=flat-square" alt="Control barrier functions" />
  <img src="https://img.shields.io/badge/Risk--Sensitive_RL-1b4965?style=flat-square" alt="Risk-sensitive RL" />
  <img src="https://img.shields.io/badge/Imitation_Learning_%C2%B7_DAgger-1b4965?style=flat-square" alt="Imitation learning and DAgger" />
  <img src="https://img.shields.io/badge/Diffusion_Policy-1b4965?style=flat-square" alt="Diffusion policy" />
  <img src="https://img.shields.io/badge/Set_Transformers-1b4965?style=flat-square" alt="Set transformers" />
</p>

<!-- ============================== EXPLAINERS ============================== -->

## 📚 Papers, explained

I also rebuild research papers as **interactive, scroll-driven explainers** with redrawn diagrams, the maths kept intact, and mechanisms you can play with. Topics so far include PPO, REINFORCE, DreamerV3, I-JEPA and V-JEPA 2.1. They live at **[papers.zahid.win](https://papers.zahid.win)**.

<!-- ============================== STACK ============================== -->

## 🧰 Toolbox

<table>
  <tr>
    <td align="center" width="150"><b>RL & ML</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv" alt="RL and ML" /><br/>
      <img src="https://img.shields.io/badge/MuJoCo-0d1b2a?style=flat-square" alt="MuJoCo" />
      <img src="https://img.shields.io/badge/PettingZoo-0d1b2a?style=flat-square" alt="PettingZoo" />
      <img src="https://img.shields.io/badge/Gymnasium-0d1b2a?style=flat-square" alt="Gymnasium" />
      <img src="https://img.shields.io/badge/Meta--World-0d1b2a?style=flat-square" alt="Meta-World" />
      <img src="https://img.shields.io/badge/CUDA-0d1b2a?style=flat-square&logo=nvidia&logoColor=76B900" alt="CUDA" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Robotics & Systems</b></td>
    <td><img src="https://skillicons.dev/icons?i=cpp,c,raspberrypi,arduino,ubuntu,bash" alt="Robotics and systems" /></td>
  </tr>
  <tr>
    <td align="center"><b>Twins & Viz</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,react,nextjs,threejs,vite,fastapi" alt="Digital twins and visualisation" /></td>
  </tr>
  <tr>
    <td align="center"><b>Infra & Writing</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,git,githubactions,gcp,latex,vim,vscode" alt="Infra and writing" /></td>
  </tr>
  <tr>
    <td align="center"><b>Design</b></td>
    <td><img src="https://skillicons.dev/icons?i=ps,ai,xd" alt="Design" /></td>
  </tr>
</table>

<!-- ============================== STATS ============================== -->

## 📈 GitHub activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Zahid8&hide_border=true&background=0D1B2A&stroke=1B4965&ring=5FA8D3&fire=5FA8D3&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=5FA8D3&sideLabels=A9C7DD&dates=7A93A8" alt="GitHub streak" />
</div>

<!-- ============================== FOOTER ============================== -->

## 🤝 Let's talk

- 🎓 **MS Computer Engineering**, Texas A&M University · **B.Tech Electronics Engineering**, ZHCET, Aligarh Muslim University (2019–2023)
- 🔬 Open to **research collaborations** and **opportunities** in RL, robotics and autonomous systems
- 📫 **zahidhussain909@gmail.com**

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:5fa8d3,45:1b4965,100:0d1b2a" width="100%" alt="" />
