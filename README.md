Hola world! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

<img src="https://raw.githubusercontent.com/moisestech/moisestech/master/assets/avatar/MoisesTech_Zepeto_MLwJS.png" align="right" width="315px"/>

I'm <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Moises Sanabria — an AI Engineer, Creative Technologist, and interdisciplinary artist from 🇻🇪 Venezuela based in 🏝️ Miami.

I build intelligent systems that connect AI agents, software, data, creative tools, and physical environments.

My work spans production AI systems, generative media, institutional infrastructure, interactive installations, and forward-deployed engineering. I’m especially interested in the full path from model → interface → infrastructure → deployment → human adoption.

Previously, I helped build generative storytelling systems at Lore Machine. Today, I’m developing agentic workflows, creative infrastructure, and technical systems for organizations, artists, and new forms of cultural production.



const build = async (problem) => {
  const context = await observe(problem);
  const constraints = map(context);
  let prototype = await make(constraints);

  while (!prototype.isUseful()) {
    prototype = await iterate(prototype);
  }

  return deploy(prototype, {
    humans: true,
    documentation: true,
    poeticComputation: true,
  });
};

<br clear="right"/>

What I build

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>🤖 AI Systems</strong><br/><br/>
      Agents<br/>
      MCP + tool use<br/>
      RAG + retrieval<br/>
      Evals + observability<br/>
      Multimodal workflows<br/>
      Human-in-the-loop systems
    </td>
    <td valign="top" width="33%">
      <strong>🧩 Forward-Deployed Systems</strong><br/><br/>
      Technical discovery<br/>
      Organizational workflows<br/>
      Rapid prototyping<br/>
      Deployment + enablement<br/>
      Client-facing implementation<br/>
      Physical + institutional systems
    </td>
    <td valign="top" width="33%">
      <strong>🎛️ Creative Technology</strong><br/><br/>
      Generative media<br/>
      Interactive interfaces<br/>
      Three.js / WebGL / WebGPU<br/>
      TouchDesigner<br/>
      Physical computing<br/>
      Experimental software
    </td>
  </tr>
</table>

I work across the full path from model → agent → API → product → data → infrastructure → physical environment → people.

Selected systems

● PRODUCTION / FIELD WORK    ◐ ACTIVE    ○ RESEARCH / REFERENCE IMPLEMENTATION

◐ agentic-ops

An auditable multi-tool agent runtime for organizational workflows.

A public reference implementation for multi-step AI systems that can plan, retrieve context, use tools, respect permissions, request human approval, execute actions, and evaluate their own operational behavior.

Python TypeScript FastAPI Next.js MCP RAG Postgres pgvector Docker Evals HITL

Instruction
    ↓
Planner
    ↓
Agent Runtime
    ↓
MCP / Tools
    ↓
Retrieval + Memory
    ↓
Human Approval
    ↓
Execution
    ↓
Evaluation

Current focus: tool orchestration, structured outputs, retrieval, approval boundaries, auditability, and evaluation.

● Lore Machine

Generative storytelling infrastructure for turning narrative inputs into multimodal creative outputs.

My work there helped shape how I think about AI product systems: prompt architecture, multimodal workflows, production interfaces, iterative model behavior, and the orchestration required to make generative systems useful to actual creators.

Generative AI Multimodal Systems Prompt Architecture Product Engineering Creative Tools

Visit Lore Machine →

◐ SmartSigns

Distributed digital-signage infrastructure for cultural and artist environments.

A field-deployed system connecting web software to Raspberry Pi devices, kiosk-mode browsers, physical displays, remote configuration, and the operational realities of maintaining technology outside a developer laptop.

Raspberry Pi Linux Chromium Kiosk Systems Web Infrastructure Device Operations

Admin / Content
      ↓
 Web Infrastructure
      ↓
 Device Registry
      ↓
 Raspberry Pi
      ↓
 Chromium Kiosk
      ↓
 Physical Display

◐ AI24 Control Room

Programming and operational infrastructure for an AI-native media network.

A system for organizing artists, media assets, playlists, programming, schedules, distribution, and eventually analytics across a continuously evolving creative network.

Next.js TypeScript Postgres Automation Media Pipelines Scheduling Streaming

Content Sources
      ↓
  Ingestion
      ↓
Editorial Layer
      ↓
 Programming
      ↓
 Scheduling
      ↓
 Distribution
      ↓
 Analytics

◐ Creative AI

AI-assisted creative production across art, interfaces, client work, and generative media.

