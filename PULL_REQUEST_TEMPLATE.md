<!--
IMPORTANT: We applaud pull requests, they excite us every single time. As we have an obligation to maintain a healthy code standard and quality, we take sufficient time for reviews. Please do create a separate pull request per change/issue/feature; we will ask you to split bundled pull requests.
-->

**Fixes #0000**

**Changes proposed in this pull request:**
<!-- fill this out, mention the pages and/or components which have been impacted -->

**Reviewers should focus on:**
<!-- fill this out, ask for feedback on specific changes you are unsure about -->

**Screenshot**
<!-- include an image of the most relevant user-facing change, if any -->


**Necessity**

- [ ] Has the problem that is being solved here been clearly explained?
- [ ] If applicable, have various options for solving this problem been considered?
- [ ] For core PRs, does this need to be in core, or could it be in an extension?
- [ ] Are we willing to maintain this for years / potentially forever?

**Confirmed**

- [ ] Frontend changes: tested on a local Flarum installation.
- [ ] Backend changes: tests are green (run `composer test`).
- [ ] Core developer confirmed locally this works as intended.
- [ ] Tests have been added, or are not appropriate here.

**Required changes:**

- [ ] Related documentation PR: (Remove if irrelevant)
- [ ] Related core extension PRs: (Remove if irrelevant)

---

Do not edit below here! This is documentation for review / merge processes

### Implementation Review Criteria

- Adheres to our conventions or can be patched up easily after merging, follows proper code style.
- Are there any implementation details that could be done better through alternate technologies/technical approaches?
- Does not touch any lines outside of the intended changes, eg through formatting or compilation.
- If the changes are to code intended as a public API, has a proper doc block been included?

### Merge Time!

If all of the above are met, **any** core developer may merge this PR. If the PR is authored by a core developer, they should probably be the ones to merge it.

- Merging:
  - GitHub offers several ways to merge a PR. Choose between the following strategies:
    - **Merge** when the PR branch consists of atomic, well-described commits that are nice to have in the version history.
    - **Squash** when lots of cleanup commits have accumulated. Please make sure to write a [good commit message](https://chris.beams.io/posts/git-commit/) for the squash commit.

- After merging:
  - Make sure the *issue* (if none exists, the PR - but not both) belongs to the appropriate milestone. PRs in extensions cannot be assigned to core milestones, so assign it to the current release's project board instead.
  - Close all relevant issues (*if* they are closed completely).
  - Check for follow-up tasks:
    - Merge related PRs (language files, extensions, documentations)
    - Documentation updates
  - Create issues for further follow-up tasks, if necessary.

