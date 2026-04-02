# Test Checklist - Homescapes Core Features

| Field | Value |
|-------|-------|
| Project | Homescapes - Playrix |
| Test Objective | Verification of interruption handling, lives system, and audio functionality |
| Identifier | CHK-001 |
| Requirements | BUG-001, BUG-002, BUG-003 |
| Test Date | - |
| Tester | Kseniia Romanovskaia |
| Test Environment | iPhone 15 Pro, iOS 17.4, Homescapes v6.x (latest App Store build) |

## Results

| Test Type | Test Name | Result |
|-----------|-----------|--------|
| Smoke | App launches without crash | - |
| Smoke | Main menu loads within acceptable time | - |
| Smoke | Match-3 level loads and is playable | - |
| Critical Path | Level progress is preserved after incoming phone call | - |
| Critical Path | Level progress is preserved after switching to another app | - |
| Extended | Level progress is preserved after locking and unlocking the screen | - |
| Smoke | Lives counter displays correctly (0-5) | - |
| Critical Path | One life is deducted on level fail | - |
| Critical Path | Lives timer counts down correctly in real time | - |
| Critical Path | Lives timer works correctly after returning from background | - |
| Extended | Lives timer is not affected by manual device time change | - |
| Extended | Lives are not deducted when app is closed mid-level | - |
| Smoke | Background music plays on launch | - |
| Smoke | Sound effects play on tile match | - |
| Critical Path | Audio resumes after returning from background | - |
| Critical Path | Audio resumes after incoming phone call | - |
| Extended | Mute toggle works correctly and persists between sessions | - |
