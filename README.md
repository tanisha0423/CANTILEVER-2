# Phishing Page Simulation using Zphisher

This project demonstrates a phishing page simulation using the **Zphisher** tool.  
It was created as part of my Cybersecurity Internship at Cantilever.

The objective of this task is to simulate a phishing attack in a controlled and test environment to understand how attackers operate, and to use this knowledge for training and awareness purposes.

---

## Steps to Run

1. Open Google Cloud Shell and run:
  ```bash
   git clone https://github.com/htr-tech/zphisher.git

```
2. Navigate into the directory:
  ```bash
  cd zphisher
  chmod +x *
```
3. Run the tool:
  ```bash
bash zphisher.sh
   ```
4. Choose the phishing page category (e.g., Instagram, Facebook, Google) from the interactive menu. I chose Spotify.

5. Select the link generation method (e.g., Localhost or Ngrok) to host the phishing page. I chose Localhost.

6. Share the generated URL in a simulated test environment to observe how credentials could be harvested.

In this test scenario, a Spotify login page was generated using Zphisher.
When I entered a test username and password into the page, the credentials were captured and displayed in the test environment terminal/record.

This demonstrated how attackers can trick users into entering sensitive information on a fake page, and how such data is immediately visible to the attacker’s terminal.

- `commands.md` — contains the commands I ran.  
- `output.pdf` — contains exported output and screenshots of the test run.