I use AI as more than a generation endpoint: as a production system, interface material, creative collaborator, automation layer, and cultural object.

Current work includes projects such as ArtLikes, artist/client web systems, generative image and video workflows, and experimental interfaces.

Creative Direction Generative Media AI Workflows Interactive Design Web Production

Currently building — agentic-ops

This is the current technical flagship: one small, real system designed to make modern AI engineering practices inspectable rather than simply listed on a résumé.

✓ Multi-step orchestration
✓ Structured tool interfaces
◐ MCP server + client
◐ Retrieval / organizational knowledge
◐ Human approval gates
◐ Evaluation suite
○ Public replayable demo
○ Production deployment

What it is designed to prove

Capability

Evidence

Agent orchestration

Multi-step stateful workflows

MCP + tool use

Explicit tool schemas and execution

RAG

Retrieval over organizational knowledge

Human-in-the-loop

Approval boundaries for consequential actions

Evals

Behavioral regression and tool-selection tests

Python

Agent runtime + API

TypeScript

User-facing control interface

FastAPI

Service layer

Postgres / pgvector

Persistence + retrieval

Docker

Reproducible runtime

CI/CD

Automated lint, tests, and build

Observability

Run timeline, errors, cost, and tool traces

The goal is not another chatbot. The goal is an auditable system that does useful work across multiple tools while keeping humans in control.

Production + field experience

I’m particularly interested in engineering where the technical system is only one part of the problem.

DISCOVER
   ↓
MAP
   ↓
PROTOTYPE
   ↓
DEPLOY
   ↓
ENABLE
   ↓
MEASURE
   ↓
ITERATE

Lore Machine

AI product engineering and generative storytelling systems.

Oolite Arts

Creative technology infrastructure, digital fabrication, artist enablement, workshops, and technical systems operating inside a cultural institution.

Bakehouse Art Complex / SmartSigns

Physical deployment, Raspberry Pi infrastructure, kiosk systems, artist-facing technology, and operational implementation.

Independent + client work

Creative AI production, interactive websites, generative workflows, technical consulting, implementation, and translating technical capabilities for non-technical collaborators.

This is the part of engineering I enjoy most: entering an ambiguous environment, understanding its people and constraints, building something useful, and making sure the system can actually be operated after the prototype works.

Technical capabilities

<img src="https://github.com/moisestech/moisestech/blob/master/assets/avatar/MoisesTech_Zepeto_Dancing.gif?raw=true" alt="MoisesTech Dancing" width="285px" align="left" />

<table>
  <tr>
    <td valign="top" width="250"></td>
    <td valign="top" width="250"></td>
  </tr>

  <tr>
    <td valign="center" width="250">
      <strong>🤖 AI Systems</strong>
    </td>
    <td valign="center" width="250">
      <strong>💻 Software Engineering</strong>
    </td>
  </tr>

  <tr>
    <td valign="top" width="250">
      <div align="center">
        <img width="40" title="Python" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"/>
        <img width="40" title="PostgreSQL" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png"/>
        <img width="40" title="FastAPI" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/fastapi/fastapi.png"/>
        <img width="40" title="Jupyter" src="https://github.com/moisestech/moisestech/blob/master/assets/logos/jupyter_notebooks.png?raw=true"/>
      </div>
      <br/>
      <div align="center">
        <strong>
          Agents · MCP · Tool Use<br/>
          RAG · Vector Search<br/>
          Structured Outputs · Evals<br/>
          Multimodal AI · HITL
        </strong>
      </div>
    </td>

<td valign="top" width="250">
  <div align="center">
    <img width="40" title="TypeScript" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/typescript/typescript.png"/>
    <img width="40" title="React" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png"/>
    <img width="40" title="Next.js" src="https://raw.githubusercontent.com/moisestech/moisestech/master/assets/logos/nextjs.png"/>
    <img height="40" title="Node.js" src="https://raw.githubusercontent.com/moisestech/moisestech/master/assets/logos/nodejs.png"/>
    <img width="40" title="HTML" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"/>
    <img width="40" title="CSS" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"/>
  </div>
  <br/>
  <div align="center">
    <strong>
      TypeScript · React · Next.js<br/>
      Python · FastAPI · Node<br/>
      APIs · Realtime Systems<br/>
      Authentication · Interfaces
    </strong>
  </div>
