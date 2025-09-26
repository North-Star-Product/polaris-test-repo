🧪 Polaris Test Repo

This repo exists only for QA testing Polaris.
Use it to create simple code changes and pull requests so we can verify the Polaris integration.

✅ How to Run Your Test

Clone this repo to your machine
  git clone https://github.com/<your-username>/polaris-test-repo.git
  cd polaris-test-repo

Create a branch for your test
  git checkout -b feature/my-test-change

Make a small change
  Edit hello.ts or example.js

Add a line like:
  // TODO: fix this later
  let unusedVariable = 123;

Save and commit:
  git add .
  git commit -m "Test change for Polaris QA"
  git push origin feature/my-test-change


Open a Pull Request
Go to the repo on GitHub
You’ll see a banner to “Compare & pull request” → click it
Title it: QA Test – Troy
Leave the description empty or write a note if you want

Check Polaris
Open the QA app:
👉 https://north-star-product-polaris-qa.vercel.app
Click “Import Code Changes”
You should see your PR appear
Confirm Polaris shows issues (Critical/High/Other) and updates the Risk Score

📝 Notes

Keep changes small (1–2 lines)
Don’t worry about breaking code — this repo is only for testing
If your PR shows up in Polaris, 🎉 success!
