This application is a Python/JavaScript application to help language learners.

It is intented to be 100% vibe coded. You (the agent reading this!) need to be extra dilligent on:
- Writing unit and integrations tests for everything
- Keeping quality extremely high
- Testing web functionality using your browser

Tools to use heavily:
- pytest for testing
- `agent-browser` for browser testing (use --help param to learn how to use it)

Our normal workflow is as follows:
- Human will be using opencode or claude or similar
- Human will descript a general feature to work on
- Together we will do the "grill me" workflow of working through questions to get all the details figured out
- Write our detailed software implementation plan for another agent to use into file `wip.md` (overwrite if exists already)
- A new agent & context will be started and that agent will be instructed to perform the implementation of the plan in `wip.md`
- The implementation will include heavy testing, both for new changes as well as existing functionality to ensure no regressons


