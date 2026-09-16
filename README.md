<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&pause=1400&color=4ADE80&center=true&vCenter=true&width=700&lines=full+stack+developer+%26+engenheiro+eletr%C3%B4nico;do+circuito+ao+deploy+em+produ%C3%A7%C3%A3o;react+%C2%B7+node.js+%C2%B7+typescript+%C2%B7+docker" alt="" />

</div>

```console
$ ssh marcos@ponta-grossa

Last login: today — building things that ship

  role    full stack developer & engenheiro eletrônico
  stack   typescript · react · node.js · docker
  where   ponta grossa, pr — brasil
  status  aberto a oportunidades · construindo saas
```

<div align="center">

[![linkedin](https://img.shields.io/badge/linkedin-0D1117?style=flat-square&logo=linkedin&logoColor=4ADE80&labelColor=0D1117)](https://www.linkedin.com/in/marcos-giovanni-24768537b)
[![email](https://img.shields.io/badge/e--mail-0D1117?style=flat-square&logo=maildotru&logoColor=4ADE80&labelColor=0D1117)](mailto:MarcosAllmeida167@gmail.com)
[![workspace](https://img.shields.io/badge/workspace_rh-0D1117?style=flat-square&logo=googlechrome&logoColor=4ADE80&labelColor=0D1117)](https://workspacejobs.com.br)
[![views](https://komarev.com/ghpvc/?username=1a8jkf&style=flat-square&color=4ADE80&label=views)](https://github.com/1a8jkf)

</div>

<br/>

## `$ cat about.md`

Construo software que precisa ficar de pé sozinho e, quando dá, também o hardware que roda embaixo dele.

Venho da eletrônica: passei um ano diagnosticando falha em nível de componente antes de escrever código para produção. Isso mudou como eu programo. Sei o que acontece quando uma dependência externa cai às 3h da manhã, e é por isso que meus sistemas assumem falha como padrão, não como exceção.

Hoje divido o tempo entre **ecossistemas corporativos** ERPs, CRMs, plataformas logísticas, integrações com Oracle e Fluig e **produtos próprios**, onde eu escolho o problema, a stack e o prazo.

<br/>

## `$ tree ~/stack`

```console
$ tree ~/stack --dirsfirst -L 2

~/stack
├── frontend/
│   ├── typescript · javascript · html5 · css3
│   ├── react · angular · next.js
│   └── tailwind · componentes modulares
├── backend/
│   ├── node.js · express · rest apis · jwt
│   └── clean code · arquitetura modular
├── data/
│   ├── postgresql · mysql · oracle
│   ├── mongodb · redis
│   └── prisma orm
├── infra/
│   ├── docker · nginx · linux
│   ├── git · ci/cd · github actions
│   └── cloudflare · deploy · monitoramento
├── ai/
│   └── ollama · claude · deepseek · llm integration
├── enterprise/
│   └── fluig · otrs · notion
└── hardware/
    ├── eletrônica analógica e digital
    └── mecatrônica · g-code · automação robótica
```

<div align="center">

![typescript](https://img.shields.io/badge/typescript-0D1117?style=flat-square&logo=typescript&logoColor=3178C6&labelColor=0D1117)
![react](https://img.shields.io/badge/react-0D1117?style=flat-square&logo=react&logoColor=61DAFB&labelColor=0D1117)
![node](https://img.shields.io/badge/node.js-0D1117?style=flat-square&logo=nodedotjs&logoColor=5FA04E&labelColor=0D1117)
![angular](https://img.shields.io/badge/angular-0D1117?style=flat-square&logo=angular&logoColor=DD0031&labelColor=0D1117)
![next](https://img.shields.io/badge/next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=FFFFFF&labelColor=0D1117)
![tailwind](https://img.shields.io/badge/tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=38BDF8&labelColor=0D1117)
![postgres](https://img.shields.io/badge/postgresql-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1&labelColor=0D1117)
![redis](https://img.shields.io/badge/redis-0D1117?style=flat-square&logo=redis&logoColor=FF4438&labelColor=0D1117)
![prisma](https://img.shields.io/badge/prisma-0D1117?style=flat-square&logo=prisma&logoColor=FFFFFF&labelColor=0D1117)
![docker](https://img.shields.io/badge/docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED&labelColor=0D1117)
![linux](https://img.shields.io/badge/linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624&labelColor=0D1117)
![nginx](https://img.shields.io/badge/nginx-0D1117?style=flat-square&logo=nginx&logoColor=009639&labelColor=0D1117)
![cloudflare](https://img.shields.io/badge/cloudflare-0D1117?style=flat-square&logo=cloudflare&logoColor=F38020&labelColor=0D1117)
![bun](https://img.shields.io/badge/bun-0D1117?style=flat-square&logo=bun&logoColor=FBF0DF&labelColor=0D1117)

</div>

<br/>

## `$ ls ~/projects`

```console
$ ls ~/projects -1 --classify

universal-resilience-toolkit/*
devflux/
workspace-rh/*
limiar-code/*
```

<br/>

### `universal-resilience-toolkit`

Uma ferramenta única para **retries, rate limits, circuit breakers e persistência de estado** sem obrigar nenhuma dependência no seu projeto.

Exponential backoff para tentativas, token buckets para limitar requisições, circuit breakers com *half-open state* para dar fôlego a serviços caindo. O estado tenta SQLite ou Redis e faz fallback silencioso para a memória do processo. Deixei preparado para plugar OpenTelemetry e rastrear cada tentativa.

```console
node · bun · deno · cloudflare workers · vercel edge
@1a8jkf/universal-resilience-toolkit
```

[![repo](https://img.shields.io/badge/ver_repositório-0D1117?style=flat-square&logo=github&logoColor=4ADE80&labelColor=0D1117)](https://github.com/1a8jkf/universal-resilience-toolkit)

<br/>

### `devflux`

Uma IDE mobile de verdade, para quem não tem PC. Roda **Alpine Linux nativo** com shell funcional dá para subir aplicação Node.js direto do Android, com gerenciamento de memória para não torrar o aparelho.

SSH, conexão com Supabase e AWS, sync de código e backup de projeto no estilo Git.

```console
status: em desenvolvimento → play store
```

<br/>

### `workspace-rh`

Recrutamento ainda roda em planilha na maioria das empresas brasileiras. Construí o sistema que muda isso — e ele está no ar.

Triagem com IA rankeando fit técnico e cultural, pipeline visual do anúncio ao onboarding, portal de vagas com SEO, notificação automática por e-mail e dashboards em tempo real.

```console
react · tailwind · node.js · express · postgresql · llm
```

[![site](https://img.shields.io/badge/workspacejobs.com.br-0D1117?style=flat-square&logo=googlechrome&logoColor=4ADE80&labelColor=0D1117)](https://workspacejobs.com.br)

<br/>

### `limiar-code`

Minha agência. Sites institucionais, landing pages e e-commerces com SEO técnico e performance real, entregues em até 15 dias — para clínicas, concessionárias e lojas que passaram a gerar cliente pelo Google, não só pelo Instagram.

<br/>

## `$ git log --oneline`

```console
$ git log --oneline --graph

* fev/2026 — set/2026   lumo negócios imobiliários · full stack
│                       erp + crm modular para gestão imobiliária. módulos
│                       independentes de rh, financeiro, operacional, crm
│                       com kanban interativo e dashboards de bi.
│
* nov/2025 — fev/2026   egadnet · front-end
│                       interface do sistema logístico new monaco.
│                       componentes modulares em react, typescript e
│                       angular. bugs complexos e documentação técnica
│                       para onboarding do time.
│
* set/2023 — out/2025   support ltda · full stack
│                       ciclo completo de aplicações web corporativas com
│                       react, node.js e oracle. deploys, homologação,
│                       produção, customizações em fluig e suporte via otrs.
│
* fev/2022 — mar/2023   world games · técnico em eletrônica
│                       diagnóstico e reparo de placas e equipamentos.
│                       análise de falha em nível de componente.
│
* 2022 — 2025           engenharia de software · unicesumar
```

<br/>

## `$ htop`

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=1a8jkf&show_icons=true&hide_border=true&bg_color=0D1117&title_color=4ADE80&icon_color=4ADE80&text_color=8B949E&include_all_commits=true&count_private=true&hide_title=true" alt="" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=1a8jkf&layout=compact&hide_border=true&bg_color=0D1117&title_color=4ADE80&text_color=8B949E&langs_count=8&hide_title=true" alt="" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=1a8jkf&bg_color=0D1117&color=8B949E&line=4ADE80&point=FFFFFF&area=true&area_color=4ADE80&hide_border=true&hide_title=true" alt="" />

</div>

<br/>

## `$ contact --help`

```console
$ contact --help

usage: reach-out [options]

  -l, --linkedin    linkedin.com/in/marcos-giovanni-24768537b
  -e, --email       MarcosAllmeida167@gmail.com
  -w, --workspace   workspacejobs.com.br
  -a, --agency      limiar code — sites, landing pages, e-commerce
  -s, --status      aberto a oportunidades e colaborações

$ reach-out --linkedin
connecting... done
```

<br/>

```console
$ exit

logout
Connection to marcos closed.
```
