1. Make sure you have: `export JULIA_PKG_USE_CLI_GIT=true`
2. Make sure you have your [SSH public key setup for your github account](https://docs.github.com/en/authentication/troubleshooting-ssh/error-permission-denied-publickey#verify-the-public-key-is-attached-to-your-account)
3. In the julia pkg REPL, do: `registry add git@github.com:lemieux-lab/LabRegistry.git`
4. You can verify with: `registry status`
