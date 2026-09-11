# KnowIt Backlog

## Bugs
- [ ] My Classes page loads differently from the other pages
- [ ] Progress doesn't actually save in environments — check both free and premium users
- [ ] Subject Comparison widget still shows Learning Plans as if they were Subjects
- [ ] Subject Comparison hover tooltip shows "Value: n" instead of "Lesson Count: n"
- [ ] Multiplayer: full or 1hr+ old rooms aren't cleaned up — remove them
- [ ] Multiplayer: exiting a room still counts the user as present, inflating the room count
- [ ] Some personalized-learning lessons fail to render graphs/visualizations — verify all animations/graphs render
- [ ] Exam generation fails: Edge Function returns a non-2xx status code
- [ ] Tab favicon doesn't match the actual site logo
- [ ] Community posts layout is broken (hearts, comments, trash icon)
- [ ] Payment history is locked behind premium — should not be, fix/unlock
- [ ] Quick learn multiple choice options show false no matter what, even if you got a correct answer

## Environments
- [ ] Verify environment invites actually work
- [ ] Verify other users' actions in a shared environment show up live for everyone, and persist
- [ ] Add per-user colors (Google Docs-style) showing where each user is, including a colored wrapper/outline around the tool/element they're using
- [ ] Teachers should be able to create environments
- [ ] Build tutor-specific functionality
- [ ] Add export of environment activity data (who did what)

## Multiplayer / Competitions
- [ ] Add competitions to multiplayer, with a profile-page box showing which ones a user has won
- [ ] Verify multiplayer works end-to-end
- [ ] Verify users can actually get into classes

## Community
- [ ] Add a way to invite someone to a community
- [ ] Show which users are currently in a community
- [ ] Add community settings controlling who can create new channels, etc.
- [ ] Allow private community posts (visible only to friends), sorted most-recent-first

## Profile / Social
- [ ] Add fuzzy search + auto-suggested closest friends in "Add Friends"
- [ ] Add achievements
- [ ] Add a button to add a friend in the hover card and the profile view
## Curriculum / Lessons — Content Coverage
- [ ] Build out actual lesson content in /lessons
- [ ] Support additional curricula: IB (MYP and DP), AP, GCSE, A-Levels, Le Bac, others
- [ ] Use PirateIB repo (git.pirateib.sh/pirateIB) for IB DP past papers — free, past papers only
- [ ] IB MYP: add Personal Project assistance (creating a project, step-by-step guidance, design help, feedback)
- [ ] IB DP: add CAS, EE, TOK, IA support

## Curriculum / Lessons — Learning Plan Creation
- [ ] Let students specify details when making a learning plan, including current grades (e.g. a 9th grader building a plan around their actual grades)
- [ ] Allow extending a plan timeline beyond 6 months
- [ ] Adapt next lessons based on solved time — replace the countdown with a count-up timer that adjusts future lessons based on performance
- [ ] Instead of static question sequencing, generate each question on demand until the user demonstrates understanding, then base the next lesson's content/questions on how many attempts it took (Elicėjus-style adaptive approach)
- [ ] Add final tests for each topic
- [ ] Quick learn - make it so it generates questions more about the mathematical answers and no theory questions in the quizzes

## Lesson Experience
- [ ] Don't paste all theory at once — add a "read on" button so users progress through content in chunks
- [ ] Add an "ask AI" button in each section for when a user doesn't understand
- [ ] Add callout boxes: common mistakes, warnings, tips
- [ ] Link book pages inline (hover-to-preview like AI chatbot citations, with the relevant text highlighted in the book)
- [ ] Quizzes: add flashcards and more interactive formats beyond typing/multiple-choice — reference RevisionDojo and Brilliant for hands-on lesson design
- [ ] Design original cheatsheets
- [ ] Add FreeCodeCamp-style roadmap workshops into learning plans (e.g. "write a proof" exercise in a math plan)
- [ ] After a career learning plan is completed, show relevant interview questions at the end

## CoWorker / AI
- [ ] Add web search to CoWorker so it can pull relevant data
- [ ] Add whatever else an agent needs to be useful (browsing, graphing, normal equation rendering, warning blocks like .md notes and stuff)
- [ ] Allow AI to access user data (grades, etc.) where relevant
- [ ] Add guardrails: restrict use to studying/help with what Gamma offers (our tools/connections) — prevent misuse
- [ ] Make chats account-based, not device-based, so any device can access a user's chat history
- [ ] Refine AI output prompts to avoid generic filler ("here is x", "that's an interesting question," etc.)
- [ ] If a user's message is long, the input box should expand downward
- [ ] Teachers don't care about levels/XP — adjust what's shown to teacher-facing views accordingly

## General-Purpose Tools
- [ ] Add humanizer, plagiarism checker, and AI detector

## IQ Test
- [ ] Refine to MENSA-level rigor using real research/public data
- [ ] Add anti-cheating: prevent leaving the page, require camera on to confirm focus

## Nirala
- [ ] Expand the notes embed box in the library — too much empty space currently

## Quick Learn
- [ ] Add a "teach baby Jojo" mode — user teaches the AI instead of being taught

## Integrations
- [ ] Add missing connections: Spotify, Gmail, Google Calendar, Google Drive

## Billing / Marketplace
- [ ] Settings → Billing: add PayPal linking so users can sell notes on the marketplace
- [ ] Add textbook privacy (visible only if self-posted)
- [ ] Add favoriting (TikTok-style saved folder) and likes (separate count + list) for textbooks
- [ ] Add settings to a book (per user, so a user can modify if it's still private or public and modify information about it later

## Notifications
- [ ] Currently email-only — build actual in-app notifications

## Onboarding
- [ ] Build onboarding (currently none — users land straight in the full dashboard)

## Repo / Docs Hygiene
- [ ] Consolidate Implementation Status, roadmap, phases, etc. into one single-source-of-truth .md file
- [ ] what you ask in the CoWorker also changes your learning plan







- [ ] We need to add more functionality like a study thingy where you mark which days you studied and for how long and so on and/or a study routine generator and anything else
- [ ] Adding tips for nootropics and stuff
- [ ] Our questions and problems generated need to be 10x harder than any program ever created. So if you solver our "easy" questions perfectly, and maybe only 5 "medium" level problems, you would pass flawlessly in any test.
- [ ] We need to create one unified grading system so our grades would convert perfectly into any national system or curricula a student might have.