<img align="right" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">

# Saúl Laínez

**AI Engineer & Cloud Solutions Architect** · San Salvador, El Salvador

I design event-driven AWS platforms and the AI agents that run on top of them.
Over the last twelve months: **28 projects, 60 repositories, 10 clients, 754 commits** —
moving from *"get me this data"* to *"here is the platform your team builds on."*

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/sa%C3%BAl-la%C3%ADnez-764a131a8" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
<a href="https://twitter.com/sallanez" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="sallanez" height="30" width="40" /></a>
<a href="mailto:saul.alejandro19@gmail.com">📫 saul.alejandro19@gmail.com</a>
</p>

## What I do

**Cloud architecture & IaC.** Designed and deployed a **362-resource, ten-service
event-driven AWS platform solo in eleven days** — a single EventBridge bus with
per-source IAM restriction, filtered subscriptions, DLQs, dashboards and anomaly alarms
across 26 Lambda functions, with a formal architecture document generated from the code.
Built a Terraform/Terragrunt landing zone for a regional food manufacturer including a
**site-to-site VPN to their on-premises network** (customer gateway, BGP ASN, tunnel
addressing), .NET Lambdas, and a four-stage CodePipeline with SonarQube static analysis.
I can stand up a complete client engagement — IaC, backend, CI/CD, front-end shells — in
a day.

**AI & agent engineering.** Seven Amazon Bedrock projects: text-to-SQL over PostgreSQL,
text-to-DAX against Power BI via Microsoft Entra OAuth2, and a vision agent scoring
retail shelf photography. The design principle is consistent — *let the model generate
the query, constrain what the query can do*: read-only SQL validation backed by a
read-only database user, injection prevention at the tool boundary. I also build the AI
working environment itself, from repo instruction files to ~30 machine-readable rule
sets published as Claude Agent Skills.

**Data acquisition & ETL.** Nine production pipelines against systems that did not want
to be read — subscription trade platforms, a bot-protected supplier portal with SMS 2FA,
an SAP ERP, and a government customs API. One ran in production for ten months, with
deduplication solved at the schema level. The most recent one started by asking whether
an API existed: 517 lines instead of 14,000.

**Deployment, documentation, security.** The recurring role across projects someone else
wrote — making them deployable, secure and repeatable with Docker, ECR, App Runner,
Amplify, SAM and CodePipeline. I usually write more documentation than code, including
Spanish end-user manuals for non-technical staff, and I have shipped unprompted security
assessments (disabled TLS verification, exposed tokens, secrets at rest) with prioritized
remediation.

## Tech

- **Cloud & IaC** — AWS · Terraform · Terragrunt · AWS SAM · Docker · ECR · CodePipeline · Amplify · App Runner
- **AWS** — Lambda · EventBridge · S3 · Glue · DynamoDB · Aurora · RDS Proxy · API Gateway · AppSync · Cognito · SQS/SNS · CloudWatch · X-Ray · WAF
- **AI** — Amazon Bedrock (agents, action groups, agent runtime, vision) · MCP · Claude Agent Skills
- **Languages** — Python · TypeScript · PHP · C# / .NET · SQL
- **Data** — PostgreSQL · pandas · Polars · Playwright · pipeline & schema design

<h3 align="left">Languages and Tools:</h3>
<p align="left">
<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" alt="aws" width="40" height="40"/></a>
<a href="https://www.terraform.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original-wordmark.svg" alt="terraform" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="python" width="40" height="40"/></a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
<a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dotnetcore/dotnetcore-original.svg" alt="dotnet" width="40" height="40"/></a>
<a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/></a>
<a href="https://www.php.net" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/></a>
<a href="https://laravel.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original-wordmark.svg" alt="laravel" width="40" height="40"/></a>
<a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original-wordmark.svg" alt="fastapi" width="40" height="40"/></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
<a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="nextjs" width="40" height="40"/></a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original-wordmark.svg" alt="git" width="40" height="40"/></a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>
</p>

## Also

Learned PHP/Laravel/Filament from zero and shipped a 26,500-line budget-management
product for an industrial manufacturer in six months. Work bilingually: Spanish client
domains and end-user documentation, English engineering.

<h2 align="center">My Contribution Streak !! :fire:</h2>

![activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Saul19-L98&theme=github-compact&hide_border=true)

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Saul19-L98&theme=radical&hide_border=true" alt="streak stats" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Saul19-L98&theme=radical" alt="profile summary" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Saul19-L98&theme=radical" alt="languages by repo" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Saul19-L98&theme=radical" alt="languages by commit" />
</p>

<h1 align="center">Watch a 🐍 eating my Contribution Graph</h1>
<p align="center">
  <img src="https://raw.githubusercontent.com/Saul19-L98/Saul19-L98/output/github-contribution-grid-snake.gif" alt="snake" />
</p>

---

> Most of my work from the past year lives in private repositories under a separate work
> account, so this profile's contribution graph is not a useful signal.
