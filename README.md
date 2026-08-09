# Saúl Laínez

**AI Engineer & Cloud Solutions Architect** · San Salvador, El Salvador

I design event-driven AWS platforms and the AI agents that run on top of them.
Over the last twelve months: **28 projects, 60 repositories, 10 clients, 754 commits** —
moving from *"get me this data"* to *"here is the platform your team builds on."*

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

## Also

Learned PHP/Laravel/Filament from zero and shipped a 26,500-line budget-management
product for an industrial manufacturer in six months. Work bilingually: Spanish client
domains and end-user documentation, English engineering.

---

> Most of my work from the past year lives in private repositories under a separate work
> account, so this profile's contribution graph is not a useful signal.

**[LinkedIn](https://www.linkedin.com/in/sa%C3%BAl-la%C3%ADnez-764a131a8)** · **[Email](mailto:saul.alejandro19@gmail.com)**