</td>

  </tr>

  <tr>
    <td valign="center" width="250">
      <strong>🏗️ Data + Infrastructure</strong>
    </td>
    <td valign="center" width="250">
      <strong>🎛️ Creative Computing</strong>
    </td>
  </tr>

  <tr>
    <td valign="top" width="250">
      <div align="center">
        <img width="40" title="PostgreSQL" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png"/>
        <img height="50" title="AWS" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/aws/aws.png"/>
        <img width="40" title="Docker" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"/>
        <img width="40" title="GitHub" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png"/>
        <img width="40" title="Terminal" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png"/>
      </div>
      <br/>
      <div align="center">
        <strong>
          SQL · Postgres · Data Modeling<br/>
          ETL · Analytics · Warehousing<br/>
          Docker · Linux · CI/CD<br/>
          Cloud · GitHub Actions
        </strong>
      </div>
    </td>

<td valign="top" width="250">
  <div align="center">
    <img width="40" title="JavaScript" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"/>
    <img width="40" title="Three.js" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/threejs/threejs.png"/>
    <img width="40" title="Raspberry Pi" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/raspberry-pi/raspberry-pi.png"/>
  </div>
  <br/>
  <div align="center">
    <strong>
      Three.js · WebGL · WebGPU<br/>
      TouchDesigner · ComfyUI<br/>
      Raspberry Pi · Physical Computing<br/>
      Generative Media · Interactive Systems
    </strong>
  </div>
</td>

  </tr>
</table>

<br clear="left"/>

Evidence over self-rating

I’m trying to make every major technical claim on this profile traceable to something inspectable:

SKILL
  ↓
REPOSITORY
  ↓
WORKING SYSTEM
  ↓
ARCHITECTURE
  ↓
CASE STUDY
  ↓
DEMO / SCREENSHOT

Rather than collecting isolated demo repos, I’m building a smaller set of systems where each project proves multiple adjacent capabilities.

Current evidence map

Capability

Primary proof

Agent orchestration

agentic-ops

MCP / tool use

agentic-ops

RAG / retrieval

agentic-ops

Evals / observability

agentic-ops

Multimodal AI

Lore Machine + public reference work

Full-stack product engineering

AI24 + moises.tech

Linux / field deployment

SmartSigns

Raspberry Pi

SmartSigns

Data architecture

Data platform work + prior production experience

Creative AI

Lore Machine + ArtLikes + client work

Creative computing

Interactive / installation work

Forward-deployed engineering

Oolite + Bakehouse + client implementations

How I think about engineering

I don't see software as separate from the environment where it operates.

A production system can include:

models
+
agents
+
interfaces
+
APIs
+
databases
+
permissions
+
people
+
hardware
+
physical space
+
documentation
+
training

The interesting engineering problem is often not making any one component work.

It's making the whole system legible, reliable, maintainable, useful, and adaptable to the people operating it.

That is why I’m especially interested in AI engineering, forward-deployed engineering, creative technology, and technical infrastructure.

Poetic computation

My engineering practice grew alongside an artistic practice centered on poetic computation — using software not only to automate tasks, but to expose new relationships between technology, culture, attention, humor, labor, and everyday life.

Sometimes that results in software.

Sometimes it becomes an installation, an image, a physical object, a workflow, a website, a tool for another artist, or infrastructure inside an organization.

The medium changes. The underlying question is often the same:

What happens when computation becomes part of the material itself?

What I can help build

Agentic AI products with real tool use and operational guardrails

Forward-deployed AI implementations inside organizations

AI-enabled workflows for technical and non-technical teams

Multimodal creative systems for images, video, narrative, and media

Full-stack AI products from interface to API to persistence

Data + AI infrastructure connecting models to useful organizational context

Interactive and physical computing systems that leave the browser

Creative technology prototypes where software, art, media, and hardware overlap

I'm particularly interested in roles around AI Engineering, Forward-Deployed Engineering, Creative Technology, AI Solutions Architecture, and Technical / Creative Innovation.

📈 GitHub activity



<img height="150px" src="https://github-readme-stats.vercel.app/api?username=moisestech&hide_title=true&hide_border=true&show_icons=true&include_all_commits=true&line_height=21&bg_color=0,EC6C6C,FFD479,FFFC79,73FA79&theme=graywhite" />

<img src="https://raw.githubusercontent.com/moisestech/moisestech/master/assets/banner/contributions.gif" alt="Contributions" width="722px" height="112px" />

🌐 Find more of my work

🏠 moises.tech💼 LinkedIn💻 GitHub📫 m@moises.tech

Art × AI × Infrastructure × Poetic Computation

I build technology, artworks, interfaces, and systems for a world where software increasingly participates in how culture, organizations, and everyday life operate.
