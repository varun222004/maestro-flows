# Maestro Flows 🎭

Mobile and web UI automation flows built with Maestro Studio.
Covers real-world user journeys across popular platforms — login, signup, search, and more.

---

## 📁 Structure

maestro-flows/
├── spotify/          # Spotify web automation flows
├── amazon/           # Amazon web automation flows (coming soon)
├── recordings/       # Screen recordings of each flow execution
└── screenshots/      # Screenshots captured during flows

---

## 🎵 Spotify Flows

### Signup Flow
Tests the complete Spotify account creation journey on web browser.

**Steps covered:**
- Navigate to open.spotify.com
- Dismiss cookie consent
- Click Sign Up
- Enter email address
- Set password
- Enter display name and date of birth
- Assert successful account creation

**File:** `spotify/signup_flow.yaml`
**Recording:** `recordings/spotify_signup.mp4`

---

### Login Flow
Tests the Spotify login journey for an existing user.

**Steps covered:**
- Navigate to open.spotify.com
- Click Log In
- Enter email credentials
- Enter password
- Assert successful login and homepage load

**File:** `spotify/login_flow.yaml`
**Recording:** `recordings/spotify_login.mp4`

---

### Search Flow
Tests the Spotify search functionality post login.

**Steps covered:**
- Complete login flow
- Navigate to Search
- Input search query
- Assert search results appear
- Tap on artist result
- Assert artist page loads

**File:** `spotify/search_flow.yaml`
**Recording:** `recordings/spotify_search.mp4`

---

## 🛒 Amazon Flows

> Coming soon — Search flow and Add to Cart flow

---

## 🛠 Tools Used

| Tool | Purpose |
|------|---------|
| Maestro Studio | Flow authoring and execution |
| Chromium Web Browser | Test environment |
| YAML | Flow scripting language |

---

## ▶ How To Run

1. Install Maestro Studio
2. Open any `.yaml` file in Maestro Studio
3. Click **Run Locally**

---

## 👨‍💻 Built By

**Varun V** — SDET Intern @ LYBL | Game Tester @ Ixie Gaming

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/varun-v-3448a6259)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/varun222004)
