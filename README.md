# Socratic Tutor by Mumbai AI Lab

Claude answers questions. A tutor asks them. This plugin makes Claude tutor the way a good teacher does: it finds out what you have tried, asks the one question that lets you take the next step, and gives you the answer only after you have made an attempt and asked for it. You still do the reasoning, so what you learn stays learned.

It was built by Mumbai AI Lab, a student-run programme in Navi Mumbai founded by Rayhaan Khan. Our sessions teach students to use AI as a questioner rather than an answer machine, and the method in this plugin is the one we use.

## What it does

The plugin contains two skills and no connectors. It adds instructions to Claude and makes no other change.

- **socratic-tutor** loads when you ask for help with homework, a problem set, a proof, a concept, code you are debugging, or an essay you are writing. Claude asks what you have tried, finds the one thing blocking you, and asks one question per turn. Hints escalate when you stall: a nudge, then the relevant concept, then a worked partial step, then the full solution. As you get steps right on your own, the hints fade. Subject notes cover mathematics, physics, chemistry, biology, programming, writing, languages, and history and economics.
- **quiz-me** loads when you say "quiz me", "test me" or "check whether I understood". Claude asks one question at a time, grades your answer, and ends with your score and the two ideas to review.

## Install

- **claude.ai and the Claude desktop app:** open Customize > Plugins and search the directory for "Socratic Tutor". Before the plugin is listed, choose Add > Add marketplace, paste `https://github.com/Rayhaan1345/socratic-tutor`, then install Socratic Tutor by Mumbai AI Lab.
- **Claude Code:** run `/plugin` and search for "Socratic Tutor". Before the plugin is listed, run `/plugin marketplace add Rayhaan1345/socratic-tutor`, then `/plugin install mailab-socratic-tutor@mumbai-ai-lab`.

Once installed, the skills load on their own when a message fits them. You do not need to switch anything on.

## Try it

1. "I have to solve 2x^2 - 5x - 3 = 0 for homework. Can you help?"
2. "My Python loop prints the wrong total. Here is the code: ..." (paste your code)
3. "Can you look at the introduction of my essay? I don't think it works." (paste the introduction)
4. "I got x = 11/2 for 2x + 4 = 7. Is that right?"
5. "Quiz me on Newton's laws, five questions."

## Getting the answer

Say "just tell me" at any point and Claude gives the full answer, followed by one question to check you can reproduce the key step. If you say you are out of time, Claude answers directly. If you ask whether your answer is right, Claude tells you first, then helps you find the mistake if there is one. Factual questions, definitions and syntax are answered plainly; the questioning is for reasoning. Teachers and parents who say they are preparing to help someone get a direct explanation and the method to use with the learner.

## What it will not do

It will not sit a graded test or exam for you while it is in progress. It will work through the method with you afterwards. Past papers and practice questions are fine.

## Why it works this way

- In a field experiment with nearly 1,000 high school mathematics students, those given an unrestricted chatbot during practice scored 17% lower on a later exam taken without it than students who never had access; a tutor version built to give hints instead of answers largely removed that harm ([Bastani et al., PNAS, 2025](https://papers.ssrn.com/abstract=4895486)).
- A randomised trial in a Harvard physics course found that an AI tutor built on active learning, managed cognitive load and step-by-step scaffolding more than doubled learning gains over an in-class active-learning lesson ([Kestin et al., Scientific Reports, 2025](https://pmc.ncbi.nlm.nih.gov/articles/PMC12179260/)).
- Recalling an answer strengthens memory more than rereading it, which is why quiz-me asks before it tells (Roediger and Karpicke, Psychological Science, 2006).
- The rules on one question per turn, fading hints and asking for a summary at the end follow the principles of active learning, cognitive load, adapting to the learner and metacognition set out in [Google's pedagogical framework for AI tutoring](https://services.google.com/fh/files/misc/googlespedagogicalframework.pdf).

## Privacy and data

The plugin is instructions only. It runs no code, connects to no server, collects no data and sends no data anywhere. It does not ask for personal details beyond your class or level, and it keeps no record of you between conversations. Your conversation is handled by Claude under Anthropic's own terms and privacy policy, as it would be without the plugin. The full privacy policy is in [PRIVACY.md](https://github.com/Rayhaan1345/socratic-tutor/blob/main/PRIVACY.md).

## Troubleshooting

- **Claude solved the problem instead of asking.** Say "tutor me through this" or mention it is homework. The skill loads when the message reads as studying; a bare equation can read as a request for the answer.
- **Claude keeps asking when you want the answer.** Say "just tell me". It will.
- **No change after installing.** Check that the plugin is enabled under Customize > Plugins, then start a new conversation.
- **A question was too hard or too easy.** Tell Claude your class or year. It uses that level from then on.

## Feedback and support

Open an issue at [https://github.com/Rayhaan1345/socratic-tutor/issues](https://github.com/Rayhaan1345/socratic-tutor/issues) to report a problem, suggest a subject note, or ask a question. Mumbai AI Lab maintains the plugin and reads the issues.

## For contributors

The subject notes in `skills/socratic-tutor/references/subject-notes.md` are where the plugin improves: add a blocker you have seen students hit and the question that moved them past it. Run `claude plugin eval .` from the plugin folder to check that a change kept the behaviour; the cases are in `evals/`. Raise `version` in `.claude-plugin/plugin.json` with a new release.

## Licence

MIT. See [LICENSE](LICENSE).
