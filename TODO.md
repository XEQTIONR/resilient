- [ ] instrumentation
- [ ] add duration to mark success/failure; use it for tracking latency and for making circuit decisions
- [ ] add timeout to metrics separate from failures (if we add duration)?
- [ ] should force closed still instrument and all that so we can test in prod before enabling or should we allow enabling/disabling with instrumentation in a different way?