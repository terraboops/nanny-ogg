# nanny-ogg
A nagging reminder engine.

**This project is in a proof-of-concept phase.** Basically we'd like to learn our way around Go.

TODO 
- [ ] I want the ability to set reminders
- [ ] I want the ability to retain the state of a reminder
  state: active
      state: nag (inheriting from active)
  state: completed
- [ ] A reminder should be associated with a time span, in which I should be nagged
- [ ] I want reminds to nag me  
    (iteration 1: send nags to stdout
    iteration 2: send nags to twilio)
- [ ] Later iterations, we'd like an API for nags
  - Web interface built on API
  - Phone client built on API

