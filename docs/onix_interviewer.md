# Onix interviewer guide

## Goals as the interviewer

1. Make the candidate feel comfortable
2. Assess communication ability - how well do they explain their thought
   process? Do they use the tools to communicate ideas effectively?
3. Assess human skills - empathy, teamwork, kindness, curiosity, leadership,
   grit, etc.
4. Assess technical skills - can they demonstrate the ability to write software,
   debug problems, and design systems?

## Before the interview

1. Review the core [README.md](./README.md) so you're on the same page with the
   candidate
2. Review the candidate's resume. Have it open for reference.
3. Create a git branch for the candidate (named `candidate/first.last`) on the
    `onix-net/tech-interview-private` repo. If the branch already exists, reuse
    it. a. If you're running VSCode locally, it's recommended to use a
    devcontainer (`Command palette > Dev Containers: Open folder in container`)
    or at the least launch a dedicated IDE window for the interview. This helps
    keep client work separate from the interview. b. If using the browser-based
    editor, open the github repo in a new tab, press `.` to launch the editor,
    and create a branch via the UI (left status bar) or (`Command palette > Git:
    Create Branch`).
4. Install the repo's recommended extensions. Your coding environment should be
   ready to go.
5. Start a Live Share session ([instructions
   here](https://code.visualstudio.com/learn/collaboration/live-share#_get-started-with-live-share)
   or `Command palette > live Share: Start Collaboration Session`). Copy the
   Live Share link into [scratch.md](../scratch.md) so you have it handy.
6. (Optional) Navigate to [excalidraw](https://excalidraw.com/), create a live
   collaboration session, and copy the session link into the
   [scratch.md](../scratch.md).

## During the interview

1. Follow the format outlined in the [README.md](./README.md).
2. Find the candidates's depth on a given question but provide help if they're
   stuck for any more than a couple minutes.
3. For a coding question, paste the question into the editor as a comment. This
   helps the candidate stay focused on the problem and not the question.
4. Keep tabs on the time. An interview moves fast and it's easy to get carried
   away in intros or the initial question.
5. Get comfortable with the live share functionality. You have tools to bring
   their attention to a specific file/line, follow along where the candidate
   navigates, and to add in-session comments that you may be saving for
   discussion later.
6. If using excalidraw, use the laser pointer (tool on the far right) to help
   draw attention to specific areas of the diagram.

## After the interview

1. If you used excalidraw, save the source contents to disk (it'll download an
   `.excalidraw` file) and copy this to the repo (the root or potentially next
   to source code they wrote). If you closed excalidraw, you can likely reopen
   the tab or launch it again from the link you saved in `scratch.md`.
2. Ensure you're working on a branch, commit the work from the session, and push
   it to the remote repo. This is where it should stay archived, on that branch
   of the private repo, for any follow up review. Don't merge to `main`.
