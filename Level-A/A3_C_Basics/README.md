C Basics readme file
# Level A.3 — C Language Basics (Embedded)

## Goals
- Use fixed-width types, write functions/headers cleanly
- Understand arrays vs pointers and basic pointer arithmetic
- Implement debounce in plain C on MCU (no Arduino wrappers)

## Tasks
- Practice exercises at https://www.learn-c.org/
- Read K&R Ch. 1–5 (reference)
- STM32: CubeMX project with GPIO and `HAL_GetTick()`-based debounce
- Optional: UART print of press count

## Code Pseudocode
// In main loop:
read pin -> edge detect with 30–50 ms guard -> toggle LED and count presses

## Lessons Learned
- Arrays decay to pointers; mind bounds
- Separate interface (`.h`) from implementation (`.c`)
- Avoid busy-waits when possible; millis-style timing is friendlier

## References
- Learn-C.org (interactive)
- K&R book
- Tutorialspoint headers overview / StackOverflow thread
