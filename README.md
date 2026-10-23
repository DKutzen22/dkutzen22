<div align="center">

# Dalton Kutzen

### Small genomes. Reproducible workflows. Systems built to be understood.

Molecular biology @ BYU · Bioinformatics · Research software · Self-hosted infrastructure

[![Scientific computing](https://skillicons.dev/icons?i=py,r,bash,anaconda,git,githubactions&theme=dark)](https://skillicons.dev)

[![Infrastructure](https://skillicons.dev/icons?i=linux,docker,raspberrypi&theme=dark)](https://skillicons.dev)

</div>

---

## `01 / overview`

I study molecular biology and build tools for understanding biological systems.

My work connects bacteriophage genomics, scientific programming, and reproducible
research. I develop analysis workflows, build tools for the questions that come
after genome annotation, and manage the infrastructure underneath my projects.

I’m interested in the whole chain:

```text
biological question
    └── data + assumptions
        └── reproducible analysis
            └── interpretable results
                └── better questions
```

## `02 / project bench`

### Phantom · Phage-analysis workflow

A Snakemake-based workflow for organizing and automating phage genome analysis.

I'm developing Phantom to connect individual analysis tools into a more coherent,
inspectable research workflow—with an emphasis on reproducibility, useful reports,
and a clear path from input data to biological interpretation.

- Workflow development with Snakemake, Python, and Conda
- Phage genome annotation and comparative analysis
- Integration of analysis outputs into interpretable reports
- Ongoing work toward stronger QC, validation, and documentation

Current direction: extending beyond annotation toward phage-therapy-focused
genomic comparison, including safety screening and carefully evaluated
prioritization methods.

<!-- Add the Phantom repository link here. -->

### Phage analysis & visualization · R / Python

Tools for exploring what an annotation actually tells us.

I'm developing an R package for phage post-annotation analysis and visualization,
alongside Python tools that support genomic data processing and exploration.

- Working with genome annotations and comparative data
- Building visualizations that support biological interpretation
- Designing reusable analysis functions rather than one-off scripts
- Exploring integration with Phantom and command-line interfaces

Development goals: a documented, tested package, with Bioconductor conventions
informing the R package's design.

<!-- Add package repositories and example figures here. -->

### Homelab · Infrastructure as a learning environment

A working environment for self-hosted services, automation, and systems experiments.

- Linux server administration
- Virtual machines and containers with Proxmox and Docker
- Service deployment, configuration, and troubleshooting
- Repurposed hardware and Raspberry Pi projects
- Practical exploration of networking, security, and system reliability

The goal isn't just to get a service running. It's to understand the layers
underneath it—and make the next rebuild less mysterious.

<!-- Add infrastructure documentation or a homelab repository here. -->

## `03 / technical toolkit`

### Computational biology

Bacteriophage genomics · Genome annotation · Comparative genomics  
Post-annotation analysis · Genomic data visualization · Reproducible research

My focus is connecting computational outputs to biological questions:
what is present, how genomes differ, and which conclusions the data can support.

### Scientific programming

[![Programming tools](https://skillicons.dev/icons?i=py,r,bash&theme=dark)](https://skillicons.dev)

- Python for automation, data processing, and scientific tooling
- R for analysis, visualization, and package development
- Bash for command-line workflows and connecting tools

### Workflow & software development

[![Development tools](https://skillicons.dev/icons?i=git,github,githubactions,anaconda&theme=dark)](https://skillicons.dev)

- Snakemake for dependency-aware analysis workflows
- Conda for managing scientific software environments
- Git and GitHub for version control and open-source development
- GitHub Actions for workflow automation and CI
- Quarto for reproducible documents and technical communication

### Systems & infrastructure

[![Infrastructure tools](https://skillicons.dev/icons?i=linux,docker,raspberrypi&theme=dark)](https://skillicons.dev)

- Linux administration and command-line troubleshooting
- Proxmox virtualization and containerized services
- Self-hosted infrastructure and research-support automation
- Hardware selection, repurposing, and system integration
  
## `04 / skills under construction`

Tools I use, practices I'm strengthening, and subjects I'm studying aren't
all the same category.

My current development priorities:

| Area | Focus |
| :--- | :--- |
| Research software | Python package design, reusable APIs, and CLI development |
| Software quality | Automated testing, CI/CD, and maintainable documentation |
| R ecosystem | Package structure and Bioconductor development practices |
| Quantitative biology | Statistics, probability, linear algebra, and mathematical modeling |
| Machine learning | Understanding and evaluating applications to biological data |
| Infrastructure | Kubernetes, GitOps, and high-availability systems |
| Security & administration | Network visibility, vulnerability assessment, Intune, and Entra |

## `05 / how I build`

> Make it work. Understand why it works. Make it reproducible.

- Start with the biological question, not the tool list.
- Keep inputs, parameters, dependencies, and assumptions visible.
- Automate repeated work without hiding important decisions.
- Treat documentation and validation as part of the project.
- Prefer reusable components over collections of disconnected scripts.
- Build for the next person—including future me.

## `06 / beyond the bench`

I love poetry, electronics, indie and folk music, anime, 
and finding another use for a computer someone else retired.

Different projects. Same habit of taking things apart to understand
how they fit together.

---

<div align="center">
  <sub>Reading genomes. Writing tools. Keeping notes.</sub>
</div>
