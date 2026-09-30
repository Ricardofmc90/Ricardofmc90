<h1 align="center">Ricardo Felipe</h1>

<p align="center">
  <b>DevOps & Cloud Engineer</b><br>
  Infraestrutura como código, CI/CD e Kubernetes em Azure e AWS
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ricardofmc/"><img src="https://skillicons.dev/icons?i=linkedin" height="40" alt="LinkedIn"></a>
  <a href="mailto:ricardofmc90@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="40" alt="Gmail"></a>
</p>

---

### Sobre mim

```hcl
module "ricardo_felipe" {
  source = "github.com/ricardofmc90/ricardofmc90"

  role     = "DevOps & Cloud Engineer"
  clouds   = ["azure", "aws", "gcp"]
  pipeline = ["build", "test", "sonarqube", "veracode", "deploy-aks"]
  learning = ["aws organizations"]

  practices = [
    "módulos terraform reutilizáveis, versionados por tag",
    "um state por aplicação e ambiente",
    "workflows de ci/cd reutilizáveis no github actions",
  ]
}
```

### Stack

<img src="https://skillicons.dev/icons?i=terraform,azure,aws,gcp,docker,kubernetes,githubactions,git,py,mongodb&theme=dark" alt="Terraform, Azure, AWS, GCP, Docker, Kubernetes, GitHub Actions, Git, Python, MongoDB">
