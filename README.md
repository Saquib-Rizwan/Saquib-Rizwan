<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=200&section=header&text=Saquib%20Rizwan&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=full-stack%20%C2%B7%20LLM%20systems%20%C2%B7%20things%20that%20grade%20themselves&descAlignY=54&descSize=16" width="100%" alt="" />

<a href="https://github.com/Saquib-Rizwan">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&pause=1200&color=7AA2F7&center=true&vCenter=true&width=680&lines=I+build+systems+that+judge+work+%E2%80%94+answers%2C+code%2C+correctness.;Most+of+my+bugs+live+in+the+layer+I+swore+was+fine.;Currently+losing+an+argument+with+cgroups." alt="" />
</a>

</div>

<br>

## whoami

```ts
const saquib = {
  role: "CS student · building through placement season",
  building: "an interview prep platform that reads your answer and finds the gaps",
  stack: ["TypeScript", "React", "Node", "Python", "FastAPI", "PostgreSQL", "Prisma"],
  interests: ["LLM evaluation", "sandboxed execution", "developer tooling"],
  learnedTheHardWay: "Docker Desktop will never give you cgroup v1. Stop trying.",
} as const;
```

<br>

## what I'm building right now

**[mock-interview](https://github.com/Saquib-Rizwan/mock-interview)** — a placement prep platform where practice actually tells you something.

You pick a company and a role, work through its real interview rounds, and type your answer like you would in the room. An LLM then grades it **strictly against expected answer points** — no invented criteria, no vague encouragement — and tells you which points you missed and why. Coding rounds run your solution against real test cases in a sandbox.

The parts I care about:

- **Scoped grading.** The model is given the marking scheme and forbidden from adding to it. An off-topic-but-correct answer scores zero, because that's what happens in an interview.
- **Prompt-injection resistant.** Student answers are delimited data, not instructions. "Ignore all previous instructions" scores 0/3.
- **Criteria never leave the server.** The API cannot be asked for the answers it's grading you against.
- **One file owns the LLM.** Swapping providers touches exactly one module.

`TypeScript · React · Node · Python/FastAPI · PostgreSQL · Prisma · Gemini · Judge0`

<br>

## stack

**Languages & frameworks**

<img src="https://skillicons.dev/icons?i=ts,js,python,react,nodejs,express,fastapi&theme=dark" alt="" />

**Data & infra**

<img src="https://skillicons.dev/icons?i=postgres,prisma,docker,azure,linux&theme=dark" alt="" />

**Tooling**

<img src="https://skillicons.dev/icons?i=git,github,vscode,vite,html,css&theme=dark" alt="" />

<br>

## currently figuring out

- Why sandboxing code is a kernel problem before it's a code problem — `isolate`, cgroups, and the difference between a container and a jail
- Getting an LLM to grade consistently instead of generously
- Schema design that survives the phase *after* the one you designed it for

<br>

## the numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Saquib-Rizwan&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=00000000" alt="" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Saquib-Rizwan&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=00000000" alt="" />

<br><br>

<img src="https://streak-stats.demolab.com?user=Saquib-Rizwan&theme=tokyonight&hide_border=true&background=00000000" alt="" />

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Saquib-Rizwan/Saquib-Rizwan/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Saquib-Rizwan/Saquib-Rizwan/output/snake.svg" />
  <img alt="contribution graph" src="https://raw.githubusercontent.com/Saquib-Rizwan/Saquib-Rizwan/output/snake.svg" />
</picture>

</div>

<br>

## say hello

<div align="center">

<a href="mailto:saquibrizwan2005@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="" />
</a>
<a href="https://www.linkedin.com/in/saquib-rizwan-27b8632b3">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="" />
</a>
<a href="https://github.com/Saquib-Rizwan?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="" />
</a>

<br><br>

<sub>Ask me about grading answers with an LLM without it inventing the marking scheme,<br>or why a sandbox is a kernel decision you make months before you write the feature.</sub>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=120&section=footer" width="100%" alt="" />

</div>
