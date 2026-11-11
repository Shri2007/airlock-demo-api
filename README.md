# airlock-demo-api

API documentation issues, including two benign keyword-filter examples for Airlock.

This is a small, intentionally harmless public test repository for
[Airlock](https://github.com/Shri2007/airlock-archil). Its issues are authored
sample data, and it contains no application code or real credentials.

In Airlock's viewer, enter `Shri2007/airlock-demo-api` and select **Scan repo**.
Airlock fetches this README and the issue text, then runs its own sample
issue-summarizer against variations of that setting. Airlock plants its own
malicious issue and fake BAIT credentials inside disposable workspaces.
The tool under test belongs to Airlock, not to this repository.

Two benign issue reports deliberately mention password or maintainer, so the default keyword filter should skip two reports.
