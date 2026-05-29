# Controller (Tablet / Ground Station)

The controller is responsible for:

- mission start/stop
- mode switching (manual/autonomous)
- safety override (pause/emergency)

---

## Bring-up order

1. Confirm server + viewer works
2. Confirm phone streaming works
3. Only then start controller and test manual mode
4. Switch to autonomous mode with a small mission

---

## Safety expectations

- Manual takeover must always be possible
- Provide a clear “pause” and “land now” action
- Battery threshold should trigger automatic return/landing
