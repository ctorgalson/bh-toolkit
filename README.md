# BH Toolkit

This repo contains various small utilities. Use at your own risk!

## GNB: giti(hub) new branch

This tool makes it easy to create a new git branch of the form
`{issue number}-{issue-title}` where spaces and (some) punctuation characters
are replaced by dashes, and all text is lowercased. It's designed to be used
with Github's issue titles which take the form `#{issue number} {issue title}`.

For example, given `gnb 'Fix typo on about page #3445'`, gnb will issue the
command `git checkout -b '3445-fix-typo-on-about-page`. For more information,
run the command with no arguments (e.g. `gnb`).
