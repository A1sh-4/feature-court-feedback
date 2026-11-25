<p align="right"><a href="README.md">日本語</a> | <b>English</b></p>

# Feature Court — feedback

**Feature Court** is a free tool that helps a product team decide whether a feature is worth building. Everyone scores the feature on their own, then the court gives one verdict: **Build**, **Don't build** or **Prototype first**. It also shows where the team disagrees.

🌐 **Website:** https://feature-court.a1sh-4.workers.dev
👤 **Operator:** AISH ([@A1sh-4](https://github.com/A1sh-4))

This repository is the public place to report problems and suggest improvements. The app's source code is kept separately.

## How to give feedback

1. Look at the [open issues](https://github.com/A1sh-4/feature-court-feedback/issues) first. If someone has already reported the same thing, add a 👍 or a comment there.
2. Otherwise, [open a new issue](https://github.com/A1sh-4/feature-court-feedback/issues/new/choose) and choose a form:

| Form | Use it for |
|---|---|
| 🐞 **Bug report** | Something is broken, looks wrong, or doesn't work on your device |
| 💡 **Idea or improvement** | A new feature, a change to the scoring or weights, or a design suggestion |
| 🌐 **Copy or translation** | Japanese or English text that is wrong, unclear or unnatural |
| ❓ **Question** | Anything else about how Feature Court works |

You can write in **English or Japanese**.

## Examples

Use these as a guide to filling in the forms. They are all **made up**.

<details>
<summary>🐞 Bug report example</summary>

> **Title:** [Bug] Moving a slider on a phone shifts the page sideways
>
> **What happened?**
> In solo mode, dragging the fourth question's slider with a finger moves the whole page a little to the side.
>
> **What did you expect?**
> Only the slider moves; the page stays still.
>
> **Steps to reproduce**
> 1. Open the site on a phone
> 2. Press "Judge solo, right now"
> 3. Drag the fourth slider to the right
>
> **Where?** Solo mode
> **Device and browser:** iPhone 15 · Safari 18
> **Language and theme:** English · Light

</details>

<details>
<summary>💡 Idea or improvement example</summary>

> **Title:** [Idea] Let the facilitator set a scoring deadline
>
> **What problem would this solve?**
> Team members don't know when they need to score by, so the verdict takes days.
>
> **Your idea**
> When opening a case, let the facilitator set a deadline, and show it on the case room and in the reminder message.
>
> **Type:** New feature
> **Anything else?** Closing the case automatically at the deadline would be even better.

</details>

<details>
<summary>🌐 Copy or translation example</summary>

> **Title:** [Copy] "In session" on the case room is unclear
>
> **Language:** English
> **Where is the text?** The top line of the case room (`$ case #… · in session`)
>
> **Current text:** in session
> **Suggested text:** open for scoring
> **Why?** A first-time visitor can't tell what "in session" means they should do.

</details>

<details>
<summary>❓ Question example</summary>

> **Title:** [Question] Can the weights be changed later?
>
> **Your question**
> I opened a case and now want to change the weights. Can I still change them after someone has submitted their scores?
>
> **Privacy check:** ✅ I didn't include case links, facilitator links, real names or confidential information.

</details>

## Please don't post private information

Issues are **public**. Don't paste case links, facilitator links, real names or anything confidential. A case link lets anyone who has it see that case.

- **Privacy or data request** (for example, deleting a case): open a *Question* that says only what you need, with no links or personal details. We'll arrange a private way to continue. Remember that the facilitator can delete a case at any time, and every case is deleted automatically 30 days after its last activity.
- **Security issue:** don't open an issue. Follow [SECURITY.en.md](SECURITY.en.md).

## What happens next

AISH reads every issue. Labels show the status. Fixes go live on the website automatically once they ship. This is a small personal project, so replies may take a few days.
