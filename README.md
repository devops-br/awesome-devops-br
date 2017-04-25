# awesome-devops-br
Lista de recursos (links, livros, Q&amp;A) discutidos no canal do Telegram Devops-BR (https://t.me/devopsbr)
## Table of Contents
* [Awesome Devops BR](#awesome-devops-br)
  * [Por Onde Começar](#por-onde-começar)
  * [Ferramentas](#ferramentas)
  * [Livros](#livros)
  * [Q&amp;A](#q--a)
  * [Bookmarks](#bookmarks)
  * [Segurança](#segurança)
  * [Blogs técnicos de grandes empresas](#blogs-técnicos-de-grandes-empresas)

## Por onde começar

- [gutocarvalho](http://gutocarvalho.net/blog/2016/09/06/por-onde-iniciar-os-estudos-sobre-devops/) - Por onde iniciar os estudos sobre Devops?
- [origens](http://gutocarvalho.net/blog/2016/06/02/origens-da-cultura-devops/) - Origens da cultura Devops
- [perguntas comuns](http://gutocarvalho.net/octopress/2015/04/15/perguntas-pontuais-devops/)
- [quora](https://www.quora.com/What-are-the-best-resources-for-learning-about-DevOps) - What are the best resources for learning about Devops?
- [opsschool](http://www.opsschool.org/en/latest/) - Learn to be an operations engineer
- [jedi](http://www.jedi.be/blog/2010/02/12/what-is-this-devops-thing-anyway/) - What is this devops thing?
- [newrelic](https://blog.newrelic.com/2014/05/16/devops-name/) - Devops origins
- [newrelic-devops](https://blog.newrelic.com/2017/01/26/how-new-relic-does-devops/) - How New Relic does Devops

## Ferramentas

- [netdata](http://my-netdata.io/) - Ferramenta de monitoramento
- [hystrix](https://github.com/Netflix/Hystrix/wiki/How-it-Works) - Biblioteca do Netflix que implementa mecanismos de tolerância a falhas
- [sentry](https://sentry.io/welcome/) - Ferramenta de tracking de erros
- [chocolatey](https://chocolatey.org/) - Ferramenta de pacotes para windows
- [testinfra](https://testinfra.readthedocs.io/en/latest/) - Ferramenta para teste de infra
- [vault-ui](https://github.com/nyxcharon/vault-ui) - UI para o hashicorp vault
- [vault-web](https://github.com/AMeng/vault-web) - UI para o hashicorp vault
- [hygieia](https://github.com/capitalone/Hygieia) - Hygieia, um dashboard para agregar informações
- [flywaydb](https://flywaydb.org/) - Ferramenta para migração de bancos
- [linux-performance-tools](https://www.reddit.com/r/linux/comments/4x4smu/linux_performance_tools_full_version_draft/) - Excelente gráfico de ferramentas para profiling no Linux

## Livros

**The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win** (*Kevin Behr, George Spafford, Gene Kim*): Uma narrativa sobre a introdução de DevOps em uma empresa fícticia - que em certos momentos farão você cogitar a possibilidade do Gene Kim ser um espião trabalhando ao seu lado devido as grandes semelhanças com _qualquer empresa de TI_. Será impossível não se identificar de forma assustadora com os personagens do livro e dar pequenos sorrisos ao encontrar versões "da vida real" dos mesmos.

**The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations** (*Gene Kim, Jez Humble, Patrick Debois, and John Willis*): Está com a sensação de que o projeto unicórnio do Phoenix Project é pura ficcão? Não sabe como colocar o "Three Ways" em prática ou por onde começar? Este livro vai te ajudar a entender DevOps e ilustrar o case de grandes organizações completamente transformadas ou impulsionadas por DevOps, Lean, Agile, TPS e etc.

> **Citações**:

* *"In DevOps, we typically define our technology value stream as the process required to convert a business hypothesis into a technology-enabled service that delivers value to the customer."*

* *"Agile often serves as an effective enabler of DevOps, because of its focus on small teams continually delivering high quality code to customers."*

* *"DevOps isn’t about automation, just as astronomy isn’t about telescopes."*

* *"Because value is created only when our services are running in production, we must ensure that we are not only delivering fast flow, but that our deployments can also be performed without causing chaos and disruptions such as service outages, service impairments, or security or compliance failures."*

* *"Instead of a culture of fear, we have a high-trust, collaborative culture, where people are rewarded for taking risks."* 

**Release It!: Design and Deploy Production-Ready Software** (*Michael T. Nygard*): Porque a Amazon não fica indisponível na Black Friday e meu site não fica em pé com um aumento de 20% na carga por causa de um cupom novo? Qual o custo dessa indisponibilidade para a minha empresa? Como reverter essa situação? Porque a distância entre `feature-complete` e `production-ready` é tão grande? Se você *não* estiver familiarizado com os termos "Inversão de SLA", "Circuit Breaker", "Zero downtime deployments", "Falhas em cascata", "Bulkheads", "Unbalanced Capacities", "Unbounded Result Sets", leia-este-livro-agora.

> **Citações**:

* *"First, you need to accept that fact that despite your best laid plans, bad things will still happen. Second, realize that “Release 1.0” is not the end of the development project but the beginning of the system’s life on its own.*"

* *"Software design today resembles automobile design in the early 90s: disconnected from the real world."*

* *"Systems spend much more of their life in operation than in development—at least, the ones that don’t get canceled or scrapped do."*

* *"Don't avoid one-time development expenses at the cost of recurring operational expenses."*

* *"Team assignments are the first draft of the architecture. (See ​Conway’s Law​.) It’s a terrible irony that these very early decisions are also the least informed."*

* "*Denying the inevitability of failures robs you of your power to control and contain them."*

**Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment Automation** (*Jez Humble, David Farley*): Todas as funcionalidades foram implementadas, mas ainda serão necessárias semanas ou meses para seu software ser entregue. Como manter meu software sempre pronto para produção? Quais práticas utilizar? Quais não utilizar? Quais os benefícios? Embutir qualidade no processo de desenvolvimento e antecipar riscos é potencialmente o melhor investimento a ser feito no seu software!

> **Citações**:

* *"A working software application can be usefully decomposed into four components: executable code, configuration, host environment, and data."*

* *"Configuration management refers to the process by which all artifacts relevant to your project, and the relationships between them, are stored, retrieved, uniquely identified, and modified."*

* *"In software, when something is painful, the way to reduce the pain is to do it more frequently, not less."*

* *"It should always be cheaper to create a new environment than to repair an old one"*

* *"The repeatability and reliability derive from two principles: automate almost everything, and keep everything you need to build, deploy, test, and release your application in version control."*

**Site Reliability Engineering: How Google Runs Production Systems** (*Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Richard Murphy*): Coletanêa de artigos do time de SRE do Google, ilustrando a origem do termo, cultura, princípios e práticas internas, da formação de time até valiosas lições de como potencializar o feedback de sistemas em produção para o desenvolvimento - e sem deixar de lado conceitos como gerenciamento de mudança, monitoramento, planejamento de capacidade e resposta a incidentes.

> **Citações**:

* *"Software engineering has this in common with having children: the labor before the birth is painful and difficult, but the labor after the birth is where you actually spend most of your effort."*

* *"SRE is what happens when you ask a software engineer to design an operations team."*

* *"One could equivalently view SRE as a specific implementation of DevOps with some idiosyncratic extensions."*

* *"The most relevant metric in evaluating the effectiveness of emergency response is how quickly the response team can bring the system back to health — that is, the MTTR."* 

> **Notas**:

- Disponível gratuitamente [online](https://landing.google.com/sre/book/index.html)

- [Review completo por Fernando Ike](https://medium.com/@fernandoike/site-reliability-engineer-sre-b9440f02ca26)


## Q&A

## Bookmarks

- [continuous-integration](http://www.martinfowler.com/articles/continuousIntegration.html) - Artigo Martin Fowler integração contínua
- [continuous-delivery](http://martinfowler.com/bliki/ContinuousDelivery.html) - Artigo Martin Fowler "continuous delivery"
- [deployment-pipeline](http://martinfowler.com/bliki/DeploymentPipeline.html) - Artigo Martin Fowler sobre deployment pipeline
- [git-branching](http://pcottle.github.io/learnGitBranching/) - A interactive Git visualization tool to educate and challenge!
- [git-branching-successful](http://nvie.com/posts/a-successful-git-branching-model/) - Como trabalhar com branches
- [git-branching-merging](https://www.simple-talk.com/opinion/opinion-pieces/branching-and-merging-ten-pretty-good-practices/) - Branching and Merging: Ten Pretty-Good Practices
- [git-guide](http://rogerdudler.github.io/git-guide/) - Simple Git guide
- [serverless](http://zanon-io.github.io/serverless-presentation/slides/index.html#1) - Serverless presentation
- [puppet x ansible](http://gutocarvalho.net/blog/2016/06/02/puppet-vs-ansible/) - Comparativo Puppet x Ansible
- [highscalability](http://highscalability.com/) - Excelente site para referência em arquiteturas reais
- [scaling-nagios](http://www.slideshare.net/lozzd/leveling-up-monitoring-a-decade-of-automating-and-scaling-nagios)
- [devops-antipatterns](http://www.slideshare.net/fernandoike/dev-ops-anti-patterns) - Apresentação Fernando Ike
- [serverless-concepts](http://martinfowler.com/articles/serverless.html) - Artigo Martin Fowler
- [uber-postgresql-mysql](http://rhaas.blogspot.com.br/2016/08/ubers-move-away-from-postgresql.html) - Artigo sobre a mudança de SGDB do Uber
- [devops-enterprise](http://www.slideshare.net/marceloancelmo/devops-enterprise-devops-meetup-zurich) - Apresentação sobre a adoção de Devops em grandes corporações
- [spotify-scaling](http://www.slideshare.net/davidpoblador/scaling-operations-at-spotify) - Scaling operations at Spotify
- [remote-jobs-brazil](https://github.com/lerrua/remote-jobs-brazil) - Uma listagem de algumas empresas que aceitam trabalho remoto no Brasil
- [remote-jobs](https://github.com/lukasz-madon/awesome-remote-job) - Awesome remote jobs
- [htop-distilled](https://peteris.rocks/blog/htop/#memory-usage-virt-res-shr-mem) - Excelente explicação sobre as informações do utilitário htop
- [devops-periodic-table](https://xebialabs.com/periodic-table-of-devops-tools/) - "Tabela periódica" de ferramentas Devops
- [circuit-breaker](https://martinfowler.com/bliki/CircuitBreaker.html) - Artigo Martin Fowler sobre o mecanismo "circuit-break"
- [software-devlopers-readlist](https://stevewedig.com/2014/02/03/software-developers-reading-list/) - Lista com boas referências para leitura
- [10-monitoring-talks](https://techbeacon.com/10-monitoring-talks-every-developer-should-watch) - Lista de 10 apresentações sobre monitoramento que todo desenvolvedor deve assistir
- [12-factor](https://12factor.net/) - Metodologia para desenvolver aplicações modernas e escaláveis
- [ansible-windows](http://some.ops4devs.info/) - Artigo de automação com ansible no windows
- [terraform x cloudformation](https://www.terraform.io/intro/vs/cloudformation.html) - Comparação do Terraform com Cloudformation e outras ferramentas de nuvem
- [8practices-containers-apps](https://opensource.com/life/16/9/8-best-practices-building-containerized-applications) - Melhores práticas para construção de aplicações baseadas em containeres
- [learncodethehardway](https://learncodethehardway.org/) - Site para aprender a programar
- [12-licoes-performance-tests](http://www.bugbang.com.br/12-licoes-aprendidas-em-testes-de-performance-server-side/) - Lições aprendidas em testes de performance
- [destilando-jmeter](http://www.bugbang.com.br/destilando-jmeter-i-introducao-e-conceitos/) - Destilando Jmeter (ferramenta de teste de performance)
- [why-google-uses-single-repository](https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext) - Why Google Stores Billions of Lines of Code in a Single Repository
- [evolution-of-container-usage-netflix](http://techblog.netflix.com/2017/04/the-evolution-of-container-usage-at.html) - The Evolution of Container Usage at Netflix

## Segurança

- [dev-sec.io](http://http://dev-sec.io/) - Hardening Framework
- [devopssec](https://www.oreilly.com/learning/devopssec-securing-software-through-continuous-delivery) - Livro sobre segurança de sw com CD
- [awesome-devsecops](https://github.com/devsecops/awesome-devsecops) - Awesome list devopssec
- [selinux-seccomp](http://some.ops4devs.info/) - Análise de algumas ferramentas  de auditoria e segurança

## Blogs técnicos de grandes empresas

* [Airbnb Engineering](http://nerds.airbnb.com/)
* [Atlassian Developers](https://developer.atlassian.com/blog/)
* [Autodesk Engineering](http://cloudengineering.autodesk.com/blog/)
* [AWS Blog](https://aws.amazon.com/blogs/aws/)
* [Bitly Engineering Blog](http://word.bitly.com/)
* [Box Blogs](https://www.box.com/blog/engineering/)
* [Cloudera Developer Blog](http://blog.cloudera.com/blog/)
* [Dropbox Tech Blog](https://tech.dropbox.com/)
* [Engineering at Quora](http://engineering.quora.com/)
* [Ebay Tech Blog](http://www.ebaytechblog.com/)
* [Evernote Tech Blog](https://blog.evernote.com/tech/)
* [Etsy Code as Craft](http://codeascraft.com/)
* [Facebook Engineering](https://www.facebook.com/Engineering)
* [Flickr Code](http://code.flickr.net/)
* [Foursquare Engineering Blog](http://engineering.foursquare.com/)
* [GitHub Engineering Blog](http://githubengineering.com/)
* [Google Research Blog](http://googleresearch.blogspot.com/)
* [Groupon Engineering Blog](https://engineering.groupon.com/)
* [Heroku Engineering Blog](https://engineering.heroku.com/)
* [Hubspot Engineering Blog](http://product.hubspot.com/blog/topic/engineering)
* [High Scalability](http://highscalability.com/)
* [Instagram Engineering](http://instagram-engineering.tumblr.com/)
* [Intel Software Blog](https://software.intel.com/en-us/blogs/)
* [Jane Street Tech Blog](https://blogs.janestreet.com/category/ocaml/)
* [LinkedIn Engineering](http://engineering.linkedin.com/blog)
* [Microsoft Engineering](https://engineering.microsoft.com/)
* [Microsoft Python Engineering](https://blogs.msdn.microsoft.com/pythonengineering/)
* [Netflix Tech Blog](http://techblog.netflix.com/)
* [Paypal Developer Blog](https://devblog.paypal.com/category/engineering/)
* [Pinterest Engineering Blog](http://engineering.pinterest.com/)
* [Quora Engineering](https://engineering.quora.com/)
* [Reddit Blog](http://www.redditblog.com/)
* [Salesforce Engineering Blog](https://developer.salesforce.com/blogs/engineering/)
* [Slack Engineering Blog](https://slack.engineering/)
* [Spotify Labs](https://labs.spotify.com/)
* [Twilio Engineering Blog](http://www.twilio.com/engineering)
* [Twitter Engineering](https://engineering.twitter.com/)
* [Uber Engineering Blog](http://eng.uber.com/)
* [Yahoo Engineering Blog](http://yahooeng.tumblr.com/)
* [Yelp Engineering Blog](http://engineeringblog.yelp.com/)
* [Zynga Engineering Blog](https://www.zynga.com/blogs/engineering)
