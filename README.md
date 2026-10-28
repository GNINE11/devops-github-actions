# Docker e GitHub Actions

Exercício prático da disciplina de DevOps da UFLA, utilizando FastAPI, Docker e GitHub Actions para automatizar a construção e publicação de imagens no GHCR.

## DevSecOps

O pipeline utiliza Gitleaks para detectar segredos, SonarCloud para análise estática, Trivy para verificar vulnerabilidades e Syft para gerar o SBOM.

Vulnerabilidades HIGH e CRITICAL com correção disponível, segredos detectados e falhas no Quality Gate bloqueiam o pipeline. As LOW e MEDIUM são registradas em relatórios.

A imagem só é publicada no GHCR após a aprovação das verificações.

## Evidências

[Relatório do trabalho prático](docs/evidencias.pdf)