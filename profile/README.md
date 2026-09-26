# Utilvo

**Privacy-first browser engineering for local data processing.**

Utilvo develops browser-based software and research focused on client-side computation, privacy-preserving architectures, WebAssembly, and secure browser runtimes.

Our work explores how data-intensive applications can perform processing locally on the user's device while minimizing unnecessary server-side data exposure.

---

## Research

### Privacy-Preserving Client-Side Information Processing
A technical study of browser-based local processing architectures using WebAssembly, Web Workers, and client-side execution.

The research includes implementation materials, benchmark methodology, and reproducibility resources.

- **Research repository:** [utilvo-platform/privacy-preserving-client-side-processing](https://github.com/utilvo-platform/privacy-preserving-client-side-processing)
- **Preprint Archive (Zenodo DOI):** [10.5281/zenodo.22975427](https://doi.org/10.5281/zenodo.22975427)
- **Preprint Archive (Figshare DOI):** [10.6084/m9.figshare.34003734](https://doi.org/10.6084/m9.figshare.34003734)

---

## Engineering Principles

Utilvo projects generally follow these principles:

- **Client-side processing** — perform computation locally whenever practical.
- **Data minimization** — avoid sending user data to servers when server processing is unnecessary.
- **Reproducibility** — document implementations, benchmarks, and methodology.
- **Explicit security boundaries** — document what the architecture protects and what it does not.
- **Open technical documentation** — make implementation decisions inspectable where possible.

---

## Applications

- **PDF Tools** — Browser-based PDF processing designed around local execution.  
  [https://utilvo.com/pdf-tools](https://utilvo.com/pdf-tools)

- **Calculators** — Browser-based mathematical and engineering calculators.  
  [https://utilvo.com/calculators](https://utilvo.com/calculators)

- **Unit Converter** — Physical and SI unit conversion utilities.  
  [https://utilvo.com/unit-converter](https://utilvo.com/unit-converter)

---

## Open Source

Public repositories contain implementations, experiments, benchmarks, and supporting research materials.

Repositories are published when they contain sufficient implementation or documentation to be independently inspected or reproduced.

---

## Security & Privacy

Privacy claims are evaluated within an explicit technical threat model.

Client-side processing can prevent a server from receiving the processed source data, but it does not by itself protect against a compromised device, malicious browser extensions, compromised dependencies, or malicious code executed in the browser environment.

Security documentation and project-specific limitations are provided in each repository.

---

## Links

- **Website:** [https://utilvo.com](https://utilvo.com)
- **GitHub:** [https://github.com/utilvo-platform](https://github.com/utilvo-platform)
- **Research:** [https://github.com/utilvo-platform/privacy-preserving-client-side-processing](https://github.com/utilvo-platform/privacy-preserving-client-side-processing)
- **Facebook:** [https://www.facebook.com/tilvo](https://www.facebook.com/tilvo)
