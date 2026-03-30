
RetinaScan is an experimental AI-assisted retinal image analysis prototype designed to explore how retinal fundus photographs may reveal biomarkers associated with systemic and ocular health.
The long-term goal of the project is to develop a tool that analyzes retinal images and integrates them with basic patient screening information to identify potential retinal biomarkers, suggest possible condition patterns, and support clinicians' decision-making workflows.
This repository functions as the central storage and development hub for the RetinaScan prototype.
---

# Repository Purpose

This repository is used as a shared file bank for:

- RetinaScan prototype versions
- Research documents and notes
- Retinal fundus datasets
- Development experiments
- Backend and analysis code

The goal is to maintain a clear and organized structure for collaboration as the project evolves.

---

# Current Project Stage

RetinaScan is currently an **educational prototype and product-design project**.  

The system is **not a validated medical tool and does not provide diagnoses or treatment recommendations.**

The focus at this stage is on:

- prototype development
- workflow design
- biomarker detection concepts
- backend architecture
- dataset exploration

---

## Planned Development Areas

Key development goals include:

- Building a secure backend for image analysis
- Organizing retinal datasets for experimentation
- Developing biomarker detection workflows
- Improving the prototype user interface
- Building documentation and research infrastructure


---

## Contributors

Founder: Ethan Stimson  

Additional contributors and collaborators will be added as the project develops.

---

## GitHub Authentication Methods

> **Note:** Password-only sign-in is no longer supported for Git operations on GitHub. See below for the methods that are currently supported.

As of March 2026, GitHub supports the following authentication methods depending on how you access it. See the [official GitHub documentation](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github) for full details.

### Signing in to GitHub.com (browser)

You can sign in to your GitHub account in the browser using:

- **Username and password** – still supported for web sign-in. GitHub recommends using a strong, unique password and enabling 2FA.
- **Social login** – sign in with Google or Apple (if linked to your account).
- **Two-factor authentication (2FA)** – strongly recommended and now mandatory for many GitHub users. Options include a TOTP app, SMS, security key (WebAuthn), or GitHub Mobile.
- **Passkey** – a passwordless option that satisfies both password and 2FA requirements in a single step. See [About passkeys](https://docs.github.com/en/authentication/authenticating-with-a-passkey/about-passkeys).
- **SAML single sign-on** – for members of organizations or enterprises that require SSO through an identity provider (IdP).

### Git operations (command line / HTTPS)

Password-based authentication **has been removed** for Git over HTTPS. When Git prompts for a password, you must use one of:

- **Personal Access Token (PAT)** – classic (`ghp_`) or fine-grained (`github_pat_`). Generate one at *Settings → Developer settings → Personal access tokens*. Use it in place of your password.
- **GitHub CLI** (`gh auth login`) – authenticates via your browser or a PAT and caches credentials automatically.
- **Git Credential Manager** – a cross-platform helper that stores tokens securely on your machine.

### Git operations (SSH)

- **SSH key** – generate an SSH keypair and add the public key to your GitHub account under *Settings → SSH and GPG keys*. No password or token needed for day-to-day Git use.

### API and automation

- **Personal Access Token (PAT)** – for personal scripts and tooling.
- **OAuth token** (`gho_`) – issued by OAuth Apps acting on behalf of a user.
- **GitHub App token** (`ghs_`, `ghu_`) – for apps that act on behalf of installations or users.
- **`GITHUB_TOKEN`** – automatically available inside GitHub Actions workflows.

---

## Disclaimer

RetinaScan is an educational and experimental prototype.  
It is **not a medical device**, has **not been clinically validated**, and should **not be used for medical decision making. YET ;)**

---

Ethan Stimson  
March 2026
