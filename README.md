[![gridai-session](https://github.com/robert-s-lee/grid-sessions/actions/workflows/gridai_session.yml/badge.svg)](https://github.com/robert-s-lee/grid-sessions/actions/workflows/gridai_session.yml)

# grid-sessions
Grid.ai Session continuous test.  The test is run 24 x 7 at 3 minutes past the hour.  Steps of the tests as follows:

- Create a new session 3 minutes past an hour
- Login in
- Run `ls` then `exit`
- Pause
- Resume
- Run `ls` then `exit`
- Delete the session